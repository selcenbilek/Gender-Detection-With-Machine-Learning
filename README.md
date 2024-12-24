

Makine Öğrenmesi ile Cinsiyet Tespiti

Projenin Amacı:

Bu proje, bir bilgisayarın, bir insanın fotoğrafına bakarak o kişinin kadın mı yoksa erkek mi olduğunu belirlemesini sağlamayı amaçlıyor. Yani, bir fotoğrafı bilgisayarımıza gösterdiğimizde, bilgisayar bize bu kişinin cinsiyetini söyleyebilecek bir sistem oluşturmak istiyoruz.
Bu proje, bilgisayarlı görme ve makine öğrenmesi tekniklerini kullanarak, yüz görüntülerinden cinsiyet tahmini yapmayı amaçlamaktadır. Sistem, verilen bir yüz görüntüsünü analiz ederek kişinin cinsiyetini (kadın veya erkek) yüksek doğrulukla sınıflandırmayı hedeflemektedir.

Kullanılan Teknolojiler:

**Python: Projenin ana programlama dili. Veri işleme, modelleme ve görselleştirme için kullanılmıştır.
**OpenCV: Bilgisayarlı görme uygulamaları için endüstri standardı bir kütüphane. Görüntü işleme, yüz algılama ve özellik çıkarma işlemlerinde kullanılmıştır.
**NumPy: Nümerik hesaplamalar için optimize edilmiş bir kütüphane. Özellikle büyük boyutlu diziler üzerinde işlemler yaparken kullanılır.
**Scikit-learn: Makine öğrenimi algoritmalarının uygulanması için kapsamlı bir kütüphane. Sınıflandırma, regresyon gibi birçok algoritma içerir. Bu projede, destek vektör makineleri (SVM) veya rastgele ormanlar gibi sınıflandırma algoritmaları kullanılabilir.
**TensorFlow/Keras: Derin öğrenme modelleri geliştirmek için popüler bir kütüphane. Özellikle büyük ve karmaşık veri setlerinde yüksek doğruluk elde etmek için kullanılabilir.

Projenin Adımları:

**Fotoğrafları Hazırlama:

Farklı insanların fotoğraflarını toplayıp, bunları bilgisayara tanıtacağız.
Fotoğrafları bilgisayanın anlayabileceği bir hale getireceğiz (örneğin, boyutlarını ayarlayacağız).
Fotoğraftaki yüzleri bulacağız.

**Bilgisayara Öğretme:

Topladığımız fotoğraflardan bilgisayara, hangi fotoğrafın bir kadına, hangisinin bir erkeğe ait olduğunu göstereceğiz.
Bilgisayar, bu bilgileri kullanarak, yeni bir fotoğraf gördüğünde bunun bir kadına mı yoksa erkeğe mi ait olduğunu tahmin etmeye çalışacak.

**Tahmin Yapma:

Bilgisayara daha önce görmediği bir fotoğraf göstereceğiz.
Bilgisayar, öğrendiklerini kullanarak bu fotoğraftaki kişinin cinsiyetini tahmin edecek.

**Sonuçları Değerlendirme:

Bilgisayarın tahminlerinin ne kadar doğru olduğunu kontrol edeceğiz.

**Özetle:

Bu proje, bilgisayarların görme yeteneğini kullanarak insanların cinsiyetini belirlemelerini sağlamayı amaçlıyor. Bu sayede, birçok farklı alanda kullanılabilecek yeni teknolojiler geliştirmek mümkün olabilir.

Ek Bilgiler:

Bu uygulamayı kullanmak isteyenler aşağıdaki linkten erişim sağlayabilir.

https://gendercls.streamlit.app/

Veri linki: https://www.kaggle.com/datasets/cashutosh/gender-classification-dataset

