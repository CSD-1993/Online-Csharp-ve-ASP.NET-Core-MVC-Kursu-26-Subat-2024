# CSharp ile Nesne Yönelimli Programlama

## Temel kavramlar
+ .NET ortamına ilişkin temel kavramlar (JIT, MSIL, CLR, CTS, CLS...)
+ Platform bağımsız çalışma olgusu
+ Çevirici programlar, derleyiciler yorumlayıcılar
+ .NET ortamının aşağı seviyede incelenmesi ve Java ile karşılaştırılması
+ Atom kavramı
+ Console sınıfının etkin kullanımı

## Tür kavramı
+ .NET ortamının ortak tür sistemi, Type Inference
+ Değişkenler, sabitler ve faaliyet alanı
+ Ömür kavramı

## Metotlar
+ Metotların geri dönüş değerleri
+ _return_ deyimi
+ Metotların parametre değişkenleri
+ Opsiyonel parametreler
+ Default argüman alan metotlar
+ Variadic metotlar

## Sabitler
+ Sabit kavramı
+ Sabitlerin türleri
+ Tamsayı sabitleri
+ Gerçek sayı sabitleri
+ bool türden sabitler
+ Karakter sabitleri
+ Escape sequence karakterler
+ Tamsayı sabitlerinin hexadecimal, binary ve octal gösterilişleri
+ Gerçek sayı sabitlerinin bilimsel gösterilişi
+ Sabit bildiriminde alttire karakterinin kullanımı

## Temel Operatörler
+ Operatörlerin sınıflandırılması
+ Operatör önceliği
+ Aritmetik Operatörler
+ Karşılaştırma operatörleri
+ Mantıksal operatörler
+ Atama operatörü ve işlemli atama operatörleri

## Kontrol deyimleri
+ _if_ ve _switch_ deyimleri 
+ _while_ ve _do while_ döngü deyimleri
+ _for_ ve _foreach_ döngü deyimleri
+ _break_ ve _continue_ deyimleri
+ Örnek programlar

## Tür dönüştürmeleri
+ Farklı türlerin birbirine atanması
+ İşlem öncesi otomatik tür dönüşümleri
+ Tür dönüştürme operatörü

## Koşul operatörü
+ Koşul operatörünün özellikleri
+ Koşul operatörünün kullanıldığı durumlar

## Aynı isimde metotlar _(method overloading)_
+ Bir sınıf içerisinde aynı isimde metotlar
+ Bir metodun imzası
+ Çağırma sırasında hangi metodun çağrılacağının belirlenme süreci _(overload resolution)_
+ Tam uyum _(best match)_
+ Tam uyum olmadığında hangi metodun çağrılacağının belirlenme süreci

## Nesne Yönelimli Programlama Paradigması
+ Nesne yönelimli programlama paradigmasına ilişkin temel kavramlar, diğer paradigmalar ile karşılaştırma
+ Sınıf ve nesne kavramları

## Adres kavramı
+ Adres kavramı
+ unsafe uygulamalarda pointer (gösterici) kullanımı
+ Stack, Code ve Heap alanları

## Temel sınıf kavramları
+ Sınıf ve nesne kavramları
+ Referans türleri ve değer türleri
+ Referans kavramı
+ _new_ operatörü
+ Sınıfın _static_ olmayan veri elemanlarına erişim ve nokta operatörü
+ Sınıfın _static_ olmayan veri elemanlarının varsayılan değerleri
+ Referans parametreli metotlar
+ Referans geri dönüş değerli metotlar
+ Sınıfın _static_ veri elemanları
+ Sınıfın _non-static_ ve _static_ metotları
+ Sınıfın _non-static_ metotları içerisinde _non-static_ ve _static_ elemanlara doğrudan erişim durumu
+ Sınıfın _static_ metotları içerisinde _non-static_ ve _static_ elemanlara doğrudan erişim durumu
+ Örnek yararlı sınıflar

## Sınıfların başlangıç metotları _(constructors)_
+ Nesne oluşturulması adımları
+ Sınıfın varsayılan _(default)_ başlangıç metodu
+ Başlangıç metotlarının _overload_ edilmesi
+ Örnek yararlı sınıflar

## Rassal sayı üretimi _(Random sınıfı)_

