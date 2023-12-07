# Insertion Sort Projesi

[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

1-  Average case: Aradığımız sayının ortada olması
2- Worst case: Aradığımız sayının sonda olması
3- Best case: Aradığımız sayının dizinin en başında olması.

## Çözüm

1. [22, 27, 16, 2, 18, 6]
2. [22, 27, 16, 2, 18, 6]
3. [16, 22, 27, 2, 18, 6]
4. [2, 16, 22, 27, 18, 6]
5. [2, 16, 18, 22, 27, 6]
6. [2, 6, 16, 18, 22, 27]


Big-O -> O(n^2)

Time Complexity: O(n^2)

18 sayısı, dizinin ortasında. Bu nedenle arama işlemi için Average Case senaryosuna olur.

### [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımı


1. [2, 3, 5, 8, 7, 9, 4, 15, 6]
2. [2, 3, 5, 8, 7, 9, 4, 15, 6]
3. [2, 3, 4, 8, 7, 9, 5, 15, 6]
4. [2, 3, 4, 5, 7, 9, 8, 15, 6]

