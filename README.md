# Praktik LLM dengan API Gemini

Notebook ini membahas cara memanggil model bahasa besar (LLM) lewat API Gemini, lalu mengamati bagaimana parameter dan cara penulisan prompt memengaruhi hasilnya.

## Yang akan kamu lakukan:

- Menyiapkan API key dan memanggil model pertama kali.
- Membaca jumlah token dari setiap respons.
- Mengamati pengaruh temperature.
- Mengatur output agar berbentuk JSON dan memeriksanya.
- Mengirim riwayat percakapan agar model terlihat "mengingat".
- Membandingkan hasil beberapa prompt dengan kriteria yang sama.

Cara menjalankan sel: klik ▶ di sebelah kiri kotak kode, atau tekan Shift + Enter.

## Yang perlu disiapkan: 

API key dari Google AI Studio (https://aistudio.google.com/apikey), disimpan di panel Secrets (ikon kunci) dengan nama GEMINI_API_KEY dan Notebook access aktif. Jangan menulis key langsung di kode.