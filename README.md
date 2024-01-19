# patikaDev-Project1
PatikaAcademy- Data Structures and Algorithms
---------------------------------------------
  ````
Q1:
   Adım 1: [22,27,16,2,18,6]   // 22 zaten 27'den küçük olduğu için hiç bir sıralama yapılmadı
   Adım 2: [22,16,27,2,18,6]   // 27 ile 16 yer değişti
   Adım 3: [16,22,27,2,18,6]   // 22 ile 16 yer değişti
   Adım 4: [16,22,2,27,18,6]   // 27 ile 2 yer değişti
   Adım 5: [16,2,22,27,18,6]   // 22 ile 2 yer değişti
   Adım 6: [2,16,22,27,18,6]   // 16 ile 2 yer değişti
   Adım 7: [2,16,22,18,27,6]   // 27 ile 18 yer değişti
   Adım 8: [2,16,18,22,27,6]   // 22 ile 18 yer değişti
   Adım 9: [2,16,18,22,6,27]   // 27 ile 6 yer değişti
   Adım 10: [2,16,18,6,22,27]  // 22 ile 6 yer değişti
   Adım 11: [2,16,6,18,22,27]  // 18 ile 6 yer değişti
   Adım 12: [2,6,16,18,22,27]  // 16 ile 6 yer değişti
````


````
Q2:
 O(n^2)

````
````
Q3:
Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.
A:
Average Case
````

```
Q4: 
Adım 1:               [22,17,16]                             [2,18,6]
                    /           \                         /           \
Adım 2:          [22,17]    -    [16]                  [2,18]    -    [6]
                /        \             \               /      \            \
Adım 3:      [22]    -    [17]    -    [16]        [2]     -    [18]    -    [6]   
                \       /              /             \         /            /
Adım 4:          [22,17]    -    [16]                  [2,18]    -    [6]
                     \            /                        \           /
Adım 5:                [22,17,16]                            [2,18,6]
                                  
Adım 6:     
