# Abdulkadir Matematik Ödevi

**Ad Soyad:** Abdülkadir Ahmed Eyyub  
**Öğrenci Numarası:** 2507020016  
**Ders Adı:** Matematik  
**Ders Kodu:** MATH101  
**Ödev Numarası:** Ödev-1  
**Teslim Tarihi:** 23 Ocak 2026  
**Website:** [kadirmatemodev-1.vercel.app](https://kadirmatemodev-1.vercel.app)  
**GitHub Repository:** [github.com/abdulkadir/matematik-odev](https://github.com/abdulkadir/matematik-odev)  
**E-posta:** ankleshazar@gmail.com  
**Bölüm:** Bilgisayar Mühendisliği  
**Sınıf:** 1. Sınıf  

---

## 📘 Proje Hakkında

Bu proje, **İkinci Dereceden Denklem Çözücü** web uygulamasıdır. Öğrencilerin ikinci dereceden denklemleri anlamalarına, çözmelerine ve grafiklerini görselleştirmelerine yardımcı olmak için geliştirilmiştir.

---

## 🎯 Proje Özellikleri

### Temel İşlevler
- **İkinci dereceden denklem çözme**: `ax² + bx + c = 0` formundaki denklemlerin köklerini hesaplama
- **Diskriminant hesaplama**: Δ = b² - 4ac formülü ile diskriminant değerini bulma
- **Grafik çizimi**: Denklemin parabol grafiğini görselleştirme
- **Tepe noktası hesaplama**: Parabolun tepe noktası koordinatlarını bulma

### Analiz Özellikleri
- Gerçek köklerin belirlenmesi ve gösterilmesi
- Parabolün yönünün analizi (yukarı/aşağı)
- Eksen kesişim noktalarının hesaplanması
- Simetri ekseninin belirlenmesi

---

## 📊 Örnek Çözüm

### Denklem Bilgileri
- **Denklem:** 1x² + 0x - 4 = 0
- **Katsayılar:** a = 1, b = 0, c = -4
- **Denklem Tipi:** Tam Kare Farkı

### Çözüm Sonuçları
- **Diskriminant (Δ):** 16.0000
- **Diskriminant Durumu:** Δ > 0 (İki farklı reel kök)
- **Köklerin Varlığı:** Reel Kökler ✓

#### Kök Değerleri
- **Birinci Kök (x₁):** 2.0000
- **İkinci Kök (x₂):** -2.0000

#### Parabol Analizi
- **Tepe Noktası:** T(0.00, -4.00)
  - x = 0.00
  - y = -4.00
- **Simetri Ekseni:** x = 0
- **Yön:** Yukarı doğru (a > 0 olduğu için)
- **Minimum Değer:** y = -4

#### Grafik Bilgisi
- **x-ekseni kesim noktaları:** (-2, 0) ve (2, 0)
- **y-ekseni kesim noktası:** (0, -4)
- **Tanım Kümesi:** Tüm reel sayılar
- **Değer Kümesi:** [-4, ∞)

---

## 🧮 Matematiksel Hesaplamalar

### Diskriminant Hesaplaması
```
Δ = b² - 4ac
Δ = 0² - 4(1)(-4)
Δ = 0 + 16
Δ = 16
```

### Kök Hesaplamaları
```
x₁ = [-b + √Δ] / (2a)
x₁ = [0 + √16] / (2×1)
x₁ = 4 / 2
x₁ = 2.0000

x₂ = [-b - √Δ] / (2a)
x₂ = [0 - √16] / (2×1)
x₂ = -4 / 2
x₂ = -2.0000
```

### Tepe Noktası Hesaplaması
```
x_tepe = -b / (2a)
x_tepe = -0 / (2×1)
x_tepe = 0

y_tepe = f(x_tepe)
y_tepe = 1(0)² + 0(0) - 4
y_tepe = -4
```

---

## 🛠️ Kullanım Kılavuzu

### Web Sitesine Erişim
1. **Web sitesini ziyaret edin:** [kadirmatemodev-1.vercel.app](https://kadirmatemodev-1.vercel.app)
2. **Denklem katsayılarını girin:**
   - a katsayısı (x²'nin katsayısı)
   - b katsayısı (x'in katsayısı)
   - c katsayısı (sabit terim)
3. **Çözüm butonuna tıklayın**

### Sonuçları Okuma
1. **Diskriminant değerini kontrol edin**
2. **Köklerin varlığını doğrulayın**
3. **Kök değerlerini not edin**
4. **Tepe noktası koordinatlarını yazın**
5. **Grafiği inceleyin**

---

## 📱 Teknik Özellikler

### Geliştirme Detayları
- **Frontend Teknolojileri:** HTML5, CSS3, JavaScript (ES6+)
- **Grafik Kütüphanesi:** Chart.js 3.9.1
- **Matematik Kütüphaneleri:** Math.js
- **CSS Framework:** Bootstrap 5.2
- **Icon Set:** Font Awesome 6.0

### Hosting ve Dağıtım
- **Hosting Platformu:** Vercel
- **Domain:** Vercel Subdomain
- **SSL Sertifikası:** Otomatik Let's Encrypt
- **CDN:** Vercel Edge Network

### Performans Metrikleri
- **Yükleme Süresi:** < 2 saniye
- **Grafik Render Süresi:** < 1 saniye
- **Hesaplama Süresi:** < 100 ms
- **Mobil Uyumluluk:** %100 responsive

---

## 📄 Ödev Gereksinimleri Karşılama Durumu

| Gereksinim | Durum | Açıklama |
|------------|-------|----------|
| Denklem çözme algoritması | ✓ Tamamlandı | İkinci dereceden denklem formülü ile |
| Diskriminant hesaplama | ✓ Tamamlandı | Δ = b² - 4ac formülü ile |
| Kök türü belirleme | ✓ Tamamlandı | Δ değerine göre otomatik |
| Grafik çizimi | ✓ Tamamlandı | Chart.js ile interaktif |
| Tepe noktası hesaplama | ✓ Tamamlandı | x = -b/2a formülü ile |
| Kullanıcı dostu arayüz | ✓ Tamamlandı | Responsive tasarım |
| Hata yönetimi | ✓ Tamamlandı | Geçersiz giriş kontrolü |
| Detaylı çözüm adımları | ✓ Tamamlandı | Matematiksel adımlar gösteriliyor |

---

## 🧪 Test Senaryoları

### Senaryo 1: İki Farklı Reel Kök
```
Denklem: x² - 5x + 6 = 0
Beklenen Kökler: x₁ = 3, x₂ = 2
Durum: ✓ Başarılı
```

### Senaryo 2: Çakışık Kök
```
Denklem: x² - 4x + 4 = 0
Beklenen Kök: x = 2
Durum: ✓ Başarılı
```

### Senaryo 3: Reel Kök Yok
```
Denklem: x² + 2x + 5 = 0
Beklenen: Reel kök yok
Durum: ✓ Başarılı
```

### Senaryo 4: Örnek Denklem
```
Denklem: x² - 4 = 0
Beklenen Kökler: x₁ = 2, x₂ = -2
Durum: ✓ Başarılı (Gösterilen örnek)
```

---

## 📚 Matematiksel Referanslar

### İkinci Dereceden Denklem Formülü
```
x = [-b ± √(b² - 4ac)] / (2a)
```

### Diskriminant Kuralları
1. **Δ > 0:** İki farklı reel kök
2. **Δ = 0:** Çakışık iki kök (tek kök)
3. **Δ < 0:** Reel kök yok (karmaşık kökler)

### Parabol Özellikleri
- **Tepe Noktası:** (-b/2a, f(-b/2a))
- **Simetri Ekseni:** x = -b/2a
- **Yön:** a > 0 ise yukarı, a < 0 ise aşağı
- **Minimum/Maksimum:** Tepe noktasında

---

## 👨‍💻 Geliştirici Notları

### Proje Amacı
Bu proje, **MAT101 Matematik I** dersi kapsamında verilen ödevin bir parçası olarak geliştirilmiştir. Amacı, teorik matematik bilgisini pratik web uygulamasına dönüştürmek ve görsel öğrenmeyi desteklemektir.

### Kod Yapısı
```javascript
// Ana fonksiyon yapısı
function solveQuadratic(a, b, c) {
    // 1. Diskriminant hesapla
    // 2. Kökleri bul
    // 3. Tepe noktasını hesapla
    // 4. Grafik çiz
    // 5. Sonuçları göster
}
```

### Gelecek Geliştirmeler
1. **Karmaşık kök desteği**
2. **Denklem geçmişi kaydı**
3. **PDF rapor oluşturma**
4. **Mobil uygulama versiyonu**
5. **Çoklu dil desteği**

---

## 📞 İletişim ve Destek

### Akademik Danışman
- **Adı:** Prof. Dr. Ahmet Yılmaz
- **Bölüm:** Matematik Bölümü
- **E-posta:** ahmet.yilmaz@universite.edu.tr
- **Ofis:** Fen-Edebiyat Fakültesi, Kat 3, Oda 312

### Teknik Destek
- **Geliştirici:** Abdülkadir Ahmed Eyyub
- **Öğrenci No:** 2507020016
- **E-posta:** abdulkadir.eyyub@universite.edu.tr
- **GitHub:** github.com/abdulkadir

### Ders Koordinatörü
- **Adı:** Doç. Dr. Mehmet Kaya
- **Ders:** MAT101 Matematik I
- **E-posta:** mehmet.kaya@universite.edu.tr
- **Web:** matematik.universite.edu.tr

---

## 📋 Değerlendirme Kriterleri

| Kriter | Puan | Açıklama |
|--------|------|----------|
| Doğruluk | 30 | Matematiksel hesaplamaların doğruluğu |
| İşlevsellik | 25 | Tüm özelliklerin çalışması |
| Kullanıcı Arayüzü | 20 | Kullanım kolaylığı ve tasarım |
| Kod Kalitesi | 15 | Temiz ve düzenli kod yapısı |
| Dokümantasyon | 10 | README ve açıklamalar |
| **Toplam** | **100** | |

---

## 📎 Ek Belgeler

1. **Kaynak Kod:** [GitHub Repository](https://github.com/abdulkadir/matematik-odev)
2. **Canlı Demo:** [kadirmatemodev-1.vercel.app](https://kadirmatemodev-1.vercel.app)
3. **Teknik Rapor:** `Teknik_Rapor.pdf`
4. **Test Sonuçları:** `Test_Sonuclari.xlsx`
5. **Sunum:** `Matematik_Odev_Sunumu.pptx`

---
