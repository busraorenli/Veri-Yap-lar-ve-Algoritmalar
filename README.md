# Veri-Yap-lar-ve-Algoritmalar
3 ödev

## Ödev1
[22,27,16,2,18,6] -> Insertion Sort
1.	Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
2.	Big-O gösterimini yazınız.
3.	Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
4.	Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

1.	[2,27,16,22,18,6]
[2,6,16,22,18,27]
[2,6,16,18,22,27]
2.	O(n2) = (62) = 36
3.	 
4.	18 sayısı ortada olduğu için average case kapsamına girer.

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
[2,3,5,8,7,9,4,15,6]
[2,3,4,8,7,9,5,15,6]
[2,3,4,5,7,9,8,15,6]
[2,3,4,5,6,9,8,15,7]

## Ödev2
[16,21,11,8,12,22] -> Merge Sort
1.	Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
2.	Big-O gösterimini yazınız.
1.	[16,21,11]                                  [8,12,22]
[16,21]    [11]                       [8,12]        [22]
[16]   [21]   [11]                [8]     [12]       [22]
[16,21]    [11]                       [8,12]         [22]
[11,16,21]                               [8,12,22]
[8,11,12,16,21,22]

2.	O(log(n)) = log(6) = 0.778

## Ödev3
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.
Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.
Çözüm: Binary search için sıralı bir dizi olduğu varsayılır. Bu yüzden önce sıralamamız gerekir.
[0,1,2,3,4,5,6,7,8,9]
İkinci aşamada bu dizide aradığımız sayının var olup olmadığını bulabilmek için diziyi tam ortadan ikiye ayırmamız gerekir. Örneğin 1 varlığını sorguladığımızda; orta değeri 5 olarak belirlesek, 5ten küçük kısımda aramamız gerekir. İkinci aşamada belirlediğimiz 2 orta değerinden de küçük olduğu için 2den küçük kısımda aradığımızda 1in var olduğunu görüyoruz.
[0,1,2,3,4,5,6,7,8,9]
[0,1,2,3,4,5,6,7,8,9]
