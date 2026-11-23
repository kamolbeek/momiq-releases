# Momiq — ochiq yuklamalar

<p align="center">
  <img src="media/1-buyruq.gif" alt="1 — Momiq buyruqni strelka bilan bajaradi" width="520"><br><br>
  <img src="media/2-ruxsat.gif" alt="2 — Momiq avval ruxsat so'raydi" width="520"><br><br>
  <img src="media/3-boshqaruv.gif" alt="3 — Momiq ekranni o'zi boshqaradi" width="520">
</p>

Bu repoda Momiq ilovasi o'zi yuklab oladigan fayllar turadi (kod yo'q):

- `models/v1/` — oflayn nutq modellari (o'zbekcha RubaiSTT va ko'p tilli Whisper Small), 90 MB lik bo'laklarga bo'lingan; `manifest.json` da har bo'lak va butun faylning SHA-256 xeshi. Litsenziyalar: `models/v1/NOTICE.md`.
- `updates/` — Momiq kod yangilanishlari: `momiq-update-<asos>.json` lentasi va imzolangan (Ed25519) `.upd.gz` to'plamlari. Ilova har bir to'plamni yozishdan oldin xesh va imzo bilan tekshiradi.

Momiq modellarni avval asl manbadan (Hugging Face, tezroq) yuklaydi; u ishlamasa — shu repodagi bo'laklardan.
