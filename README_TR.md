# Öğrenci Performans Tahmin Projesi

[English](README.md)

Bu makine öğrenmesi projesi, çeşitli demografik ve eğitimsel faktörlere dayalı olarak öğrencilerin matematik performansını tahmin etmeye odaklanmaktadır. Veri analizinden model dağıtımına kadar eksiksiz bir uçtan uca makine öğrenmesi uygulamasını göstermektedir.

## Proje Genel Bakış
Proje, cinsiyet, ırk/etnik köken, ebeveyn eğitim düzeyi ve test hazırlık kursu tamamlama gibi özellikleri kullanarak matematik puanlarını tahmin etmek için öğrenci akademik performans verilerini analiz eder. Uygulanan çözüm, kapsamlı keşifsel veri analizi (EDA), veri ön işleme, model eğitimi ve tahminler için web arayüzü içerir.

## Teknoloji Yığını
- **Python** - Ana programlama dili
- **Scikit-learn** - Makine öğrenmesi uygulamaları
- **Pandas & NumPy** - Veri manipülasyonu ve sayısal işlemler
- **Matplotlib & Seaborn** - Veri görselleştirme
- **Flask** - Web uygulama çerçevesi
- **HTML/CSS** - Önyüz arayüzü

## Özellikler
- **Veri Analizi**: Görselleştirmelerle kapsamlı EDA
- **Önişleme Pipeline'ı**: Veri hazırlama için özel dönüştürücüler
- **Model Eğitimi**: Çeşitli ML algoritmalarının uygulanması
- **Web Arayüzü**: Tahminler için kullanıcı dostu arayüz
- **Hata Yönetimi**: Özel istisna yönetimi
- **Loglama**: Detaylı izleme için loglama

## Proje Yapısı
```
mlproject/
├── artifacts/          # Model artifactları ve işlenmiş veri
├── notebook/          # EDA ve modelleme için Jupyter not defterleri
│   ├── data/         # Ham veri seti
│   └── EDA & Model Eğitim not defterleri
├── src/              # Kaynak kod
│   ├── components/   # Temel bileşenler
│   └── pipeline/     # Tahmin pipeline'ı
├── templates/        # HTML şablonları
├── logs/            # Uygulama logları
├── requirements.txt  # Proje bağımlılıkları
└── application.py   # Flask uygulaması
```

## Kurulum
1. Repository'yi klonlayın
```bash
git clone https://github.com/berkay000/mlproject.git
cd mlproject
```

2. Sanal ortam oluşturun ve aktifleştirin (Windows)
```bash
python -m venv venv
.\venv\Scripts\activate
```

3. Bağımlılıkları yükleyin
```bash
pip install -r requirements.txt
```

4. Uygulamayı çalıştırın
```bash
python application.py
```

## Kullanım
1. Web arayüzüne `http://localhost:5000` adresinden erişilebilir
2. Verilen forma öğrenci bilgilerini girin
3. Matematik performansı için anlık tahminler alın

## Model Bilgisi
- Algoritma: Linear Regression, Random Forest ve CatBoost dahil olmak üzere çeşitli modeller kullanılarak optimize edildi
- Özellikler: Demografik ve eğitimsel faktörleri içeren 8 giriş değişkeni
- Metrikler: R2 Score, MAE ve RMSE kullanılarak değerlendirildi

## Geliştirme İş Akışı
1. Jupyter not defterlerinde veri keşfi ve temizleme
2. Özellik mühendisliği ve önişleme pipeline'ı oluşturma
3. Model eğitimi ve hiperparametre optimizasyonu
4. Hata yönetimi ve loglama implementasyonu
5. Web arayüzü geliştirme
6. Test ve dağıtım

## Gelecek İyileştirmeler
- [ ] Model yeniden eğitim pipeline'ı implementasyonu
- [ ] Daha fazla görselleştirme seçeneği ekleme
- [ ] Tahmin açıklamalarını geliştirme
- [ ] Bulut platformuna dağıtım
- [ ] Kullanıcı kimlik doğrulaması ekleme
- [ ] API endpoint'leri implementasyonu


## İletişim
- LinkedIn: [Berkay Akparlar](https://www.linkedin.com/in/berkay-akparlar)
- Email: [bakparlarr@gmail.com](mailto:bakparlarr@gmail.com)

## Lisans
Bu proje MIT Lisansı altında lisanslanmıştır. Detaylar için LICENSE dosyasına bakınız.

---
**Not**: Bu proje, makine öğrenmesi ve yazılım mühendisliği yeteneklerini göstermek için bir veri bilimi portföyünün parçası olarak geliştirilmiştir.