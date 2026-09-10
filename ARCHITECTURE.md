# Mimari (yüksek seviye)

Kaynak kod yok. Sadece nasıl parçalandığı.

```
Internet
   │
   ▼
Cloudflare Tunnel ──► public hostnames (*.deadcommunity.com)
   │
   ▼
Nginx / app containers (host localhost ports)
   │
   ├── Web: Next.js (ana site) + Django CMS
   ├── Forum, tool suite (PDF, video, sound, image, …)
   ├── Discord bot stacks (API + dashboard + DB)
   ├── Matrix / Element / LiveKit
   └── Games (Minecraft, Palworld)
```

## Tipik katmanlar

1. **Edge:** Cloudflare DNS + Tunnel (TLS dışarıda)
2. **App:** Docker Compose ile izole servisler
3. **Data:** PostgreSQL, Redis, MinIO (ürüne göre)
4. **AI (isteğe bağlı):** Ollama (PDF / özet vb.)

## Güvenlik notu

Public vitrinde secret yok. Production secret’lar sunucuda ve private ortamlarda kalır.
