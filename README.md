# Patika-Insertion-Sort-Projesi
## Proje 1

## [22,27,16,2,18,6] -> Insertion Sort

### Sorular
1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
2. Big-O gösterimini yazınız.
3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
5. [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

### Cevaplar
1. [2,27,16,22,18,6] => [2,6,16,22,18,27] => [2,6,16,18,22,27]
2. O(n^2)
3. Avarage Case: 16,18 Worst Case: 27 Best Case: 2
4. Avarage Case
5. [7,3,5,8,2,9,4,15,6] => [2,3,5,8,7,9,4,15,6] => [2,3,4,8,7,9,5,15,6] => [2,3,4,5,7,9,8,15,6] => [2,3,4,5,6,9,8,15,7] 

## Proje 2
### Sorular
[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

### Cevaplar
1. [16,21,11,8,12,22] => [16,21,11] , [8,12,22] => [16,21] , [11] , [8,12] , [22] => [16] , [21] , [11] , [8] , [12] , [22] => [16,21] , [11] , [8,12] , [22] => [11, 16,21] , [8,12,22] => [8,11,12,16,21,22] 
2. O(logn)
