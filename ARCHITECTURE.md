# ◆ Architecture (high level)

> No source code — only how the system is split.

```text
Internet
   │
   ▼
Cloudflare Tunnel ──► public hostnames (*.deadcommunity.com)
   │
   ▼
Nginx / app containers (localhost ports on the host)
   │
   ├── ▣ Web: Next.js (main site) + Django CMS
   ├── ▣ Forum + tool suite (PDF, video, sound, image, …)
   ├── ▣ Discord bot stacks (API + dashboard + databases)
   ├── ▣ Matrix / Element / LiveKit
   └── ▣ Games (Minecraft, Palworld)
```

### ◆ Layers

▸ **Edge** — Cloudflare DNS + Tunnel (TLS at the edge)  
▸ **App** — Docker Compose isolated services  
▸ **Data** — PostgreSQL · Redis · MinIO (per product)  
▸ **AI (optional)** — Ollama for PDF / summarize helpers  

### ◆ Security

▸ Public showcases never include secrets  
▸ Production credentials stay on the server and in private environments  
