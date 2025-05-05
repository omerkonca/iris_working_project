# YMT5270 - Vize Projesi (Makine Öğrenmesi Uygulaması)

Bu proje, YMT5270 "Yenilikçi Makine Öğrenme Ortamları" dersi kapsamında, Orange Data Mining aracı kullanılarak gerçekleştirilmiştir. Amacımız, hazır bir veri seti üzerinde sınıflandırma modelleri kullanarak en iyi sonucu veren modeli belirlemektir.

---

## 📁 Kullanılan Araçlar ve Ortamlar

- **Orange Data Mining** v3.x
- Görsel (kod yazmadan) makine öğrenmesi
- Windows 10 işletim sistemi
- Veri seti: `iris.tab` (Orange ile birlikte gelen örnek veri seti)

---

## 📊 Kullanılan Veri Seti: Iris

Bu veri seti, 3 farklı iris çiçeği türünün (setosa, versicolor, virginica) sınıflandırılmasını içermektedir. Her örnek şu özellikleri içerir:

- `sepal length`
- `sepal width`
- `petal length`
- `petal width`
- `class` (hedef değişken – çiçek türü)

---

## 🔧 Uygulama Adımları

1. Orange açıldı ve boş bir proje oluşturuldu.
2. `File` bileşeni ile `iris.tab` veri seti yüklendi.
3. `Data Table` ile veri gözlemlendi.
4. `Select Columns` bileşeni ile `class` sütunu hedef (target) olarak belirlendi.
5. 3 farklı model eklendi:
   - Logistic Regression
   - Random Forest
   - Naive Bayes
6. Bu modeller, `Test & Score` bileşeni ile karşılaştırıldı.
7. Sonuçlar gözlemlendi ve başarı oranları analiz edildi.

---

## 🧪 Elde Edilen Sonuçlar (örnek veriler)

| Model               | Accuracy (CA) | AUC    | F1 Score |
|---------------------|---------------|--------|----------|
| Logistic Regression | 0.96          | 0.99   | 0.96     |
| Random Forest       | 0.97          | 1.00   | 0.97     |
| Naive Bayes         | 0.95          | 0.98   | 0.95     |

✅ **En iyi sonuç veren model:** `Random Forest`

---

## 🖼️ Ekran Görüntüleri

`img/` klasörü içinde tüm adımların ekran görüntüleri mevcuttur:

- Veri seti yükleme
- Model bağlantıları
- Test & Score ekranı
- Confusion Matrix çıktısı

---

## 📁 Dosya Yapısı


---

## 👨‍💻 Hazırlayan

- **Ad Soyad**: Ömer Faruk Konca  
- **Numara**: [Numaranız buraya]  
- **Ders**: YMT5270 – Yenilikçi Makine Öğrenme Ortamları  
- **Danışman**: Dr. Öğr. Üyesi Ferhat Uçar  
