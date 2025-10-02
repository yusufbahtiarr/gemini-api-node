# Gemini Flash API (Express + Node.js)

Proyek ini adalah backend sederhana menggunakan **Node.js (Express)** yang mengintegrasikan **Google Gemini API** untuk berbagai use case:

- Generate teks dari prompt
- Analisis gambar
- Ringkasan dokumen
- Transkripsi audio

---

## 🚀 Fitur

- **/generate-text** → menghasilkan teks dari prompt
- **/generate-from-image** → menghasilkan deskripsi berdasarkan gambar yang di-upload
- **/generate-from-document** → membaca & meringkas dokumen (PDF/DOCX, dsb)
- **/generate-from-audio** → transkripsi atau ringkasan audio

---

## 🔑 Prasyarat & Instalasi

### 1. Pastikan Terpasang

- Node.js v18+ (mendukung ES Modules)
- API Key Gemini
  - Dapatkan di [Google AI Studio](https://aistudio.google.com/)
  - API Key ini wajib untuk akses model Gemini

### 2. Clone repository

```bash
git clone https://github.com/yusufbahtiarr/gemini-flash-api.git
cd gemini-flash-api
```

### 3. Install dependencies

```bash
npm install
```

### 4. Setup environment

Ubah file .env.example menjadi .env.  
Lalu isi dengan konfigurasi berikut:

```bash
API_KEY=your_generated_api_key_here
MODEL=gemini-2.5-flash
```

### 5. Jalankan server

```bash
npm run dev
```

## 🧪 Testing Endpoint

Gunakan file test.http (untuk VSCode dengan REST Client)

## 📜 Lisensi

MIT License
