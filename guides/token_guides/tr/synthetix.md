# Synthetix Basitçe Açıklandı

[Synthetix](https://synthetix.io/), Synth'ler olarak bilinen sentetik varlıkların ticareti için Ethereum üzerinde merkezi olmayan bir platformdur.

> Synth'ler, kripto para birimlerini, hisse senetlerini, fiat para birimlerini, değerli metalleri ve diğer ticareti yapılabilir varlıkları temsil eden ERC-20 tokenleridir.

Bu Synth'ler, temsil ettikleri varlığın fiyatını yansıtacak şekilde tasarlanmıştır ancak diğer özelliklerinden hiçbiri yoktur.

Örneğin sBTC, Synthetix'te mevcut Bitcoin fiyatından alınıp satılabilen sentetik bir Bitcoin tokenidir.

Benzer şekilde, bir sMKR tokeni gerçek bir [MKR](../../token_guides/tr/makerdao.md) tokenı ile aynı fiyata sahiptir ancak oy haklarını içermez.

- Synth tokenlarına sahip olmak, temsil ettikleri gerçek tokenlara sahip olmakla aynı fiyat riskini sunar.
- Kullanıcılar, gerçek varlığı elinde bulundurmadan çeşitli finansal araçların fiyat hareketleri hakkında spekülasyon yapabilir.
- Synth varlıkları kullanıcılar arasında aktarılabilir ve merkezi olmayan borsalarda alınıp satılabilir.

Özetle Synthetix, gerçek dünya varlıklarını temsil eden Ethereum tabanlı ERC-20 tokenlarının oluşturulmasını sağlar.

> Fiyat akışına sahip herhangi bir varlık potansiyel olarak Synthetix'e bir synth varlığı olarak eklenebilir.

Şu anda mevcut synth varlıkları arasında kripto para birimleri, hisse senetleri ve değerli metaller yer alıyor. Synthetix, hisse senetleri gibi geleneksel piyasalarda yaygın olarak bulunan daha fazla varlığı içerecek şekilde tekliflerini genişletmeyi hedefliyor.

## Desteklenen Synth'ler

Synthetix platformu şu anda yaklaşık iki düzine farklı synth'i destekliyor ve çok daha fazlası için potansiyel sunuyor.

> Fiyat akışı ve topluluk onayı olduğu sürece piyasa fiyatı olan herhangi bir varlık Synthetix'e eklenebilir.

Şu anda iki tür synth varlığı vardır:

1. **Standart Sentezler**

 Bunlar, temsil ettikleri varlığın fiyatını takip eder ve varlıklarda uzun vadeli pozisyon almak isteyenler için uygundur.
 - sUSD: sentetik USD
 - sEUR: sentetik EUR
 - sAUD: sentetik AUSDollar
 - sBTC: sentetik Bitcoin
 - sETH: sentetik Eter
 - sMKR: Sentetik Yapıcı
 - sBNB: sentetik BNB
 - sXTZ: sentetik Tezolar
 - sADA: sentetik Cardano
 - sXRP: sentetik Dalgalanma
 - sLTC: sentetik Litecoin
 - sBCH: sentetik Bitcoin Cash
 - sXAU: sentetik Altın Onsu
 - sXAG: sentetik Gümüş Onsu
 - sDEFI: sentetik DEFI İndeksi
 - sLINK: sentetik Chainlink

2. **Ters Sentezler**

 Bunlar, kullanıcıların bir varlığın fiyatında açığa satış yapmasına ve fiyat amortismanından ters yönde kar elde etmesine olanak tanır.
 - iBTC: ters Bitcoin
 - iETH: ters Ethereum
 - iBNB: Binance'in tersi
 - iXTZ: ters Tezos
 - iADA: ters Cardano
 - iXRP: ters Dalgalanma
 - iLTC: Ters Litecoin
 - iBCH: ters Bitcoin Cash
 - iDEFI: ters DEFI Endeksi
 - iLINK: ters Chainlink

Synth'ler saklama dışı [Synthetix.Exchange](https://synthetix.exchange) üzerinde 7/24 alınıp satılır ve böylece [Ethereum ekosistemindeki](../../token_guides/tr/ethereum.md) herkesin çeşitli varlıklarda uzun veya kısa pozisyon alın.

## Synth'ler Nasıl Oluşturulur?

Synthetix'i anlamak için yeni sentezlerin nasıl oluşturulduğunu ve dolaşımdan kaldırıldığını bilmek önemlidir.

1. Synthetix, kullanıcıların SNX tokenlerini %600 teminat oranıyla akıllı bir sözleşmeye [kilitleyerek](https://mintr.synthetix.io/) sUSD (sentetik USD) tokenları oluşturmalarına olanak tanır.
2. 1000 sUSD tokeni oluşturmak için kullanıcının en az 6000 $ değerinde SNX tokenini kilitlemesi gerekir. Kullanıcı ödünç alınan tutarı geri ödediğinde bu jetonlar iade edilir.
3. Oluşturulduktan sonra sUSD tokenleri Synthetix borsasında mevcut piyasa fiyatlarından diğer synth varlıkları ile takas edilebilir.
4. Synthetix borsasındaki emirler anında gerçekleşir ve piyasa fiyatlarından gerçekleştirilir.
5. Yatırımcılar her zaman kullanıcıdan alınan varlığı yok eden ve kullanıcı tarafından satın alınan varlığı yaratan borsaya karşı ticaret yapar.
6. Örneğin, Bitcoin 10.000 $ iken sBTC satın almak, 10.000 sUSD'yi yok etmeyi ve 1 sBTC oluşturmayı içerir.

Bu süreç, her synth varlığının SNX tokenleri tarafından desteklenmesini sağlar.

Spekülatörler ayrıca [Uniswap](../../token_guides/tr/uniswap) gibi [merkezi olmayan bir borsada](../../defi/tr/3-decentralized-exchanges.md) mevcut sUSD veya sETH'yi satın alabilirler. md) ETH kullanarak.

## Synth'lerin Ticareti Nasıl Yapılıyor?

Synthetix ekosistemi, synth ticareti için kendi merkezi olmayan borsası [Synthetix.Exchange](https://synthetix.exchange)'i içerir.

- Diğer merkezi olmayan borsalardan farklı olarak Synthetix.Exchange, emir defterleri veya [likidite havuzları](../../defi/tr/3-decentralized-exchanges.md) gibi likidite eşleştirme mekanizmalarına ihtiyaç duymaz.
- Tüm emirlerin saniyeler içinde piyasa fiyatlarında gerçekleştirilmesi garanti edilir.
- İşlem ücretleri %0,1 ila %1 (genellikle %0,3) arasında değişir ve SNX tokenlerini teminat olarak kilitleyerek sUSD tokenleri oluşturanlara gider.

Synthetix.Exchange'te işlem yapmak, özellikle büyük siparişler için genellikle daha ucuzdur ve bunu [Uniswap](../../token_guides/tr/uniswap.md) veya [Curve]( gibi diğer merkezi olmayan borsalara göre kullanmak için ekonomik bir teşvik sağlar. ./../token_guides/tr/curve-finance.md).

## Neden Synth Oluşturulmalı?

Sentetik ticaret daha ucuzdur ve tamamı Ethereum blok zincirinde olmak üzere dünyadaki tüm alım satım yapılabilir varlıklara erişim sağlar. Bu güçlülük yaratır Spekülatörlerin gerçek varlıklar yerine Synth ticareti yapmasına yönelik teşvikler.

%600 teminatlandırma oranı, synth varlıklarının istikrarını SNX fiyat dalgalanmalarına karşı korur.

Yeni sentezler oluşturmak için SNX'lerini platforma kilitleyenler iki tür ödül alırlar:
1. **SNX Staking Ödülleri**: SNX'in enflasyonist para politikası yoluyla oluşturulmuştur. Mart 2019 ile Ağustos 2023 arasında toplam SNX arzı, haftalık %1,25 azalma oranıyla 100 milyondan 260,3 milyona çıkacak.
2. **Değişim Ücretleri**: [Synthetix.Exchange](https://synthetix.exchange/#/) üzerindeki synth alım satımından elde edilen ücretler, SNX stakerlarının haftalık talep edebileceği bir ücret havuzuna gider.

SNX stakerları, tokenlarını kilitledikleri zaman bir borç pozisyonu oluştururlar. Bu borç, basılan sUSD miktarıyla başlar ve diğer tüm synth varlıklarının fiyat hareketlerine göre değişir.

- Tüm synth'lerin fiyatı sBTC olsaydı ve BTC fiyatı yarıya inseydi, toplam borç yarıya inerdi ve her stakerın borcu da yarıya inerdi.
- Tersine, eğer sBTC ve BTC'nin fiyatı yalnızca %50'si iki katına çıkarılsaydı, her stakerın borcu dörtte bir oranında artardı.

Bu şekilde, SNX stakerları tüm synth borsalarında havuzlanmış bir karşı taraf olarak hareket ederek genel sistem borcunun riskini üstleniyor.

## Synthetix İstatistikleri

Kilitli fon miktarı ve dolaşımdaki synth sayısı da dahil olmak üzere Synthetix platformundaki güncel istatistikler için [DeFi Pulse](https://dashboard.synthetix.io) adresindeki Synthetix genel bakışını ziyaret edin.

9 Eylül 2020 itibarıyla:
- Toplam Kilitli (ABD Doları cinsinden): 650,2 Milyon Dolar
- Toplam Kilitli (ETH'de): 1,9 milyon ETH
- Toplam Kilitli (BTC cinsinden): 63,3K BTC
- Toplam Kilitli (SNX'te): 141M SNX
- Kilitli SNX Kaynağının Yüzdesi: %70,/tr/