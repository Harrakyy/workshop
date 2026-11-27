# Pembuat Agent AI — Workshop "Dari User ke Builder"

Web app statis (1 file HTML, tanpa build) untuk workshop Agentic AI yang Bertanggung Jawab.

- **Pembuat Agent**: isi form (peran, jenis konten, audiens, gaya, guardrails, alat) → salin prompt ke ChatGPT/Gemini, salin prompt app ke v0, atau klik **Bikin App-ku** untuk dapat link app personal (`?a=...`).
- **Mode app**: agent jalan beneran pakai API key Gemini milik pengguna (dipanggil langsung dari browser), dengan diagram alur animasi, cek diri + perbaiki sendiri, dan tombol Setuju/Revisi.

## Deploy versi kamu sendiri
1. Klik tombol Deploy di bawah, login GitHub, buat repo.
2. Edit `agent.config.js` di repo barumu, tempel konfigurasi dari halaman Pembuat Agent, Commit.
3. Vercel otomatis update dalam ~1 menit.

Catatan: Gemini API wajib 18+. Di free tier, data bisa dipakai Google untuk melatih model, jadi jangan masukkan data pribadi.

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2FHarrakyy%2Fworkshop)
