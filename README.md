# Kütüphaneler
Matplotlib: Python'da 2D grafikler ve görselleştirmeler oluşturmak için kullanılan temel kütüphanedir.Genellikle çizgi grafik, çubuk grafik, histogram gibi temel grafikler için tercih edilir.

Seaborn: İstatistiksel verilerin görselleştirilmesi için Matplotlib üzerine inşa edilmiş, daha estetik ve kolay kullanımlı bir kütüphanedir.Isı haritaları, dağılım grafikleri ve kategorik grafikler gibi gelişmiş görselleştirmeler sağlar.

Pandas: Veri analizi ve veri işleme için kullanılan güçlü bir kütüphanedir, veri çerçevesi (DataFrame) yapısıyla çalışır.Veriyi okuma, düzenleme, filtreleme ve analiz etme işlemlerini kolaylaştırır.

Scikit-learn (sklearn): Makine öğrenmesi algoritmalarını kolayca uygulamak için kullanılan popüler bir Python kütüphanesidir.Sınıflandırma, regresyon, kümeleme ve model değerlendirme gibi temel makine öğrenmesi işlemlerini sağlar.

Scipy: Bilimsel ve teknik hesaplamalar için kullanılan bir Python kütüphanesidir.İstatistiksel analizler, optimizasyon, integral hesaplama ve lineer cebir işlemleri için kullanılır.

#  ilk 5 veriyi aşağıdaki gibi inceleyebilirsiniz
print(df.head()) 

              Invoice ID Branch       City Customer type  Gender  \
              0  750-67-8428   Alex     Yangon        Member  Female   
              1  226-31-3081   Giza  Naypyitaw        Normal  Female   
              2  631-41-3108   Alex     Yangon        Normal  Female   
              3  123-19-1176   Alex     Yangon        Member  Female   
              4  373-73-7910   Alex     Yangon        Member  Female   
              
                           Product line  Unit price  Quantity   Tax 5%     Sales       Date  \
              0       Health and beauty       74.69         7  26.1415  548.9715   1/5/2019   
              1  Electronic accessories       15.28         5   3.8200   80.2200   3/8/2019   
              2      Home and lifestyle       46.33         7  16.2155  340.5255   3/3/2019   
              3       Health and beauty       58.22         8  23.2880  489.0480  1/27/2019   
              4       Sports and travel       86.31         7  30.2085  634.3785   2/8/2019   
              
                        Time      Payment    cogs  gross margin percentage  gross income  \
              0   1:08:00 PM      Ewallet  522.83                 4.761905       26.1415   
              1  10:29:00 AM         Cash   76.40                 4.761905        3.8200   
              2   1:23:00 PM  Credit card  324.31                 4.761905       16.2155   
              3   8:33:00 PM      Ewallet  465.76                 4.761905       23.2880   
              4  10:37:00 AM      Ewallet  604.17                 4.761905       30.2085   
              
                 Rating  
              0     9.1  
              1     9.6  
              2     7.4  
              3     8.4  
              4     5.3  
