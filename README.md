# Akbank_ml

Bu proje, meme kanseri teşhisi yapmak için geliştirilmiş bir karar ağacı tabanlı bir makine öğrenimi modelidir. Model, meme kanseri veri seti üzerinde eğitilmiş ve sağlanan özelliklere dayanarak bir hastanın kanser olup olmadığını tahmin edebilir.

**1.Veri Seti Hazırlığı:**
    İlk adım, modelin eğitim için kullanacağı veri setini hazırlamaktır. Bu veri seti, meme kanseri teşhisi konulan ve konulmayan hastaların klinik özelliklerini içerir. Her hastaya ilişkin özellikler ve kanser teşhisi bulunur.
**2.Model Eğitimi:**
    Temizlenmiş veri seti, karar ağacı modeli için eğitim amacıyla kullanılır. Karar ağacı, veri setindeki özelliklerin değerlerine göre bir dizi karar düğümü oluşturur. Her düğüm, bir özelliğin belirli bir değerine göre veriyi bölerek sınıflandırır.
**3.Model Değerlendirmesi:**
    Eğitimden sonra, modelin performansını değerlendirmek için ayrılmış bir test veri seti kullanılır. Bu adım, modelin doğruluğunu, hassasiyetini, özgüllüğünü ve diğer performans metriklerini değerlendirir. 
