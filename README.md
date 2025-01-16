# [Ek Ders Hesaplama](https://ekdershesaplama.com)

## ✨ Giriş
[Ek Ders Hesaplama](https://ekdershesaplama.com), öğretmenlerin ek ders saatlerini ve ödemelerini kolayca hesaplamasına yardımcı olan basit ve verimli bir araçtır. Bu program, süreci otomatikleştirerek manuel işlemleri azaltır ve hesaplamalarda doğruluğu sağlar.

[![Ek Ders Hesaplama](https://ekdershesaplama.com/1.png)](https://ekdershesaplama.com)

## 💡 Özellikler
- Girilen verilere göre ek ders saatlerini hesaplama
- Otomatik maaş ve ek ödeme hesaplamaları
- Kullanıcı dostu arayüz
- Farklı formatlarda çıktı alma (CSV, PDF vb.)
- Farklı öğretmen kategorilerini ve ücretlerini destekleme

## 📚 Kurulum
**[Ek Ders Hesaplama](https://ekdershesaplama.com)** programını kurmak ve kullanmak için aşağıdaki adımları izleyin:

### Gereksinimler
Sisteminizde aşağıdaki yazılımların yüklü olduğundan emin olun:
- Python 3.x
- Gerekli bağımlılıklar (`requirements.txt` içinde listelenmiştir)

### Kurulum Adımları
1. Depoyu klonlayın:
   ```bash
   git clone https://github.com/yourusername/ek-ders-hesaplama.git
   cd ek-ders-hesaplama
   ```
2. Bağımlılıkları yükleyin:
   ```bash
   pip install -r requirements.txt
   ```
3. Programı çalıştırın:
   ```bash
   python main.py
   ```

## 🔧 Kullanım
1. Çalışılan saatler, öğretmen kategorisi ve geçerli ücretleri girin.
2. Sistem toplam kazancı otomatik olarak hesaplar.
3. Sonuçları ekranda görüntüleyin veya rapor olarak dışa aktarın.

Örnek kullanım:
```python
from ekders import calculate_extra_hours

# Örnek hesaplama
hours = 10  # Ek ders saat sayısı
rate_per_hour = 50  # Saat başına ödeme

total_payment = calculate_extra_hours(hours, rate_per_hour)
print(f"Toplam Ödeme: {total_payment} TL")
```

## 📝 Yapılandırma
Ücret değerlerini ve kategorileri `config.json` dosyasını düzenleyerek özelleştirebilirsiniz.
Örnek:
```json
{
  "standard_rate": 50,
  "overtime_rate": 75
}
```

## ⚙ Yol Haritası
Planlanan geliştirmeler:
- Web tabanlı sürüm
- Çoklu dil desteği
- Gelişmiş raporlama sistemi
- Okul veritabanlarıyla entegrasyon

## 🚀 Katkıda Bulunma
Katkılarınızı bekliyoruz! Katkıda bulunmak için:
1. Depoyu forklayın.
2. Yeni bir dal oluşturun (`feature/yeni-ozellik`).
3. Değişikliklerinizi kaydedin.
4. Dalınızı yükleyin ve bir çekme isteği oluşturun.

## 🌟 Teşekkürler
Geliştirme sürecinde geri bildirim sağlayan tüm katkıda bulunanlara ve eğitimcilere özel teşekkürler.

## 🌐 Lisans
Bu proje MIT Lisansı altında lisanslanmıştır. Daha fazla detay için `LICENSE` dosyasına bakabilirsiniz.

