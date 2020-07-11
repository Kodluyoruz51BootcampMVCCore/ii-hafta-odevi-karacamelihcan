
# II Hafta (6-7 Haziran) Ödevleri 

## 6 Haziran Ödevleri:
- [ ] Github'ın Gitflow'u ile diğer yaklaşımları arasındaki fark nedir? ( gitflow vs ..)
- [ ] [Git and GitHub with Briana Swift](https://www.youtube.com/playlist?list=PLg7s6cbtAD17Gw5u8644bgKhgRLiJXdX4) Youtube Listesi incelensin. (11 Video)
- [ ] Merge pull request
    - [ ] Create a merge commit
    - [ ] Squash and merge 
    - [ ] Rebase and merge altında ne fark var (Ödev)
- [ ] issue ve #pull request de id ler neden artıyor farklı sekmeler olmasına rağmen?
- [ ] [Ramp up on Git and GitHub](https://lab.github.com/githubtraining/paths/ramp-up-on-git-and-github) (ödev)
- [ ] Aspnetboilerplate ve yan ürünler araştırması. [AspNet Boilerplate - Web Application Framework](https://aspnetboilerplate.com/)
- [ ] hackerRank.com --> [30 Days Of Code](https://www.hackerrank.com/domains/tutorials/30-days-of-code)


## 7 Haziran Ödevleri:
- [ ] Razor Pages Nedir?
- [ ] 4 Farklı Projede Yapılacak *Change Authentication* :
  - [ ] No Authentication
  - [ ] Individual User Account
  - [ ] Work or School Accounts
  - [ ] Windows Authentication seçili projeler oluşturulmalı
- [ ] Ayarlardaki Output kısmındaki Console Application nedir? diğerleri arasında fark nedir? [Ders Akışındaki 6. Madde'yi inceleyin.] ( araştırma ödev verildi ).
- [ ] c# json serialize / deserialize
- [ ] MVC vs MVVM
   - [ ] MVP vs MVW vs MVU Pattern arasındaki farkı araştır
   - [ ] Model-View-Update (MVU) nedir?

# Github'ın Gitflow'u ile diğer yaklaşımları arasındaki fark nedir? ( gitflow vs ..)

### Github nedir?
Git versiyon kontrol sistemidir. GitHub ise, git yazılımı ile entegre olmuş bir depolama alanıdır.GitHub sayesinde dünyanın çeşitli ülkelerinden, bu ülkelerin bazı yerlerinden, projenize farklı bir kaç kişi ekleyerek takım çalışması yapabilirsiniz.  

Git Flow, yazılım geliştirmenin her aşamasını kolayca yönetmek için farklı dallarla çalışır.Özellik dalları,sürüm dalları,ana hat veya geliştirme dalları ve düzeltmelerin nasıl ilişkili olduğunu açıklar. Bu yaklaşım,kullaıcılar tarafından kütüphane ve masaüstü uygulamaları gibi indirilen paket yazılımlar için çalışır. Ancak bir çok web sitesi için tercih edilmez.

GitHub, Git Flow gibi alternatif bir iş akışı önerir. Git Flow ile bazı öğelere sahiptir. GitHub, ana hattı ve sürüm dallarını bir master olarak birleştirir ve düzeltmeleri tıpkı özellik dalları gibi ele alır. 

Bu basitleştirilmiş model, değişikliklerin hızlı bir şekilde yapılabileceği ve bazen günde birkaç kez kolayca dağıtabileceği sürekli dağıtım modellerine daha uygundur.

### Merge Çeşitleri

GitHub, birleştirme işlemlerinde birleştirirken üç seçenek sunar; bu üç seçenek şunlardır:
* Create a Merge Commit
* Squash and Merge
* Rebase and Merge

#### Create a Merge Commit 
Varsayılan seçenek olan github'da Merge Pull Request, tüm yorumları Pull Request'ten alır ve birleştirme işleminde yeni bir yorumları Mastar Branch'e ekler.
#### Squash and Merge
Squash merging is a merge option that allows you to condense the Git history of topic branches when you complete a pull request. Instead of each commit on the topic branch being added to the history of the default branch, a squash merge takes all the file changes and adds them to a single new commit on the default branch.

#### Rebease and Merge
**rebase** komutu kullandığımızda ise ile A dalındaki her bir commit B dalına sanki commit işlemi B dalında yapılmış gibi yeniden yazılır. Bu sayede B dalının commit tarihçesi sanki tüm değişiklikler bu dalda olmuş gibi düz ve kesintisiz görünür. Rebase komutu yerel ve kısa süreliğine (örneğin bir hata giderme veya deneysel bir çalışma için oluşturulan) geçerli dallar için kullanılmalı. Paylaşılan depolarda rebase komutunu kullanmamanızı tavsiye ediyorum, çünkü rebase sonrasında projenizin ana dallarında değişikliklerin nereden kaynaklandığına dair bir bilgi veya ipucu göremezsiniz. Bu durum takım çalışmasını olumsuz yönde etkiler.


**Ramp up on Git and GitHub**

- [X] Kursa başlangıç yapıldı.

##


## Ayarlardaki Output kısmındaki Console Application nedir? diğerleri arasında fark nedir?**
Bir Console Application(Uygulaması), C# bağlamında düşünürsek, üç temel data akışına(standart input, standart output ve standart error) erişerek girdileri alıp çıktıları gösteren bir komut satırı(command line) konsol uygulamasıdır. Bir konsol uygulaması genellikle stand-alone executable dosya formatı içinde ya minimal bir grafik arayüzü barındırır ya da hiç barındırmaz.

## c# json serialize / deserialize**
**Serialization:** Bir nesnedeki verinin bir yerde depolaması veya ağ ortamında bir yerden bir yere gönderilmesi gerektiği durumlarda uygun formata dönüştürülmesi işlemine serileştirme denir. Serileştirilen nesneler veritabanı, hafıza veya dosya gibi ortamlarda saklanabilirler.

**Deserialisation:** Ulaşılabilir hale gelmiş datayı tekrardan hangi dilde yazıyorsak o dildeki objeye çevirmektir.

## ASP.NET Boilerplate

ASP.NET Boilerplate, “her şirket tek tek uğraşmasın, tüm .NET developer’lar için ortak bir framework geliştirelim” hedefiyle ortaya çıkmış açık kaynak kodlu, iyi dokümante edilmiş bir projedir. Sadece framework değil, modern uygulamalar için DDD(Domain Driven Design) tekniklerini baz alan sağlam bir mimari ve model sunar.

**Bağlantılar**

Tüm ABP framework paketleri nuget üzerinden dağıtılmaktadır ve Github üzerindeaçık kaynak kodlu olarak geliştirilmektedir. Aşağıdaki linklerden çok daha detaylı bilgilere ulaşabilirsiniz:

-   Web sitesi:  [http://www.aspnetboilerplate.com](http://www.aspnetboilerplate.com/)
-   Forum:  [http://forum.aspnetboilerplate.com](http://forum.aspnetboilerplate.com/)
-   Github:  [https://github.com/aspnetboilerplate](https://github.com/aspnetboilerplate)

## Razor Page Nedir?

**ASP.NET Core 2.0** ile beraber hayatımıza giren Razor Pages, ASP.NET Core MVC alt yapısında, sayfa bazlı web uygulamaları geliştirebileceğimiz bir programlama modeli. Tamamen MVC alt yapısı üzerine geliştirilmiş bir kabuk olarak düşünebilirsiniz. MVC template’lerindeki klasör sayısını azaltmak, sayfa bazlı uygulamaları daha kolay geliştirmek için tasarlanmış yeni bir model.

##  MVC vs MVP vs MVVM

MVC (Model-View-Controller), MVP (Model-View-Presenter) ve MVVM (Model-View-View Model) 
patternlerinin oluşmasının arkasında yatan temel motivasyon aslında az öncede bahsettiğim gibi hem Separation of Concerns prensibini uygulamak hemde kolay bir şekilde Unit Test yazılmasına olanak sağlamak, yani Test Driven Development (TTD) yöntemini uygulayabilmek. Bazı durumlarda da reusibility’i arttırabiliyor tabi, çünkü bu patternleri uyguladığımız zaman ufak değişiklerle, alt yapımızı koruyarak uygulamımın farklı platformlarda (Windows Forms, Asp.NET, WPF …) çalışmasını sağlayabiliyoruz yani UI bağımsız uygulamalar geliştirebiliyoruz.


### MVC (Model-View-Controller)

Controller kullanıcıdan gelen inputları karşılar, ayrıca UI ile ilgili bütün akışı yönetir ve kararları verir. Controller View hakkında hiç birşey bilmez ama View Controller’ı bilir. Görüldüğü üzere Controller ile View arasında 1-n bir ilişki var yani bir Controller birden fazla View tarafından kullanılabilir. Controller kullanıcıdan gelen inputlar doğrultusunda Model üzerinde değişikleri yapar, Model değiştiğini View’e notify eder yani View ile Model arasında Observer ilişkisi var. View, Model’e register olur, görüldüğü üzere bir model’e birden fazla View register olabilir. Aralarında ki observer ilişkisi sayesinde, Model’deki herangi bir değişiklik ona register olmuş bütün View’lere yansır.

MVC’nin en büyük avantajı sorumlulukları Model,View ve Controller’a temiz bir şekilde dağıtmasıdır. Controller’lar uygulamanın akışını kontrol ederler, nerede neyin nasıl yapılmasına gerektiğine karar verirler. View sadece kendisinin nasıl update olacağına ilişkin business’ı içerir, Model’i oluşturur ve kullanıcıya gösterir. View uygulamayla ilgili hiç bir logic içermediğinden dolayı farklı platformlar (Windows, Web) için aynı controller’ı kullanan birden fazla View olabilir.

### MVP (Model-View-Presenter)
MVP Pattern’i aslında MVC’den evrilmiş bir pattern, sadece bağımlılıklar değişiyor ve Controller’ın yerine Prenseter (ki bu durumda kendisine hala Controller denebiliyor) geliyor.

İnputları direk View karşılıyor, modern programlama ortamlarının mantığına daha uygun. View Presenter’ını biliyor, Presenter ise View’i bir interface aracılığıyla biliyor aralarında bir abstraction var. Ayrıca MVC’nin aksine View ile Presenter arasında 1–1 ilişki var. Presenter Model’i manipule ediyor, Model’in değişikleri Presenter’a notify etme durumu birazcık tartışmalı, etmeyedebilir, Presenter ilgili değişikliği yapıp, View’i kendisi güncelleyebilir. Zaten buradaki en büyük fark MVC’nin aksine Presenter’ın View’i bir interface aracılığıyla kendisinin güncellemesi, View burada Presenter’a interface aracılığıyla istediği bilgiyi açabilir, ister Textbox’ın Text’i olsun ister Buton’ın Enabled’ı olsun. Presenter View’in nasıl bir View, Web mi? Windows mu? olduğuyla ilgilenmiyor, sadece data akışıyla ilgili ne yapması gerektiğini, View’den gelen etkileşimleri nasıl karşılaması gerektiğini ve View’de nasıl değişikler yapması gerektğini biliyor. Yani Prensenter’ımız burada karar mekanizaması rölünü üstleniyor.


### MVVM (Model-View-ViewModel)
MVVM Pattern’i hakkında bilgi vermeden önce Presentation Model hakkında bilgi vermek istiyorum. Çünkü MVVM dediğimiz şeye; WPF ve Silverlight için Prensentation Model diyebiliriz.

MVVM birazcık MVP’yi andırıyor fakat buradaki fark, Presentation Model hem View ile ilgili stateleri tutuyor hemde View hakkında hiç birşey bilmiyor. Aslında PM View’in state ve davranışlarıyla ilgili bilgiyi kendi üzerine alıyor ve Business Layer ile arasındaki kordinasyonu sağlıyor ve View’e karar vermeyle ilgili çok az şey bırakıyor. View yine stateleri tutuyor aslında. Fakat MVP’nin aksine Presentation Model View ile ilgili hiç bir bilgiye ihtiyaç duymuyor, bu yüzden ki View ile PM arasında 1-n bir ilişki var, bir PM birden fazla View’de kullanılabiliyor, bu kısmıyla MVC’ye benziyor, fakat MVC’nin aksine View üzerinde ki manipulasyonlar PM üzerinden gerçekleşiyor. Aslında şöylede bakabiliriz, PM ile View arasında yine bir observer ilişkisi var, .Net’e kullanım şekillerinden biride INotifyPropertyChanged interface’inden türeyip, .Net’in binding alt yapısını kullanması. Zaten özünde yaptığı iş DataBinding. Kendi propertylerini View’in propertyleriyle senkronize ediyor, aynı zamanda state’lerede karar veriyor, mesela şu şu TextBox dolduğunda şu Buton enabled olsun gibi. Tabi herzaman enabled olucak bir kontrol’un state’ini PM’de tutmak anlamsız.

PM’in en büyük avantajı, hiç bir View’e ihtiyaç duymadan bir View’in davranışlarını ve Data’sını barındarabilmesi, bu yapısıyla TDD’ye (Test Driven Development) çok uygun.

