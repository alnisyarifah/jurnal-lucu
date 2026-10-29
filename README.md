# Mochi Journal

Aplikasi Personal Journal & Dashboard mobile-first berbasis React, TypeScript, Vite, Tailwind CSS, dan Lucide Icons. Data jurnal, transaksi, curhat, serta profil disimpan otomatis di `localStorage` browser.

## Menjalankan project

```bash
npm install
npm run dev
```

Build produksi:

```bash
npm run build
```

Hasil build berada di folder `dist`.

## Export dan publish mandiri

### Melalui GitHub + Vercel/Netlify
1. Download source project sebagai ZIP lalu extract.
2. Buat repository GitHub dan upload seluruh source project (termasuk `package.json`, jangan hanya `dist`).
3. Import repository tersebut di Vercel atau Netlify.
4. Gunakan build command `npm run build` dan output/publish directory `dist`.
5. Deploy melalui dashboard layanan yang dipilih.

### Melalui ZIP + Netlify Drop
1. Jalankan `npm install`, lalu `npm run build` di komputer.
2. Upload atau drag folder `dist` ke Netlify Drop.

## Catatan privasi dan backup

Aplikasi ini frontend-only. Data hanya tersimpan di browser perangkat yang digunakan, tidak tersinkron antarperangkat, dan dapat hilang bila data browser dibersihkan. Gunakan tombol **Export / Backup Data** untuk mengunduh salinan JSON secara berkala.
