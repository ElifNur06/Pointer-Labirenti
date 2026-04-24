# 🤖 Pointer Labirenti (Pointer Labyrinth)

![Flutter](https://img.shields.io/badge/Flutter-%2302569B.svg?style=for-the-badge&logo=Flutter&logoColor=white)
![Dart](https://img.shields.io/badge/dart-%230175C2.svg?style=for-the-badge&logo=dart&logoColor=white)
![Google Play](https://img.shields.io/badge/Google_Play-414141?style=for-the-badge&logo=google-play&logoColor=white)

**Pointer Labirenti**, yazılım dünyasının en temel ve zorlu konularından biri olan **C Tipi Bellek Yönetimi ve Pointer (İşaretçi)** mantığını oyunculara bir hacker/robot simülasyonu içinde öğreten mobil bir "Edutainment" oyunudur.

## 🚀 Öne Çıkan Özellikler

* **Gerçekçi Bellek Simülasyonu:** STACK ve HEAP bölgeleri arasında gerçek pointer operatörlerini (`*`, `->`, `++`, `--`) kullanarak gezinin.
* **500+ Seviye:** Temelden (Linked List, Trees) başlayıp algoritmik olarak üretilen karmaşık labirentlere uzanan geniş içerik.
* **Eğitici Bilgi Kartları:** Seviye aralarında bellek mimarisi hakkında 50'den fazla teknik bilgi (Stack Overflow, 32-bit/64-bit farkları vb.).
* **Dinamik Mekanikler:** Enerji %20'nin altına düştüğünde hedef vurgusunun kaybolması gibi zorlayıcı UI elementleri.

## 🛠️ Teknik Mimari

Bu proje modern Flutter mimarisi ve best-practice yaklaşımları ile geliştirilmiştir:

* **State Management:** `Provider` (GameController merkezi yönetimi).
* **Persistence:** `SharedPreferences` ile can senkronizasyonu ve ilerleme takibi.
* **Ads Integration:** `Google Mobile Ads` (Ödüllü ve Geçiş reklamları).
* **Animations:** `animate_do` ve `confetti` ile zenginleştirilmiş kullanıcı deneyimi.
* **Localization:** `LocalizationManager` ile tam Türkçe ve İngilizce desteği.

## 🕹️ Nasıl Oynanır?

Oyunda bir "Robot" (Pointer) kontrol edilmektedir. Amaç, enerji bitmeden ve bellek hataları (NULL Pointer) yapmadan hedef adrese ulaşmak ve bellek sızıntılarını (`JUNK`) temizlemektir.

| Komut | İşlev |
| :--- | :--- |
| `ptr++` / `ptr--` | Bellek adresini bir birim kaydırır. |
| `*bot` (Dereference) | Robotun üzerinde bulunduğu adresteki veriye/adrese ışınlanmasını sağlar. |
| `bot->` (Arrow) | Struct yapıları içindeki özel alanlara (next, data) erişir. |
| `free()` | Kırmızı renkli sızıntıları temizler. |

## Görseller

<img width="336" height="595" alt="image" src="https://github.com/user-attachments/assets/7837cfa2-6ad9-47f5-b147-3fa6f75b8d73" />
<img width="336" height="595" alt="image" src="https://github.com/user-attachments/assets/aaf63be6-e2d4-4ef0-981e-523de4765723" />
<img width="336" height="598" alt="image" src="https://github.com/user-attachments/assets/10b84a0a-f5ec-457b-84e5-8d62b2256c21" />
<img width="337" height="597" alt="image" src="https://github.com/user-attachments/assets/e223f384-3743-4b6b-901a-ca2f0b3fcd44" />
<img width="339" height="596" alt="image" src="https://github.com/user-attachments/assets/a9e9fc2a-4964-48be-b751-66b8d27b5dfb" />
<img width="336" height="597" alt="image" src="https://github.com/user-attachments/assets/21c81cdb-c3c5-467d-804a-a6725630a536" />
<img width="339" height="598" alt="image" src="https://github.com/user-attachments/assets/3b842751-5467-4d09-ad5d-66a16c536435" />
<img width="336" height="593" alt="image" src="https://github.com/user-attachments/assets/c7125f4e-b666-43bd-b6d8-9d9580a3548c" />




