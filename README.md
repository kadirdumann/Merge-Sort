# Merge-Sort
Kodluyoruz Eğitimi kapsamında merge sort porjesi

## Proje 2

* [16,21,11,8,12,22] dizinin Merge Sort türüne göre aşamalarını yazınız.

  1. [16,21,11] ve [8,12,22]                  ===> Dizi ikiye bölünür.
  2. [16,21] [11] [8,12] [22]                 ===> Diziler 2 element ve 1 element olmak üzere yine bölünür.
  3. [16] [21] [11] [8] [12] [22]             ===> Diziler 1 elementli olucak şekilde yine bölünür.
  4. [16,21] [11] [8,12] [22]                 ===> Olarak aynı kalırlar.
  5. [11,16,21] ve [8,12,22]                  ===> Diziler karşılaştırılarak 3 elementli diziler oluşturulur.
  6. [8,11,12,16,21,22]                       ===> Son olarak bu iki dizilerin öğeleri karşılaştırılır.
 
* Big-O gösterimini yazınız.

  O(nlogn)
