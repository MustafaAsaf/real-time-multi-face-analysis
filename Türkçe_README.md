# Gerçek Zamanlı Çoklu Yüz Analizi ve Grafik Raporlama

Bu proje, gerçek zamanlı kamera görüntüsü üzerinden **çoklu yüz algılama** yaparak her yüz için:
- Duygu analizi
- Yaş tahmini
- Cinsiyet tahmini

gerçekleştiren bir **bilgisayarla görme ve derin öğrenme** uygulamasıdır.

Analiz sırasında elde edilen veriler toplanmakta ve program sonlandığında **grafiksel raporlar** ile sunulmaktadır.

---

## 🚀 Özellikler

- Gerçek zamanlı webcam desteği
- Aynı karede birden fazla yüz algılama
- Her yüz için:
  - Duygu
  - Yaş
  - Cinsiyet analizi
- Performans için:
  - Thread kullanımı
  - Zaman kontrollü analiz
- Oturum sonunda:
  - Duygu dağılım grafiği
  - Yaş dağılım grafiği
  - Cinsiyet oranı grafiği
- CSV formatında veri kaydı

---

## 🧠 Kullanılan Teknolojiler

- Python
- OpenCV
- DeepFace
- Matplotlib
- Threading

---

## ⚙️ Kurulum

Gerekli kütüphaneleri yüklemek için:

```bash
pip install opencv-python deepface matplotlib
