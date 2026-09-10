# DeadCommunity — Product Showcase

Bu depo **kaynak kod içermez**. DeadCommunity ekosisteminde canlı çalışan ürünlerin kısa özetidir: ne yaptık, hangi rolde, nereden denenebilir.

Hesap: [Semaru47](https://github.com/Semaru47) · Canlı: [deadcommunity.com](https://deadcommunity.com)

---

## Ana platform

| Ürün | Ne işe yarar | Canlı |
|------|----------------|-------|
| **DeadCommunity Web** | Ana site, blog/CMS, ekip sayfaları, navigasyon | [deadcommunity.com](https://deadcommunity.com) |
| **DeadForum** | Topluluk forumu (v2) | [forum.deadcommunity.com](https://forum.deadcommunity.com) |
| **Portföy — İlhami Malik** | Kişisel portföy sitesi | [malik.deadcommunity.com](https://malik.deadcommunity.com) |
| **Portföy — Utku** | Kişisel portföy sitesi | [utku.deadcommunity.com](https://utku.deadcommunity.com) |

**Yığın (özet):** Next.js, Django CMS, PostgreSQL, Redis, Docker, Cloudflare Tunnel, Nginx.

---

## Web araçları

| Ürün | Ne işe yarar | Canlı |
|------|----------------|-------|
| **DeadPDF** | PDF araçları (dönüştürme, TTS, AI yardımcıları) | [pdf.deadcommunity.com](https://pdf.deadcommunity.com) |
| **DeadVideo** | Tarayıcıda video düzenleme | [video.deadcommunity.com](https://video.deadcommunity.com) |
| **DeadSound** | Ses düzenleme | [sound.deadcommunity.com](https://sound.deadcommunity.com) |
| **DeadImage** | Görsel araçları | [image.deadcommunity.com](https://image.deadcommunity.com) |
| **DeadQR** | QR üretimi | [qr.deadcommunity.com](https://qr.deadcommunity.com) |
| **DeadColor** | Renk araçları | [color.deadcommunity.com](https://color.deadcommunity.com) |
| **DeadDiff** | Metin / diff karşılaştırma | [diff.deadcommunity.com](https://diff.deadcommunity.com) |
| **DeadPaste** | Paste / snippet paylaşım | [paste.deadcommunity.com](https://paste.deadcommunity.com) |
| **DeadSummarize** | Metin özetleme | [summarize.deadcommunity.com](https://summarize.deadcommunity.com) |
| **Bounty** | Ödül / görev panosu | sunucu üzerinde aktif (`:3040`) |

**Yığın (özet):** Containerize edilmiş web uygulamaları, Nginx reverse proxy, yerel AI (Ollama) entegrasyonları (PDF vb.).

---

## Discord & topluluk botları

| Ürün | Ne işe yarar | Panel / not |
|------|----------------|-------------|
| **Dead Anime** | Anime odaklı Discord bot + web | [anime.deadcommunity.com](https://anime.deadcommunity.com) |
| **Dead Music** | Müzik botu + dashboard | [music.deadcommunity.com](https://music.deadcommunity.com) |
| **Dead Bot (Boss)** | Topluluk yönetim botu + panel | [boss.deadcommunity.com](https://boss.deadcommunity.com) |
| **Dead İndirim** | İndirim / fırsat botu | Discord bot (port `8085`) |

**Yığın (özet):** Discord API, Node/Python servisleri, Postgres, Redis, MinIO, Nginx panelleri.

---

## Altyapı & iletişim (kendi sunucumuz)

| Ürün | Ne işe yarar |
|------|----------------|
| **Matrix + Element + LiveKit** | Kendi chat / voice altyapısı (Synapse, Element Web, LiveKit, Coturn) |
| **DeadCoDrive** | Dosya / drive servisi |
| **Dead Hub** | Araçlar ana menü / hub |
| **Dead Ops** | Operasyon / sunucu yardımcıları |
| **Cloudflare Tunnel** | Public hostname → localhost yönlendirme |
| **Open WebUI + Ollama** | Yerel LLM arayüzü |
| **Minecraft / Palworld** | Topluluk oyun sunucuları |

---

## Bu depoda ne var / ne yok?

| Var | Yok |
|-----|-----|
| Ürün listesi, amaç, canlı linkler | Kaynak kod |
| Yüksek seviye tech özeti | `.env`, secret, API key |
| Mimari notlar (`ARCHITECTURE.md`) | Production compose / şifreler |

Kaynak kod **private** tutulur. Bu repo yalnızca “ne yaptık” vitrini.

---

## Nasıl okunur?

1. Yukarıdaki tablolardan ürünü seç.
2. Canlı linki aç — çalışan ürünü gör.
3. Detay için: [`ARCHITECTURE.md`](./ARCHITECTURE.md) · [`PROJECTS.md`](./PROJECTS.md)

---

*Son güncelleme: 2026-09-10 — sunucuda o an çalışan container’lara göre.*
