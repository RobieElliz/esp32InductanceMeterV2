# Portable ESP32 Inductance Meter

A DIY ESP32-based inductance meter designed to bridge the gap in electronics testing. Developed at the Polytechnic University of the Philippines, this low-cost, high-precision tool is ideal for students, researchers, and hobbyists.

---

## 🔧 Bridging the Gap in Electronics Testing

Accurate inductance measurement is crucial in electronics. Yet, professional meters are often expensive and inaccessible. This project provides an affordable alternative for educational and experimental applications.

---

## 🚀 What It Does

Using LC resonance principles, the device:
- Excites inductors and detects oscillations
- Calculates inductance with high accuracy
- Measures various types of inductors:
  - Toroidal
  - Power
  - Surface-mount (SMD)
  - Air-core  
- Employs dual reference capacitors (100nF & 5µF) for precise mH and µH readings

---

## 🛠 Key Features & Innovations

- **ESP32-powered processing** for real-time calculations  
- **Dual reference capacitors** to optimize accuracy  
- **Capacitive touch controls** for seamless operation  
- **Rechargeable 18650 battery** for true portability  
- **OLED display** for clear, instant readings  
- **Multiple measurement modes:** Single or continuous testing

---

## 📌 Why It Matters

By democratizing access to essential testing equipment, this project empowers the next generation of engineers to innovate and experiment without breaking the bank.

---

## Detailed Components

### 🔧 Dual Reference Capacitors (100nF & 5µF)
- **100nF:** For higher inductance (mH range) with enhanced accuracy  
- **5µF:** Ideal for lower inductance (µH range) ensuring frequency stability

### 🟢 TLV3202 Comparator
- Ultra-high-speed and low-power
- Ensures precise detection of LC oscillations

### ⚡ IP2312 Battery Management IC
- Supports USB Type-C charging (5V, up to 3A)
- Provides overvoltage, undervoltage, and overcurrent protection
- Delivers a stable 3.3V output with buck-boost regulation

### 📟 2.4-inch OLED Display
- Connected via I²C for reduced wiring complexity
- Stacked on the PCB using screws for a compact design
- Displays real-time inductance, frequency, and battery status

---

## Additional Resources

- **Project Files & BOM:**  
  [Google Drive Folder](https://drive.google.com/drive/folders/1Q7-kwRnVLeR-DjHSxVJFgb-IRqVza03g?usp=sharing)

- **OLED Module Purchase:**  
  [Shopee: 2.4" 2.42 inch 128x64 OLED LCD Display Module SSD1309](https://shopee.ph/2.4-2.42-inch-128x64-OLED-LCD-Display-Module-SSD1309-12864-7-Pin-SPI-IIC-I2C-Serial-Interface-for-Arduino-UNO-R3-C51-i.517103615.18774113725?sp_atk=a92714bc-abb0-4431-8565-57df95d88b4a&xptdk=a92714bc-abb0-4431-8565-57df95d88b4a)

---

## License

This project is open source. See the [LICENSE](LICENSE) file for more details.
