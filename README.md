# Todo App Test Automation

## Overview
This project contains automated test scripts for testing a todo application using Katalon Studio.

## Test Cases

### TC_01 - Tambahkan todo dengan deskripsi
1. Masukkan ke dalam halaman todos.
2. Masukkan teks/deskripsi pada input field todos.
3. Todos bertambah sesuai dengan deskripsi yang sudah diinput.

### TC_02 - Tambahkan todo dengan mengisi huruf saja
1. Masukkan ke dalam halaman todos.
2. Masukkan teks/deskripsi berupa huruf pada input field todos.
3. Todos bertambah sesuai dengan yang diinput yaitu deskripsi hanya berupa huruf.

### TC_03 - Tambahkan todo dengan mengisi angka saja
1. Masukkan ke dalam halaman todos.
2. Masukkan teks/deskripsi berupa angka pada input field todos.
3. Todos bertambah sesuai dengan yang diinput yaitu deskripsi hanya berupa angka.

### TC_04 - Tambahkan todo dengan mengisi huruf dan angka
1. Masukkan ke dalam halaman todos.
2. Masukkan teks/deskripsi berupa angka dan huruf pada input field todos.
3. Todos bertambah sesuai dengan yang diinput yaitu deskripsi hanya berupa angka dan huruf.

### TC_05 - Tambahkan todo dengan mengisi karakter spesial seperti +/*#@!<>{}.
1. Masukkan ke dalam halaman todos.
2. Masukkan teks/deskripsi berupa karakter spesial pada input field todos.
3. Todos bertambah sesuai dengan yang diinput yaitu deskripsi hanya berupa karakter spesial.

### TC_06 - Tambahkan todo dengan mengisi huruf, angka dan karakter spesial
1. Masukkan ke dalam halaman todos.
2. Masukkan teks/deskripsi berupa angka, huruf dan karakter spesial pada input field todos.
3. Todos bertambah sesuai dengan yang diinput yaitu deskripsi berupa angka, huruf dan karakter spesial.

### TC_07 - Centang todo
1. Sudah menambahkan todo.
2. Tambahkan todos.
3. Klik centang.
4. Warna teks todo yang sudah dicentang berbeda dengan yang tidak dicentang.

### TC_08 - Hapus todo
1. Sudah menambahkan todo.
2. Tambahkan todos.
3. Klik icon X.
4. Todo yang dipilih sudah tidak muncul lagi / sudah dihapus.

### TC_09 - Filter todo by All
1. Sudah menambahkan todo.
2. Tambahkan todos.
3. Klik tombol filter All.
4. Menampilkan seluruh todo (yang sudah selesai ataupun belum).

### TC_10 - Filter todo by Active
1. Sudah menambahkan todo.
2. Tambahkan todos.
3. Klik tombol filter Active.
4. Menampilkan todo yang belum selesai / belum dicentang.

### TC_11 - Filter todo by Completed
1. Sudah menambahkan todo.
2. Tambahkan todos.
3. Klik tombol filter All.
4. Menampilkan seluruh todo yang sudah dicentang.

### TC_12 - Klik dropdown todo saat todo sudah dicentang
1. Sudah menambahkan todo.
2. Tambahkan todos.
3. Klik dropdown.
4. Mengcollaps dan mengexpand todo.
5. Meng-unchecklist seluruh todo yang telah dicentang.

### TC_13 - Klik dropdown todo saat todo belum dicentang
1. Sudah menambahkan todo.
2. Tambahkan todos.
3. Klik dropdown.
4. Mengcollaps dan mengexpand todo.
5. Mencentang seluruh todo.



## Prerequisites
- Install Katalon Studio.
- Configure WebDriver for your browser (e.g., ChromeDriver).

## How to Run the Tests
1. Open Katalon Studio.
2. Open the project: File -> Open Project -> Select the project folder (MyAutomationProject).
3. In the Test Explorer, navigate to Test Cases.
4. Right-click on the desired test case and select "Run."
5. Observe the execution in the console and the browser.

## Notes
- Adjust the Object Repository and other configurations as needed.
- Update the WebDriver path and URLs in the test scripts.
