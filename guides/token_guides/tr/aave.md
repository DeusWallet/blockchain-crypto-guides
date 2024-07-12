# Basit Bir Şekilde Aave

[Aave](https://app.aave.com/), Ethereum blockchain üzerinde kullanıcıların Ethereum tabanlı kripto para birimi varlıklarını ödünç almasına ve ödünç almasına olanak tanıyan, gözetimsiz, merkezi olmayan bir hizmettir. Ocak 2020'de piyasaya sürülen Aave hızla büyüdü ve yalnızca sekiz ayda yaklaşık 2 milyar dolar değerinde kripto para birimini kendine çekti.

## Aave Nasıl Çalışır?

- **Mevduat Sahipleri**: Kullanıcılar, kripto para birimlerini merkezi olmayan borç verme havuzlarına yatırıp karşılığında faiz kazanarak likidite sağlarlar.
- **Borç Alanlar**: Kullanıcılar bu borç verme havuzlarından ücret ödeyerek borç alabilirler.
- **Benzersiz Özellik**: [Compound](../../token_guides/tr/compound.md) veya [MakerDAO](../../token_guides/tr/makerdao.md) gibi diğer hizmetlerden farklı olarak, Aave teminatsız borçlanmaya izin veriyor.
- **Faiz Oranları**: Genel olarak diğer platformlara göre daha yüksektir.
- **Güvenlik**: Aave'nin akıllı sözleşmeleri gözetim altında değildir ve merkezi değildir, yani Aave ekibi kullanıcı fonlarına erişemez.

## Desteklenen Varlıklar

Eylül 2020 itibarıyla Aave, 20 farklı Ethereum tabanlı kripto para birimi tokeninin ödünç verilmesini ve ödünç alınmasını desteklemektedir:

- [USD Coin (USDC)](https://app.aave.com/reserve-overview/USDC?pool=Aave)
- [Tether (USDT)](https://app.aave.com/reserve-overview/USDT?pool=Aave)
- [Gerçek USD (TUSD)](https://app.aave.com/reserve-overview/TUSD?pool=Aave)
- [Dai (DAI)](https://app.aave.com/reserve-overview/DAI?pool=Aave)
- [sUSD](https://app.aave.com/reserve-overview/SUSD?pool=Aave)
- [Binance (BUSD)](https://app.aave.com/reserve-overview/BUSD?pool=Aave)
- [Ethereum (ETH)](https://app.aave.com/reserve-overview/ETH?pool=Aave)
- [ETHLend (LEND)](https://app.aave.com/reserve-overview/LEND?pool=Aave)
- [YFI](https://app.aave.com/reserve-overview/YFI?pool=Aave)
- [Temel Dikkat Jetonu (BAT)](https://app.aave.com/reserve-overview/BAT?pool=Aave)
- [EnjinCoin (ENJ)](https://app.aave.com/reserve-overview/ENJ?pool=Aave)
- [REN](https://app.aave.com/reserve-overview/REN?pool=Aave)
- [Kyber Ağı (KNC)](https://app.aave.com/reserve-overview/KNC?pool=Aave)
- [ChainLink (LINK)](https://app.aave.com/reserve-overview/LINK?pool=Aave)
- [Merkezsiz Bölge (MANA)](https://app.aave.com/reserve-overview/MANA?pool=Aave)
- [Yapımcı (MKR)](https://app.aave.com/reserve-overview/MKR?pool=Aave)
- [Augur (REP)](https://app.aave.com/reserve-overview/REP?pool=Aave)
- [Synthetix (SNX)](https://app.aave.com/reserve-overview/SNX?pool=Aave)
- [WBTC Coin (wBTC)](https://app.aave.com/reserve-overview/WBTC?pool=Aave)
- [0x (ZRX)](https://app.aave.com/reserve-overview/ZRX?pool=Aave)

Her varlığın kendine özgü borçlanma ve borç verme gereksinimleri vardır. Desteklenen kripto para birimleri üzerindeki kontrol, sonunda Aave token sahiplerine devredilecek.

## Aave'de Borç Verme

- **Faiz Kazanma**: Borç verenler yatırılan varlıklar üzerinden faiz kazanırlar.
- **Güvenlik**: Mevduatlar borçlular tarafından sağlanan teminatlarla güvence altına alınmaktadır.
- **aTokens**: Borç verenler, faiz kazandıran ve kazançlarla birlikte mevduatları çekmek için kullanılabilen aTokenlar alırlar. aTokenlar dayanak varlığa 1:1 oranında sabitlenir.

## Aave'den Borç Alma

- **Teminat Gereksinimleri**: Borçlanma, başka bir kripto para birimi biçiminde teminat gerektirir.
- **Kredi-Değer (LTV) Oranı**: Maksimum borçlanma gücünü temsil eder (örn. %75 LTV, teminat değerinin %75'ine kadar borçlanma anlamına gelir).
- **Faiz Oranları**: Borçlular sabit veya değişken oranlar arasında seçim yapabilir.
- **Teminatın Korunması**: Borçlular, tasfiyeyi önlemek için teminat değerinin gereken minimum değerin üzerinde kalmasını sağlamalıdır.

## Flaş Krediler

Flaş krediler Aave'ye özeldir ve kullanıcıların teminat olmadan borç almasına olanak tanır:

- **Mekanizma**: Varlıkları tek bir işlemde ödünç alın ve işlem bitmeden iade edin.
- **Ücret**: Flaş kredilerden %0,09 oranında ücret alınır.

Flaş krediler öncelikle programcılar tarafından arbitraj ve yeniden finansman gibi faaliyetler için kullanılır.

## Aave Yönetişim

Aave, tamamen topluluk tarafından yönetilen, merkezi olmayan özerk bir kuruluş (DAO) olmayı hedefliyor:

- **AAVE Token**: Protokol iyileştirmeleri ve yönetişim kararlarına oy vermek için kullanılır.
- **Teşvikler**: AAVE token sahipleri ödüller alır ve yönetime katılabilirler.
- **Acil Durum Fonu**: Beklenmedik olaylara karşı kredi verenlerin varlıklarını korur.
- **Deflasyonist Token**: Ücretlerin bir kısmı AAVE tokenlarını geri satın almak ve yakmak için kullanılır.

## Aave 2.0 ile tanışın

14 Ağustos 2020'de duyurulan Aave 2.0, birçok yeni özellik sunuyor:

- **Teminatla Ödeme**: Kredi geri ödeme işlemlerini kolaylaştırır.
- **Sabit Faizler**: Borç verme ve borç alma faiz oranlarında öngörülebilirlik sağlar.
- **İşlem Maliyetlerini Düşürün**: Platform etkileşimlerinin maliyetlerini azaltır.
- **Ticaret Özellikleri**: Kullanıcıların, desteklenen kripto para birimleri arasında borç pozisyonları ve yatırılan varlıklarla ticaret yapmasına olanak tanır.

## Riskler

Herhangi bir DeFi hizmetinde olduğu gibi akıllı sözleşme hatalarıyla ilgili riskler vardır. Aave, sözleşmelerini denetlettirdi ve topluluk üyelerinin güvenlik açıklarını bildirmeleri için bir hata ödül programı sunuyor.

## Kullanışlı bağlantılar

- [Resmi Aave Portalı](https://app.aave.com/)
- [Resmi Aave Blogu](https://medium.com/aave)
- [Belge Bağlantı Portalı](https://docs.aave.com/portal/)
- [Yönetim Portalı](https://governance.aave.com)