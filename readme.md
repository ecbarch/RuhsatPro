# RuhsatPro



## Genel açıklama

ECB-BPG ile ruhsat projelerinde yer alan KAKS, TAKS, arsa payı, otopark, sığınak, ağaç, kazı-dolgu hesapları ve metrekare cetveli ile kat irtifakı tabloları gereken parametreleri girerek hızlı bir şekilde oluşturulabilmektedir. ECB-BPG sayesinde uzun süren ruhsat projesi hesapları kısa sürede tamamlanıp zamandan tasarruf sağlanmaktadır.

![Untitled](ECB-BPG%20User%20Manual%208ee8d20fe2f141fab8637257040a6742/Untitled.png)

## Ön Hazırlık: Kullanıcının yapması gerekenler

- Parametreler template dosyadan transfer project ile aktarılır.
- [ ]  Schedule tabloları template dosyadan copy paste ile alınır.

- Tüm kat planları oluşturulmalıdır.
- Kat planlarında Emsal hesabı için gerekli tüm “Room”lar girilmiş ve doğru isimleri verilmiş olmalıdır.
- Roomlara Bağımsız bölüm no ve blok no parametreleri verilmiş ve uygun değerleri girilmiş olmalıdır.
- Room Eğer depo ya da bağımsız bölüme dahil bir eklenti Alanı ise Eklenti/Değil parametresi işaretlenmelidir.

Not: Eklenti parametresi varsayılan olarak eklenti değil olarak işaretlidir. Eğer room eklenti değilse bir şey yapmaya gerek yoktur.

![Untitled](ECB-BPG%20User%20Manual%208ee8d20fe2f141fab8637257040a6742/Untitled%201.png)

- Project information TAKS ve KAKS parametreleri proje yönetmeliğince uygun değer ile doldurulurmalıdır.

![Untitled](ECB-BPG%20User%20Manual%208ee8d20fe2f141fab8637257040a6742/Untitled%202.png)

# Area Planlar

## Area Planları oluşturma

![plans.png](ECB-BPG%20User%20Manual%208ee8d20fe2f141fab8637257040a6742/plans.png)

Create Area Plans

- Kat planlarının bağımsız bölüm metrekareleri ve emsal metrekarelerini ölçen area planları oluşturmaktadır.
- Kat planlarının eksiksiz olduğundan emin olunuz. Eksik kat planı olması durumunda o katın area planlarını oluşturmayacaktır.
- Kat planlarının isimlendirmelerinin doğru olduğundan emin olunuz. Kat planları ile area plan isimleri aynı olacaktır.
- Oluşan Emsal area Planına “ECB-Emsal Alan” View Temlate’ı, Bağımsız Bölüm Area Planlarına “ECB-Bağımsız Bölüm” Template’ı Atanır.

## Emsal Area Boundary oluşturma

![Untitled](ECB-BPG%20User%20Manual%208ee8d20fe2f141fab8637257040a6742/Untitled%203.png)

Emsal Area Boundary

Kat bazında Çalışır. İlgili kat room name’lerini Tanıyarak Emsal Area Planların oluşturur.

### Uygulama

- İlgili Kat planının Emsal area Plan view’ı açılır.
- Plugin üzerinden Emsal Area Boundary Butonuna basılır.
- Birkaç saniyede doğrudan emsal dışı ve 30/70 kapsamında emsal dışı alanları oluşturur. Ayrıca elemanlar kendi içinde gruplanacak ve View template’da renkli olarak ayrılacaktır.
- Birbiriyle Eş katlar olması durumunda; Bu plandaki gruplanmış olan area boundary area ve tag’ler  diğer katlara kopyalanarak işlem kolaylığı sağlanabilir.
- Eğer Eş katlar yok ise her katta bu işlem tekrarlanır.

### Düzeltme ve kontrol

- area’ları oluşan view’lar kontrol edilip gerekli küçük düzeltmeler sağlanmalıdır.
- 

### Karşılaşılabilcek sorunlar

- Projedeki Room boundary’lerinde var olan hatalar ya da eksik girilen parametreler sorunlara yol açabilir.

## BB Area Boundary oluşturma

![Untitled](ECB-BPG%20User%20Manual%208ee8d20fe2f141fab8637257040a6742/Untitled%204.png)

BB Area Boundary

Kat bazında çalışır. İlgili kat mahal isimlerini tanıyarak bağımsız bölüm Area Planların oluşturur.

### **Uygulama**

- İlgili Kat planının Bağımsız Bölüm area Planı açılır.
- BB Area Boundary butonuna basılır.
- Birkaç saniyede Bağımsız bölümler ve ortak alanlar oluşacaktır.
- Katlar arası kopyalama yapılmamalıdır.

### Düzeltme ve kontrol

- Oluşan planda sınırlar kontrol edilmeli ve gereken yerlerde ufak düzeltmeler  yapılmalıdır.

### Karşılaşılabilcek sorunlar

- Eğer Bağımsız bölüm no girilmediyse ortak alan olarak oluşacaktır. Bağımsız bölümlerin doğru olması için roomlarda BB No parametresinin girilmiş olması gerekmektedir.

# Tablolar

## Emsal Özet

![Untitled](ECB-BPG%20User%20Manual%208ee8d20fe2f141fab8637257040a6742/Untitled%205.png)

Emsal Özet

- Emsal area planları okuyarak kat bazında gerekli hesapları yaparak Level üzerine ilgili parametreleri doldurur.
    
    ![Untitled](ECB-BPG%20User%20Manual%208ee8d20fe2f141fab8637257040a6742/Untitled%206.png)
    
- Area boundary oluşturulduktan sonra Emsal Özet butonu ile emsal hesapları tabloya aktarılmaktadır.
- Oluşturuken grupları bozmak isterse ungroup’u işaretleyiniz.
    
    ![Untitled](ECB-BPG%20User%20Manual%208ee8d20fe2f141fab8637257040a6742/Untitled%207.png)
    
- Bu işlem öncesi her adımın eksiksiz yapıldığından emin olunuz.
- Son olarak tabloyu kontrol ediniz

### Karşılaşılabilcek sorunlar

- Bu işlem öncesinde yapılan hatalar bu tabloya yansıyacaktır.

## Metrekare Cetveli

![Untitled](ECB-BPG%20User%20Manual%208ee8d20fe2f141fab8637257040a6742/Untitled%208.png)

Metrekare Cetveli

- Metrekare cetveli butonu;  Metrekare cetveli tablosundaki değerleri doldurmaktadır.
- Cinsi parametresi manual olarak doldurulmalıdır.

*NOT: Bu işlem öncesi her adımın eksiksiz yapıldığından emin olunuz.*

*NOT: Bu işlem öncesinde yapılan hatalar bu tabloya yansıyacaktır.*

![Untitled](ECB-BPG%20User%20Manual%208ee8d20fe2f141fab8637257040a6742/Untitled%209.png)

- Son olarak tabloyu kontrol ediniz.

## Sığınak-Otopark

![Untitled](ECB-BPG%20User%20Manual%208ee8d20fe2f141fab8637257040a6742/Untitled%2010.png)

Sığınak-Otopark

- Sığınak-Otopark butonu ile yönetmeliklere göre ne kadar sığınak ve otopark gerekli olduğu hesaplanmaktadır.
- Tabloda ihtiyacın yanında projedeki mevcut durum otomatik olarak gözükmektedir.

Not: Mevcut otopark sayısını sizin belirleyeceğiniz park family’si üzerinden hesaplanmaktadır.

![Untitled](ECB-BPG%20User%20Manual%208ee8d20fe2f141fab8637257040a6742/Untitled%2011.png)
