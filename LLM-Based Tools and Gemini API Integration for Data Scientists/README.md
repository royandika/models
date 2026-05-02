# IT Helpdesk Assistant — Streamlit & Gemini API

Repositori ini berisi proyek chatbot **IT Helpdesk/Support Assistant** yang dibangun menggunakan **Streamlit**, **Google Gemini API**, dan dijalankan melalui **Google Colab** dengan bantuan **ngrok**.

Proyek ini merupakan bagian dari program training:
**"Maju Bareng AI course LLM-Based Tools and Gemini API Integration for Data Scientists"** oleh **Hacktiv8** (27 April – 30 April 2026).

---

## 🚀 Fitur Utama
- **Virtual IT Support**: Membantu troubleshooting masalah komputer, jaringan, dan software.
- **Natural Language**: Menggunakan model `gemini-2.5-flash` untuk interaksi yang santai dan personal.
- **Session Persistence**: Menggunakan `st.session_state` agar chatbot mengingat konteks percakapan.
- **Sidebar Configuration**: Pengaturan API Key dan fitur Reset Percakapan yang mudah diakses.
- **Cloud Ready**: Dikonfigurasi khusus untuk berjalan di lingkungan Google Colab.

## 🛠️ Teknologi yang Digunakan
- **Python**: Bahasa pemrograman utama.
- **Streamlit**: Framework untuk antarmuka web (UI).
- **Google GenAI SDK**: Integrasi dengan model LLM Gemini.
- **Pyngrok**: Untuk mengekspos localhost Colab ke URL publik.

## 📖 Cara Menjalankan
1. Buka file `.ipynb` di Google Colab.
2. Masukkan **Ngrok Authtoken** Anda pada bagian Colab Secrets dengan nama `NGROK_TOKEN`.
3. Jalankan sel instalasi dan konfigurasi.
4. Masukkan **Google AI API Key** (didapat dari [Google AI Studio](https://aistudio.google.com/)) pada sidebar aplikasi Streamlit yang muncul.
5. Mulai berinteraksi dengan asisten IT.

---
*Dibuat oleh Roy Andika untuk tujuan edukasi dalam rangkaian pelatihan Hacktiv8.*
