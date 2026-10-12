# CSS Layout
## Profil
| Variable | Isi |
| -------- | --- |
| **Nama** | Hafiz Faturrohman |
| **NIM** | 312210375 |
| **Mata Kuliah** | Pemrograman WEB |

### Tugas
1. Buatlah repository baru dengan nama Lab4Web.
2. Kerjakan semua latihan yang diberikan sesuai urutannya.
3. Screenshot setiap perubahannya.
4. Buatlah file README.md dan tuliskan penjelasan dari setiap langkah praktikum beserta
screenshotnya.
5. Commit hasilnya pada repository masing-masing.
6. Kirim URL repository pada e-learning ecampus.

### Pertanyaan dan Tugas
1. Tambahkan Layout untuk menu About.
=> buat single layout yang berisi deskripsi, portfolio, dll.
2. Tambahkan layout untuk menu Contact
=> yang berisi form isian: nama, email, message, dll.

# Jawaban

**Hasil tugas :**

<img width="270" height="616" alt="image" src="https://github.com/user-attachments/assets/33ae87bf-5ac1-4f5d-a6e8-06d86cb44082" />

# Penjelasan :
## 1. lab4_box.html
```<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Box Element</title>
</head>
<body>
    <header>
        <h1>Box Element</h1>
    </header>
</body>
</html>

<style>
    div {
    float:left;
    padding: 10px;
    }
    .div1 {
    background: rgb(243, 5, 5);
    }
    .div2 {
    background: rgb(23, 206, 191);
    }
    .div3 {
    background: rgb(6, 243, 6);
    }
    .div4 {
background-color: blue;
clear: left;
float: none;
}
</style>

<section>
    <div class="div1">Div 1</div>
    <div class="div2">Div 2</div>
    <div class="div3">Div 3</div>
    <div class="div4">Div 4</div>
</section>
```
**Hasil :**
<img width="1358" height="704" alt="Screenshot 2026-10-12 110056" src="https://github.com/user-attachments/assets/a0ca2e53-f596-4ca1-9792-51a340808887" />
