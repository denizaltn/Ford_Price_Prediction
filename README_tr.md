# Ford Focus Fiyat Tahmin Modeli 🚗💰

Bu proje, **Ford Focus** araçlarının fiyatlarını tahmin etmek için makine öğrenmesi tekniklerini kullanır.

Kaggle üzerinde yayınlanan [Used Car Dataset - Ford and Mercedes](https://www.kaggle.com/datasets/adityadesai13/used-car-dataset-ford-and-mercedes?select=ford.csv) veri seti kullanılmıştır.  

## 🔍 Projenin Amacı
İkinci el araç piyasasında fiyatların değişkenliği, alıcılar ve satıcılar için önemli bir sorun teşkil etmektedir. Bu proje, geçmiş verilerden faydalanarak araçların piyasa değerini tahmin etmeyi amaçlar.  

## 🛠️ Kullanılan Teknolojiler
- Python 3.11  
- Pandas, NumPy → Veri işleme  
- Matplotlib, Seaborn → Veri görselleştirme  
- Scikit-learn → Veri ön işleme, model seçimi  
- XGBoost → Fiyat tahmin modeli  

## 📊 Proje Aşamaları
1. **Veri Yükleme ve İnceleme**  
   - Kaggle’dan alınan Ford veri seti kullanıldı.  
   - Eksik ve hatalı veriler kontrol edildi.  

2. **Veri Ön İşleme**  
   - İlgili sütunlar seçildi: `year`, `mileage`, `tax`, `mpg`, `engineSize`.  
   - Eksik değerler temizlendi, kategorik veriler encode edildi.  

3. **Keşifsel Veri Analizi (EDA)**  
   - Değişkenlerin dağılım grafikleri incelendi.  
   - Korelasyon matrisi çıkarıldı.  

4. **Modelleme**  
   - Veriler eğitim ve test setine ayrıldı.  
   - XGBoost Regressor modeli kuruldu.  
   - Model eğitildi ve test verileri üzerinde değerlendirildi.  

5. **Değerlendirme**  
   - MSE ve RMSE metrikleri hesaplandı.  
   - Tahmin performansı grafiklerle gösterildi.  

