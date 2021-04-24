# LinkedinWebScraping
Kodluyoruz ve TED Üniversitesinin ortaklığında yaptığımız genç istihdamı sorununda yetenek açığı ve bilgi eksikliğinin 
giderilmesi projesi kapasamında ihtiyaç duyduğumuz verilerin bir kısmını Linkedin üzerinden web scraping yöntemi ile elde 
ettik.

Bu projenin diğer linkedin web scraping projelerinden farkı ulaşmak istediğimiz hemen hemen bütün web elementlerine
ulaşabiliyor oluşumuz ve belli başlı web elementleriyle sınırlı kalmamasıdır. Kodları yazarken , algoritmayı tasarlarken
özellikle sonradan doğabilecek ihtiyaçlara karşı projenin sürdürülebilir olmasını istedim. Farklı web elementlerine ait
bilgilere ulaşma ihtiyacımız olursa eğer sadece o web elementine ulaşmamı sağlayacak html kodunu bulmam ve kodların içerisinde
selenium kullanarak eklemem yeterli.

Genel olarak proje 4 parçadan oluşuyor, selenium ile web scraping ortamın yaratılması aşamasında başlangıçta gerekli olan işlemler ve 
çekilmesi gereken bilgiler için boş listelerin oluşturulması , tasarlanan algoritma ve proje kapsamında gerekli bilgilerin web scraping
yöntemi ile elde edilip listelere eklenmesi , oluşturulan algoritma gereği ana_baslik ve kıdemd_isb_sek_ist listeleri 1'den fazla bilgi tutuyor 
örneğin ana_baslik listesi hem şehir hemde şirket ismini içeriyor bu noktada ana_baslik listesi için gerekli bilgiler scrape edildikten sonra bu 
bilgileri de ayrı listelerde depolamak gerek. Son aşama ise tüm istenilen bilgiler ayrı ayrı listelerde toplandıktan sonra dataframe oluşturulması ve 
tasarlanan algoritma gereği gelen tekrarlanan aynı ilanların dataframe'den silinip dataframe'in kaydedilmesi. 

Scrape ortamı oluşturulurken kullanılan kodlar, tasarlanan algoritmanın mantığı ve web elementlerinden elde edilen bilgilerden dataframe oluşturulması gibi
konular detaylı bir şekilde kodların bulunduğu dosyada açıklanmıştır. Bu noktada sorularınız olursa benimle iletişime geçmekten çekinmeyin lütfen.

Not: Kodlar google chrome'un 88.0.4324.96 ve 88.0.4324.104 sürümüyle uyumlu bir şekilde çalışmaktadır. Chrome'un sürüm güncellemesi durumunda stabil çalışmayacaktır.
