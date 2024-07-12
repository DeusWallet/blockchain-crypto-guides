# Uniswap Basitçe Açıklandı

[Uniswap](https://uniswap.info/home), Ethereum ve Ethereum tabanlı tokenların ticareti için merkezi olmayan, eşler arası bir kripto para borsasıdır.

Uniswap, Ethereum'daki ilk [merkezi olmayan borsalar](../../defi/tr/3-decentralized-exchanges.md) arasındadır ve birkaç temel özelliğe sahiptir:

- Uniswap'in akıllı sözleşmeleri yüz milyonlarca dolarlık kripto para birimini özerk ve merkezi olmayan bir şekilde yönetir.
- Gerçekten merkezi olmayan borsalardan biri olarak kabul edilir, yani operatörler kullanıcıları sansürleyemez veya hizmeti kapatamaz.
- Merkezi olmayan borsalar arasında, birçok merkezi borsayı geride bırakarak en yüksek işlem hacmine sahiptir.
- Uniswap çok sayıda kripto para alım satım çiftini listeler ve herkesin herhangi bir tokenı listelemesine ve likidite sağlamasına olanak tanıyan ücretsiz bir token listeleme politikasına sahiptir.
- Varlık fiyatlarını belirlemek ve işlemleri gerçekleştirmek için basit bir matematiksel formül ve likidite havuzundaki mevcut tokenları kullanır. Daha fazla ayrıntıyı [burada](https://uniswap.org/docs/v2/protocol-overview/how-uniswap-works) ve [burada](https://uniswap.org/docs/v2/core-) bulabilirsiniz. kavramlar/takaslar/).
- Uniswap V1 ve daha yeni Uniswap V2 olmak üzere iki sürümü vardır. DeFi ilkeleri uyarınca Uniswap'in önceki sürümleri kapatılamaz.
- Uniswap V3, borsanın çeşitli unsurlarını daha da geliştirmek için geliştiriliyor.

Bugün Uniswap, 24 saatlik işlem hacminde [100 milyon doların üzerinde](https://migrate.uniswap.info/home) sahip en büyük DEX'lerden biridir.

## Uniswap'te işlem yapma

Uniswap'in ticaret arayüzüne, [uniswap.org](https://app.uniswap.org/#/swap) adresindeki genel ön uçtan erişebilirsiniz.

- İşlemlerin yürütülmesi için %0,03 oranında hizmet ücreti alınmaktadır.
- Ethereum'un yerel ETH para birimi ile Ethereum tabanlı ERC20 tokenleri arasında işlem yapmak, ERC20 tokenleri arasında işlem yapmaktan genellikle daha ucuzdur.
- Uniswap'in akıllı sözleşme tasarımı, diğer merkezi olmayan borsalara kıyasla daha düşük Ethereum işlem ücretleri sağlar.
- Yatırımcılar daha büyük siparişlerde ciddi fiyat kaymaları (piyasa fiyatından sapma) yaşayabilir.
- Daha fazla likiditesi olan işlem çiftleri, daha büyük emirler için daha az likiditesi olanlara göre daha iyi fiyatlar sağlayacaktır.
- Uniswap'in iyi çalışması ve büyük işlemlere olanak sağlaması için büyük likidite havuzları gereklidir.

Uniswap'teki tüm işlem çiftlerini ve ilgili likidite havuzlarını [burada](https://uniswap.info/pairs) görüntüleyebilirsiniz.

## Likidite Sağlayıcıları

Uniswap, likidite havuzları aracılığıyla otomatik piyasa yapımını başlatan ilk projelerden biriydi.

- Uniswap'teki her işlem çiftinin, herkesin oluşturabileceği veya katılabileceği kendi likidite havuzu vardır.
- Bir likidite havuzuna katılmak için kullanıcıların işlem çiftinde yer alan iki tokeni yatırması gerekir.
- Likidite sağlayıcıları, mevcut piyasa fiyatlarına göre her iki tokenden eşit miktarda yatırmalıdır.
- Örneğin, [ETHUSDT](https://uniswap.info/pair/0x0d4a11d5eeaac28ec3f61d100daf4d40471f1852) işlem çifti, hem ETH hem de USDT tokenlerinin yatırılmasını gerektirir.
- Likidite sağlayıcıları, yatırdıkları varlıkların değerine göre işlem ücretlerinden pay alırlar.
- Sağlayıcılar, havuzdaki varlık paylarını temsil eden havuza özel tokenlar alırlar.
- Likidite sağlayıcılar varlıklarını ve kazançlarını diledikleri zaman çekebilirler.

## Havuz Karlılığı

Uniswap likidite havuzları, boşta kalan kripto para varlıklarını çalıştırarak pasif gelir elde etmenin garantili bir yolu gibi görünse de riskler mevcut:

> Yatırım ücretleri kazanılmasına rağmen yatırılan varlıkların kümülatif değeri düşebilir.

Ücretlerden elde edilen gelire rağmen bir likidite sağlayıcısının payının neden azalabileceğini anlamak için Uniswap ticaretini yöneten formülü göz önünde bulundurun. Bu basit formül, likidite havuzlarını değerlendirirken dikkate alınması gereken faktörlerle birlikte [burada](https://medium.com/@pintail/uniswap-a-good-deal-for-liquidity-providers-104c0b6816f2) açıklanmaktadır.

Likidite sağlayıcıları için genel bir kural: yatırılan varlıklardaki herhangi bir fiyat değişikliği, yalnızca orijinal varlıkların tutulmasına kıyasla hissenin değerini azaltabilir.

> Bu nedenle, stabil kripto paralar gibi stabil varlıkları içeren likidite havuzlarının daha iyi performans göstermesi muhtemeldir.

Varlık fiyat değişiklikleri kâr hesaplamasında önemli bir rol oynadığından gelecekteki getirileri tahmin etmek karmaşık olabilir.

## Uniswap Jetonu

Eylül 2020'de Uniswap, yerel yönetim jetonu UNI'yi [tanıttı](https://uniswap.org/blog/uni/).

UNI'nin birincil kullanım durumu, karar alma süreçlerine ve topluluk hazinesindeki fonların yönetilmesi gibi diğer yönetişim yönlerine katılmaktır.