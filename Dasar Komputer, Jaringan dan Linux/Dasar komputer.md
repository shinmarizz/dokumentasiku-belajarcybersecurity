software : perintah program untuk pengolahan data 
- operation system : linux, macOS, windows
- software aplikasi : QGIS, epc games

hardware : perangkat keras secara fisik seperti mouse, pc

brainware : orang yang terlibat dalam komputer 

jenis-jenis komputer : PC Desktop, Laptop, Handheld PC

komponen utama
motherboard : penghubung semua komputer
cpu/processor : mengeksekusi perintah perangkat lunak
ram : tempat penyimpanan sementara data yang dipakai dalam komputer 
storage: menyimpan data secara permanen
- hdd : bekerja secara mekanis 
- ssd : membaca data jauh lebih cepat
graphics card : untuk memvisualisasikan komputer
psu : jantung komputer agar dapat menyala

# Materi Ringkas: Dasar-Dasar Komputer

*Disarikan dari buku "Dasar-Dasar Komputer" (Yahfizham, 2019) — versi ringkas untuk belajar cepat sebelum lanjut ke materi cyber security.*

---

## BAB 1: Pengenalan Komputer

### Apa itu komputer?
Secara sederhana, komputer adalah alat elektronik yang bisa menerima data (input), mengolahnya sesuai instruksi/program, menyimpan hasilnya, lalu mengeluarkan hasil olahan tersebut (output) — semua dilakukan secara otomatis tanpa perlu campur tangan manusia di setiap langkahnya.

Tiga komponen utama komputer:

| Komponen | Penjelasan |
|---|---|
| **Hardware** (perangkat keras) | Bagian fisik yang bisa disentuh — terdiri dari alat input, alat proses, alat output, dan peripheral/aksesoris |
| **Software** (perangkat lunak) | Kumpulan instruksi/program yang mengatur cara kerja hardware — mencakup sistem operasi, aplikasi, dan bahasa pemrograman |
| **Brainware** | Manusia yang menjalankan komputer — programmer, sistem analis, administrator, teknisi hardware/jaringan, web master |

### Sejarah singkat (4 generasi)
1. **Generasi 1** — pakai tabung hampa udara (vacuum tube), ukuran raksasa (contoh: ENIAC tahun 1946, berat ±30 ton)
2. **Generasi 2** — pakai transistor, lebih kecil, lebih hemat daya, tidak mudah pecah dibanding tabung hampa
3. **Generasi 3** — pakai IC (integrated circuit), komputer makin kecil dan cepat
4. **Generasi 4** — pakai microprocessor, cikal bakal komputer pribadi (PC) modern

### Jenis-jenis komputer
- **Berdasarkan golongan:** analog, digital, hybrid
- **Berdasarkan kapasitas:** mainframe, mini computer, micro computer (PC)
- **Berdasarkan data yang diolah:** komputer khusus data tertentu vs komputer serba guna

### Konsep dasar sistem komputer (4 bagian penting)
1. **Input Device** — alat untuk memasukkan data (keyboard, mouse, scanner)
2. **Processing Device** — otak komputer yang mengolah data (CPU/processor)
3. **Output Device** — alat untuk menampilkan hasil (monitor, printer, speaker)
4. **Peripheral/Accessories** — alat tambahan pendukung (flashdisk, webcam, dll)

---

## BAB 2: Sistem Operasi

### Definisi
Sistem operasi (OS) adalah software utama yang menjembatani antara hardware dan pengguna — dia yang mengatur sumber daya komputer (memori, CPU, penyimpanan) agar aplikasi lain bisa berjalan.

### Komponen dasar sistem operasi
- Manajemen proses
- Manajemen memori
- Manajemen file dan penyimpanan
- Manajemen perangkat (device driver)
- Antarmuka pengguna (user interface)

### Perbandingan OS populer

| | Kelebihan | Kekurangan |
|---|---|---|
| **Windows** | Antarmuka ramah pengguna, kompatibel dengan banyak software dan hardware | Rentan virus, berbayar, cenderung lebih berat |
| **Linux** | Gratis/open source, lebih aman dari virus, ringan dan fleksibel untuk dikustomisasi | Kurva belajar lebih curam, dukungan software komersial lebih terbatas |

> Ini kenapa di roadmap cyber security kamu diarahkan belajar Linux — sistem operasi ini jadi standar di dunia keamanan siber karena open source, ringan, dan bisa dikontrol penuh lewat command line.

