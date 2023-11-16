# C# ve ASP.NET Core MVC 

## Açıklama: 
+ Bu kurs içerik bakımından iki ana kısma ayrılmıştır; C# programlama dili ve ASP.NET MVC Core framework’ü. 
+ İlk kısımda C# dilinin sentaks kuralları, nesne yönelimli programlama ve .NET kütüphanesinin önemli sınıfları ele alınmaktadır. 
+ İkinci kısım ise ASP.NET MVC Core isimli framework ile modern ve platform bağımsız web uygulamaları/servislerinin geliştirilmesine odaklıdır. Bu kısımda ASP.NET Core haricinde (SOLID, UML, Pattern, Idiom, AntiPattern, ...) gibi pek çok önemli konu ve teknolojiye de (Entity Framework, SQL Server, RabbitMQ, Git, ...) değinilmekte yanı sıra pek çok örnek uygulama geliştirilmektedir.        
# Kısım 1 (.NET ve C#’a Giriş)
+	.NET ortamına ilişkin temel kavramlar (JIT, MSIL, CLR, CTS, CLS…)
+	Platform bağımsız çalışma olgusu
+	Çevirici programlar, derleyiciler yorumlayıcılar
+	.NET ortamının aşağı seviyede incelenmesi ve Java ile karşılaştırılması
+	Atom kavramı
+	Console sınıfının etkin kullanımı
# .NET Tür Sistemi
+	Değişkenler, Sabitler 
+	Faaliyet alanı ve Ömür kavramı
+	Type Inference
# Metotlar/Fonksiyonlar
+	Parametre ve Argüman kavramları
+	ref/out parametreler 
+	Default argüman alan metotlar
+	Variadic (değişken sayıda parametre alan) metotlar
+	İsimlendirilmiş parametreler
+	Overloading
# Operatörler
# Akış Kontrol deyimleri
+	if ve switch deyimleri
+	Koşul Operatörü
+	while ve do while döngü deyimleri
+	for ve foreach döngü deyimleri
+	break ve continue deyimleri
# Tür dönüştürmeleri
# Nesne Yönelimli Programlama (OOP) Paradigması
+	Sınıf ve nesne kavramları
+	Referans türleri ve değer türleri
+	Referans (adres) kavramı
+	new operatörü
+	Sınıfın static olmayan veri elemanlarına erişim ve nokta operatörü
+	Sınıfın static olmayan veri elemanlarının varsayılan değerleri
+	Referans parametreli metotlar
+	Referans geri dönüş değerli metotlar
+	Sınıfın static veri elemanları
+	Sınıfın non-static ve static metotları
+	Sınıfın non-static metotları içerisinde non-static ve static elemanlara doğrudan erişim durumu
+	Sınıfın static metotları içerisinde non-static ve static elemanlara doğrudan erişim durumu
Sınıfların başlangıç metotları (constructors)
+	Nesne oluşturulması adımları
+	Sınıfın varsayılan (default) başlangıç metodu
+	Başlangıç metotlarının overload edilmesi
+	Birincil başlangıç metotları (primary constructor’s) 
# İsim alanları (Namespace)
+	Paketleme ve granülasyon kavramları
+	Farklı isim alanlarındaki sınıflara erişim
+	İç içe isim alanı bildirimleri
+	using anahtar sözcüğü
# İsim arama
+	Niteliksiz (unqualified) isim arama
+	Nitelikli (qualified) isim arama
# Diziler (Arrays) ve uygulamalar
+	Dizi referansları
+	Diziye ilişkin nesnelerin bellekteki durumu
+	Dizi elemanlarına erişim
+	Dizilere ilk değer verilmesi
+	Dizilerin metotlara geçirilmesi: dizi referansı parametreli metotlar
+	Dizi referansı döndüren metotlar
+	Sıralama algoritmaları: (bubble sort, selection sort, quick sort) 
+	char türden diziler
+	char türden diziler ve String sınıfı
+	Referans dizileri
+	Referans dizilerine ilkdeğer verilmesi
+	String türden diziler
+	Dizi dizileri
+	Dizi dizilerinin çok boyutlu dizi gibi kullanılması
+	Dizi dizilerine ilk değer verilmesi
# Sınıflarda temel erişim kuralları
+	public erişimcisi
+	private erişimcisi
+	protected erişimcisi
+	internal erişimcisi
+	file erişimcisi
+	Başlangıç metodunun private, protected ya da internal olması durumu
+	Singleton ve Factory tasarım kalıpları
+	Encapsulation kavramı, Property ve AutoProperty’ler
+	Object Initializer kullanımı
# Enum’lar
+	enum sabitleri
+	enum sınıfların sabit dışındaki elemanları
+	enum sınıfların başlangıç metotları (constructor)
+	enum’ların karşılaştırılması
+	enum’ların kullanımı
# Sınıflar arası ilişkiler
+	Association, Composition, Aggregation, Inheritance, Dependency
+	UML modelleme diline giriş
# Türetme (inheritance)
+	Base class (taban sınıf) ve derived class (türemiş sınıf) kavramları
+	Başlangıç metodu içerisinde taban sınıfın başlangıç metodunun çağrılması
+	Başlangıç metodu içerisinde taban sınıfa ait istenilen bir başlangıç metodunun çağrılması
+	Başlangıç metodu içerisinde başka bir başlangıç metodunun çağrılması
+	protected bölümün anlamı
+	Object sınıfı
# Taban sınıf ve türemiş sınıf arasındaki dönüşümler
+	Yukarıya doğru dönüşüm (upcasting)
+	Aşağıya doğru dönüşüm (down-casting)
+	is opetörü
+	Otomatik kutulama (auto-boxing) ve otomatik kutuyu açma (auto-unboxing)
+	sealed sınıflar
+	this referansının anlamı ve kullanımı
+ null referans kavramı
# Çöp Toplayıcı (garbage collector)
+	Çöp toplayıcı’nın çalışma biçimi
+	Referans sayma, GC Sınıfı 
+	IDisposable ve using anahtar sözcüğü ile Dispose kalıbının idiomatik uygulaması
# Önemli Veri Yapılarına İlişkin Sınıflar
+	ArrayList, List
+	HashTable, Dictionary, SortedList 
+	Tupple
# Çok biçimlilik (Polymorphism)
+	Sanal metotlar ve Overriding
+	base referansı
+	Override edilen metot içerisinde taban sınıfın aynı metodunun çağrılması (augmentation)
+	Override edilen metodun erişim belirleyicisinin erişim anlamında yükseltilmesi
+	sealed metotlar
# Soyut sınıflar ve metotlar (abstract classes and methods)
+	Soyut sınıf ve metotların anlamı
+	Soyut metotların override edilmesi
+	Soyut metotların override edilmemesi durumu
+	Soyut sınıfların taban sınıf referansı olarak kullanılması
+	Soyut sınıfların başlangıç metotları
# Exception Handling 
+	Exception kavramı kullanımı
+	throw anahtar sözcüğü ve bir exception nesnesinin fırlatılması
+	Try/Catch/Finally mekanizması
+	Yeniden fırlatma (rethrow)
+	İçiçe try bloklarının bulunması durumu
+	Özgün Exception sınıfları
+	checked ve unchecked exception sınıfları
+	Önemli exception sınıfları
# Arayüzler (Interface’s)
+	Bir sınıfın desteklediği arayüzler ve metotların override edilmesi
+	Arayüzler ile abstract sınıflar arasındaki farklar
+	Arayüzler arası tür dönüştürme ayrıntıları
+	Sıkça kullanılan bazı arayüzler
# Generic’ler ile Türden Bağımsız İşlemler 
+	Generic sınıflar ve metotlar
+	Generic sınıflarda türetme işlemleri
+	Generic sınıflarda new operatörü ile <> (diamond syntax) kullanımı
+	Generic arayüzler
+	Kısıtlamalar (constraint’s)
+	Generic sınıflarda alt sınır ve üst sınır belirlenmesi (invariant, covariant ve contra-variant)
+ Extension metotlar
+ Delegate (Temsilci) ve Event’ler
+ Lambda İfadeleri
+ Thread ve Process Sınıfları
+ Reflection ve Metadata kavramları
+ Attribute sınıfları
+ Bit seviyesinde işlemler ve ilişkili operatörler
+ Dinamik kütüphanelerin (DLL) oluşturulması ve kullanılması
+ Dosya işlemleri
+ ADO.NET ile VeriTabanı İşlemleri
+ Asenkron Çalışma ve TPL (Task Parallel Library) 

