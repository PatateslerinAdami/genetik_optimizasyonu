# genetik_optimizasyonu
Bir lojistik firması, yeni akıllı deposunda raf yerleşim sistemini optimize etmek istiyor. Amaç, maliyeti düşürmek.

Seçilim - Turnuva Yöntemi: Minimizasyon problemi olduğu için, rastgele seçilen bireyler arasından maliyeti en düşük olanı seçmek adına Turnuva yöntemi (k=3) kullanılmıştır. Bu yöntem seçilim baskısını dengeler.


Çaprazlama - Aritmetik: Sayısal değerlerle çalışıldığı için ebeveynlerin genlerinin ağırlıklı ortalamasını alan aritmetik çaprazlama uygulanmıştır.


Mutasyon - Gaussian: Yerel minimumlara takılmayı önlemek ve çözüm uzayını taramak için genlere küçük rastgele değerler (Gaussian noise) eklenmiştir.


Elitizm: Her jenerasyondaki en iyi birey, bozulmadan bir sonraki jenerasyona aktarılır.
