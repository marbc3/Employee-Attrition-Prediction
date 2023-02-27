# Employee-Attrition-Prediction

# İş Problemi
* Çalışan hakkında elimizde yeterli veri bulunduğunda bu çalışanın işten ayrılıp ayrılmayacağını tahmin eden ve ayrılma olasılığı en yüksek olan çalışanları belirleyebileceğimiz bir makine öğrenmesi modeli geliştirebilir miyiz?
* Çalışanların ayrılmasında hangi faktörler etkilidir?
* Şirketin, işten ayrılan kişilerin şirkete uzaklığı ayrılmayan kişilere göre daha fazla olduğuna dair bir hipotezi var. Bu hipotezi test edebilir miyiz?
* Şirketin, çalışanların mesai durumu ve işten ayrılmaları arasında bir ilişki olduğuna dair hipotezi var.  Bu hipotezi test edebilir miyiz?
* Şirketin, ayrılmayan çalışanların aldığı ortalama zam oranının ayrılan çalışanların aldığı ortalama zam oranından daha fazla olduğuna dair bir hipotezi var, bu durumda çalışanların aldığı mevcut zam oranının üzerine %5 oranında bir zam yapmayı daha düşünüyorlar. Bu hipotezi test edebilir miyiz ve yapılması düşünülen zammın doğru bir hamle olup olmayacağına dair neler söyleyebiliriz?
# Veri Seti
Veri setimiz toplamda 1470 satırdan ve 35 değişkenden oluşmaktadır.

Kaynak: https://www.kaggle.com/datasets/patelprashant/employee-attrition
## Değişkenler
* **AGE**: Çalışanın yaşı
* **ATTRITION**: Çalışanın işten ayrılıp ayrılmadığı bilgisi
* **BUSINESS TRAVEL**: Çalışanın ne sıklıkla seyahat ettiği bilgisi
* **DAILY RATE**: Çalışanın günlük maaş seviyesi
* **DEPARTMENT**: Çalışanın departman bilgisi
* **DISTANCE FROM HOME**: Çalışanın işi ile evi arasındaki mesafe
* **EDUCATION**: (1, 2, 3, 4, 5 ,6)
* **EDUCATION FIELD**: (1=HR, 2=LIFE SCIENCES, 3=MARKETING, 4=MEDICAL SCIENCES, 5=OTHERS, 6= TEHCNICAL)
* **EMPLOYEE COUNT**: Çalışan sayısı
* **EMPLOYEE NUMBER**: Çalışan numarası
* **ENVIROMENT SATISFACTION**: Çalışanın memnuniyet seviyesi
* **GENDER**: Cinsiyet
* **HOURLY RATE**: Çalışanın saatlik maaş seviyesi
* **JOB INVOLVEMENT**: Çalışanın işe bağlılık seviyesi
* **JOB LEVEL**: (1, 2, ..., 9)
* **JOB ROLE**: (1=HC REP, 2=HR, 3=LAB TECHNICIAN, 4=MANAGER, 5= MANAGING DIRECTOR, 6= REASEARCH DIRECTOR, 7= RESEARCH SCIENTIST, 8=SALES EXECUTIEVE, 9= SALES REPRESENTATIVE)
* **JOB SATISFACTION**: Çalışanın işine memnuniyet seviyesi
* **MARITAL STATUS**: Çalışanın evlilik durumu
* **MONTHLY INCOME**: Çalışanın aylık maaşı
* **MONTLHY RATE**: Çalışanın aylık maaş seviyesi
* **NUMCOMPANIES WORKED**: Çalışanın çalıştığı şirket sayısı
* **OVER 18**: Çalışan 18 yaşından büyük mü?
* **OVERTIME**: Mesai bilgisi
* **PERCENT SALARY HIKE**: Maaştaki yüzdelik artış
* **PERFORMANCE RATING**: Performans seviyesi
* **RELATIONS SATISFACTION**: Çalışanın ilişkiler memnuniyeti
* **STANDARD HOURS**: Standart saatler
* **STOCK OPTIONS LEVEL**:Stock option seviyesi
* **TOTAL WORKING YEARS**: Toplam çalışılan yıl
* **TRAINING TIMES LAST YEAR**: Geçen yıl eğitime harcanan saat
* **WORK LIFE BALANCE**: İş ile iş dışı arasındaki geçirilen vakit oranı
* **YEARS AT COMPANY**: Çalışanın kaç yıldır şirkette olduğu bilgisi
* **YEARS IN CURRENT ROLE**: Çalışanın kaç yıldır mevcut rolde olduğu bilgisi
* **YEARS SINCE LAST PROMOTION**: Alınan son promosyondan mevcut zamana kadar geçen yıl sayısı
* **YEARS WITH CURRENT MANAGER**: Mevcut yöneticiyle geçirilen yıl sayısı
