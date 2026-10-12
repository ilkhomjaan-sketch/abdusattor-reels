# abdusattor-reels

AI Montajor pipeline uchun vaqtinchalik ommaviy video ombori.

Bu yerga tayyor Reels videoning **yengil** (light, <30MB) nusxasi push qilinadi,
shunda GitHub raw URL orqali Metricool uni o'qib o'z CDN'iga ko'chirib oladi.
Metricool muvaffaqiyatli yuklab olgach, fayl bu yerdan o'chiriladi (ombor shishib
ketmasligi uchun) — Metricool'dagi post allaqachon o'zining nusxasini saqlab oladi.

4K master fayllar bu yerga PUSH QILINMAYDI (GitHub 100MB limiti va bu ombor
faqat vaqtinchalik "ko'prik" ekanligi sababli). Masterlar foydalanuvchining
Mac'idagi `AI Montajor/tayyor/` papkasida saqlanadi.

## Tuzilma
- `videos/<sana>-<mijoz>-<slug>.mp4` — vaqtinchalik, Metricool uchun

Loyiha: AI Montajor (claude.ai Project "AI montaj")
