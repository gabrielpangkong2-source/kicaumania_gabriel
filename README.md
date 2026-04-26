# 🐱 Kicau Mania AI Overlay (Double Window Mode)

Proyek filter webcam berbasis AI yang lagi viral di TikTok! Aplikasi ini bisa memunculkan video "Kucing Joget" dan memutar musik **Kicau Mania** secara otomatis hanya dengan menggunakan gestur jari kamu.

## ✨ Fitur Keren
- **Dual Window Auto-Layout**: Face Cam dan Video Kucing muncul sejajar rapi secara otomatis tanpa perlu digeser manual.
- **AI Hand Tracking**: Menggunakan MediaPipe untuk mendeteksi gestur tangan secara real-time.
- **Gesture Command**: 
  - 👈 Telunjuk ke **Kiri**: Panggil Kucing + Musik Kicau Mania dimulai!
  - 👉 Telunjuk ke **Kanan**: Kucing pulang + Musik mati otomatis.
- **Multi-Hand Detection**: Bisa deteksi dua tangan sekaligus lengkap dengan titik-titik sidik jari AI.

## 🛠️ Persyaratan
Gunakan **Python 3.11** untuk hasil yang paling stabil.

## 🚀 Cara Pakai

1. **Download/Clone** repo ini ke laptop kamu.
2. Instal semua library yang diperlukan melalui terminal:
   ```bash
   pip install opencv-python mediapipe pygame
   ```
3. Pastikan file berikut ada di dalam folder yang sama:
   - `kicau_mania.py` (Kodenya)
   - `cat_dance.mp4` (Video kucing joget)
   - `kicau_mania.mp3` (Audio kicau mania)

4. Jalankan programnya:
   ```bash
   python kicau_mania.py
   ```

## 📝 Catatan
Jika jendela video tidak muncul pas di samping, kamu bisa sesuaikan koordinat di bagian `cv2.moveWindow` pada kode `kicau_mania.py` sesuai resolusi layar monitor kamu.

---
Dibuat dengan oleh [boybands](https://github.com)
