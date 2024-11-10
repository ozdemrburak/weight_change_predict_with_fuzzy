# weight_change_predict_with_fuzzy
## Sonuçlar
1. Kurduğum sistem, bazı değerler için iyi tahminler yürütemiyor. Bunun sebepleri kullandığım inputların(yaş, fiziksel aktivite, alınan kalori farkı ve süre) kişinin kilo değişimini tahmin etmek için yeterli olmaması. Veri setinde verilen stres ve uyku kalitesi değerleri araştırılarak kişilerde nasıl sonuçlara sebep olduğu öğrenilip ona göre kurallar yazılabilinirse sistem tahmin edemediği uç değerleri tahmin edebilir.
2. Yazdığım kurallarda eksiklik var. Fiziksel aktivitede ligthly active ve moderatly active değerleri orta yaşlı insanlarda tahmini değiştirmiyor. İyileştirme yapmalı!
3. Veri seti küçük olduğundan herhangi bir makine öğrenmesi algoritmasıyla karşılaşılabilecek overfitting, bias gibi durumlardan kaçınmak için bir fuzzy sistemi kurmak mantıklı olmakla birlikte, elde edilen sonucun bir modele girdi olarak verilerek modelin başarısını artırmak da mümkün olabilir. Yani burada elde edilen sonucu bir ML algoritmasına vererek sonuçları tekrar gözlemleyeceğim.
