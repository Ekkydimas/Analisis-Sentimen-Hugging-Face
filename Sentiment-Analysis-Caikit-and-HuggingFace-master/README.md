# Text Sentiment Analysis using Caikit and Hugging Face
## IBMSkillsNetwork GPXX0PYAEN
---

### Author: Cognitive Class AI
### Mentee Assignment  
Bagian dari penyelesaian kursus **IBM Advance AI @ Infinite Learning** pada proyek **Text Sentiment Analysis using Caikit and Hugging Face** oleh **CognitiveClass.ai**.

---

### Assignment By : 
- **Program:** IBM Advance AI @ Infinite Learning  

---

### Tech Stack
- **Python**

---

## Struktur Proyek
Proyek ini terorganisir dengan struktur direktori berikut:

### 1. **`models/text_sentiment`**
   - **`config.yml`**: File konfigurasi yang mengatur parameter model analisis sentimen, seperti model yang digunakan, tokenizer, dan pengaturan lainnya.

### 2. **`text_sentiment`**
   - **`__pycache__/`**: Folder ini berisi file bytecode Python yang dihasilkan secara otomatis untuk mempercepat eksekusi.
   - Modul utama untuk pemrosesan data input dan pipeline awal sentimen.

### 3. **`data_model`**
   - **`classification.py`**: File ini mengimplementasikan logika klasifikasi untuk memetakan input teks ke sentimen tertentu (positif, negatif, atau netral).
   - **`__init__.py`**: File untuk menginisialisasi modul Python dalam folder ini.

### 4. **`runtime_model`**
   - **`client.py`**: Skrip untuk menjalankan API klien yang berinteraksi dengan pipeline analisis sentimen.
   - **`config.yml`**: File konfigurasi runtime, mencakup pengaturan API, logging, dan parameter lain.
   - **`__init__.py`**: Inisialisasi modul Python untuk folder ini.

### 5. **File Utama**
   - **`start_runtime.py`**: Skrip untuk memulai pipeline runtime model, menjalankan server, dan mengelola proses analisis sentimen.
   - **`requirements.txt`**: File untuk menginstal dependensi yang diperlukan. Semua pustaka terkait Python dapat diinstal dengan perintah:
     ```bash
     pip install -r requirements.txt
     ```
   - **`README.md`**: Dokumentasi utama proyek ini.

---

## Cara Menggunakan
Ikuti langkah-langkah berikut untuk menjalankan proyek ini:

1. **Instal Dependensi**  
   Pastikan semua pustaka yang diperlukan telah diinstal dengan menjalankan:
   ```bash
   pip install -r requirements.txt
