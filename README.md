# 📐 Euclidean Distance Calculator and Plotter

A simple Python program that calculates the Euclidean distance between two user-defined points on a 2D plane and visualizes the result with a matplotlib plot.

---

## 🚀 Features

- Takes two point coordinates (A and B) as input from the user
- Validates input — only numeric values are accepted
- Calculates the Euclidean distance using the standard formula
- Plots both points, the direct distance line, and the right-triangle components (horizontal and vertical differences)

---

## 🧮 Formula

$$d = \sqrt{(x_2 - x_1)^2 + (y_2 - y_1)^2}$$

---

## 📦 Requirements

- Python 3.x
- `matplotlib` library

Install the required library with:

```bash
pip install matplotlib
```

---

## ▶️ How to Run

```bash
python euclidean_distance.py
```

Then follow the prompts to enter the X and Y coordinates for Point A and Point B.

**Example:**

```
Enter the coordinates of Point A (x1, y1):
X1 value (Horizontal): 0
Y1 value (Vertical): 0

Enter the coordinates of Point B (x2, y2):
X2 value (Horizontal): 7
Y2 value (Vertical): 24

--- Result ---
The Euclidean distance between A(0.0, 0.0) and B(7.0, 24.0) is: 25.00
```

---

## 📊 Plot

After the calculation, a window will open showing:

| Element | Description |
|---|---|
| 🔴 Red dot | Point A |
| 🔵 Blue dot | Point B |
| ⬛ Black line | Direct distance between A and B |
| 🟢 Green dashed line | Horizontal difference (Δx) |
| 🟣 Purple dashed line | Vertical difference (Δy) |

---

## 📁 Project Structure

```
euclidean-distance/
│
├── euclidean_distance.py   # Main script
└── README.md               # This file
```

---

## 📝 Notes

- The program uses a `while` loop with `try/except` to handle invalid (non-numeric) input gracefully.
- The `math.sqrt()` function is used for the distance calculation.
- The plot is generated with `matplotlib.pyplot`.

---

## 📄 License

This project is open source and free to use for educational purposes.

---
---

# 📐 Öklid Mesafesi Hesaplayıcı ve Grafikleyici

Kullanıcının girdiği iki nokta arasındaki Öklid mesafesini hesaplayan ve sonucu matplotlib grafiğiyle görselleştiren basit bir Python programı.

---

## 🚀 Özellikler

- Kullanıcıdan iki noktanın koordinatlarını (A ve B) alır
- Geçersiz giriş kontrolü yapar — yalnızca sayısal değerler kabul edilir
- Öklid uzaklık formülü ile mesafeyi hesaplar
- İki noktayı, aralarındaki doğrudan mesafe çizgisini ve dik üçgen bileşenlerini (yatay ve dikey farklar) grafikte gösterir

---

## 🧮 Formül

$$d = \sqrt{(x_2 - x_1)^2 + (y_2 - y_1)^2}$$

---

## 📦 Gereksinimler

- Python 3.x
- `matplotlib` kütüphanesi

Gerekli kütüphaneyi yüklemek için:

```bash
pip install matplotlib
```

---

## ▶️ Çalıştırma

```bash
python euclidean_distance.py
```

Ardından ekrandaki yönergeleri takip ederek A ve B noktalarının X ve Y koordinatlarını girin.

**Örnek Kullanım:**

```
Enter the coordinates of Point A (x1, y1):
X1 value (Horizontal): 0
Y1 value (Vertical): 0

Enter the coordinates of Point B (x2, y2):
X2 value (Horizontal): 7
Y2 value (Vertical): 24

--- Result ---
The Euclidean distance between A(0.0, 0.0) and B(7.0, 24.0) is: 25.00
```

---

## 📊 Grafik

Hesaplama tamamlandıktan sonra bir pencere açılır ve şunlar gösterilir:

| Öğe | Açıklama |
|---|---|
| 🔴 Kırmızı nokta | A noktası |
| 🔵 Mavi nokta | B noktası |
| ⬛ Siyah çizgi | A ile B arasındaki doğrudan mesafe |
| 🟢 Yeşil kesikli çizgi | Yatay fark (Δx) |
| 🟣 Mor kesikli çizgi | Dikey fark (Δy) |

---

## 📁 Proje Yapısı

```
euclidean-distance/
│
├── euclidean_distance.py   # Ana betik
└── README.md               # Bu dosya
```

---

## 📝 Notlar

- Program, geçersiz (sayısal olmayan) girişleri düzgün şekilde ele almak için `while` döngüsü ve `try/except` bloğu kullanır.
- Mesafe hesaplaması için `math.sqrt()` fonksiyonundan yararlanılır.
- Grafik `matplotlib.pyplot` ile oluşturulur.

---

## 📄 Lisans

Bu proje açık kaynaklıdır ve eğitim amaçlı serbestçe kullanılabilir.
