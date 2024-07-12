# Özel Anahtarlar

Daha önce de belirttiğimiz gibi, gerçek kripto para cüzdanları, belirli miktarda kripto para birimini kontrol eden kriptografik anahtarları saklar. Cüzdan uygulaması, bu şifreleme anahtarından kullanıcının sahip olduğu kripto para miktarını belirleyebilir ve cüzdanla ilişkili geçmiş işlemleri türetebilir. Bu şifreleme anahtarına genellikle özel anahtar denir.

> **Cüzdan uygulaması esasen özel anahtarınızı saklar ve bu da size belirli miktarda kripto para birimi üzerinde kontrol sağlar.**
>
> **Gözetimsiz bir cüzdan uygulaması, kripto para birimi bakiyelerini ve blockchain'deki geçmiş işlemleri almak için özel anahtarı kullanır.**

Özel anahtarların teknik işleyişine girmeyeceğiz. Özel anahtarın daha önce tartıştığımız şifreleme anahtarını ifade ettiğini bilmeniz yeterli. Özel anahtarların güvenlik yönlerini ve ilgili hususları inceleyelim.

## 1. Anahtarınızı Gizli Tutun

Dolandırıcılar, kullanıcıları özel anahtarlarını paylaşmaları için kandırmak amacıyla genellikle cüzdan destek ekiplerinin kimliğine bürünür. Anahtarınızı paylaşırsanız dolandırıcılar paranızı çalabilir.

> **Özel anahtarlarınızı kimseyle paylaşmanın kesinlikle geçerli bir nedeni yoktur. Bu, tüm cüzdanlar için geçerlidir.**
>
> **Cüzdan uygulamanızı geliştiren kişilerle iletişim kurarken bile asla özel anahtarınızı açıklamayın.**

Özel anahtarınızı yalnızca fonlarınızın sahipliğini kasıtlı olarak başka birine devretmek istediğinizde açıklayabilirsiniz. Neredeyse tüm saklama dışı cüzdanlar, uygulama içinden özel anahtarınıza erişmeniz ve bunları görüntülemeniz için bir yol sağlar.

## 2. Özel Anahtarınızı Yedekleyin

Saklanmayan cüzdan uygulamalarının çoğu, kurulum sırasında özel anahtarı görüntüler ve kullanıcılardan bunu yazıp çevrimdışı olarak güvenli bir şekilde saklamalarını ister.

> **Cüzdan uygulamasının bulunduğu cihazın çalınması veya çalışmayı durdurması gibi nedenlerle erişilemez hale gelmesi durumunda, özel anahtar, cüzdanınıza erişimi yeniden sağlamanın tek yoludur.**

Özel anahtarın yedeklenmesini kolaylaştırmak için blockchain mühendisleri, onu 12 veya 24 normal kelimeden oluşan bir diziye dönüştürecek bir yöntem geliştirdiler. Saklanmayan cüzdanların çoğu, özel anahtarı insan tarafından okunabilen biçimde görüntüler.

Özel anahtarınızı yazım hatası olmadığından emin olarak dikkatli bir şekilde yedekleyin. Kelimelerin doğru sırası çok önemlidir.

> **Özel anahtarınızı kaybederseniz veya açığa çıkarırsanız, başkaları kripto para biriminizi kontrol edebilir.**

Saklama dışı cüzdanlar, bir yazım hatası yaptığınızda sizi uyarabilir, ancak yanlış kelime sırası, sizinkini değil, farklı, rastgele bir cüzdanı geri yükleyecektir.

## 3. Özel Anahtar Üretimi

Saklanmayan bir cüzdan oluşturduğunuzda, uygulama rastgele bir güvenli özel anahtar oluşturur. Anahtarın gerçekten güvenli olması için gerçekten rastgele olması gerekir.

> **Eğer saklanmayan bir cüzdan gerçek anlamda rastgele bir anahtar üretmiyorsa güvenli değildir.**

