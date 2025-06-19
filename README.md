# Appl.json
All are allowed 
 (
  "Semua izin":"string "
  "izinkan" : "Diatas aplikasi lainnya"
  "Driver"  : "true"
  "izinkan' : "kamera"
  "izinkan" : "ambil gambar dan video"
  "izinkan" : "KONTAK"
  "izinkan" : "baca kontak Anda"
  "izinkan" : "LOKASI"
  "izinkan" : "akses perkiraan lokasi (berbasis jaringan) hanya di latar depan"
  "izinkan" : "akses lokasi pasti hanya saat di latar depan"
  "izinkan" : "akses lokasi di latar belakang"
  "izinkan  : "rekam audio"
  "izinka"  : "PENYIMPANAN"
  "izinkan" : "memodifikasi atau menghapus konten penyimpanan bersama Anda"
  "izinkan" : "membaca konten penyimpanan bersama Anda"
  "izinkan" : "KEMAMPUAN APLIKASI LAINNYA"
  "izinkan" : "terima data dari internet"
  "izinkan" : "mencegah ponsel menjadi tidak aktif"
  "izinkan" : "ubah setelan audio Anda"
  "izinkan" : "dapatkan akses jaringan penuh"
  "izinkan" : "lihat sambungan jaringan"
  "izinkan" : "lihat sambungan Wi-Fi"
  "izinkan" : "kontrol getaran"
  "izinkan" : "Izin ID Iklan"
  "izinkan" : "menyusun ulang apl yang berjalan"
  "izinkan" : "sambungkan panggilan telepon melalui sistem"
  "izinkan" : "android.permission.USE_FULL_SCREE N_INTENT"
  "izinkan" : "jalankan layanan di latar depan"
  "izinkan" : "sambung dan putuskan Wi-Fi"
  "izinkan" : "ubah konektivitas jaringan"
  "izinkan" : "sandingkan dengan perangkat Bluetooth"
  "izinkan" : "gunakan hardware biometrik"
  "izinkan" : "gunakan hardware sidik jari"
  "izinkan" : "mengukur ruang penyimpanan apl"
  "izinkan" : "Play Install Referrer API"
  "izinkan" : "dijalankan saat dimulai"
  "izinkan" : "baca konfigurasi layanan Google" 
  )
  "Tampilkan notifikasi"
   "izinkan" : "FoodyNotify_button" : off/on
   "izinkan" : "Push MessageService_button" : off/on
   "izinkan" : "Izinkan titik notifikasi_button" : off/on
   ( 
    "MEMBUKA LINK" : "izinkan"
     "izinkan" : "Buka link yang didukung"
     "izinkan: : "Buka di aplikasi ini"
     "izinkan" : "Link yang didukung"
     "izinkan" : "Buka shopeefooddriveriddebug.onelink.me dan URL lain"
     "izinkan  : "DEFAULT LAINNYA"
     "izinkan" : "Tidak ada setelan default"
     "izinkan" : "HAPUS DEFAULT"
    ) 
    
Configure
# Create the runner and start the configuration experience
$ ./config.cmd --url https://github.com/AriesTriputranto99/Repos --token AY3FPRE2NBSAXOEHLFDPLUDIKRVII# Run it!
$ ./run.cmd

Download
# Create a folder
$ mkdir actions-runner && cd actions-runner# Download the latest runner package
$ curl -o actions-runner-linux-x64-2.325.0.tar.gz -L https://github.com/actions/runner/releases/download/v2.325.0/actions-runner-linux-x64-2.325.0.tar.gz# Optional: Validate the hash
$ echo "5020da7139d85c776059f351e0de8fdec753affc9c558e892472d43ebeb518f4  actions-runner-linux-x64-2.325.0.tar.gz" | shasum -a 256 -c# Extract the installer
$ tar xzf ./actions-runner-linux-x64-2.325.0.tar.gz
