
# Kalkulator BMI

### Yuk, kenali tubuhmu lebih dekat!

Kalkulator BMI adalah aplikasi desktop sederhana yang membantu kamu menghitung Indeks Massa Tubuh (BMI) berdasarkan berat dan tinggi badan.

Aplikasi ini dibuat menggunakan Java dan JavaFX dengan tampilan yang simpel, interaktif, dan mudah digunakan. Cukup masukkan data diri, klik tombol hitung, dan hasil BMI kamu akan langsung muncul!

---

## Tampilan Aplikasi


### Standar Kemenkes RI

<p align="center">
  ![Tampilan Kalkulator BMI](Screenshots/bmiKemenkes-app.png)
</p>

### Standar WHO

<p align="center">
  <![Tampilan Kalkulator BMI](Screenshots/bmiWho-app.png)
</p>

## Fitur Aplikasi

- Memasukkan nama pengguna
- Mengisi berat badan dalam kilogram
- Mengisi tinggi badan dalam sentimeter
- Menghitung BMI secara otomatis
- Menampilkan hasil dan kategori BMI
- Mengosongkan data dengan tombol reset

---

## Teknologi yang Digunakan

| Teknologi | Kegunaan |
|---|---|
| Java 17 | Bahasa pemrograman utama |
| JavaFX 21 | Membuat tampilan aplikasi |
| FXML | Mengatur layout GUI |
| CSS | Mempercantik tampilan aplikasi |
| Maven | Mengelola dependency dan project |

---

# Cara Menjalankan Aplikasi

### Persiapan

Pastikan laptop kamu sudah memiliki:
- Java Development Kit (JDK) 17
- Apache Maven

### Langkah-langkah

**1. Clone repository**

```bash
git clone https://github.com/USERNAME/BMIApp.git
```

**2. Masuk ke folder project**

```bash
cd BMIApp
```

**3. Jalankan aplikasi**

```bash
mvn javafx:run
```

Tunggu sebentar, dan aplikasi Kalkulator BMI siap digunakan! 🎉

---

## Struktur Project

```text
BMIApp/
├── src/
│   └── main/
│       ├── java/
│       │   ├── controller/
│       │   ├── main/
│       │   └── model/
│       └── resources/
│           ├── form-bmi.fxml
│           └── style.css
├── screenshots/
│   └── bmi-app.png
├── pom.xml
└── README.md
```

---

## Tentang Project

Project ini dibuat sebagai bagian dari tugas pemrograman Java sekaligus menjadi kesempatan untuk belajar dan mencoba langsung:

- Konsep Object-Oriented Programming (OOP)
- Inheritance dan polymorphism
- Pembuatan GUI menggunakan JavaFX
- Event handling
- Pengelolaan project menggunakan Maven

---

## Pengembang

**ofidefiyanti**

Project Pemrograman Java | 2026

---

