# 🌸 Bütçe Defterim

Ajanda gibi sayfaları çevrilen, tek bir HTML dosyasından oluşan kawaii bir bütçe defteri. Kurulum, derleme ya da sunucu gerekmez; `index.html` dosyasını tarayıcıda açman yeterli.

## 🌐 Canlı demo

- **Demo:** (https://imer-coder.github.io/Butce-Defterim/)

Demoyu denerken eklediğin veriler yalnızca kendi tarayıcında saklanır, başka kimse göremez.

## Özellikler

- **Ajanda gibi sayfalar:** Aylar arasında sayfa çevirme animasyonuyla gezinirsin.
- **Gün sayfaları:** Bir tarihe tıklayınca o günün sayfası açılır. Alacaklarını fiyat, fotoğraf, kategori ve ürün linkiyle listeler, günün toplam bütçesini görürsün. Günün notunu ve ruh halini de kaydedebilirsin.
- **Aldım işareti:** Planlanan ve gerçekten aldıkların ayrı toplanır.
- **Yatırım bütçesi:** Ana sayfanın köşesinde biriktirdiğin parayı, hedefini, ilerleme çubuğunu ve birikim geçmişini görürsün.
- **Aylık özet:** Limit, gelir, gider, kalan tutar ve kategori pasta grafiği.
- **Tekrarlayan giderler:** Fatura ve abonelikler her ay otomatik takvime gelir.
- **İstek listesi:** Tarihsiz “bir gün alacağım” listesi. Hazır olunca bir güne taşınır.
- **Yıl özeti:** Her ayın gider çubuğu, yıllık gider ve gelir toplamı.
- **Kapak sayfası:** Defterine istediğin adı verebilirsin.
- **Renk temaları:** Rose Quartz, Peach Fuzz, Very Peri, Viva Magenta, Living Coral ve Mocha Mousse paletleri. Renk kodları Pantone renklerinin ekrandaki yaklaşık karşılıklarıdır.

## Kullanım

1. `index.html` dosyasını tarayıcıda aç.
2. Takvimden bir güne tıkla ve alacaklarını ekle.
3. Ay özeti, tekrarlayan giderler, istekler ve yıl özeti için üstteki sekmeleri kullan.

## GitHub Pages ile yayınlama

1. [github.com/imer-coder](https://github.com/imer-coder) altında `butce-defterim` adında bir repo oluştur ve `index.html` ile `README.md` dosyalarını yükle.
2. Repoda **Settings → Pages** bölümüne git.
3. **Source** olarak **Deploy from a branch** seç, branch olarak `main` ve klasör olarak `/ (root)` seç, kaydet.
4. Birkaç dakika sonra defterin https://imer-coder.github.io/butce-defterim/ adresinde açılır.

## Veriler nerede duruyor?

Tüm veriler tarayıcının `localStorage` alanında saklanır. Sunucuya hiçbir şey gönderilmez.

- Veriler yalnızca o tarayıcıda ve o cihazda görünür.
- Tarayıcı verilerini temizlersen defter de silinir.
- **💾 Yedek** sekmesinden verini metin olarak kopyalayıp başka bir cihazda içe aktarabilirsin. Düzenli yedek almanı öneririm.
- Fotoğraflar küçültülerek kaydedilir. Çok fazla fotoğraf eklersen tarayıcının kayıt alanı dolabilir.

## Teknik notlar

- Tek dosya, bağımlılık yok. Yalnızca yazı tipleri Google Fonts’tan yüklenir (Fredoka, Pacifico). Çevrimdışıyken sistem yazı tipine döner.
- Saf HTML, CSS ve JavaScript ile yazıldı.
