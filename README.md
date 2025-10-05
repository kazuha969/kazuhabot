# kazuhabot
WhatsApp Bot powered by Baileys 6.7.x — created by Kazuha
<h1 align="center">💀 KAZUHABOT v2.3 — Dark Red Elegant Edition</h1>

<p align="center">
  <img src="https://img.shields.io/badge/version-2.3-darkred?style=for-the-badge">
  <img src="https://img.shields.io/badge/author-Kazuha-red?style=for-the-badge">
  <img src="https://img.shields.io/badge/license-MIT-black?style=for-the-badge">
  <img src="https://img.shields.io/badge/status-Stable-green?style=for-the-badge">
</p>

<p align="center">
  ⚡ Powered by <strong>Kazuha</strong> (wa.me/6288706477028)  
  <br>Built with <strong>@whiskeysockets/baileys 6.7.x</strong> — Fast • Stable • Lightweight  
</p>

---

## 🌐 Deskripsi

**KazuhaBot** adalah bot WhatsApp multifungsi berbasis Node.js, dirancang dengan tampilan *Dark Red Elegant*.  
Fokus pada kecepatan, keamanan, dan kemudahan pengaturan untuk penggunaan pribadi maupun grup.

---

## ⚙️ Fitur Lengkap

### 🔧 Sistem
- `.menu` — tampilkan semua fitur  
- `.bot on/off` — aktifkan atau nonaktifkan bot  
- `.restart` — restart bot *(owner only)*  

### 🛡️ Proteksi
- `.antilink on/off` — hapus link otomatis & beri 3x peringatan  
- `.delete` — hapus pesan (reply, admin only)  
- `.kick @user` — keluarkan anggota  
- `.open / .close` — buka/tutup grup  
- `.setwelcome / .setgoodbye` — atur pesan masuk & keluar  

### 💬 Sosial
- `.hidetag / .h` — tag semua member  
- `.afk <alasan>` — tandai AFK  
- `.link` — ambil link grup  

### 🎬 Media
- `.downloadertiktokHD <url>` — download video TikTok tanpa watermark  
- `.hd` — tingkatkan kualitas gambar (balas gambar)  

### 📢 Broadcast
- `.jpm all|grup|priv <pesan>` — kirim pesan massal *(owner only)*  
  - Delay otomatis **2 menit per grup** untuk mencegah spam  

---

## 👑 Owner
| Nama | Nomor |  
|------|--------|  
| **Kazuha** | [wa.me/6288706477028](https://wa.me/6288706477028) |

---

## 🚀 Cara Install (Termux)
```bash
pkg update && pkg upgrade
pkg install git nodejs -y
git clone https://github.com/kazuha969/kazuhabot.git
cd kazuhabot
npm install
node index.js
