# Machine Learning Model Comparison

Bu proje, farklı makine öğrenmesi algoritmalarını kullanarak bir maaş tahmin veri seti üzerinde çalışmaktadır. Hedef, her modelin performansını **R² (determinasyon katsayısı)** ile karşılaştırmaktır.

## Kullanılan Algoritmalar:
1. **Linear Regression**: Basit doğrusal ilişkiyi modellemek için.
2. **Polynomial Regression**: Doğrusal olmayan ilişkiler için.
3. **Support Vector Regression (SVR)**: Daha karmaşık tahmin modelleri için.
4. **Decision Tree**: Veri setini bölerek tahmin yapan ağaç yapısı.
5. **Random Forest**: Birden fazla karar ağacının birlikte çalıştığı yöntem.

## Model Performansları:
| Model               | R² Değeri            |
|---------------------|----------------------|
| Linear Regression   | 0.5857              |
| Polynomial Regression | 0.9990            |
| SVR                 | 0.6287              |
| Decision Tree       | 1.0                 |
| Random Forest       | 0.9475              |


## Veri Seti:
Kullanılan veri seti şu sütunları içermektedir:
- **UnvanSeviyesi**: Çalışanın unvan seviyesi.
- **Kıdem**: Çalışanın kıdem yılı.
- **Puan**: Çalışanın performans puanı.
- **Maaş**: Hedef değişken (tahmin edilecek değer).

## Gereksinimler:
- Python 3.x
- Scikit-learn
- Numpy
- Pandas


