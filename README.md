# AniVerse API

## Selamat datang di AniVerse API 🌟

AniVerse API membawa Anda ke dunia yang penuh dengan keajaiban anime! Temukan anime favorit Anda, jelajahi detail seru, dan nikmati pengalaman anime yang tak terlupakan.

ℹ️ **AniVerse API** adalah REST API scraping yang dibuat menggunakan Flask, yang menyediakan akses mudah dan cepat ke informasi anime dari [Samehadaku](https://samehada.care).

## 🚀 Fitur Utama

### 🎉 Cari Anime dengan Mudah
Dengan AniVerse API, Anda bisa dengan mudah menemukan anime favorit Anda. Gunakan fitur pencarian kami untuk menemukan anime berdasarkan judul atau kata kunci tertentu.

### 💫 Detail Anime yang Menakjubkan
Nikmati detail anime yang menakjubkan dengan AniVerse API. Dapatkan informasi lengkap tentang judul, genre, sinopsis, dan bahkan daftar episode.

### 📅 Rilis Anime Terbaru
Jangan lewatkan rilis anime terbaru! Dengan AniVerse API, Anda dapat melihat daftar rilis anime terbaru dan tetap terupdate dengan dunia anime.

## 🔍 Endpoint API

Base URL: `https://aniverse-api.vercel.app/`

1. **Pencarian Anime**
   - **URL**: `/api/search?q={query}`
   - **Metode**: GET
   - **Deskripsi**: Temukan anime berdasarkan judul atau kata kunci tertentu.

2. **Detail Anime**
   - **URL**: `/api/details?url={anime_url}`
   - **Metode**: GET
   - **Deskripsi**: Dapatkan detail tentang sebuah anime berdasarkan URL-nya.

3. **Rilis Anime Terbaru**
   - **URL**: `/api/release`
   - **Metode**: GET
   - **Deskripsi**: Dapatkan daftar rilis anime terbaru.

## 🌈 Contoh Penggunaan

1. **Pencarian Anime**
   ```bash
   GET https://aniverse-api.vercel.app/api/search?q=naruto
   ```

2. **Detail Anime**
   ```bash
   GET https://aniverse-api.vercel.app/api/anime?url=https://samehada.care/anime/naruto/
   ```

3. **Rilis Anime Terbaru**
   ```bash
   GET https://aniverse-api.vercel.app/api/release
   ```

## 📦 Format Tanggapan
- Tanggapan dari AniVerse API disajikan dalam format JSON yang informatif dan mudah dipahami.

## ⚡ Nikmati Petualangan Anime Anda!

Mari bergabung dengan AniVerse API dan jelajahi dunia anime yang tak terbatas. Segera temukan anime favorit Anda, nikmati detail seru, dan tetap terupdate dengan rilis anime terbaru!
