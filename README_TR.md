# 📖 **Dil:** [English](README.md) | [Deutsch](README_DE.md) | **Türkçe**



# 🚗 CO₂ Emisyonları – Doğrusal Regresyon



Bu proje, araçların CO₂ emisyonlarını doğrusal regresyon yöntemiyle analiz eden ve tahmin eden bir makine öğrenmesi çalışmasıdır. Motor büyüklüğü, yakıt tüketimi ve vites türü gibi araç özellikleri kullanılarak CO₂ emisyonlarının tahmin edilmesi amaçlanmıştır. Kullanılan veri seti 7.385 satır ve 12 sütundan oluşmakta olup çeşitli araç markaları, sınıfları ve yakıt türlerini kapsamaktadır. Proje kapsamında hem basit hem de çoklu doğrusal regresyon modeli geliştirilmiş, çapraz doğrulama ve artık analizi ile karşılaştırmalı olarak değerlendirilmiştir.



## 📋 Proje İçeriği



1. Veri Seti Hakkında
2. Kütüphanelerin İçe Aktarılması
3. Veri Setinin Yüklenmesi
4. Veri Setine Genel Bakış
5. Veri Temizleme ve Ön İşleme
6. Keşifsel Veri Analizi (EDA)
7. Modelleme Öncesi (Korelasyon Matrisi, Pairplot)
8. Basit Doğrusal Regresyon Modeli
9. Çoklu Doğrusal Regresyon Modeli
10. Final Model Tahmini



## 📊 Model Sonuçları



|Model|Hata Oranı|
|-|-|
|Basit Doğrusal Regresyon (yalnızca motor büyüklüğü)|\~%12|
|Çoklu Doğrusal Regresyon (motor büyüklüğü + yakıt tüketimi)|\~%8|



Çoklu doğrusal regresyon modeli daha verimli bulunarak final model olarak seçilmiştir. Model dört özellik kullanmaktadır: motor büyüklüğü, şehir içi, şehir dışı ve kombine yakıt tüketimi. Tahmin doğruluğu yaklaşık **%92** olarak hesaplanmıştır.



## 🛠️ Kullanılan Araçlar ve Kütüphaneler



* **Python**
* **Pandas, NumPy**
* **Matplotlib, Seaborn, Plotly**
* **Scikit-learn**
* **Yellowbrick**



## 📊 Veri Seti



[CO2 Emission by Vehicles – Kaggle](https://www.kaggle.com/datasets/debajyotipodder/CO2-emission-by-vehicles/data)



## 📧 İletişim



**Süha Çağrı Özbakışlar**



[!\[LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge\&logo=linkedin\&logoColor=white)](https://www.linkedin.com/in/ozbakislar)
[!\[GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge\&logo=github\&logoColor=white)](https://www.github.com/ozbakislar)
[!\[Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge\&logo=kaggle\&logoColor=white)](https://www.kaggle.com/ozbakislar)
[!\[Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge\&logo=tableau\&logoColor=white)](https://public.tableau.com/app/profile/ozbakislar)

