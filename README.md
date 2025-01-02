# Catatan AI Bootcamp

Source code catatan yang mungkin dapat membantu teman-teman belajar khususnya selama pelatihan Mastering AI Bootcamp

---

## Instalasi

Pastikan teman-teman sudah menginstall requirement dibawah ini:
- [Python](https://www.python.org/downloads/) (version ^3.9.*)
- [pip](https://pip.pypa.io/en/stable/) (Python package manager)

**Cek Versi Python**

Ketik _python_ pada command prompt atau terminal teman-teman

---

## Cloning repositori

1. **Clone the Repository**  
   Gunakan command di bawah pada terminal atau command prompt teman-teman:
   ```bash
   git clone https://github.com/Marfin12/catatan-ai-bootcamp.git
   ```
   bisa juga buka langsung di terminal vscodenya dengan buka _vscode > terminal > new terminal_
   <img width="1225" alt="Screenshot 2025-01-02 at 19 51 18" src="https://github.com/user-attachments/assets/c71c0ce1-6fbe-45ac-82f4-49e87f36b9b8" />


3. **Open the Repository**  
   Buka folder repository yang temen-temen sudah clone tadi, misalnya ingin akses _webinar#1-python_1_ maka seperti dibawah:
   ```bash
   cd catatan-ai-bootcamp/Foundational_Knowledge/webinar#1_python_1
   ```
   

## Virtual Environment

1. **Membuat virtual environment**
   jika menginstall python, maka gunakan
   ```bash
   python -m venv my_venv
   ```
   atau python3, seperti dibawah
   ```bash
   python3 -m venv my_venv
   ```

3. **Aktivasi Virtual Environment**  
   - On **Windows**:
     ```bash
     my_venv\Scripts\activate
     ```
   - On **macOS/Linux**:
     ```bash
     source my_venv/bin/activate
     ```
     jika sudah aktif, harusnya ada tulisan my_venv di belakang folder lokasi di terminal atau command promptnya seperti gambar dibawah
     <img width="276" alt="Screenshot 2025-01-02 at 19 42 15" src="https://github.com/user-attachments/assets/d6483ead-ad30-4dc2-95d0-df6fe506562c" />


4. **Instalasi**
   Setelah virtual environmentnya sudah aktif,  direkomendasikan update pip terlebih dahulu
   ```bash
   python -m pip install --upgrade pip
   ```
   setelah itu, install packagenya dari file requirement menggunakan pip:
   ```bash
   pip install -r requirements.txt
   ```

---

## Jalankan Aplikasi

1. **Jalankan Aplikasi**  
   Jalankan aplikasi sesuai python yang di install
   ```bash
   python main.py
   ```

---

## Deaktivasi virtual environment

Untuk deaktivasi virtual environment, jalankan:
```bash
deactivate
```

---

## Catatan Tambahan

- Jika `requirements.txt` tidak ada pada folder, kamu bisa membuat sendiri requirements nya dengan cara:
  ```bash
  pip freeze > requirements.txt
  ```

- Selalu pastikan teman-teman berada di virtual environment sebelum install package dengan pip atau running aplikasinya untuk menghindari konflik package instalasinya.

---
