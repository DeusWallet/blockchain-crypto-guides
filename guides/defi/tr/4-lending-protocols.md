# Borç Verme Havuzları

Ödünç verme havuzları, saklama dışı kripto para ödünç verme ve borç almayı kolaylaştıran DeFi hizmetleridir.

## Borçlanma

Borçlanma hizmetleri, kullanıcıların başka bir kripto para biriminde teminat sağlayarak akıllı bir sözleşmeden kripto para birimini ödünç almasına olanak tanır. Bu, borçluların kripto para birimlerini satmadan likiditeye erişmelerini sağlar. Borçlular, teminatlarını geri almak için istedikleri zaman krediyi geri ödeyebilirler.

## Borç verme

Borç verme hizmetleri, kripto para birimi sahiplerinin varlıklarını akıllı bir sözleşmeye borç vermelerine ve faiz kazanmalarına olanak tanır. Borç verenler mevduatlarını tahakkuk eden faiziyle birlikte istedikleri zaman çekebilirler.

Tipik olarak piyasa katılımcıları, bu fonları borçlanma maliyetinden daha yüksek getiri sağlayan faaliyetlerde kullanmak için akıllı bir sözleşmeden varlık ödünç alır. Örneğin, birisi bir DeFi hizmetinden bir kripto para birimini ödünç alabilir ve onu daha yüksek getiri sağlayan başka bir hizmete ödünç verebilir.

## Teminatlı Krediler

- Borçlular, teminat olarak genellikle ödünç alınan miktardan önemli ölçüde daha fazla başka bir kripto para birimini koymak zorundadır.
- Teminatın değerinin keskin bir şekilde düşmesi durumunda borç verenleri korumak için yüksek teminat gereklidir.
- Teminat değeri gereken seviyenin altına düşerse akıllı sözleşme, ödünç verilen varlıkları geri satın almak için teminatı tasfiye etmeye çalışacaktır.

Borçlular, teminatlarının bir kısmını kaybetmemek için krediyi geri ödemeye ve teminat tasfiyesini önlemeye teşvik edilir.

## Flaş Krediler

Flaş krediler, teminat içermeyen bir kripto para birimi borçlanma şeklidir.

> Flaş kredi, krediyi aynı işlem içerisinde geri ödemek koşuluyla, borçlunun herhangi bir teminata ihtiyaç duymadan fon almasına olanak sağlar.

Flaş krediler şu anda ekosistem hakkında derinlemesine bilgi sahibi olanlarla sınırlıdır. Aşağıda flaş kredilerin nasıl kullanılabileceğine dair bir örnek verilmiştir:

1. Akıllı sözleşmeden flaş kredi (tokenX cinsinden) alın.
2. Ödünç alınan tokenX'i DEX1'deki tokenB ile değiştirin.
3. DEX2'de tokenB'yi tokenC'ye dönüştürün.
4. DEX3'te tokenC'yi tokenA'ya dönüştürün.
5. Flaş krediyi akıllı sözleşmeye geri ödeyin.

İşlem zincirindeki herhangi bir adım başarısız olursa önceki adımlara geri dönülür ve işlem sanki hiç olmamış gibi başarısız olur.

> Aynı işlem içerisinde kredinin iade edilmesi şartıyla herkes, teminatsız olarak ihtiyacı kadar borç almak için flaş kredi kullanabilir.

Flaş krediler eşzamanlı finansal işlemlere olanak tanır: borçlanma fonları, birden fazla DeFi platformunda çeşitli arbitraj işlemleri yapılması ve orijinal borç verene geri ödeme; hepsi tek seferde.

## 1. Bileşik

Compound, kripto para birimini ödünç almak ve ödünç vermek için popüler, merkezi olmayan bir hizmettir.

[Bileşik Finans](https://compound.finance/markets) kredileri genellikle ödünç alınan varlığın %0-90'ı arasında değişebilen teminat gerektirir. Compound'daki her varlığın farklı bir teminat gereksinimi vardır.

Okuyun: [Basit Terimlerle Bileşik](../../token_guides/tr/compound.md)

## 2. Aave

[Aave](https://app.aave.com/home) hem teminatlı hem de teminatsız flaş kredilere erişim sağlar.

Flaş krediler, diğer kullanıcılar tarafından finanse edilen bir likidite havuzundan sağlanır. Aave, flaş kredilerden %0,09 oranında ücret almaktadır. Teminatlı kredilerde kredi kullandırımında kredi tutarının %0,01'i oranında ücret tahsil edilmektedir.

Okuyun: [Basit Terimlerle Aave](../../token_guides/tr/aave.md)

## 3. Vaha

[Oasis](https://oasis.app/), MakerDAO tarafından geliştirilen ve DAI stablecoin'inin ödünç alınmasını ve ödünç verilmesini kolaylaştıran bir DEX'tir.

- Kullanıcılar, kripto para teminatı (genellikle kredi değerinin %150'si) karşılığında yeni DAI oluşturan MakerDAO akıllı sözleşmelerinden DAI ödünç alabilirler.
- DAI tokenleri iade edildiğinde, teminat borçluya geri ödenir ve iade edilen DAI tokenleri akıllı sözleşme tarafından yok edilir.

Okuyun: [Basit Terimlerle MakerDAO](../../token_guides/tr/makerdao.md)

## Riskler

Diğer DeFi hizmetlerinde olduğu gibi, borç verme hizmetinin likidite havuzunu tüketerek borç verenlerin varlıklarını kaybetmesine neden olabilecek bir saldırı veya istismar riski her zaman vardır. Bu nedenle, borç verenler yalnızca kaybetmeyi göze alabilecekleri fonları taahhüt etmelidir.