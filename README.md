# 🐾 Smart Pet Care - Sistem Monitoring & Pemberian Pakan Otomatis Berbasis IoT

Projek ini merupakan Tugas Besar mata kuliah Internet of Things (IoT) yang bertujuan untuk membantu pemilik hewan peliharaan dalam memantau kondisi kandang serta mengotomatisasi pemberian pakan secara real-time demi kesejahteraan hewan peliharaan.

---

## 👥 Anggota Kelompok

| Nama | NIM |
| :--- | :---: |
| **Rafif Zahran Haryadi** | 2309106029 |
| **Celio Arga Rumahorbo** | 2309106039 |
| **Robby Pratama** | 2309106113 |

---

## 📺 Demo Projek

Saksikan demonstrasi lengkap bagaimana sistem ini bekerja melalui video berikut:

▶️ **[Tonton Video Demo di YouTube](https://youtu.be/iEdSnXwfAvU?si=NfO_7lMQHy0aUf1e)**

---

## 📝 Deskripsi Projek

Sistem **Smart Pet Care** dirancang untuk mengatasi kekhawatiran pemilik hewan peliharaan saat harus meninggalkan hewan mereka di rumah. Sistem ini mengintegrasikan pemantauan lingkungan kandang dan otomatisasi mekanis yang dapat diakses dari mana saja.

### ✨ Fitur Utama:
1. **Pemberian Pakan Jarak Jauh:**
   * Pemberian pakan yang dapat di lakukan kapan saja.
   * Kontrol manual instan kapan saja dan di mana saja melalui aplikasi **Blynk**.
2. **Monitoring Lingkungan (Environment Monitoring):**
   * Pemantauan suhu kandang secara *real-time* untuk memastikan kenyamanan hewan peliharaan.
3. **Notifikasi Darurat (Emergency Alert):**
   * Sistem peringatan otomatis melalui **Bot Telegram** jika sensor mendeteksi persediaan air minum telah habis.

---

## 🔌 Komponen & Arsitektur Sistem

Projek ini dibangun menggunakan kombinasi perangkat keras andal dan platform IoT berbasis cloud:

### 🛠️ Perangkat Keras (Hardware)
* **Mikrokontroler:** ESP32 (Wi-Fi & Bluetooth Enabled)
* **Sensor Suhu :** DHT11
* **Sensor Air:** Water Level Sensor
* **Aktuator Pakan:** Motor Servo

### ☁️ Platform IoT
* **Blynk IoT Platform:** Digunakan sebagai dashboard monitoring suhu dan tombol kontrol manual servo pakan.
* **Telegram Bot API:** Digunakan sebagai media pengiriman notifikasi/alert kritis ke smartphone pengguna serta dapat memberikan perintah kontrol manual servo.

---

## 🗺️ Skema Rangkaian
<img width="936" height="865" alt="WhatsApp Image 2026-04-30 at 22 43 53" src="https://github.com/user-attachments/assets/5e78b220-dd96-4aab-8b80-c588407f91e5" />
