````markdown
# Matematik Ödevi 1

**Ad Soyad:** Abdülkadir Ahmed Eyyub  
**Öğrenci Numarası:** 2507020016  
**Ders Adı:** Matematik  
**Dosya:** `soru-1.cpp`  
**Website:** [https://kadirmatemodev-1.vercel.app](https://kadirmatemodev-1.vercel.app)  
**Hızlı Açma (tarayıcıda yeni sekmede):** <a href="https://kadirmatemodev-1.vercel.app" target="_blank" rel="noopener noreferrer">kadirmatemodev-1.vercel.app</a>

---

## Proje Açıklaması

Bu proje, ikinci dereceden bir denklemin köklerini bulan basit bir **C++ programıdır**.  
Kullanıcıdan `a`, `b` ve `c` katsayıları alınır, ardından diskriminant hesaplanarak denklemin **gerçek kökleri** belirlenir.

Program, kullanıcıya denklemin:

- **Gerçek kökü yoksa**, bunu bildirir.  
- **Bir tane kökü varsa**, bu kökü ekrana yazar.  
- **İki farklı kökü varsa**, her iki kökü de gösterir.

---

## Kullanılan Kütüphaneler

```cpp
#include <iostream>  // Girdi ve çıktı işlemleri için
#include <cmath>     // Matematiksel işlemler (sqrt fonksiyonu için)
````

---

## Kodun Açıklaması

Programın temel adımları şu şekildedir:

1. Kullanıcıdan `a`, `b`, `c` katsayıları alınır.
2. Diskriminant değeri hesaplanır:
   [
   D = b^2 - 4ac
   ]
3. Diskriminant değerine göre sonuçlar ekrana yazdırılır:

   * Eğer `D < 0` → Gerçek kök yok.
   * Eğer `D == 0` → Bir tane gerçek kök var.
   * Eğer `D > 0` → İki farklı gerçek kök var.

---

## Örnek Çalışma

**Girdi:**

```
a katsayisini giriniz: 1
b katsayisini giriniz: -3
c katsayisini giriniz: 2
```

**Çıktı:**

```
Diskriminant = 1
Bu denklemin iki farkli gercek koku vardir.
1. Kok: x1 = 2
2. Kok: x2 = 1
```

---

## Matematiksel Arka Plan

İkinci dereceden bir denklem şu şekilde ifade edilir:

[
ax^2 + bx + c = 0
]

Bu denklemin köklerini bulmak için kullanılan formül:

[
x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}
]

Burada:

* `a`, `b`, `c` → denklemin katsayılarıdır.
* `b^2 - 4ac` → **diskriminant** olarak adlandırılır.
* Diskriminantın işaretine göre köklerin sayısı belirlenir.

---

## Derleme ve Çalıştırma

**Adımlar:**

1. Dosyayı kaydedin: `soru-1.cpp`
2. Terminal veya komut satırını açın.
3. Aşağıdaki komutu girin:

```bash
g++ soru-1.cpp -o soru-1
```

4. Programı çalıştırın:

```bash
./soru-1
```

---

## Sonuç

Bu program, kullanıcıdan alınan katsayılara göre ikinci dereceden bir denklemin köklerini bulur ve ekrana düzgün biçimde yazdırır.
Matematikte **diskriminant kavramını** ve **kök hesaplamayı** anlamak için temel bir örnektir.

---

```
```
