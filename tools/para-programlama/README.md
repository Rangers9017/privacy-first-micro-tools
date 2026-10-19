# Bütçe ve Borç Takip

Gelir, gider ve borç bilgilerini aynı ekranda takip etmeye yardımcı olan tek sayfalık bir tarayıcı aracı.

[Uygulamayı aç](./index.html)

## Neler yapar?

- Aylık gelir ve sabit giderleri kaydeder.
- Kredi kartı, ek hesap ve kredi borçlarını ayrı ayrı izler.
- Aylık taksitleri ve ek ödemeleri hesaba katar.
- Mevcut ödeme tutarlarına göre tahmini borç kapanış sürelerini gösterir.
- Ek ödeme miktarını değiştirerek farklı ödeme planlarını karşılaştırır.

Sonuçlar girilen bilgilere ve aracın hesaplama varsayımlarına bağlı tahminlerdir; kesin kapanış tarihi veya finansal tavsiye olarak değerlendirilmemelidir.

## Kullanım

`index.html` dosyasını güncel bir tarayıcıda aç. Kayıtlar aynı tarayıcı profilinin `localStorage` alanında tutulur; başka bir tarayıcıya veya cihaza kendiliğinden aktarılmaz. Tarayıcı verilerini silmek kayıtları da siler.

Dışarı aktarım yapmadan önce önemli bilgilerin yedeğini kendin al.

## Teknik bilgiler

- Tek dosya: `index.html`
- HTML, CSS ve JavaScript
- Tailwind CSS CDN üzerinden yüklenir; CDN bağlantısı yoksa sayfa stilleri etkilenebilir.
- Uygulamanın kapsamı ve son kontrolleri Mahmutcan Zaman tarafından belirlendi. Geliştirme sırasında yapay zekâ desteğinden yararlanıldı.
