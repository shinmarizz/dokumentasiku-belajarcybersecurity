# Roadmap Belajar Cyber Security untuk Non-IT

Roadmap ini disusun berdasarkan materi yang dibagikan, tapi disesuaikan urutannya khusus untuk kamu yang **belum punya latar belakang IT**. Fokusnya: dari nol → paham dasar → siap masuk ke materi keamanan web.

---

## Fase 0: Mindset & Persiapan (Minggu 1)

- Cyber Security = melindungi sistem, jaringan, perangkat, dan data dari serangan, pencurian, atau akses tidak sah.
- Karena kamu dari non-IT, jangan loncat ke "hacking" dulu. Pondasi komputer & jaringan wajib kuat dulu, atau nanti gampang nyerah karena bingung istilah.
- Siapkan laptop dengan RAM minimal 8GB (untuk virtual machine nanti).

---

## Fase 1: Dasar Komputer & Linux (Bulan 1)

**Target:** Lancar pakai Linux (Ubuntu/Kali) dan terminal.

| Topik | Yang dipelajari |
|---|---|
| Cara kerja komputer | CPU, RAM, storage, proses |
| Sistem operasi | Perbedaan Windows vs Linux |
| Struktur file | Direktori, permission |
| Command Line | CMD, PowerShell, Bash dasar |
| Linux fokus | User permission, `chmod`, `chown`, `sudo`, `service`, `systemctl`, `cron`, log |

**Praktik:** install VirtualBox → install Ubuntu/Kali di virtual machine → biasakan pakai terminal tiap hari (ganti direktori, buat file, edit file, install package).

---

## Fase 2: Dasar Jaringan Komputer (Bulan 1-2)

**Target:** Paham bagaimana data "berjalan" di internet — ini pondasi paling penting untuk cybersecurity.

- TCP/IP, DNS, DHCP
- HTTP dan HTTPS
- FTP, SMTP, SSH
- Port dan Socket
- Firewall
- IP Address, Subnet, Routing, VPN

**Praktik:** buka Wireshark, capture traffic dari browsing biasa, coba kenali paket HTTP vs HTTPS.

---

## Fase 3: Cara Website Dibuat (Bulan 2)

**Kenapa ini penting?** Kamu tidak bisa mengamankan sesuatu yang tidak kamu pahami cara kerjanya.

- HTML — struktur halaman
- CSS — tampilan
- JavaScript — interaksi/logika di browser
- Konsep HTTP request-response
- Dasar PHP atau Python untuk backend

---

## Fase 4: Database (Bulan 3)

- SQL dasar (SELECT, INSERT, UPDATE, DELETE)
- Query, Index
- User Privilege
- Backup
- Encryption

**Catatan:** kamu sudah familiar dengan PostgreSQL/PostGIS dari kuliah, jadi bagian SQL ini akan terasa lebih mudah — tinggal fokus ke sisi *security*-nya (privilege, encryption).

---

## Fase 5: Bahasa Pemrograman (Bulan 3, paralel dengan Fase 4)

Minimal kuasai satu, disarankan **Python** — dipakai luas untuk otomasi keamanan, analisis log, dan membuat tools sendiri.

---

## Fase 6: Konsep Inti Cyber Security (Bulan 4)

- **CIA Triad**: Confidentiality, Integrity, Availability
- Authentication vs Authorization
- Session, Cookie, JWT
- MFA, OAuth
- Dasar kriptografi: Hash, Salt, SHA-256, AES, RSA, Digital Signature, SSL/TLS Certificate

---

## Fase 7: Keamanan Web — Inti Web Security (Bulan 5)

Pelajari kerentanan umum berdasarkan **OWASP Top 10**:

- SQL Injection
- Cross Site Scripting (XSS)
- Cross Site Request Forgery (CSRF)
- Broken Authentication
- Broken Access Control
- Security Misconfiguration
- File Upload Vulnerability
- Directory Traversal
- Server-Side Request Forgery (SSRF)

**Praktik:** bangun aplikasi web sederhana sendiri, lalu coba cari & perbaiki celah keamanannya sendiri (audit mandiri).

---

## Fase 8: Server & Cloud (Bulan 6)

- Apache, Nginx, Reverse Proxy
- HTTPS & SSL Certificate
- Docker dasar
- Cloud: AWS/Azure/GCP, IAM, Storage Permission

---

## Fase 9: Monitoring & Tools (Bulan 6, lanjut)

- Log Analysis, SIEM, IDS, IPS
- Tools yang wajib dicoba (hanya di sistem sendiri/yang berizin):
  - **Nmap** — scanning jaringan
  - **Wireshark** — analisis paket
  - **Burp Suite** — pengujian aplikasi web
  - **OWASP ZAP** — scanning kerentanan web
  - **Nikto** — scanning server web
  - **Metasploit** — hanya di lingkungan latihan legal

---

## Ringkasan Jalur 6 Bulan

| Bulan | Fokus |
|---|---|
| 1 | Linux, Command Line, Jaringan dasar |
| 2 | HTML, CSS, JavaScript, HTTP |
| 3 | Python/PHP, SQL, Database |
| 4 | Konsep keamanan, autentikasi, kriptografi dasar |
| 5 | Praktik amankan web buatan sendiri, kerentanan umum |
| 6 | Tools analisis keamanan di lingkungan latihan legal, mulai ikut CTF/platform latihan |

---

## Prioritas Khusus (kalau waktu terbatas)

Urutan belajar paling efisien untuk mulai:

1. HTML & DOM
2. JavaScript
3. HTTP/HTTPS
4. SQL
5. Python
6. Linux
7. OWASP Top 10
8. Audit keamanan proyek web buatan sendiri

