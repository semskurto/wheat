#  Buğday Başaklarının Tespit Edilmesi ve Diğer Nitelikli Verilerin Çıkarımı 🌾 (Wheat Detection and Other Extraction of Qualified Data)
*** 
  
  
![Workflow](https://user-images.githubusercontent.com/31928447/117125711-91f51f80-ada2-11eb-8728-44965850d6a6.png)  
##### ABSTRACT  
  In this study, it is aimed to extract spike density, maturity and basic health information from 
optical images in order to provide a healthy development process by monitoring wheat ears. Fort 
his purpose it is aimed to obtain basic health data from wheat optic images by using image 
processing and machine learning methods. These data will be beneficial in creating solutions for 
the losses in the production process of the wheat producer and obtaining quality products. 
  
##### ÖZET  
  Bu çalışmamızda buğday başaklarının takibini yapılarak sağlıklı gelişim süreci sağlanması için 
optik görüntülerden başak yoğunluğu, olgunluk ve temel sağlık bilgilerinin çıkarımı 
hedeflenmektedir. Bu amaçla görüntü işleme ve makine öğrenimi metotları kullanılarak buğday 
fotoğraflarından temel sağlık verileri elde edilmesi amaçlanmaktadır. Bu veriler buğday 
üreticisinin üretim sürecindeki kayıplara ilişkin çözümlerin oluşturulması ve kaliteli ürün elde 
edilmesi açısından fayda sağlayacaktır.  

  
#### 1. GİRİŞ  
  
  Buğday dünyada en çok üretilen ve pek çok ülkenin beslenme, ticaret ve ekim nöbeti
sistemlerinde vazgeçilmez bir kültür bitkisidir. Özellikle insan beslenmesinde alternatifsiz bir
bitki olan buğdayın ekim alanları ve üretimi, nüfus artışına paralel olarak artmaktadır. 1802
yılında 1 milyarı aşan dünya nüfusu, 1927 yılında yaklaşık 2 milyar olmuş ve 2011 yılında da
7 miyarı aşacağı, 2020’de 8.5 milyar, 2030’da 9.6 milyar, 2050’de ise 12 milyar olacağı
tahmin edilmektedir. Nüfus artışına paralel olarak artan dünya buğday üretimi de 1960’li
yıllarda yaklaşık 222 milyon ton iken, 2000’li yıllarda 586 milyon tona, 2010 yılında ise 650
milyon tona ulaşmıştır. Dünyada kişi başına buğday tüketiminin 1960’li yıllarda yaklaşık 70
kg olduğu, günümüzde ise 100 kg/kişi civarında olduğu tahmin edilmektedir. Dünya ortalama
buğday verimi son yıllarda 300 kg/da ‘a yükselmiş, ancak 2010 yılı itibarıyla dünya buğday
verim rekorunun 1.564 kg/da olduğu düşünülürse, mevcut ekim alanlarında ulaşılabilen
potansiyelin yaklaşık 1/5’ini üretebiliyoruz demektir.[28] Buna göre mevcut ekim alanlarını
artırmadan, birim alan verimini artırarak buğday üretimini artırması kritik öneme sahiptir.
Buradan yola çıkarak buğday üretim sürecinde buğday başaklarının takibini yapılması sağlıklı 
gelişimin sağlanabilmesi açısından önemlidir. Bu çalışmamızda görüntü işleme ve makine 
öğrenimi metotları kullanılarak buğday fotoğraflarından sağlık verileri elde edilmesi 
amaçlanmaktadır. Bu veriler buğday üreticisinin üretim sürecindeki kayıplara ilişkin çözümlerin 
oluşturulması ve kaliteli ürün elde edilmesi açısından üreticiye fikir sağlayacaktır. Özellikle 
fiziksel olarak büyük ölçekli tarlalarda üreticinin gözlem yapması ve analizlerin kararlı olması
açısından zorlayıcı olacaktır aynı zamanda karar aşamasında gecikmeler birçok açıdan kayıpla 
sonuçlanacaktır. Bu nedenle üreticinin karar aşamasında bilgilendirilmesi büyük ölçüde makine 
öğrenim modellerinin katkısıyla olumlu faydalar sağlanabilir.  
  
  
#### 2. ÇALIŞMANIN AMAÇ ve HEDEFLERİ  
  
  Mevcut durumda proje aşamalarında kullanılacak yöntemlerin araştırılması sürdürülmektedir. 
Çalışmamızı temellendirmiş olduğumuz makine öğrenimi modeli optik görüntülerden sadece
buğday başakların tespitini sağlayacak olup ilerleyen aşamalarda elde edilen bu buğday başağı 
çerçeveleriyle çeşitli veriler elde edilebilir hale gelecektir. Bu nedenle obje tespiti için makine 
öğrenimi modelin geliştirilme aşaması tüm sonucun temellendirildiği kısım olacak olup modelin 
kararlı olması tüm sonuca etki edecektir. Hedeflediğimiz ortalama hassasiyet(mAp) değerinin 
enaz 0.6 olması hedeflenmektedir. Bu süreçte optik görüntülerin işlenmesi ve model mimarisin 
geliştirilmesiyle eğitim sonuçlarının iyileştirilmesi planlanmaktadır.2
Ayrıca obje tespiti makine öğrenimi modelimiz ile görüntülerden meta veri elde edilecek
sonrasında gerektiği durumda farklı yaklaşımlarla meta veriler hakkında temel çıkarımlar elde 
edilmesi planlanmaktadır.  

#### 3. SONUÇ ve ÖNERİLER  
  
   Mevcut durumda elde ettiğimiz makine öğrenimi modelinde 
mAP değerleri genel olarak 0.5’ten büyük olduğu dolayısıyla da başarılı bir model olduğu
düşünülebilir. Ayrıca modelin kararlılığının arttırılması için optik görüntülerin ek işlemlerden 
geçirilerek daha iyi sonuçların elde edilmesi planlanmaktadır. Oluşturmuş olduğumuz model
sonuçların geliştirilmesi çalışmanın bütününe kaynak sağladığı için kritik öneme sahiptir ve 
sonuçların iyileştirilmesi için ek çalışmalar ile model eğitimi tekrarlanabilir. Elde edilen çıktılar 
doğrultusunda analitik yaklaşımlar ile buğday bitkisinin temel sağlık bilgileri kullanıcıya fayda 
sağlayabilir.
  
---  

#### EK BİLGİLER  
##### Çalışma Adımları:  

- [x] Görüntü Çoğaltma  
--->  *Crop, Rotate, Flip, Mixup, Mosaic, Hue ve Gaussian Noise*
- [x] Makine Öğrenim Modelinin Belirlenmesi
---> *EfficientDet-D4*
- [x] Normalizasyon Teknikleri ile Model Eğitimi  
---> *Çeşitli normalizasyon teknikleri karşılaştırıldı ve nihayetinde ardışık normalizasyon ile EfficientDet-D4 eğitildi.*
- [x] Görüntü İyileştirme  
---> *Chale histogram yöntemi uygulanarak görüntü optimize edildi.*
- [x] Analitik Yaklaşım   
---> *Çeşitli yaklaşımlar önerilerek görüntülerden temel bilgi çıkarımı yapıldı.*
  
***
#### ÇALIŞMA EK BAĞLANTILARI(ADDITIONAL LINKS OF THE STUDY)  
1. [Jupyter Notebook Workspace for Train(+includes model weights)](https://www.kaggle.com/shemskurtoglu/wheat-tpu-tfkeras-00?scriptVersionId=52800232).  
2. [Jupyter Notebook Workspace for Preliminary Report](https://www.kaggle.com/shemskurtoglu/wheat-summary-report?scriptVersionId=60239079).  