## String sınıfı
+ _Immutable_ sınıf kavramı
+ _String_ nesnesinin bellekteki durumu
+ _String_ sabitleri _(String literals)_
+ _String_ sınıfının metotları
+ _String_ işlemlerine yönelik yararlı metotların yazılması
+ Örnek programlar

## İsim alanları 
+ Paketleme ve granülasyon kavramları
+ Farklı isim alanlarındaki sınıflara erişim
+ İç içe isim alanı bildirimleri
+ using anahtar sözcüğü

## İsim arama
+ Niteliksiz _(unqualified)_ isim arama
+ Nitelikli _(qualified)_ isim arama

## Diziler _(Arrays)_ ve uygulamalar
+ Dizi referansları
+ Diziye ilişkin nesnelerin bellekteki durumu
+ Dizi elemanlarına erişim
+ Dizilere ilk değer verilmesi
+ Dizilerin metotlara geçirilmesi: dizi referansı parametreli metotlar
+ Dizi referansı döndüren metotlar
+ Dizilere ilişkin temel algoritmaların yazımı
+ Dizilere ilişkin yararlı metotların yazımı
+ Dizilerde bazı sıralama algoritmaları: kabarcık sıralaması _(bubble sort)_ ve _seçerek sıralama _(selection sort)_ algoritmaları
+ _char_ türden diziler
+ _char_ türden diziler ve _String_ sınıfı
+ Referans dizileri
+ Referans dizilerine ilkdeğer verilmesi
+ _String_ türden diziler
+ Dizi dizileri
+ Dizi dizilerinin çok boyutlu dizi gibi kullanılması
+ Dizi dizilerine ilk değer verilmesi
+ Matrisler ve matrislere ilişkin algoritmalar
+ Örnek programlar

## Sınıflarda temel erişim kuralları
+ _public_ erişimcisi
+ _private_ erişimcisi
+ _protected_ erişimcisi
+ _internal_ erişimcisi
+ Başlangıç metodunun _private_, _protected_ ya da _internal_ olması durumu
+ _Singleton_ tasarım kalıbı
+ Encapsulation kavramı, Property'ler ve property'lerin ara koda nasıl dönüştüğünün incelenmesi
+ Örnek sınıflar

## enum'lar
+ enum sabitleri
+ enum sınıfların sabit dışındaki elemanları
+ enum sınıfların başlangıç metotları (constructor)
+ enum'ların eşitlik karşılaştırması
+ enum'ların karşılaştırılması
+ enum'ların kullanımı
+ Örnek enum sınıflar

## Sınıflar arası ilişkiler
+ _Composition_
+ _Aggregation_
+ _Association_
+ _Inheritance_
+ Sınıflar arası ilişkilerin modellenmesi
+ _UML_ modelleme diline giriş 

## Türetme _(inheritance)_
+ _Base class_ (taban sınıf) ve _derived class_ (türemiş sınıf) kavramları
+ Türetme sentaksı
+ Başlangıç metodu içerisinde taban sınıfın başlangıç metodunun çağrılması
+ Başlangıç metodu içerisinde taban sınıfa ait istenilen bir başlangıç metodunun çağrılması
+ Başlangıç metodu içerisinde başka bir başlangıç metodunun çağrılması
+ _protected_ bölümün anlamı
+ Object sınıfı
+ Örnek sınıflar

## Taban sınıf ve türemiş sınıf arasındaki dönüşümler
+ Yukarıya doğru dönüşüm _(upcasting)_
+ Yukarıya doğru dönüşümün anlamı
+ Aşağıya doğru dönüşüm _(down-casting)_
+ _is_ opetörü
+ Otomatik kutulama _(auto-boxing)_ ve otomatik kutuyu açma _(auto-unboxing)_
+ _sealed_ sınıflar
+ Referansların statik ve dinamik türleri
+ Örnek programlar

## this referansı
+ _this_ referansının anlamı
+ _non-static_ metotlar içerisinde _this_ kullanmı

## null referans
+ _null_ adres kavramı ve _null_ sabiti
+ _null_ referansın kullanıldığı durumlar

