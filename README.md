WedGenProV2 - Premium Wedding Invitation Generator
WedGenProV2 adalah platform generator undangan pernikahan digital berbasis web (Single Page Application) yang dirancang untuk memberikan pengalaman eksklusif, elegan, dan interaktif. Proyek ini merupakan evolusi dari versi sebelumnya, kini hadir dengan fitur RSVP real-time dan manajemen privasi informasi hadiah yang lebih etis.

<img width="1273" height="611" alt="image" src="https://github.com/user-attachments/assets/dfaa0a66-dcd7-4e78-b364-e583e31a9223" />

## ✨ Fitur Utama

- **Premium L01 Theme**: Desain bersih dan mewah dengan nuansa Beige/Cream serta dekorasi floral watercolor.
- **Real-time RSVP & Ucapan (MQTT)**: Menggunakan protokol MQTT (HiveMQ Broker) sehingga ucapan dari tamu muncul secara instan di layar tanpa perlu refresh halaman.
- **Dynamic Guest Name**: Personalisasi nama tamu secara otomatis melalui URL parameter (`?to=Nama+Tamu`).
- **Guest Link Generator**: Dashboard khusus untuk membuat dan menyalin link undangan unik untuk setiap tamu secara otomatis.
- **YouTube Music Integration**: Musik latar yang dapat dikustomisasi dan diputar otomatis saat undangan dibuka.
- **Full Live Editor**: Ubah profil mempelai, jadwal acara, lokasi (Google Maps), galeri foto, hingga informasi hadiah (wedding gift) secara langsung.
- **Standalone Export**: Hasil undangan dapat diekspor menjadi satu file HTML utuh yang siap dideploy ke GitHub Pages atau hosting lainnya.

## 🛠️ Teknologi yang Digunakan

- **HTML5 & CSS3** (Custom Animations & Glassmorphism)
- **Tailwind CSS** (Styling Framework)
- **JavaScript (Vanilla)** (Logic & DOM Manipulation)
- **MQTT.js** (Protokol komunikasi real-time via WebSockets)
- **HiveMQ Public Broker** (Infrastruktur pesan real-time)
- **FontAwesome & Google Fonts** (Tipografi & Ikonografi)

## 🚀 Cara Penggunaan & Deployment

### 1. Menjalankan Secara Lokal
Cukup buka file `index.html` di browser pilihan Anda (Chrome, Edge, atau Firefox).

### 2. Deploy ke GitHub Pages (Gratis)
1. Buat repositori baru di akun GitHub Anda.
2. Upload file `index.html` ke repositori tersebut.
3. Masuk ke tab **Settings** > **Pages**.
4. Pada bagian **Build and deployment**, pilih branch `main` lalu klik **Save**.
5. Tunggu 1-2 menit, dan undangan Anda akan aktif secara publik.

### 3. Cara Mengirim Undangan ke Tamu
1. Buka link undangan yang sudah Anda deploy.
2. Masuk ke tab **LINK TAMU** di sidebar editor.
3. Masukkan nama tamu (Contoh: *Bapak Ahmad*).
4. Klik **SALIN LINK LENGKAP**.
5. Kirim link tersebut ke tamu melalui WhatsApp atau media sosial lainnya.

## 📡 Monitoring RSVP via MQTT Explorer
Jika Anda ingin memantau pesan masuk secara teknis melalui aplikasi **MQTT Explorer**:
- **Host**: `broker.hivemq.com`
- **Port**: `1883`
- **Topic**: `linkzwire/wedding/bitterfly/v1/wishes` (atau sesuai konfigurasi di dashboard).

## 📝 Lisensi
Proyek ini dibuat untuk keperluan edukasi dan personal. Silakan dikembangkan lebih lanjut.

---
**Developed with ❤️ by LinkzwireNode**
