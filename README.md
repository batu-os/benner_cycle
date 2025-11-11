# Benner Cycle Tester 🎯

Benner Cycle hipotezini test etmek için geliştirilmiş interaktif bir web uygulaması. Bu araç, tarihsel verilere dayanarak "risk-on" (büyüme) ve "risk-off" (güvenli liman) dönemlerinde farklı varlık sınıflarının performansını karşılaştırmanıza olanak tanır.

## 📖 Benner Cycle Nedir?

Benner Cycle, 1800'lü yıllarda Samuel Benner tarafından geliştirilen ve ekonomik döngülerin belirli bir düzen içinde tekrarladığını öngören bir hipotezdir. Benner, tarım ürünleri ve demir fiyatlarındaki dalgalanmaları inceleyerek ekonomik döngülerin tahmin edilebilir olduğunu savunmuştur.

Bu hipotez, belirli yıllarda ekonominin "iyi" (genişleme) ve "kötü" (daralma) dönemlerden geçeceğini öngörür. Bu test aracı, bu döngülere göre varlık tahsisi yapmanın uzun vadede daha iyi getiri sağlayıp sağlamadığını test etmenize olanak tanır.

## ✨ Özellikler

- **4 Farklı Strateji Karşılaştırması:**
  - 🎯 Benner Strategy: Döngüye göre aktif geçiş stratejisi
  - 🔄 Benner Reverse: Kontrol grubu (ters strateji)
  - 📈 Buy & Hold Risk-On: Pasif yüksek riskli varlık stratejisi
  - 🛡️ Buy & Hold Risk-Off: Pasif güvenli liman stratejisi

- **Geniş Varlık Seçenekleri:**
  - Risk-On: SPY, QQQ, EEM, IWM, SPXL, TQQQ
  - Risk-Off: GC=F (Altın), USD (ABD Doları)

- **Esnek Parametreler:**
  - Başlangıç bakiyesi: $10,000 - $1,000,000
  - Dönem seçimi: 1999 - Günümüz (11.11.2025)
  - Rejim değişim zamanlaması: Yılbaşı, Yıl Ortası, Yılsonu

- **Detaylı Analiz:**
  - Getiri karşılaştırmaları
  - İşlem geçmişi
  - Yüzdelik performans göstergeleri
  - Çarpan (multiplier) hesaplamaları

- **Çok Dilli Destek:**
  - 🇹🇷 Türkçe
  - 🇬🇧 English

## 🚀 Kullanım

1. **Parametreleri Ayarlayın:**
   - Başlangıç bakiyenizi seçin
   - Test döneminizi belirleyin (başlangıç ve bitiş yılı)
   - Rejim değişim zamanlamasını seçin
   - Risk-On ve Risk-Off varlıklarınızı seçin

2. **Hesapla Butonuna Tıklayın:**
   - Sonuçlar otomatik olarak hesaplanır
   - 4 farklı strateji karşılaştırmalı olarak gösterilir

3. **Sonuçları İnceleyin:**
   - Her stratejinin nihai bakiyesini görün
   - Getiri yüzdelerini ve çarpanları karşılaştırın
   - İşlem geçmişini detaylı inceleyin

## 📊 Stratejiler

### 🎯 Benner Strategy
Benner döngüsüne göre "iyi" zamanlarda risk-on varlıklara, "kötü" zamanlarda risk-off varlıklara geçiş yapan aktif strateji. Hipotezin doğruluğunu test etmek için kullanılır.

**Döngü Takvimi:**
- 1999-2005: Risk-Off Dönemi
- 2005-2007: Risk-On Dönemi
- 2007-2012: Risk-Off Dönemi
- 2012-2019: Risk-On Dönemi
- 2019-2023: Risk-Off Dönemi
- 2023-Sonrası: Risk-On Dönemi

### 🔄 Benner Reverse
Benner stratejisinin tersi: "iyi" zamanlarda risk-off, "kötü" zamanlarda risk-on. Kontrol grubu olarak kullanılır ve hipotezin rastgele olmadığını doğrulamaya yardımcı olur.

