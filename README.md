# Şiir Günlüğü — Minimal Çalıştırılabilir Demo

Bu klasör, hızlı çalıştırma için minimal Electron + Vite + React iskeleti içerir. Orijinal proje dosyaları kaybolduysa bu demo ile uygulamayı hemen çalıştırabilirsin; sonrasında orijinal dosyalar bulunursa birleştirebiliriz.

Gereksinimler
- Node.js (16+ önerilir)

Kurulum & Çalıştırma (PowerShell)

```powershell
# Proje kökünde çalıştır
npm install
npm run dev
```

Notlar
- `npm run dev` iki paralel işlem başlatmak için `concurrently` kullanır: Vite (renderer) ve electron. Eğer sorun yaşarsan önce `npm run dev:renderer` ile sadece Vite'i, sonra `npm run dev:electron` ile Electron'u tek tek çalıştır.
- Bu sadece minimal demo; şifreli özel defter, WhatsApp/Twilio ve tam özellikler sonradan eklenebilir.
