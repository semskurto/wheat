#  Wheat Detection and Other Extraction of Qualified Data 🌾  Buğday Başaklarının Tespit Edilmesi ve Diğer Nitelikli Verilerin Çıkarımı 
*** 
  
![Workflow](https://user-images.githubusercontent.com/31928447/117530943-9c085f80-afe8-11eb-846c-af664f6b72ec.png)
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

  
#### 1. INTRODUCTION:

Wheat is the most widely cultivated and commercially significant crop in many countries worldwide. It serves as a crucial staple in human nutrition. The cultivation areas and production of wheat have been increasing in parallel with population growth. The global population, which surpassed 1 billion in 1802, reached approximately 2 billion in 1927, and is projected to exceed 7 billion in 2011, 8.5 billion in 2020, 9.6 billion in 2030, and 12 billion in 2050.

In line with population growth, global wheat production has also increased. While the world wheat production, which has been on the rise alongside population increase, was around 222 million tons in the 1960s, it reached 586 million tons in the 2000s and 650 million tons in 2010. It is estimated that per capita wheat consumption worldwide was approximately 70 kg in the 1960s and has now reached around 100 kg per person. Although the world average wheat yield has increased to 300 kg/ha in recent years, considering that the world record for wheat yield was 1,564 kg/ha in 2010, it implies that we are currently able to produce only around 1/5 of the potential achievable on existing cultivation areas. Therefore, increasing wheat production by enhancing yield per unit area without expanding the existing planting areas is of critical importance.

Against this backdrop, monitoring wheat spikes in the wheat production process becomes crucial for ensuring healthy development. This study aims to obtain health data from wheat photographs by utilizing image processing and machine learning methods. These data will provide the wheat producer with insights to generate solutions for production losses and achieve high-quality products. Particularly in large-scale fields, it becomes physically challenging for producers to observe and analyze the crop, and delays in the decision-making stage can result in various losses. Hence, informing the producers during the decision stage can yield substantial benefits, largely facilitated by the contribution of machine learning models.
  
  
#### 2. PURPOSE and OBJECTIVES of the STUDY 
  
  Currently, the research on the methods to be used in the project stages is ongoing. Our study is based on a machine learning model that aims to detect only wheat spikes from optical images. In the subsequent stages, various data can be obtained using the frames of these wheat spikes. Therefore, the development phase of the machine learning model for object detection will be the fundamental part on which the entire result is based, and the stability of the model will have an impact on the overall outcome. Furthermore, it is planned to obtain useful fundamental insights through analytical approaches by extracting meta-data from images using our object detection machine learning model.

#### 3. CONCLUSION and RECOMMENDATIONS

In the current state, the machine learning model we have obtained exhibits mean Average Precision (mAP) values generally greater than 0.5, indicating a successful model. Furthermore, to enhance the stability of the model, it is planned to apply additional image processing techniques to achieve better results from the optical images. The model we have created holds critical importance as it contributes to the overall improvement of the study's results, and further training iterations can be conducted to enhance the outcomes. Based on the obtained outputs, utilizing analytical approaches, the essential health information of wheat plants can provide benefits to users.
  
---  

### Additional Informations:  
##### Basic Working Steps:  

- [x] Image Augmentation --->  *Crop, Rotate, Flip, Mixup, Mosaic, Hue ve Gaussian Noise*
- [x] Selection Machine Learning Model Algoritm ---> *EfficientDet-D4* Next time add new ML algoritm
- [x] Model Training Methodolgy ---> *Various normalization techniques were compared and finally EfficientDet-D4 was trained with sequential normalization.*
- [x] Image Processing ---> *The image was optimized by applying the Chale histogram method.*
- [x] Analytical Approach ---> *Basic information was extracted from images by suggesting various approaches.*
  
***
#### ADDITIONAL LINKS OF THE STUDY
1. [Jupyter Notebook Workspace for Train(+includes model weights)](https://www.kaggle.com/shemskurtoglu/wheat-tpu-tfkeras-00?scriptVersionId=52800232).  
2. [Jupyter Notebook Workspace for Final Report](https://www.kaggle.com/shemskurtoglu/wheat-summary-report).  