## Çöp Toplayıcı _(garbage collector)_
+ Nesnelerin ömürleri
+ Nesnelerin seçilebilir _(garbage collected)_ duruma gelmesi
+ Çöp toplayıcı'nın çalışma biçimi
+ Nesnelerin gösteren referansların takibine yönelik tipik algoritmalar
+ using anahtar sözcüğü
+ IDisposable arayüzü

## Dinamik büyüyen dizi veri yapısı
+ Dinamik büyüyen veri yapısına ilişkin temel kavramlar: _capacity_, _size_ vs.
+ Dinamik büyüyen veri yapısına ilişkin metotların karmaşıklık durumları
+ _ArrayList_ ve _List_ sınıfları
+ _HashTable_ _Dictionary_ _SortedList_ sınıfları
+ Örnek bir dinamik büyüyen dizi sınıfının yazılması

## Çok biçimlilik (polymorphism)
+ Çok biçimliliğin programlamaya yönelik tanımları
+ Çok biçimli mekanizma
+ Sanal metotlar
+ Sanal metotların _override_ edilmesi
+ Metotların _override_ edilmesinin anlamı
+ _base_ referansı
+ _Override_ edilen metot içerisinde taban sınıfın aynı metodunun çağrılması _(augmentation)_
+ _Override_ edilen metodun erişim belirleyicisinin erişim anlamında yükseltilmesi
+ _sealed_ metotlar
+ Çok biçimliliğe ilişkin örnek tasarımlar ve kodlanması

## Soyut sınıflar ve metotlar _(abstract classes and methods)_
+ Soyut sınıf ve metotların anlamı
+ Soyut metotların _override_ edilmesi
+ Soyut metotların _override_ edilmemesi durumu
+ Soyut sınıfların taban sınıf referansı olarak kullanılması
+ Soyut sınıfların başlangıç metotları
+ Örnek sınıflar

## Exception mekanizması
+ _Exception_ kavramı kullanımı
+ _throw_ anahtar sözcüğü ve bir _exception_ nesnesinin fırlatılması
+ _try_ blokları
+ _catch_ blokları
+ _catch_ blokları parametrelerine ilişkin sınıflar ve uygun _catch_ bloğunun bulunması
+ Yeniden fırlatma _(rethrow)_
+ İçiçe _try_ bloklarının bulunması durumu
+ _finally_ bloğu
+ Yakalanamayan _exception_ durumu
+ _Exception_ sınıflarının anlamı
+ _checked_ ve _unchecked exception_ sınıfları
+ Önemli _exception_ sınıfları
+ Örnek sınıfların _exception_ açısından düzenlenmesi ve genel hale getirilmesi

## Arayüzler _(interfaces)_
+ Bir sınıfın desteklediği arayüzler ve metotların _override_ edilmesi
+ Arayüzler ile _abstract_ sınıflar arasındaki farklar
+ Arayüzler arası tür dönüştürme ayrıntıları
+ Sıkça kullanılan bazı arayüzler

## Generic sınıflar ve metotlar
+ Generic sınıflar
+ Generic sınıflarda türetme işlemleri
+ Generic sınıflarda _new_ operatörü ile _<> (diamond syntax)_ kullanımı
+ Generic arayüzler
+ Generic türlerde kısıtlamalar
+ Generic sınıflarda alt sınır ve üst sınır belirlenmesi _(invariant, covariant ve contra-variant)_
+ Generic metotlar
+ Generic metotlarda parametre türlerinin tespiti
+ Örnek sınıflar ve programlar

## Programın komut satırı argümanları

## Extension metotlar

## Delegate (temsilci) ve Event'ler

## Reflection ve metadata kavramlarının uygulamada kullanılması
+ Type sınıfı
+ typeof operatörü

## Attribute sınıfları

## Lambda ifadeleri

## bit seviyesinde işlemler ve ilişkili operatörler 

## Dinamik kütüphanelerin _DLL_ oluşturulması ve kullanılması

## Dosya işlemleri
+ Dosya ve dizin _(directory)_ kavramları
+ Dosya yol ifadeleri: _absolute_ and _relative_ path
+ Processin çalışma dizini _(current working directory)_
+ Metin _(text)_ ve ikili (binary) dosyalar
+ _File_ _Directory_ sınıfları
+ _Stream_ soyut sınıfı
+ Dosya işlemleri
+ Örnek programlar
