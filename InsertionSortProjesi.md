### Insertion Sort 

[22,27,16,2,18,6]

**Yukarı verilen dizinin ınsertion sort türüne göre aşamalarını yazınız.**
  Insertion sort için patika.dev adresindeki videodaki kaynağı inceledim: http://cagataykiziltan.net/algoritmalar/1-siralama-algoritmalari/1-araya-sokma-siralamasi/
  Diziyi kaynağa göre hazırladım.

[22,27,16,2,18,6]

[16,22,27,2,18,6]

[2,16,22,27,18,6]

[2,16,18,22,27,6]

[2,6,16,18,22,27]

**Big-O gösterimini yazınız.**
Big-O Notation için lineer bir değer arayışımız olacak, çünkü tüm verilerden tek tek arayarak sıralamayı oluşturuyor. 
n(n+1) / 2'den dizideki tüm elemanları tek tek deneyerek bulacak ve O(n^2) olacaktır. Eldeki dizide n=6 olduğu için O(36)

**Time Complexity: Average case: Aradığımız sayının ortada olması, Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.**
Best case, düzenli bir liste geldiğinde O(n) = O(6) 
Avarage case, düzensiz bir liste geldiğinde yine O(n^2) tane işlem yapılacaktır. O(36)
Worst case, tam ters dizilime sahip dizinin gelmesidir, tüm elemanlar tek tek düzenlenecektir O(n^2) defa işlem yapılır. O(36)

**Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.**
Dizinin sıralanmış hali:
[2,6,16,18,22,27]
olduğu için 18 sayısının yerleşimi tam sıralı liste dışında kalır ve avarage case ve worst case kapsamına girer.  


### Insertion Sort'a Göre İlk 4 Adım

**[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.**

[7,3,5,8,2,9,4,15,6] mevcut durumu

[3,7,5,8,2,9,4,15,6] 1. adım

[3,5,7,8,2,9,4,15,6] 2. adım

[2,3,5,7,8,9,4,15,6] 3. adım

[2,3,4,5,7,8,9,15,6] 4. adım
