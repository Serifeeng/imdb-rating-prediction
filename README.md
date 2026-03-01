# IMDb Rating Prediction

## Proje Açıklaması
Bu proje, **IMDb Top 1000 Movies & TV Shows** veri setini kullanarak filmlerin IMDb puanlarını tahmin etmeyi amaçlar.  
Projede **sayısal ve kategorik özellikler** kullanılarak regression modelleri oluşturulmuştur.  

---

## Kullanılan Özellikler (Features)
- `Runtime` – Film süresi (dakika)  
- `No_of_Votes` – Oy sayısı  
- `Gross` – Gişe hasılatı  
- `Meta_score` – Eleştirmen puanı  
- `Genre` – Film türleri (Action, Drama, Comedy …)  
- `Director` – Film yönetmeni  

---

## Hedef (Target)
- `IMDB_Rating` – Filmin IMDb puanı (1–10 arası)  

---

## Modelleme
- **Linear Regression** – Basit doğrusal model  
- **Random Forest Regression** – Daha güçlü ve yüksek doğruluklu model  

---

## Sonuçlar
- Model, test verisi üzerinde iyi bir tahmin performansı gösterdi (R2 ve RMSE ile ölçüldü).  
- Feature importance analizi ile hangi özelliklerin IMDb puanını daha çok etkilediği belirlendi.  
- Görselleştirmeler (scatter plot) ile tahmin edilen ve gerçek puanlar karşılaştırıldı.
