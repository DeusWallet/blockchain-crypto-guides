# Deus Cüzdanı

Bu bölüm, saklama amaçlı olmayan cüzdan uygulamalarını kullanırken pratik yönlere ve 'bilinmesi gerekenlere' odaklanacaktır.

Kullanıcının bakış açısına göre, herhangi bir saklama dışı cüzdan uygulamasından temel beklentiler şöyle olmalıdır:

1. **Standartlarla Uyumlu Anahtar Oluşturma**: M-cüzdan uygulaması, standartlarla uyumlu bir şekilde özel anahtarlar oluşturmalı ve bunların güvenliğini ve diğer üçüncü taraf cüzdan uygulamalarıyla uyumluluğunu sağlamalıdır.

2. **Birden Fazla Kripto Para Biriminin Doğru Yönetimi**: M-cüzdan uygulaması, her bir kripto para birimi için ödeme adreslerini doğru bir şekilde yönetmeli, örneğin kullanıcının Bitcoin adresinin Ethereum adresinden farklı olmasını sağlamalıdır.

3. **Güvenli Özel Anahtar Depolama**: M-cüzdan uygulaması özel anahtarları belgelenmiş yönergelere uygun olarak saklamalıdır. Hem iOS hem de Android cüzdan uygulamaları, özel anahtarları güvende tutmak için işletim sistemlerinin sağladığı güvenli depolama mekanizmalarını kullanmalıdır.

Ek beklentiler hedef kullanıcıya göre değişiklik gösterebilir. Örneğin, kapsamlı gizlilik isteyen bir kişi, çoğu cüzdan uygulamasında bulunmayan özelliklere ihtiyaç duyabilir.

Aşağıda, saklama amaçlı olmayan cüzdan uygulamalarını kullanırken akılda tutulması gereken bazı önemli noktaları vurgulayacağız ve bu hususları açıklamak için Deus cüzdan uygulamasını kullanacağız.

### 1. Kurulum / Geri Yükleme

Her saklama dışı cüzdan, ya yeni bir cüzdan kurmakla ya da mevcut bir cüzdanı taşımakla başlar.

- **'Cüzdan Oluştur'** düğmesi yeni bir özel anahtar oluşturur ve bunu, yedeklenmesi gereken 12 kelime olarak görüntüler.
- **'Cüzdanı Geri Yükle'** seçeneği, daha önce Deus'ta oluşturulmuş mevcut bir cüzdanı veya standart uyumlu başka bir cüzdanı geri yükler.

Saklanmayan bir cüzdanın geri yüklenmesi birkaç dakikadan birkaç saate kadar sürebilir.

### 2. Yetkilendirme Kilidi

Saklanmayan cüzdan uygulamaları, yetkisiz erişimi önlemek için yerleşik önlemler içermelidir. Hem mobil hem de donanım cüzdanları bunu, cüzdana erişmek için gereken kilit açma kodu aracılığıyla gerçekleştirir.

Bu önlem, birisi cüzdan cihazınıza fiziksel erişim sağlasa bile paranızı güvende tutmak için gereklidir.

### 3. Desteklenen Kripto Para Birimleri

Bir cüzdan ne kadar çok kripto para birimini işleyebilirse o kadar iyidir. Birden fazla uygulama arasında geçiş yapmak yerine, birden fazla kripto para birimini tek bir uygulama üzerinden yönetmek daha uygundur.

M-cüzdan uygulaması aynı zamanda mevcut kripto para birimi fiyatlarını da görüntülemeli ve bakiyelerinizi USD veya EUR gibi tanıdık para birimleri cinsinden göstermelidir. Bu, hesaplamaları basitleştirdiği için özellikle ödeme yaparken faydalıdır.

### 4. Paraya Genel Bakış

Her kripto para birimi kendine has özellikleri olan benzersiz bir projedir. Bu ayrıntıları anlamak, kripto para birimlerine yatırım yapmak isteyen herkes için çok önemlidir.

Pek çok proje, teknik geçmişi olanlar için bile karanlık kalıyor. Deus, çeşitli kripto para birimlerine basit terimlerle kapsamlı bir genel bakış sunmayı amaçlamaktadır.

### 5. Grafikler ve Veriler

Tokenlar için geçmiş piyasa döviz kurlarını gösteren bir cüzdan seçin.

Geçmiş fiyatlar, bir kripto para biriminin fiyatının nasıl değiştiğine dair genel bir bakış sunar ve kullanıcıların geçmiş işlemlerdeki geçmiş döviz kurlarını görmesine olanak tanır.

### 6. Çoklu Cüzdan

Deus dahil bazı cüzdanlar, tek bir uygulama içerisinde sınırsız cüzdan oluşturulmasına olanak tanır.

Bu özellik, kullanıcıların birden fazla kripto para birimi portföyünü kolayca yönetmesine olanak tanır.

### 7. Gizlilik

Saklama amaçlı olmayan cüzdanlardaki gizlilik özellikleri önemli ölçüde farklılık gösterebilir.

Bir cüzdanı gizlilik özellikleri açısından değerlendirirken aşağıdaki noktaları göz önünde bulundurun:

- **Temel Kullanıcı Verileri**: Cüzdanın tasarımına bağlı olarak sağlayıcı, kullanıcının IP adresi ve konumu gibi tanımlanamayan bazı verileri bilebilir. Bu veriler bir sunucuda saklanıyorsa her zaman veri ihlali riski vardır.

- **Bakiye ve İşlemler**: Bazı cüzdanlar, kullanıcıların mevcut bir cüzdanı geri yüklemesine veya taşımasına olanak tanır. Cüzdan sağlayıcıları, bu görev için optimize edilmiş, kullanıcının bakiyesi ve geçmiş işlemleriyle ilgili bilgileri açığa çıkarabilecek özel bir sunucu kullanabilir.

 Bu sorunu çözmek için Deus gibi cüzdanlar, doğrudan blockchain ağının kendisinden geri yüklemeyi destekleyerek sağlayıcının, kullanıcının bakiyesi veya işlemleri hakkında hiçbir bilgiye sahip olmamasını sağlar.

- **Blockchain Gizliliği**: Farklı blockchain'ler farklı düzeylerde gizlilik sunar. Bitcoin işlemleri genellikle Ethereum işlemlerinden daha özeldir. Saklanmayan bazı cüzdanlar, belirli blok zincirlerde gizliliği artıran özellikler içerir. Örneğin Deus, Bitcoin işlemlerini tek bir varlığa bağlamayı önemli ölçüde zorlaştıracak özellikleri entegre ediyor.

Bir kullanıcı için minimum gizlilik gereksinimi, kullanıcıları hakkında kesinlikle hiçbir şey bilmeyen bir cüzdan olmalıdır.

### 8. Sansüre Direniş

Kripto para birimleri için gelişen yasal ortam göz önüne alındığında, aşağıdaki özelliklere sahip bir cüzdan uygulaması arayın:

- Sansüre dayanıklı
- Tüm bölgelerde işlevsel
- İşlemler için her zaman erişilebilir

Gerçek bir saklama dışı cüzdan her yerde çalışmalı ve işlemler için her zaman erişilebilir olmalıdır. Bölgenizde saklanmayan bir cüzdan engellenmişse, özel anahtarınızı başka bir saklamayan cüzdan uygulamasına geçirebilmeniz gerekir.