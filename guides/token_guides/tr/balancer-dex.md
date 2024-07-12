# Basit Terimlerle Dengeleyici

[Balancer](https://balancer.exchange/), Mart 2020'de faaliyete geçen merkezi olmayan bir borsadır (DEX). 2018'in başlarında [BlockScience](https://block.science/) tarafından bir araştırma projesi olarak başladı. Balancer ekibi, Balancer protokolü olarak bilinen, herhangi bir portföyün ücret üretirken sürekli olarak kendi kendini yeniden dengelemesini sağlayan bir matematiksel çerçeve geliştirdi. Bu protokolü çalıştıran Ethereum tokenı BAL'dır.

## Dengeleyicide Ticaret

Yatırımcı açısından bakıldığında Balancer, Ethereum ve ERC20 tokenlarını merkezi olmayan bir şekilde takas etmek için kullanılan bir platformdur.

- **Verimli Ticaret**: Balancer, istenen tokenlar için mevcut tüm havuzları tarar ve en iyi fiyatları sağlamak için emirleri en verimli havuzlara yayar.
- **Değişken Ücretler**: İşlem ücretleri havuzlar arasında farklılık gösterir ve ilgili tokenlara ve likidite havuzlarına bağlıdır.
- **Kayma**: Mevcut likiditeye göre daha büyük siparişler daha yüksek kaymaya neden olur.
- **Teşvikler**: Balancer, BAL tokenlerini likidite sağlayıcılarına dağıtarak düşük ücretleri teşvik eder.

## Likidite Sağlamak

Uniswap ve Curve gibi Balancer da kullanıcıların Ethereum tabanlı boşta kalan varlıklarından ücret kazanmalarına olanak tanıyor. Farklı türdeki likidite havuzları sayesinde daha esnek fırsatlar sunar.

- **Likidite Havuzları**: Kullanıcılar yeni bir havuz oluşturabilir veya mevcut havuzlara varlık ekleyebilir.
- **Havuz Bileşimi**: Her havuz, aralarında belirli bir oran korunarak 2-8 varlık içerebilir.
- **Otomatik Dengeleme**: Gerekli oranları korumak için kendi kendini dengelemeyi bir araya getirir.
- **Esnek Mevduat**: Uniswap'ten farklı olarak Balancer, havuz tarafından desteklenen herhangi bir varlığa para yatırmaya izin verir.
- **Havuz Sahipliği Tokenları**: Sağlayıcılar, likiditeyi çekmek için kullanılabilecek, havuzdaki paylarını temsil eden ERC-20 tokenları alırlar.
- **İşlem Ücretleri**: Her havuz kendi ücretlerini belirler; daha düşük ücretler daha fazla BAL tokeni kazandırır.

## Havuz Çeşitleri

1. **Ortak Havuzlar**:
 - Oluşturma sırasında belirlenen sabit jetonlar, ağırlıklar ve ücretler.
 - Yaratıcıya özel bir ayrıcalık yoktur.
 - Herkes likidite ekleyebilir ve sahiplik, Balancer Pool Tokens (BPT) ile takip edilir.

2. **Özel Havuzlar**:
 - İçerik oluşturucunun parametreleri üzerinde tam kontrol (ör. kabul edilen jetonlar, ağırlıklar, ücretler).
 - Yalnızca yaratıcı likidite sağlayabilir.
 - Yönetilen endeks fonları için kullanışlıdır.

3. **Akıllı Havuzlar**:
 - Bir kişiye değil, akıllı bir sözleşmeye aittir.
 - Esnek parametre değişiklikleriyle herkesten likidite kabul edin.
 - Sahiplik ERC-20 tokenleri tarafından takip edilir.

## Endeks Fonları

Balancer, kullanıcıların karmaşık yeniden dengeleme olmadan kişisel endeks fonları oluşturmasına olanak tanır.

- **Kendi Kendini Dengeleyen Havuzlar**: Yatırımcılar, uzun vadeli yatırım için varlıkları otomatik dengeleme havuzlarında gruplandırabilir ve diğerleri kendi portföylerine göre işlem yaparken ücret kazanabilirler.
- **Özel Endeks Fonları**: Kullanıcılar kendi kendini dengeleyen endeks fonları oluşturabilir veya bunlara yatırım yapabilir.
- **İç İçe Havuzlar**: Havuzlar diğer Dengeleyici havuzlarından oluşabilir.
- **İzinsiz**: Havuzlar etkinleştirildikten sonra sansürlenemez veya değiştirilemez.

## Dengeleyici Jetonu

1 Haziran 2020'den bu yana likidite sağlayıcılarına dağıtılan BAL tokenı aynı zamanda protokolün yönetişim tokenı olarak da görev yapıyor.

- **Toplam Arz**: 100 milyon BAL tokeni.
- **Dağıtım**: Kuruculara, geliştiricilere, danışmanlara ve yatırımcılara 25 milyon; Likidite sağlayıcılarına 75 milyon.

Yönetişim modeli ve token dağıtımına ilişkin ayrıntıları [burada](https://balancer.finance/2020/05/15/prousing-balancer-liquidity-mining/) bulabilirsiniz.

## Kullanışlı bağlantılar

- [Proje Raporu](https://balancer.finance/whitepaper/)
- [Resmi Blog](https://balancer.finance/blog-feed/)
- [Dengeleyici Havuz Yönetimi](https://pools.balancer.exchange/#/)