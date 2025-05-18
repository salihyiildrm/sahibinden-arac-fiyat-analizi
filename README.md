# Sahibinden Araç Fiyat Analizi

Bu proje, Sahibinden.com'daki ikinci el araç ilanlarını otomatik olarak toplayıp bu veriler üzerinden analiz yapar. Amaç, piyasadaki uygun fiyatlı araçları belirlemek ve veri görselleştirme ile anlamlı içgörüler elde etmektir.

## 🚀 Kullanılan Teknolojiler
- Python
- Requests / BeautifulSoup
- Pandas
- Matplotlib / Seaborn

## 🎯 Amaç
- Marka, model, yıl, km, vites, fiyat gibi verileri çekmek
- Temizleme ve analiz işlemleri yapmak
- Ortalama fiyatları, km aralıklarını ve yıllara göre fiyat değişimini grafiklerle göstermek

## 🛠️ Klasör Yapısı

sahibinden-arac-fiyat-analizi/
│
├── data/
│ └── ilanlar.csv # Çekilen ilan verisi (örnek CSV)
│
├── src/
│ └── scraper.py # Sahibinden verisi çeken script
│ └── analiz.py # Veriyi işleyen ve analiz eden kod
│
├── README.md # Proje açıklaması ve kullanım talimatı
└── requirements.txt # Gerekli kütüphaneler


## 🧪 Kullanım

```bash
python src/scraper.py
python src/analiz.py


👨‍💻 Geliştiren
Salih Yıldırım – 2025