### 📈 Buy & Hold Risk-On
Sürekli olarak seçilen risk-on varlığı tutan pasif strateji. Aktif stratejinin performansını ölçmek için referans noktası olarak kullanılır.

### 🛡️ Buy & Hold Risk-Off
Sürekli olarak seçilen risk-off varlığı tutan pasif strateji. Güvenli liman yaklaşımının uzun vadeli performansını gösterir.

## 📈 Varlıklar

### Risk-On (Büyüme Odaklı)
- **SPY**: S&P 500 ETF - Geniş piyasa endeksi
- **QQQ**: NASDAQ-100 ETF - Teknoloji ağırlıklı
- **EEM**: Emerging Markets ETF - Gelişen piyasalar
- **IWM**: Russell 2000 ETF - Küçük kaplar
- **SPXL**: S&P 500 3x Leveraged ETF - Yüksek volatilite
- **TQQQ**: NASDAQ-100 3x Leveraged ETF - En yüksek risk

### Risk-Off (Güvenli Liman)
- **GC=F**: Altın - Geleneksel güvenli liman
- **USD**: ABD Doları - Nakit pozisyon

## 🔧 Teknik Detaylar

- **Teknoloji:** Vanilla JavaScript, HTML5, CSS3
- **Veri Kaynağı:** Tarihsel fiyat verileri (1999-2025)
- **Hesaplama Yöntemi:** Basit getiri çarpımı (compound returns)
- **Rejim Değişim Seçenekleri:**
  - **Yılbaşı:** Her yıl Ocak başı
  - **Yıl Ortası:** Her yıl Haziran-Temmuz
  - **Yılsonu:** Her yıl Aralık sonu

## 📁 Proje Yapısı

```
benner_cycle/
├── benner.html       # Ana uygulama dosyası
├── image.png         # Benner Cycle tablosu görseli
└── README.md         # Bu dosya
```

## 🎨 Özellikler ve UI

- **Karanlık Tema:** Modern, göz yormayan arayüz
- **Responsive Tasarım:** Mobil ve masaüstü uyumlu
- **Animasyonlu Kartlar:** Hover efektleri ve geçişler
- **Dinamik Renkler:** Pozitif (yeşil), negatif (kırmızı), nötr (turuncu)
- **İkon Sistemi:** Görsel durum göstergeleri

## 🧪 Test Mantığı

Benner hipotezi, zamanlama stratejisinin uzun vadede sürekli aynı varlıkta kalmaya göre daha yüksek getiri sağladığını öne sürer. Bu araç:

1. ✅ Hipotezi test eder (Benner Strategy vs Buy & Hold)
2. ✅ Kontrol grubu sağlar (Benner Reverse)
3. ✅ İki pasif strateji arasında karşılaştırma yapar
4. ✅ Farklı varlık kombinasyonlarını test etmenize olanak tanır

## ⚠️ Yasal Uyarı

**YATIRIM TAVSİYESİ DEĞİLDİR**

Bu araç yalnızca eğitim ve araştırma amaçlıdır. Sonuçlar tamamen tarihsel verilere dayanır ve gelecek performans garantisi vermez. Gerçek yatırım kararları almadan önce profesyonel bir finansal danışmana başvurun.

**Önemli Notlar:**
- Geçmiş performans gelecekteki sonuçları garanti etmez
- Kaldıraçlı ETF'ler (SPXL, TQQQ) ekstra risk taşır
- İşlem maliyetleri, vergiler ve slippage hesaba katılmamıştır
- Veri doğruluğu garanti edilmez

## 👨‍💻 Yazar

**Batu**  
*"Piyasalar rastgele değil. Verinin anlattığı hikâyeleri paylaşıyorum."*

🐦 Twitter/X: [@batudotpy](https://x.com/batudotpy)

## 📄 Lisans

Bu proje açık kaynak olarak paylaşılmıştır. Eğitim ve araştırma amaçlı kullanım için serbesttir.

---

**Son Güncelleme:** 11.11.2025  
**Veri Dönemi:** 1999 - 11.11.2025
