# Proje kartları

Her satır: sunucuda **aktif** (veya canlı hostname’i olan) bir ürün grubu.

## deadcommunity-web

- **Rol:** Marka sitesi, içerik, navigasyon
- **Canlı:** https://deadcommunity.com
- **Öne çıkanlar:** Çok dilli / CMS menü, ekip portföyleri bağlantıları, mobil UX

## deadforum

- **Rol:** Topluluk forumu
- **Canlı:** https://forum.deadcommunity.com
- **Not:** Forum v2 container’ı da ayakta; DNS şu an tunnel üzerinden yayınlanıyor

## portfolios (malik / utku)

- **Rol:** Kurucu portföyleri
- **Canlı:** https://malik.deadcommunity.com · https://utku.deadcommunity.com

## tool-suite

- PDF, Video, Sound, Image, QR, Color, Diff, Paste, Summarize
- Her biri ayrı container + hostname (veya local port)

## discord-ecosystem

- Anime, Music, Boss, İndirim botları + web panelleri
- Postgres / Redis / MinIO kullanan tam stack’ler

## contact-stack

- Synapse (Matrix), Element Web, LiveKit, Coturn
- Kendi iletişim / ses altyapısı

## platform-extras

- DeadCoDrive, Dead Hub, Bounty, Dead Ops
- Oyun sunucuları (Minecraft, Palworld)
- Open WebUI + Ollama

## Bilerek vitrine alınmayanlar

- Ham `postgres` / `redis` imajları (altyapı, ürün değil)
- Backup klasörleri, secret dosyaları
- Third-party image’lerin kendisi (ürün bizim orchestration + domain katmanımız)
