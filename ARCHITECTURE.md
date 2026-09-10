# Architecture (high level)

No source code — only how the system is split.

```
Internet
   │
   ▼
Cloudflare Tunnel ──► public hostnames (*.deadcommunity.com)
   │
   ▼
Nginx / app containers (localhost ports on the host)
   │
   ├── Web: Next.js (main site) + Django CMS
   ├── Forum + tool suite (PDF, video, sound, image, …)
   ├── Discord bot stacks (API + dashboard + databases)
   ├── Matrix / Element / LiveKit
   └── Games (Minecraft, Palworld)
```

## Typical layers

1. **Edge:** Cloudflare DNS + Tunnel (TLS at the edge)  
2. **App:** Docker Compose isolated services  
3. **Data:** PostgreSQL, Redis, MinIO (per product)  
4. **AI (optional):** Ollama for PDF / summarize helpers  

## Security note

Public showcases never include secrets. Production credentials stay on the server and in private environments.
