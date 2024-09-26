# ARMUT_ARL_PROJECT
# Association Rule Learning Öneri Sistemi
Bu proje, Türkiye’nin en büyük online hizmet platformu olan Armut'un veri setini kullanarak bir öneri sistemi geliştirmek amacıyla Association Rule Learning (İlişkilendirme Kural Öğrenimi) yöntemini uygular. Proje, kullanıcıların daha önce aldığı hizmetlere dayalı olarak yeni hizmet önerilerinde bulunmayı hedefler.

İçindekiler
Proje Hakkında
Teknolojiler
Kurulum
Veri Seti
Kullanım
Sonuçlar
Katkıda Bulunanlar
Lisans
Proje Hakkında
Bu projede, Armut'un hizmet alan kullanıcıları ve bu kullanıcıların aldıkları hizmetleri içeren bir veri seti kullanılarak ürün öneri sistemi oluşturulmuştur. Association Rule Learning tekniği kullanılarak, hizmetlerin birlikte satın alınma olasılıkları belirlenmiş ve öneriler geliştirilmiştir.

Teknolojiler
Proje, aşağıdaki teknolojileri kullanarak geliştirilmiştir:

Python 3.x
Pandas
Matplotlib
Lifetimes
MLxtend
Kurulum
Projenin çalışabilmesi için gerekli kütüphaneleri yüklemek için aşağıdaki komutları terminalde çalıştırın:
pip install pandas matplotlib lifetimes mlxtend
Veri Seti
Veri seti, kullanıcıların aldıkları hizmetlerden ve bu hizmetlerin kategorilerinden oluşmaktadır. Aşağıdaki alanları içermektedir:

UserId: Müşteri numarası
ServiceId: Anonimleştirilmiş servis kimlikleri
CategoryId: Anonimleştirilmiş hizmet kategorileri
CreateDate: Hizmetin satın alındığı tarih
Kullanım
armut_data.csv dosyasını projenizin ana dizinine yerleştirin.
Sonuçlar
Bu proje, kullanıcıların geçmişte aldığı hizmetlere dayalı olarak daha uygun ve kişiselleştirilmiş önerilerde bulunmak için etkili bir yöntem sunmaktadır. Association Rule Learning kullanılarak, hizmetlerin birlikte satın alınma olasılıkları belirlenmiş ve bu sayede daha fazla müşteri memnuniyeti sağlanması hedeflenmiştir.
