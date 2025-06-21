# 🧠 CNN ile Yapay Görsel Problemlerin Çözümü

Bu projede, farklı yapay görsel problemleri çözmek için PyTorch kullanılarak Convolutional Neural Network (CNN) modelleri eğitilmiştir. Her problem, 25x25 boyutundaki siyah-beyaz matrisler (görüntüler) üzerinde çalışır ve her biri farklı bir sayısal ya da sınıflandırma problemi içerir.

## 🎯 Amaç

Farklı görsel problemleri tanımlayıp, her biri için özel veri üretme fonksiyonlarıyla eğitim verileri oluşturarak CNN tabanlı bir modelin bu problemleri öğrenip öğrenemeyeceğini test etmek.

## 📂 Problemler

### 🟡 Problem A: 
25x25 matris üzerinde rastgele yerleştirilmiş **2 nokta** arasında Öklid mesafesini tahmin etme.

### 🟡 Problem B:
Matris üzerinde 3 ila 10 adet **rastgele nokta** bulunur. Modelin, **birbirine en yakın iki nokta** arasındaki mesafeyi tahmin etmesi beklenir.

### 🟡 Problem C:
Matris üzerindeki noktalar arasında **en uzak iki nokta** arasındaki mesafe tahmin edilir.

### 🟡 Problem D:
1 ila 10 adet nokta içeren matrislerde, **toplam nokta sayısının** doğru tahmin edilmesi hedeflenir.

### 🟡 Problem E:
1 ila 10 adet **farklı boyutlarda kare** içeren matrislerde, **toplam kare sayısının** tahmini gerçekleştirilir. Kareler birbirini kesebilir.

## ⚙️ Kullanılan Teknolojiler

- Python
- PyTorch
- NumPy
- Matplotlib

## 🧪 Model Detayları

- CNN mimarisi: 2D convolution + ReLU + MaxPooling + Fully Connected katmanlar
- Kayıp Fonksiyonları: MSELoss, CrossEntropy (probleme göre)
- Optimizasyon: Adam
- Cihaz: GPU/CPU otomatik seçimi

## 🚀 Nasıl Çalıştırılır?

1. Gerekli paketleri yükleyin:
```bash
pip install torch torchvision numpy matplotlib
```
2. Data dosyasının bulunduğuna emin olun.
   
3. Notebook'u çalıştırın: `CNN.ipynb`

4. Her bir problem için ayrı veri üretme fonksiyonu ve model eğitimi bölümü bulunmaktadır.

## 📬 İletişim

**Burakhan Saruhan**  
📧 burakhansaruhan271@gmail.com
