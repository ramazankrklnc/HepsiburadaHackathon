# Hepsiburada Veri Bilimi Hackathon Projesi

## 🎯 Proje Hakkında
Bu proje, Hepsiburada Hackathon yarışması kapsamında geliştirilmiştir. Projede, e-ticaret alanında Doğal Dil İşleme (NLP) kullanılarak veri analizi ve tahminleme çalışmaları yapılmıştır.

## 📊 Veri Seti
Projede kullanılan veri setleri:
- `train.csv`: Model eğitimi için kullanılan ana veri seti
- `test.csv`: Modelin performansını değerlendirmek için kullanılan test veri seti

## 🚀 Özellikler
- Veri ön işleme ve temizleme
- Özellik mühendisliği
- Model eğitimi ve optimizasyonu
- Embedding tabanlı yaklaşım
- Tahmin sonuçlarının değerlendirilmesi

## 📁 Proje Yapısı
```
├── Code Files/
│   ├── colab_training.ipynb     # Ana model eğitim dosyası
│   └── KaggleEmbedding.ipynb    # Embedding ve veri hazırlama dosyası
├── data/
│   ├── test.csv                 # Test veri seti
│   └── train.csv                # Eğitim veri seti
└── Submission file/
    └── submission.csv           # Tahmin sonuçları
```

## 🛠️ Kullanılan Teknolojiler
- Python 3.x
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- TensorFlow/Keras
- Embedding teknikleri
- Transformers

## ⚙️ Kurulum
1. Repository'yi klonlayın:
```bash
git clone https://github.com/ramazankrklnc/hepsiburada-hackathon.git
```

2. Proje dizinine gidin:
```bash
cd hepsiburada-hackathon
```

3. Gerekli Python paketlerini yükleyin:
```bash
pip install pandas numpy scikit-learn tensorflow transformers
```

## 📝 Kullanım
1. Jupyter Notebook'u başlatın:
```bash
jupyter notebook
```

2. `Code Files` klasöründeki notebook'ları sırasıyla çalıştırın:
   - Önce `KaggleEmbedding.ipynb` ile veri hazırlama işlemlerini yapın
   - Ardından `colab_training.ipynb` ile model eğitimini gerçekleştirin

## 📈 Model Performansı
- Model değerlendirme metrikleri ve sonuçları `submission.csv` dosyasında bulunmaktadır
- Modelin performansı Hackathon değerlendirme kriterleri doğrultusunda ölçülmüştür

## 🤝 Katkıda Bulunma
1. Bu repository'yi forklayın
2. Yeni bir branch oluşturun (`git checkout -b feature/YeniÖzellik`)
3. Değişikliklerinizi commit edin (`git commit -m 'Yeni özellik eklendi'`)
4. Branch'inizi push edin (`git push origin feature/YeniÖzellik`)
5. Pull Request oluşturun.

