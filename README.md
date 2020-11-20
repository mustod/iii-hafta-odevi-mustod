# III-hafta-odevi

- .Net kodu nedir ve nasıl derlenir?

- Roslyn compiler ne işe yarar?

- Restful servisler nasıl çalışır? Alternatifleri nelerdir ve nasıl çalışırlar?

- Extension method nedir? Nasıl yazılır?

- MVC'nin alternatifleri nelerdir?

- Architectural pattern nedir? Neden ihtiyaç duyuyoruz?

- ViewData, ViewBag, TempData farkları nelerdir? Çalıştığımız proje üzerinde başka bir branch açarak bunları deneyiniz?

-----------------------
### .Net kodu nedir ve nasıl derlenir?
C# ve Visual Basic için Visual Studio IDE yalnızca tek dosya derlemeler oluşturmak için kullanılabilir. Çoklu dosya derlemeleri oluşturmak istiyorsanız, Visual C++ komut satırı derleyicilerini veya Visual Studio 'Yu kullanmanız gerekir. Çok dosyalı derlemeler yalnızca .NET Framework tarafından desteklenir.
> [Kaynak](https://docs.microsoft.com/tr-tr/dotnet/framework/app-domains/build-multifile-assembly)
* Command-line tools: Yeni bir proje oluşturma, derleme, dağıtma gibi işlemler Command-Line üzerinden yapılabilmektedir.
* .NET Framework Libraries: Birincil/temel data türlerini, uygulama derleme türlerini,  temel bileşenleri içerek bir framework kütüphane seti içermektedir.
> [Kaynak](https://mcansozeri.wordpress.com/2016/08/03/net-coreun-inanilmaz-dunyasi-net-core-nedir/)
---------
### Roslyn compiler ne işe yarar?
Visual Studio 'da canlı, proje tabanlı kod Çözümleyicileri sayesinde, API yazarları, NuGet paketlerinin bir parçası olarak etki alanına özgü kod analizini sevk edebilir. Bu çözümleyiciler .NET Compiler Platform (kod-adı "Roslyn") tarafından korunduğundan, satırı bitirmeden (sorunları çözmek için kodunuzu derlemek için daha fazla beklememeniz gerekmez) kodunuzda uyarı üretebilirler. Çözümleyiciler, kodunuzu hemen temizleyebilmeniz için Visual Studio ampul istemiyle otomatik bir kod düzeltmesini de yüzeylere açabilir.
> [Kaynak](https://docs.microsoft.com/tr-tr/visualstudio/extensibility/getting-started-with-roslyn-analyzers?view=vs-2019)
-------------------
### Restful servisler nasıl çalışır? Alternatifleri nelerdir ve nasıl çalışırlar?
 REST ,servis yönelimli mimari üzerine oluşturulan yazılımlarda kullanılan bir transfer yöntemidir.İstemci ve sunucu arasında XML ve JSON verilerini taşıyarak uygulamanın haberleşmesini sağlar.REST mimarisini kullanan servislere ise RESTful servis denir.
 > [Kaynak](https://medium.com/@bsrutmn/rest-ve-restful-web-servi%CC%87s-nedi%CC%87r-7258b7db7f66#:~:text=REST%20%2Cservis%20y%C3%B6nelimli%20mimari%20%C3%BCzerine,servislere%20ise%20RESTful%20servis%20denir.)
SOAP(en: Simple Access Protocol ,tr: Basit Nesne Erişim Protokolu) en temel anlamda, internet üzerinden küçük miktarda bilgileri yada mesajları aktarma protokoludur. SOAP mesajları XML formatındadırlar ve genellikle HTTP(Hyper Text Transfer Protocol) protokolu(bazende TCP/IP) kullanılarak gönderilirler. SOAP ,XML tabanlı kullanıma mecbur bırakır. Bu konuda esnek değildir.
>[Kaynak](https://medium.com/android-t%C3%BCrkiye/rest-api-kavramlar%C4%B1-soap-ile-farklar%C4%B1-4c6f19ddbc6c)
-----------
### Extension method nedir? Nasıl yazılır?
Extension metodlar herhangi bir yeni nesne oluşturmadan, üzerinde işlem yaptığınız nesne üzerinden çağrılabilen "genişletilmiş" manasına gelen çok pratik metodlardır. Bu metodları kullanarak hem extra iş yükünden kurtulmuş olursunuz, hem de sürekli aynı kodları yazmak zorunda kalmazsınız.

Extension metodların kullanımı da çok kolaydır. Extension metodları kullanacağınız kaynak koda, using anahtar kelimesini kullanarak eklediğinizde bu metodlarınızı kullanabilirsiniz.
> [Kaynak](http://www.yavuzaydogan.com/c-sharp/extension-metod-nedir-nasil-yazilir-nasil-kullanilir-147#:~:text=Extension%20metodlar%20herhangi%20bir%20yeni,ayn%C4%B1%20kodlar%C4%B1%20yazmak%20zorunda%20kalmazs%C4%B1n%C4%B1z.)
-------------
### MVC'nin alternatifleri nelerdir?
Action-Domain-Responder, 2014 yılında Paul M. Jones tarafından duyuruldu. Paul M. Jones, PHP komunitesinde oldukça aktif, bazı PSR standartlarının belirlenmesinde görev almış bir adam. Dolayısı ile komunitede belirli bir kredibilitesi var.

ADR, HTTP üzerinden haberleşen web uygulamalarını tanımlamak üzere geliştirilmiş bir tanımlama. Net bir implementasyonu yok. Vurguladığı önemli noktalardan biri, bir uygulama mimarisi olmaması ve sadece web uygulamaları için bir kullanıcı etkileşimi pattern’i olması.

ADR elemanları olan action, domain ve responder’ı MVC’deki elemanlara benzetebiliriz.
> [Kaynak](https://blog.cemunalan.com.tr/2019/10/17/adr-bir-mvc-alternatifi/)
---------
### Architectural pattern nedir? Neden ihtiyaç duyuyoruz?
Mimari desenler, yazılım mühendisliğindeki mimari sorunlara çözümler öneren yazılım desenleridir. Bir mimari desen, yazılım sistemi için alt sistemlerden ve bunların sorumluluklarıyla iç ilişkilerinden meydana gelen temel ve yapısal bir organizasyon şemasını ifade eder. Tasarım desenleri ile mukayese edilirse, mimari desen daha büyük ölçeklidir.
>[Kaynak](https://tr.wikipedia.org/wiki/Mimari_desen)
Yazılım mimarisine ihtiyaç duymamızın en önemli sebeplerinden biri de sistemin karmaşıklığını yönetmek ve bütünlüğünü korumak için pratik bir yapı sunmasıdır.
> [Kaynak](https://www.horato.com/tr/post/yazilim-mimarisi-software-architecture-60#:~:text=Neden%20Yaz%C4%B1l%C4%B1m%20Mimarisine%20%C4%B0htiya%C3%A7%20Duyar%C4%B1z,geli%C5%9Ftirme%20s%C3%BCreci%20karma%C5%9F%C4%B1k%20bir%20s%C3%BCre%C3%A7tir.&text=Yaz%C4%B1l%C4%B1m%20mimarisine%20ihtiya%C3%A7%20duymam%C4%B1z%C4%B1n%20en,i%C3%A7in%20pratik%20bir%20yap%C4%B1%20sunmas%C4%B1d%C4%B1r.)
-------
### ViewData, ViewBag, TempData farkları nelerdir? Çalıştığımız proje üzerinde başka bir branch açarak bunları deneyiniz?
ViewBag , ViewData ve TempData aralarındaki en büyük fark ise TempData nesnesini eğer ki bir daha kullanmak istersek bir sonraki redirek ettiğimiz actionda herhangi bir işleme mağruz kalmadan kullanabiliriz. Fakat ViewBag ve ViewData nesnelerine ulaşamayız.
> [Kaynak](http://www.aspmvcnet.com/tr/m/razor/viewbag-viewdata-ve-tempdata-asp-net-mvc-3-kullanimi-ve-farklari.html)