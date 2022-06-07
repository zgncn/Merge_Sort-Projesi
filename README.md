# Merge_Sort-Projesi
Veri Yapıları ve Algoritmalar > Merge Sort Projesi
patika.dev profilim -> https://app.patika.dev/zgncn

Soru 1 Cevabı ([16,21,11,8,12,22] -> Merge Sort)

1.Aşama
-ikiye bölüyoruz.
 16,21,11-----8,12,22

2.Aşama 
-tekrar ikiye bölüyoruz
16,21----11----------8,12-------22

3.Aşama 
-tek parça haline getiriyoruz
16---21---11--------8---12---22

4.Aşama 
-Yanyana olan parçaları kıyaslıyoruz
-16,21 den küçük, 11 ,16 dan küçük swap ediyoruz, 8,12den 12 ,  22 den küçük
11,16,21---8,12,22

5.Aşama
-Son 2 parçadaki elemanları da kıyaslıyoruz
8,11,12,16,21,22

Soru 2 Cevabı
n/2 n/2 olarak ayrıldığı için 

2^x = n den -> Big o gösterimi O(nlogn) dir

