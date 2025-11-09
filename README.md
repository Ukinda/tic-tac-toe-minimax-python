# ❌⭕ Tic-Tac-Toe AI (Minimax & Alpha-Beta Pruning)

![Python Logo](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)
![Game Status](https://img.shields.io/badge/Game-Completed-brightgreen?style=for-the-badge)

Proyek ini adalah implementasi game **Tic-Tac-Toe** (Juga dikenal sebagai _Noughts and Crosses_) yang dimainkan melawan Komputer dengan kecerdasan buatan (AI) yang **tidak terkalahkan**. AI ini dirancang menggunakan algoritma pencarian **Minimax** yang dioptimalkan dengan **Alpha-Beta Pruning**, memastikan bahwa komputer akan selalu bermain secara optimal, yang berarti pemain akan selalu berakhir dengan **seri** atau **kalah**.

---

## ✨ Fitur Utama

- **AI Optimal:** Menggunakan algoritma **Minimax** dengan **Alpha-Beta Pruning** untuk memilih langkah terbaik.
- **Permainan Sederhana:** Antarmuka baris perintah (CLI) yang mudah digunakan.
- **Pemangkasan (Pruning):** Implementasi Alpha-Beta untuk meningkatkan kecepatan pencarian langkah AI.
- **Bahasa:** Ditulis sepenuhnya dalam Python.

---

## ⚙️ Persyaratan (Requirements)

Anda hanya perlu menginstal **Python 3.x** di sistem Anda.

Tidak ada _library_ eksternal yang diperlukan selain _built-in module_ **`math`** dan **`random`** (yang sudah termasuk dalam instalasi Python standar).

---

## 🚀 Cara Menjalankan

Ikuti langkah-langkah berikut untuk menjalankan permainan:

1.  **Kloning Repositori** (atau unduh file `tictactoe.py` Anda):

    ```bash
    git clone [https://github.com/USERNAME_ANDA/NAMA_REPO_ANDA.git](https://github.com/USERNAME_ANDA/NAMA_REPO_ANDA.git)
    cd NAMA_REPO_ANDA
    ```

2.  **Jalankan Skrip Python:**

    ```bash
    uts_praktek.ipynb
    ```

3.  **Bermain!**
    - Anda akan diminta untuk memasukkan langkah Anda dengan angka **1 hingga 9** sesuai posisi papan:
      ```
      -------------
      | 1 | 2 | 3 |
      | 4 | 5 | 6 |
      | 7 | 8 | 9 |
      -------------
      ```

---

## 🧠 Cara Kerja AI (Minimax)

Komputer berperan sebagai pemain **Minimizing** (Minimizer), berusaha mencari langkah yang meminimalkan skor kemenangan pemain Manusia (**Maximizing** Player).

|       Hasil Game        | Nilai Skor (Evaluation) |
| :---------------------: | :---------------------: |
| **Manusia (X) Menang**  |          `+1`           |
| **Komputer (O) Menang** |          `-1`           |
|        **Seri**         |           `0`           |

Fungsi `minimax` akan secara rekursif mensimulasikan semua kemungkinan langkah hingga permainan berakhir (kasus basis), dan memilih langkah yang menghasilkan skor terburuk bagi Manusia (yaitu: -1 atau 0).

---

## ✍️ Kontribusi

Kontribusi disambut baik! Jika Anda memiliki saran atau menemukan _bug_, silakan buka **Issue** atau buat **Pull Request** di repositori ini.

---

## 📜 Lisensi

Proyek ini berada di bawah Lisensi MIT - lihat file [LICENSE](LICENSE) untuk detail lebih lanjut.

---

**Dibuat oleh** [Ukinda Feriando Setiawan/UKINDA]