# Kısım 2 (ASP.NET MVC Core ve C# ile Web Uygulamaları Geliştirmek)
+ Middleware kavramı
+ Request ve Response Manipülasyonları
+ Dependency Inversion, Inversion Of Control
+ Dependency Injection kavramı
+ Katmanlı Mimarı Kullanarak Uygulama Geliştirme
+ Repository, UnitOfWork kalıpları
+ Katmanlı mimaride exception handling
+ Razor sentaksı
+ MVC (Model ViewController) kalıbı 
+ Razor Engine ve Razor sentaksı
+ Dinamik tür sistemi ve Expando Nesneler
+ Transfer Data (ViewBag, ViewData, TempData)
+ Tag Helper’lar
+ Validasyon
+ Blazor Framework
+ Entity Framework Core ile veritabanı işlemleri
+ Container ve Docker Kavramları
+ Container ortamında ASP.NET Core uygulamalarının çalıştırılması
+ ASPNET Core Güvenlik
+ Authentication, Authorization, OAuth
+ Javascript programlama dili
+ WebAPI ile Rest Servislerin Yazılması
+ JWT (Json Web Token)
+ CQRS 
+ Mikroservis Mimarisi
+ LibMan ve Npm Paket Yönetim Sistemleri
+ Cookie (Çerezler) 
+ Session Mekanizması
+ Onion Architecture
+ RabbitMQ, MSMQ gibi mesaj kuyruklama altyapılarının kullanımı
+ Ve diğerleri
