Kullanılan Teknolojiler:
1) C# (C Sharp):
C#, Microsoft tarafından geliştirilen bir programlama dilidir ve genellikle Windows tabanlı uygulamaların geliştirilmesinde kullanılır. C#, nesne odaklı bir dil olup güçlü bir şekilde tip güvenliği ve modern programlama özelliklerini destekler. Programın temel yazılım altyapısı C# dilinde geliştirilmiştir, bu da programın güvenilir, hızlı ve ölçeklenebilir olmasını sağlar.
2) .NET Framework:
.NET Framework, Microsoft'un geliştirdiği bir yazılım platformudur ve C# gibi dillerle yazılmış uygulamaların çalıştığı ortamı sağlar. Bu platform, çeşitli kütüphaneleri, API'ları ve araçları içerir. .NET Framework, programın geliştirilmesi ve çalıştırılması için temel altyapıyı oluşturur. Ayrıca, .NET'in sunduğu zengin sınıf kütüphaneleri, kodun daha etkili ve hızlı bir şekilde yazılmasına olanak tanır.
3) Visual Studio:
Visual Studio, Microsoft'un entegre geliştirme ortamıdır. C# gibi dillerle yazılan projelerin tasarımından derlenmesine ve hata ayıklanmasına kadar birçok geliştirme sürecini destekler. Geliştiricilere zengin bir kod editörü, hata ayıklayıcı, derleyici ve arayüz tasarım araçları sağlar. Ayrıca, Visual Studio'nun zengin eklenti ekosistemi ve entegre takım işbirliği özellikleri, yazılım geliştirme sürecini daha verimli hale getirir.
4) Microsoft SQL Server (MSSQL):
Microsoft SQL Server, ilişkisel veritabanı yönetim sistemidir ve programın veritabanı yönetimini sağlamak için kullanılır. MSSQL, güvenilirlik, performans ve ölçeklenebilirlik açısından zengin bir özellik setine sahiptir. Bu veritabanı sistemi, programın öğretmen, derslik, sınıf ve ders bilgilerini depolamak, sorgulamak ve yönetmek için kullanılır. Veritabanı işlemleri, programın genel performansını ve veri bütünlüğünü sağlamak için MSSQL üzerinden gerçekleştirilir.

1-) Giriş Ekranı : 

Projemizi ilk çalıştırdığımızda karşımıza gelen araryüzümüzde hangi veritabanı sunucusu ve veritabanı ile çalışacaksak onun bağlantı adresini veriyoruz ya da hazır bir veritabanımız yok ise sunucu adresini yazarak yeni bir veritabanı oluşturarak devam ediyoruz.

![image](https://github.com/melih756/ders-program--olusturma/assets/74192618/59770dfb-d109-4521-8409-42e6f40975fe)


2-) Ders ve Öğretmen Ekranları : 

Projemizde gerekli veritabanı bağlantılarını uyguladıktan sonra sistemimizde yer alacak olan derslerimizi,öğretmenlerimizi ,dersliklerimizi ve sınıflarımızı ekleyerek gerekli dersler hangi sınıflarda hangi öğretmenler ve dersliklerde olacak şekilde ders atamamızı yapabiliyor olacağız.Sistemizde yer alacak olan dersler ve öğretmenler konusunda çeşitli kısıtlamalara gidilebilir aynı zamanda hangi gün uygun olacaklarını ya da olmayacaklarını sistem üzerinden belirleyebiliyor olacağız.

![image](https://github.com/melih756/ders-program--olusturma/assets/74192618/f8433885-da42-49fd-8f57-2975a67316e6)
![image](https://github.com/melih756/ders-program--olusturma/assets/74192618/286476b8-d6a5-4081-88ec-8245cc4f618e)
![image](https://github.com/melih756/ders-program--olusturma/assets/74192618/37f53299-303a-43f2-bce0-9db720ac3dc6)
![image](https://github.com/melih756/ders-program--olusturma/assets/74192618/f99d4d44-5cf6-451c-8d95-a432a6616197)
![image](https://github.com/melih756/ders-program--olusturma/assets/74192618/99b7e63a-f222-4e0d-9421-0d2758f78077)
![image](https://github.com/melih756/ders-program--olusturma/assets/74192618/3d872e18-56ba-4f8d-8373-750e4b90bbd7)
![image](https://github.com/melih756/ders-program--olusturma/assets/74192618/526880a0-d722-42f3-ad98-3124819e7d86)


3-) Ders Programı Oluşturma Aracı : 

Projemizde gerekli haftalık ders dağılım şeklini öğretmenlerin müsaitlik durumunu ve nerede ders vereceklerini sistemimizde belirledikten sonra ders programı oluşturma aracımız ile gerekli konfigurasyonalara sahip haftalık ders çizelgemiz oluşturulmaktadır.Dersleri çizelge üzerinden günlerini veya saatlarini değiştirebilme özelliğimiz mevcuttur ama çakışan derslerimiz aynı zaman aralığında çizelge üzerinde yer alamazlar.

![image](https://github.com/melih756/ders-program--olusturma/assets/74192618/c8033b1e-5aba-4ae4-8d8c-9c220e552d7f)


Proje Kurulumu : 

Projemizi çalıştıracağımız makineye indirdikten sonra visual studio ile projemizi çalıştırıyoruz. Projemiz çalıştıktan sonra karşımıza veritabanı bağlantı ekranı aracı ile bizi karşılıyor. Gerekli sunucu ve veritabanı bağlantılarını veritabanı kurulum aracını kullanarak yaptıktan sonra ekranlarımız arasında ilerlemeye devam ederek,ders,öğretmen,sınıf ve derslik eklemelerini yaparak ve bunlar arasında gerekli ders atamalarını ve kısıtları uyguladıktan sonra ders programızı projemiz oluşturmaktadır.

![image](https://github.com/melih756/ders-program--olusturma/assets/74192618/958bd9c3-3ab4-4e2f-b7d7-fb01f9fb991a)
![image](https://github.com/melih756/ders-program--olusturma/assets/74192618/92b098ca-c81f-4323-8b1f-a837db798ebb)


