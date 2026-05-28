# 📝 Tugas Individu 9 - My Notes App AI (KMP + Groq AI)

Aplikasi manajemen catatan cerdas berbasis **Kotlin Multiplatform (KMP)** yang menggabungkan fitur native platform dengan kekuatan **Artificial Intelligence**.

---

## 🌟 Fitur Utama

### 1. Manajemen Catatan (CRUD & Persistence)
- **SQLDelight Database**: Penyimpanan catatan secara lokal (offline-first) yang aman dan cepat.
- **Search & Filter**: Pencarian catatan secara *real-time* dengan fitur `debounce` untuk menghemat sumber daya.
- **Favorites**: Menandai catatan penting untuk akses cepat di tab terpisah.
- **Categorization**: Pengelompokan catatan berdasarkan kategori.

### 2. Fitur Native Platform (Expect/Actual)
- **Device Info**: Menampilkan informasi hardware secara detail (Model, Manufaktur, Versi OS, dan Platform).
- **Network Monitor**: Deteksi status koneksi internet secara *real-time* dengan banner peringatan yang muncul otomatis jika koneksi terputus.

### 3. Asisten AI Cerdas (Groq Cloud)
Aplikasi ini dilengkapi dengan **AI Summarizer & Translator** yang sangat cepat:
- **Summarization**: Meringkas catatan panjang menjadi poin-poin inti dalam hitungan detik.
- **Translation**: Menerjemahkan teks antar bahasa secara akurat.
- **Chat Assistant**: Konsultasi atau tanya jawab langsung dengan AI mengenai isi catatan Anda.

### 4. UI/UX Modern
- **Material Design 3**: Antarmuka modern dengan komponen terbaru dari Google.
- **Dark & Light Mode**: Dukungan tema gelap/terang yang dapat disesuaikan di menu pengaturan.
- **Responsive Layout**: Tampilan yang menyesuaikan untuk Android dan platform lainnya.

---

## 🔑 Informasi API & Teknologi

### Groq Cloud API
Aplikasi ini menggunakan **Groq Cloud API** sebagai mesin AI utama karena kecepatannya yang superior dibandingkan penyedia lain.
- **Model**: `llama-3.3-70b-versatile` (Model Llama terbaru dan tercepat).
- **API Key**: `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`
- **Endpoint**: `https://api.groq.com/openai/v1/chat/completions`

### Library yang Digunakan
- **Koin**: Untuk Dependency Injection (DI) yang modular.
- **Ktor**: Untuk komunikasi data ke server AI.
- **SQLDelight**: Untuk manajemen database lokal.
- **Compose Multiplatform**: Untuk pembuatan UI lintas platform.
- **DataStore**: Untuk penyimpanan pengaturan aplikasi (Theme settings).

---

## ✅ Rubrik Penilaian (Compliance)

1. **Koin DI (25%)**: Implementasi penuh di `AndroidApp.kt` dan `di/Koin.kt`.
2. **Platform Features (25%)**: Penggunaan `expect/actual` pada `DeviceInfo` dan `NetworkMonitor`.
3. **AI Integration (30%)**: Integrasi Llama 3.3 melalui Groq API dengan fitur Ringkasan & Terjemahan.
4. **UX & Design**: Navigasi yang lancar dengan Bottom Navigation dan tema Dark Mode.
## Dokumentasi Visual

| AI Summarizer (Ringkas) | AI Summarizer (Translate) |
| :---: | :---: |
| <img width="328" height="718" alt="Screenshot 2026-05-28 213456" src="https://github.com/user-attachments/assets/5a863579-0356-4240-aec6-d3d4e6a6528d" /> | <img width="325" height="714" alt="Screenshot 2026-05-28 213514" src="https://github.com/user-attachments/assets/cc3e50e6-7201-4d69-832b-95f002602828" /> |

## Video Demo
Video demo fitur aplikasi dapat diakses melalui tautan berikut : https://drive.google.com/file/d/1jjYQwpi7hpfHBs6b2J_i7gD_RrcqHWkL/view?usp=drive_link


---

**Developed by:** Andinirhm 🌸
**NIM/Course:** 123140067/Pengembangan Aplikasi Mobile (PAM)
