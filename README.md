# Lab5web
Nama: Den Fahmi Satria <p>
Nim: 312410523 <p>
Kelas: TI.24.A5 <p>
Mata Kuliah: Pemrograman Web  <p>
Dosen Pengampu: Agung Nugroho, S.Kom., M.Kom <p> 
Universitas: Pelita Bangsa  <p>
### Praktikum 5: Javascript Dasar
Berikut adalah ringkasan, contoh kode, serta **hasil dan penjelasan** dari setiap langkah praktikum: <p>
### 1. Dasar: `document.write` dan `console.log` (`lab5_javascript.html`)
##### Contoh dasar penulisan kode JavaScript di dalam tag `<body>` . <p>

```
html
<!DOCTYPE html>
<html lang="en">
<body>
    <h1>Pengenalan JavaScript</h1>
    <h3>Contoh document.write dan console.log</h3>
    <script>
        document.write("Hello World"); 
        console.log("Hello World");    
    </script>
</body>
</html>
```
Tampilan di Web dan VSCODE <p>
<img src="lab5web/images/wb1.png" width="700">
Hasil : Teks "Hello World" muncul di halaman web dan di Console browser . <p>
### 2. Penggunaan `window.alert` (`alert_box.html`)
Membuat kotak peringatan (alert box) saat halaman dimuat <p>

```
html
<html>
<body>
    <script language="javascript">
        window.alert("ini merupakan pesan untuk anda"); // Pesan peringatan 
    </script>
</body>
</html>
```
Tampilan di Web dan VSCODE <p>
<img src="lab5web/images/wb2.png" width="700">
Hasil: Sebuah kotak dialog peringatan (alert box) muncul dengan pesan "ini merupakan pesan untuk anda". <p>
###  3. Pemakaian `document.write Method (`document_write_method.html`)
Contoh penggunaan `document.write` untuk menampilkan beberapa baris teks. <p>

```
html
<html>
<body>
    percobaan memakai javascript:<br>
    <script language="javascript">
        document.write("selamat mencoba javascript<br>"); 
        document.write("semoga sukses!"); 
    </script>
</body> 
</html>
```
Tampilan di Web dan VSCODE <p>
<img src="lab5web/images/wb3.png" width="700">