### Bahasa pemrograman & algoritma
- **Bahasa pemrograman** adalah alat untuk menulis instruksi yang bisa dijalankan komputer
- **Algoritma** adalah langkah-langkah logis dan sistematis untuk menyelesaikan suatu masalah, sebelum ditulis jadi kode program

---

## BAB 3: Sistem Bilangan Dasar

Ini pondasi penting untuk memahami cara komputer "berpikir" — semua data pada dasarnya diproses dalam bentuk angka.

| Sistem | Basis | Simbol yang dipakai | Contoh penggunaan |
|---|---|---|---|
| **Biner** | 2 | 0, 1 | Bahasa asli komputer (on/off, listrik nyala/mati) |
| **Desimal** | 10 | 0–9 | Angka yang biasa dipakai manusia sehari-hari |
| **Oktal** | 8 | 0–7 | Jarang dipakai langsung, tapi penting di beberapa sistem file/permission Linux (misalnya `chmod 755`) |
| **Heksadesimal** | 16 | 0–9, A–F | Dipakai untuk representasi warna (kode HEX), alamat memori, MAC address |

> Konsep biner dan heksadesimal ini nanti akan sering kamu temui lagi di jaringan komputer (IP address, subnetting) dan command Linux (`chmod` pakai oktal).

---

## BAB 4: Sistem Informasi Manajemen

### Data vs Informasi
- **Data** — fakta mentah yang belum diolah
- **Informasi** — data yang sudah diolah sehingga punya makna dan berguna untuk pengambilan keputusan

### Hirarki data (dari terkecil ke terbesar)
`Bit → Byte → Field → Record → File → Database`

### Basis Data (Database)
Kumpulan data yang terorganisir agar mudah diakses, dikelola, dan diperbarui. Komponen dasarnya mencakup hardware, software, data, prosedur, dan pengguna.

### Sistem Informasi Manajemen (SIM)
Sistem yang mengubah data menjadi informasi untuk membantu manajer/pengambil keputusan dalam sebuah organisasi.

---

## BAB 5: Teknologi Informasi dan Komunikasi (TIK/ICT)

### Internet
Jaringan global yang menghubungkan jutaan komputer di seluruh dunia sehingga bisa saling bertukar data dan informasi.

### Pengalamatan IP (IP Address)
Setiap perangkat yang terhubung ke jaringan/internet punya alamat unik berupa angka (IP Address) — ini konsep yang akan kamu perdalam lagi nanti di materi jaringan komputer untuk cyber security.

### Media pembelajaran berbasis ICT
Pemanfaatan teknologi (komputer, internet) untuk mendukung proses belajar-mengajar agar lebih efektif dan menjangkau lebih luas.

---

## BAB 6: Moral, Etika & Hukum

### Moral dan Etika
- **Moral** — nilai baik-buruk yang berlaku di masyarakat
- **Etika** — aturan perilaku yang mengatur bagaimana seseorang bersikap, termasuk dalam menggunakan teknologi

### Hukum terkait komputer
Buku ini membahas contoh regulasi di negara lain (misalnya undang-undang komputer di Amerika Serikat dan undang-undang privasi di Tiongkok) sebagai perbandingan pentingnya regulasi di era digital.

### Kejahatan Komputer (Computer Crime)
Bab ini relevan langsung dengan cyber security — membahas berbagai bentuk penyalahgunaan komputer yang melanggar hukum, seperti akses ilegal ke sistem, pencurian data, dan penyalahgunaan informasi pribadi.

> Untuk konteks Indonesia, kamu bisa lanjutkan dengan mempelajari **UU ITE (Undang-Undang Informasi dan Transaksi Elektronik)** sebagai dasar hukum yang relevan saat nanti praktik pentest — supaya kamu paham batasan legal antara "belajar/testing berizin" vs "tindakan ilegal".

---

## Ringkasan Cepat (Kalau Cuma Punya 30 Menit)

Kalau waktumu terbatas, fokus baca 3 bagian ini saja dulu:

1. **Hardware, Software, Brainware** (Bab 1) — dasar mutlak
2. **Sistem Operasi & perbandingan Windows vs Linux** (Bab 2) — karena kamu akan segera pakai Linux
3. **Sistem Bilangan (Biner & Heksadesimal)** (Bab 3) — akan sering muncul lagi di jaringan dan Linux permission

Bagian SIM, TIK/ICT, dan Moral-Etika-Hukum (Bab 4-6) bisa dibaca belakangan sebagai pelengkap wawasan, tidak mendesak untuk jalur cyber security kamu.