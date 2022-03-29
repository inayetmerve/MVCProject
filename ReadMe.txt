Controller/HomeController

Ýndex metodu genelde listeleme için kullanýlýr.
Metod varsa view de olmalýdýr.
Yeni metod yazarsan sað týkla, view ekle.
Seçerken layout ta olmasýný istiyorsan layout seç.

View da HTML yani frontend kýsmý var.

Sayfa deðiþse bile arka planda sabit kalan kýsým content
Üst tarafta sabit kalan kýsým ise Layout sayfasýdýr.

Layout Render Body metodu olmadan çalýþmaz.
Çünkü çaðýralan sayfayý layout un hangi kýsmýnda göstereceðini bilemez.
Render Body bir c# metodu.
Html sayfasý içinde C# komutu kullanmak için @ yazýp kodu yazabiliriz.

Katmanlar
1)Entity Layer (Varlýk Katmaný Tablo-Sütun==Class-Property)
2)Data Access Layer (CRUD operasyonlarý)
3)Business Layer(Ýþ Katmaný Veri tabaný iþlemlerini UI a yansýtmadan önce kontroller
Ürün adý en fazla 20 karakter olsun, ürüne eriþimi olanlar ekleme yapsýn vs)
4)Presentation Layer - User Interface

Tablolar
--------
Heading
Content
Writer
Contact
About




