# My Automation Project

## Overview
This project contains automated test scripts for testing a todo application using Katalon Studio.

## Prerequisites
- Install Katalon Studio
- WebDriver configured for your browser (e.g., ChromeDriver)
- ...

## How to Run the Tests
1. Open Katalon Studio.
2. Open the project: File -> Open Project -> Select the project folder (MyAutomationProject).
3. In the Test Explorer, navigate to Test Cases.
4. Right-click on the desired test case (e.g., `TestCase01`) and select "Run."
5. Observe the execution in the console and the browser.

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

...

## Notes
- Adjust the Object Repository and other configurations as needed.
- Update the WebDriver path and URL_HALAMAN_TODOS in the test scripts.
