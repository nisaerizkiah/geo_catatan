# Praktikum Geolokasi, Peta Digital, dan Geocoding
**Nama: Nisa Eka Kholifaturrizkiah**
**Nim: 362458302018**

Praktik  ini membahas integrasi layanan lokasi (GPS) dan peta digital dalam aplikasi Flutter. Mahasiswa akan membuat aplikasi sederhana bernama "Geo-Catatan" yang memungkinkan pengguna menandai lokasi pada peta dan menyimpan catatan terkait lokasi tersebut.

Langkah Kerja:
1.  Tambahkan dependensi yang diperlukan pada file pubspec.yaml
    <img width="834" height="266" alt="image" src="https://github.com/user-attachments/assets/82fa8d39-113b-4de4-ae31-03535ded604a" />

2. Agar aplikasi dapat mengakses GPS, tambahkan izin pada android/app/src/ main/AndroidManifest.xml
<uses-permission android:name="android.permission.ACCESS_FINE_LOCATION" />
<uses-permission android:name="android.permission.ACCESS_COARSE_LOCATION" />
<uses-permission android:name="android.permission.INTERNET" />

3. Kemudian membuat file baru lib/ catatan_model .dart untuk menyimpan struktur data.

## TugasMandiri
1. Kustomisasi Marker:Ubah ikon marker agar berbeda-beda tergantung jenis
catatan (misal:Toko,Rumah,Kantor). Disini menggunakan marker ikon rumah, selain ikon rumah juga bisa memilih ikon lain seperti toko dan kantor.
![geo catatatn1](https://github.com/user-attachments/assets/cdddca48-938d-42a7-a829-543d0206d16c)
![geo catatan2](https://github.com/user-attachments/assets/0e4bf497-5357-440a-8b17-9f7a4ae2a73d)

2. Hapus Data:Tambahkan fitur untuk menghapus marker yang sudah dibuat. Ketika marker ditekan, muncul dialog konfirmasi untuk menghapus langsung hapus hanya satu marker yang udah dibuat.
![geo catatan3](https://github.com/user-attachments/assets/afda37a1-a0a9-4dbe-b140-8f4b510b92a7)