Bu nedenle saklama dışı cüzdanlar kodlarını üçüncü tarafların incelemesine açık tutar. [WalletScrutiny.com](https://walletscrutiny.com) gibi web siteleri, Google Play'deki cüzdanların herkese açık olarak paylaşılan sürümle aynı kodu kullanmasını sağlar.

Saklama dışı iyi bir cüzdan, kamuya açık olarak belgelenen güvenlik yönergelerine ve cüzdan standartlarına uygun olmalıdır.

## 4. Bir Anahtar, Çok Para

Tek bir özel anahtar, birden fazla kripto para biriminin bakiyelerini kontrol edebilir. Cüzdan uygulamaları, desteklenen tüm kripto para birimlerinin bakiyelerini tek bir anahtar kullanarak otomatik olarak bulabilir.

Örneğin, [Deus Wallet](https://deuswallet.com) üzerinde bir cüzdan oluştururken, kullanıcılar desteklenen tüm kripto para birimleri için tek bir özel anahtara sahip olur.

Aynı özel anahtar, her birinin kendi bakiyesi ve işlemleri olan birden fazla kripto para birimini kontrol eder.

## 5. Bakiyeler ve İşlemler

Mühendisler tarafından birden fazla kripto para biriminin özel anahtarlarını yönetmek üzere tasarlanmış standartlar vardır. Bu standartlar, cüzdan uygulamalarının özel anahtarları nasıl yönettiğini tanımlar.

> **Cüzdan, her bir kripto para birimi için ödeme adresinizi elde etmek amacıyla özel anahtarınızı kullanır. Ödeme adresi, kripto para birimini almak için başkalarıyla paylaştığınız adrestir.**

Cüzdan uygulaması, özel anahtarınıza bakarak Bitcoin, Ethereum ve diğer kripto para birimleri için adreslerinizi türetebilir. Her kripto para biriminin farklı bir adresi vardır.

Özel anahtarı standart uyumlu başka bir cüzdana aktardığınızda aynı adresleri elde edecektir.

> **Özel anahtar standartlara uygun bir şekilde oluşturulduysa, diğer standart uyumlu cüzdanların, desteklenen her kripto para birimi için ödeme adreslerini ve geçmiş işlemleri doğru bir şekilde elde etmesi gerekir.**

Uygulama adresleri öğrendikten sonra ilgili blok zincirine bağlanarak bu adresleri içeren işlemleri alır, bakiyeleri ve geçmiş işlemleri görüntüler.

## 6. Cüzdanlar Arasında Geçiş Yapmak

Saklanmayan iyi cüzdanlar, cüzdanlar arasında özel anahtar geçişine izin verir. Saklanmayan bir cüzdan uygulamasında oluşturulan özel anahtarın diğerleriyle uyumlu olması gerekir.

> **Kullanıcılar tek bir cüzdan sağlayıcısıyla sınırlandırılmamalı ve diğer saklama dışı cüzdan uygulamalarına kolayca geçiş yapabilmelidir.**

Telefonunuz bozulursa veya cüzdan uygulaması çalışmayı durdurursa paranız güvendedir; Yıllar sonra bile özel anahtarı kullanarak kripto para biriminize erişimi yeniden sağlayabilirsiniz.

Bir cüzdan seçerken standartlarla uyumlu ve özel anahtarların içe/dışa aktarımını destekleyen bir cüzdan arayın.

> **Hayır te: Özel anahtarınızı taşırken hedef cüzdanın, o anahtar tarafından kontrol edilen tüm kripto para birimlerini desteklemesi gerekir.**

Özel anahtarınızda Bitcoin ve Ethereum bakiyeleri varsa ancak hedef cüzdan yalnızca Bitcoin'i destekliyorsa Ethereum bakiyeniz görünmez. Hâlâ sizin olacak ve başka bir cüzdandan erişilebilecek.