# Diabetes-Feature-Engineering
![alt text](https://cic.co.ke/wp-content/uploads/2020/11/Better-Technology-Means-Better-Care-for-Diabetes-Management.jpg)
# Özet
Belirli parametrelere bağlı olarak, özellikleri verilen kişilerin diyabet hastası olup olmadığını tahmin edebilecek bir makine öğrenmesi modelinin eğitilmesi için veri seti hazır hale getirilmiştir.

Hazırlanan bu proje, makine öğrenmesi modelinin geliştirilmesi aşamasından önceki gerekli olan Keşifçi Veri Analizi (EDA) ve Özellik Mühendisliği (Feature Engineering) adımlarını içerir. Bu sayede, veri seti üzerinde yapılacak gerekli işlemler ile modelinin eğitilmesi için uygun hale getirilmiş oldu.
Projenin sonunda, detayına girilmeden Makine Öğrenmesi algoritması olan Random Forest Classifier ile hazırlanan veri seti test edilmiştir. Test sonucunda %80 oranında accuracy oranı elde edilmiştir. Accuracy oranı dikkate alınarak, Özellik Mühendisliği adımlarında iyleştirmeler yapılacaktır.

# Veri Seti
https://www.kaggle.com/uciml/pima-indians-diabetes-database/code

Veri seti ABD'deki Ulusal Diyabet-Sindirim-Böbrek Hastalıkları Enstitüleri'nde tutulan büyük veri setinin parçası olarak Kaggle'da paylaşılmaktadır. Bu veri seti ABD'deki Phoenix şehrinde yaşayan 21 yaş ve üzerinde olan kadınlar üzerinde yapılmıştır. Veri seti incelendiğinde "outcome" değişkenin(hedef değişken) 1 olması durumu diyabet test sonucunun pozitif oluşunu, 0 olması durumu da negatif oluşunu belirtmektedir. 

Veri seti üzerindeki değişkenler sırasıyla şöyledir;

**Pregnancies:** Hamilelik sayısı

**Glucose:** Oral glikoz tolerans testinde 2 saatlik plazma glikoz konsantrasyonu

**Blood Pressure:** Kan Basıncı (Küçük tansiyon) (mm Hg)

**SkinThickness:** Cilt Kalınlığı

**Insulin:** 2 saatlik serum insülini (mu U/ml)

**DiabetesPedigreeFunction:** Fonksiyon (Oral glikoz tolerans testinde 2 saatlik plazma glikoz konsantrasyonu)

**BMI:** Vücut kitle endeksi

**Age:** Yaş (yıl)

**Outcome:** Hastalığa sahip (1) ya da değil (0)


