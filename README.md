### Google Play Store Uygulamaları Veri Analizi

Bu proje, Kaggle'dan elde edilen Google Play Store uygulama verileri üzerinde yapılan veri temizleme ve keşifçi veri analizi (EDA) çalışmasını içerir. Amacı, uygulama pazarındaki eğilimleri ve kullanıcı davranışlarını anlamaktır.

### Kullanılan Araçlar ve Kütüphaneler

Projede aşağıdaki Python kütüphaneleri kullanılmıştır:

* **pandas**: Veri işleme ve manipülasyonu için.
* **numpy**: Sayısal işlemler için.
* **matplotlib.pyplot**: Veri görselleştirmesi için.
* **seaborn**: İstatistiksel veri görselleştirmesi için..

### Veri Seti

Bu çalışma için kullanılan veri seti Kaggle üzerinden sağlanmıştır ve aşağıdaki dosyaları içerir:

* `googleplaystore.csv`
* `googleplaystore_user_reviews.csv`

### Analiz Adımları

Projede izlenen temel analiz adımları şunlardır:

1.  **Veri Yükleme ve Genel Bakış**: `googleplaystore.csv` dosyası Pandas DataFrame'ine yüklenmiş ve kolon adları, veri tipleri ve boş değerleri incelenmiştir.
2.  **Veri Temizleme**:
    * `Reviews` kolonunda yer alan sayısal olmayan değerler tespit edilip temizlenmiştir.
    * Veri Setinde analiz yapılabilmesi için veri tiplerinde gerekli tür dönüşümleri yapılmıştır.
3.  **Keşifçi Veri Analizi**:
    * Kategorilere ve türlere göre uygulama dağılımı incelenmiştir.
    * Farklı türlerdeki uygulamaların ortalama kurulum sayıları görselleştirilmiştir.

### Nasıl Çalıştırılır?

Bu projeyi yerel bilgisayarınızda çalıştırmak için aşağıdaki adımları izleyebilirsiniz:

1.  Gerekli kütüphaneleri yükle:
    `pip install pandas numpy matplotlib seaborn plotly`
2.  Proje klasörüne git ve Jupyter Notebook'u başlat:
    `jupyter notebook`
3.  Tarayıcında açılan ekrandan `google-play-store-apps-analysis.ipynb` dosyasını açıp çalıştırabilirsiniz.

### Kaggle Proje Linki: https://www.kaggle.com/code/mehmetren/google-play-store-apps-1


