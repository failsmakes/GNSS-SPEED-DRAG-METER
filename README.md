# 🛰️ RC Araçlar için GPS Hız & Drag Süresi Ölçer

Bu proje, RC araçlarda gerçek zamanlı hız ve drag süresi ölçümü yapmanızı sağlayan bir DIY cihazdır.  
**TTGO T-Display ESP32**, **ATGM336H GPS modülü** ve **AA boyutunda Li-Ion şarjlı batarya** kullanılarak oluşturulur. Tüm bileşenler özel tasarım bir **3D baskı kasaya** yerleştirilir.

[📽️ YouTube videosunu izlemek için tıklayın (fails&makes)](https://www.youtube.com/@failsmakes)  
[📦 3D baskı kasa tasarımı için Printables bağlantısı](https://www.printables.com/)

---

## 🔧 Donanım

- TTGO T-Display ESP32 geliştirme kartı  
- GPS modülü (ATGM336H)  
- AA boyutunda (14500L) Li-ion batarya  
- 1S BMS Kartı
- Mikro slide switch
- 3D baskı kasa

---

## 💡 Özellikler

- GPS ile anlık ve maksimum hız ve yükseklik ölçümü  
- Drag zamanı ölçümü (örneğin 0–50 km/s ve 0-40metre)
- Enlem ve boylam olarak konum bilgisi
- Renkli TFT ekranda veri gösterimi  
- Batarya durumu göstergesi  
- Kompakt ve taşınabilir yapı

---

## 🔌 Bağlantı Şeması

| TTGO T-Display | GPS Modülü |
|----------------|------------|
| 3.3V           | VCC        |
| GND            | GND        |
| GPIO25 (RX)    | TX         |
| GPIO26 (TX)    | RX         |

> ⚠️ Farklı bir GPS modülü kullanıyorsanız voltaj uyumluluğunu kontrol edin.

---

## 🚀 Başlarken

1. PlatformIO ile kartınıza yazılımı yükleyin.  
2. Kodları yükleyin.  
3. Cihazı dış mekanda test edin (GPS sinyali için açık alan gerekli).

---

## 🧠 Lisans

Bu proje GNU AFFERO GENERAL PUBLIC LICENSE Lisansı ile açık kaynak olarak paylaşılmıştır. Forklayabilir, geliştirebilir, katkı sağlayabilirsiniz.

---
