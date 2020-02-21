# Node.js

![nodejs](nodejs.png)

## 1. Permasalahan

Javascript merupakan bahasa pemrograman yang hanya dapat dijalankan di web browser sebagai frontend. Sehingga kita membutuhkan bahasa pemrograman lain untuk membuat backend

## 2. Penjelasan Node.js

Node.js merupakan runtime environment javascript yang membuat javascript dapat berjalan di server

## 3. Install Node.js

### 3.1. Windows

Download instalasi node.js untuk windows pada link berikut :

https://nodejs.org/en/download/

### 3.2. Ubuntu

Gunakan perintah berikut untuk menginstall node.js versi 13 pada ubuntu

```bash
curl -sL https://deb.nodesource.com/setup_13.x | sudo -E bash -
sudo apt install nodejs
```

## 4. Hello World

### 4.1. Membuat Script Node.js

Untuk membuat script node.js, buatlah sebuah file dengan ekstensi `.js`, misalnya `index.js`

```javascript
// index.js

console.log('hello world')
```

### 4.2. Menjalankan Script Node.js

Kemudian untuk menjalankan script tersebut, gunakanlah perintah `node`

```bash
node index.js
```