---

## Sertifikasi (kalau ingin ke jalur profesional nanti)

- CompTIA Security+
- CompTIA Network+
- Certified Ethical Hacker (CEH)
- eJPT
- OSCP (tingkat lanjut)
- CISSP (untuk profesional berpengalaman)

---

## Sumber Belajar per Fase

### Fase 1: Dasar Komputer & Linux
- **YouTube (ID):** channel "Kelas Terbuka", "Eko Kurniawan Khannedy" (Linux dasar)
- **YouTube (EN):** *NetworkChuck* — banyak konten Linux/Kali untuk pemula, gaya santai
- **Interaktif:** [OverTheWire: Bandit](https://overthewire.org/wargames/bandit/) — belajar command line Linux lewat game/challenge, gratis
- **Kursus:** [Linux Journey](https://linuxjourney.com/) — gratis, terstruktur per topik

### Fase 2: Jaringan Komputer
- **YouTube (EN):** *NetworkChuck* — "TCP/IP", "How the Internet Works"
- **Kursus:** [Cisco Networking Basics](https://skillsforall.com/) (gratis, ada sertifikat) — Networking Essentials
- **Buku/materi:** *Computer Networking: A Top-Down Approach* (opsional, kalau mau lebih dalam)
- **Praktik:** Wireshark (gratis) + tutorial "Wireshark for beginners" di YouTube

### Fase 3: Cara Website Dibuat
- **Interaktif (ID & EN):** [freeCodeCamp](https://www.freecodecamp.org/) — HTML, CSS, JS, gratis penuh
- **ID:** [Dicoding](https://www.dicoding.com/) — ada kelas HTML/CSS/JS dasar gratis
- **MDN Web Docs** — referensi HTML/CSS/JS paling lengkap (developer.mozilla.org)

### Fase 4: Database
- **Interaktif:** [SQLZoo](https://sqlzoo.net/) atau [Mode SQL Tutorial](https://mode.com/sql-tutorial/) — gratis, langsung praktik
- Karena kamu sudah pakai PostgreSQL/PostGIS, tinggal tambah materi soal *user privilege* dan *encryption* — bisa cari "PostgreSQL security best practices" di dokumentasi resminya

### Fase 5: Python
- **Interaktif:** [Codecademy Python](https://www.codecademy.com/learn/learn-python-3) (ada versi gratis)
- **ID:** [Dicoding - Belajar Dasar Python](https://www.dicoding.com/) — gratis
- **Untuk security:** *Automate the Boring Stuff with Python* (buku gratis online, automatetheboringstuff.com) — bagus untuk automasi/log analysis

### Fase 6: Konsep Inti Cyber Security
- **Kursus gratis:** [TryHackMe - "Pre Security" & "Cyber Security 101"](https://tryhackme.com/) — sangat cocok untuk pemula, ada learning path terstruktur
- **YouTube (EN):** *The Cyber Mentor*, *John Hammond*
- **Kriptografi:** [Cryptography I - Stanford (Coursera)](https://www.coursera.org/) oleh Dan Boneh — gratis untuk audit

### Fase 7: Keamanan Web (OWASP)
- **Wajib:** [OWASP Top 10](https://owasp.org/www-project-top-ten/) — dokumen resmi, gratis
- **Praktik:** [OWASP Juice Shop](https://owasp.org/www-project-juice-shop/) — web app sengaja dibuat rentan untuk latihan hacking legal
- **Praktik lain:** [PortSwigger Web Security Academy](https://portswigger.net/web-security) — gratis, sangat lengkap, dari pembuat Burp Suite
- **TryHackMe:** room "OWASP Top 10"

### Fase 8: Server & Cloud
- **Docker:** [Docker Get Started](https://docs.docker.com/get-started/) — dokumentasi resmi
- **Cloud:** AWS Free Tier + [AWS Skill Builder](https://skillbuilder.aws/) (gratis)
- **Nginx/Apache:** DigitalOcean Community Tutorials — banyak panduan gratis dan jelas

### Fase 9: Monitoring & Tools
- **TryHackMe:** room Nmap, Wireshark, SIEM Fundamentals
- **Nmap:** [Nmap Official Guide](https://nmap.org/book/man.html)
- **Burp Suite:** [PortSwigger Academy](https://portswigger.net/web-security) (sekalian belajar tools-nya)
- **Latihan CTF (setelah dasar kuat):** [TryHackMe](https://tryhackme.com/), [Hack The Box](https://www.hackthebox.com/), [PicoCTF](https://picoctf.org/) (cocok untuk pemula)

### Rekomendasi Platform All-in-One
Kalau mau satu platform utama yang menemani dari awal sampai mahir:
1. **TryHackMe** — paling ramah pemula, ada jalur "Pre Security" → "Cyber Security 101" → "Jr Penetration Tester"
2. **PortSwigger Web Security Academy** — gratis, fokus web security dan sangat mendalam
3. **Hack The Box** — untuk latihan lanjutan setelah dasar kuat

---

## Catatan untuk Kamu (Shima)

- Karena background kamu Geodesi, kamu sudah punya modal kuat di: **SQL/PostGIS**, **command line dasar** (dari GEE/QGIS), dan **logika spasial/analitis**. Manfaatkan itu — jangan mulai dari nol banget.
- Gunakan alat-alat security (Nmap, Burp Suite, Metasploit, dll) **hanya** pada sistem milik sendiri atau yang memang diberi izin untuk diuji. Ini bukan cuma etika, tapi juga legal di Indonesia (UU ITE).
- Alokasikan waktu belajar mulai dari topik paling sederhana yang belum kamu kuasai, jangan loncat-loncat.