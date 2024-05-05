# siralamaAlgoritmalari

Selection-Insertion-Sort

[22,27,16,2,18,6] -> Insertion Sort

-------Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

[2,27,16,22,18,6]
[2,6,16,22,18,27]
[2,6,16,22,18,27]
[2,6,16,18,22,27]

-------Big-O gösterimini yazınız.

ilk aşamada: n kez işlem
ikinci aşamada: n-1 kez işlem
üçüncü aşamada: n-2 kez işlem
.
.
.
n-1'inci aşamada: 1 kez işlem

tüm işlemler: [n*(n+1)]/2  --> O(n^2)

-------Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer?
Average case: Aradığımız sayının ortada olması   ---> Aranan sayı (18), ortada olduğu için Average Case.
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.
