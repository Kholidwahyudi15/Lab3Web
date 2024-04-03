# Lab3Web

# Tugas Pemrograman Web 3 Pertemuan Ke-3

<h1>Pengertian PHP</h1>
<p>PHP merupakan singkatan dari PHP : Hypertext Preprocessor adalah salah satu Bahasa scripting open source yang banyak digunakan oleh Web Developer untuk pengembangan Web. PHP banyak digunakan untuk membuat banyak project seperti Grafik Antarmuka (GUI), Website Dinamis, dan lain-lain.</p>

## Latihan Module 1

### Membuat Database: Studi Kasus Data Barang

<img src="C:\kuliah\semester 4\Pem. web 2\Lab3_PHP_Database\Lab3Web\img">
<h1>Membuat Database</h1>
<code>CREATE DATABASE latihan1;</code>

<h1>Membuat Tabel</h1>
<code>CREATE TABLE data_barang (
id_barang int(10) auto_increment Primary Key,
kategori varchar(30),  
 nama varchar(30),  
 gambar varchar(100),  
 harga_beli decimal(10,0),  
 harga_jual decimal(10,0),  
 stok int(4)
);</code>
