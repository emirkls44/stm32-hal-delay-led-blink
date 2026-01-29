# STM32 HAL Delay LED Blink

STM32F0 serisi mikrodenetleyici kullanılarak **HAL kütüphanesi** ile
`HAL_Delay()` fonksiyonu üzerinden yapılan temel LED blink uygulaması.

> 🎯 Amaç: STM32 HAL yapısını öğrenmek ve minimum seviyede çalışan,
temiz bir örnek oluşturmak.

---

## 🧩 Donanım

- Mikrodenetleyici: **STM32F051R8**
- Geliştirme Kartı: NUCLEO / Custom board
- IDE: **STM32CubeIDE**
- Programlayıcı: **ST-LINK**

---

## ⚙️ Proje İçeriği

- HAL tabanlı LED kontrolü
- `HAL_Delay()` ile zamanlama
- CubeMX ile oluşturulmuş proje yapısı
- Minimal ve anlaşılır kod

---

## 📁 Proje Yapısı

```text
Core/
 ├── Inc/
 └── Src/
Drivers/
STM32F051R8TX_FLASH.ld
