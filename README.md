# Praktikum Geolokasi, Peta Digital, dan Geocoding
**Nama: Nisa Eka Kholifaturrizkiah**
**Nim: 362458302018**

Praktik  ini membahas integrasi layanan lokasi (GPS) dan peta digital dalam aplikasi Flutter. Mahasiswa akan membuat aplikasi sederhana bernama "Geo-Catatan" yang memungkinkan pengguna menandai lokasi pada peta dan menyimpan catatan terkait lokasi tersebut.

Langkah Kerja:
1.  Tambahkan dependensi yang diperlukan pada file pubspec.yaml
    dependencies:
  flutter:
    sdk: flutter
  flutter_map: ^6.1.0
  latlong2: ^0.9.0
  shared_preferences: ^2.2.2
  geolocator: ^14.0.2
  geocoding: ^2.0.5
  google_maps_flutter: ^2.14.0
2. Agar aplikasi dapat mengakses GPS, tambahkan izin pada android/app/src/ main/AndroidManifest.xml
<uses-permission android:name="android.permission.ACCESS_FINE_LOCATION" />
<uses-permission android:name="android.permission.ACCESS_COARSE_LOCATION" />
<uses-permission android:name="android.permission.INTERNET" />
3. Kemudian membuat file baru lib/ catatan_model .dart untuk menyimpan struktur data.

## TugasMandiri
1. Kustomisasi Marker:Ubah ikon marker agar berbeda-beda tergantung jenis
catatan (misal:Toko,Rumah,Kantor).
![geo catatatn1](https://github.com/user-attachments/assets/cdddca48-938d-42a7-a829-543d0206d16c)
![geo catatan2](https://github.com/user-attachments/assets/0e4bf497-5357-440a-8b17-9f7a4ae2a73d)
disini menggunakan marker ikon rumah, selain ikon rumah juga bisa memilih ikon lain seperti toko dan kantor.

2. Hapus Data:Tambahkan fitur untuk menghapus marker yang sudah dibuat.
![geo catatan3](https://github.com/user-attachments/assets/afda37a1-a0a9-4dbe-b140-8f4b510b92a7)
Ketika marker ditekan, muncul dialog konfirmasi untuk menghapus langsung hapus hanya satu marker yang udah dibuat.

