# STAJ--2022

STAJ-2022 PROJEMİN KONUSU NEDİR?

Bu projede kedi ve köpek resimlerinin birbirinden ayırt edilmesi üzerinde çalıştım. Görsel veriler sağlandıktan sonra, kodlamış olduğum yazılımımda farklı farklı verilerin içerisinden hem kedi hem de köpek resimlerinin ayırt edilmesini görebilirsiniz.

PROJEDE KULLANILAN PROGRAMLAMA DİLLERİ VE MODELLER

Projemde kullanmış olduğum programlama dili olarak Python’u seçtim, çünkü yapay zeka alanında bir proje üzerinde çalışırken diğer programlama dillerine oranla daha fazla yardım sağlayabileceği metodlar ve kütüphaneler var. Ek olarak, convolutional neural network, sequential mode, max pooling, relu gibi daha birçok özelliklere de projemde yer verdim. 

PROJE HAKKINDA

Projemi özetlemem gerekirse, öncelikle buraya yüklemiş olduğum yazılım birçok kaynaktan araştırılarak hem de kendi bilgilerimle sentezlenerek yapılmış farklı yolları içeren bir yazılım. Bunun yanı sıra temel amacı tüm kodlama çeşitlerinde hep aynı olduğu için – kedi ve köpek resimlerinin sınıflandırılması- projemdeki hangi yazılımı seçerseniz seçin doğru sonuca sizin de birkaç ekleyeceğiniz kodlama ile birlikte rahatlıkla ulaşabileceğinizi gözlemleyebilirsiniz.

NOT: Yorum satırlarına almış olduğum farklı yolları oluşturmaktadır. Benim burada asıl net bir şekilde doğru sonucu sağlayan kodum ise yorum satırsız olan kodlama bölümleridir. 

Projede ilk olarak bahsetmem gereken en önemli şeylerden biri Kaggle ile Google Collabı bağlamış olmam zaten bu kodlamaları direkt projemi açtığınızda görebilirsiniz. Ardından, Burada 3x3 cnn ve ardından 2x2 relu yaparak max pooling ile sıralamayı bu şekilde ilerletmeye çalıştım. Daha sonra, datayı kaggledan aldığım için train ve test verilerim oldu. Bu yüzden ilk olarak bu verilerden train ile kodlamamda kedi ve köpek resimlerinin ayırt edilmesini öğretmeyi amaçlarken, test ile yine traine yaptığım benzer işlemleri yaparak kedi ve köpek resimlerinin sınıflandırılmasını test etmiş oldum. Ek olarak kodlama içerisinde belli bölümlerde rastgele kedi ve köpek resimlerini de bastırdım. 
Projemde en sonda her bir epoch u (totalde 20 epoch var) 256 ya kadar çalıştırdım ve ardından bu verilerin öğrenilmiş sonuçları ile plot özelliğini kullanarak train test grafiğini bastırdım. Burada test ve trainim birbirine yakın çıktı bu grafik sonucu da yazmış olduğum yazılımın doğruya çok yakın çalıştığını gösteriyor. Ek olarak, incelemek isterseniz tüm epochların accurancy ve loss değerlerini de bastırdım.
Yani bu projeyle amaçlamış olduğum kedi ve köpek sınıflandırılmasının yapılmasına doğruya çok yakın bir şekilde ulaştım. Böylece yazmış olduğum yazılım kedi ve köpek resimlerini birbirinden ayırt edebiliyor.

İyi çalışmalar…
