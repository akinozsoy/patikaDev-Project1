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


````
````

[16,21,11,8,12,22] --> Merge Sort

1- [16,21,11]    [8,12,22]
2- [16,21] [11]  [8,12] [22]
3- [16] [21] [11] [8] [12] [22]
4- [16,21] [11,8] [12,22]
5- [8,11,16,21] [12,22]
6- [8,11,12,16,21,22]

Big-O notation --> O(n*logn)
````
```
Answer: 
Root x = 6
                             6
                           /   \ 
                          5     7
                        /         \
                       1           8
                     /   \           \
                    0     3           9
                        /   \      
                       2     4    
                                
Step 1:     7 > 6 için root'un sağında 7 bulunur.
Step 2:     5 < 6 için root'un solunda 5 bulunur.
Step 3:     1 < 6 için 1 root'un soluna eklenir.
Step 4:     8 > 6 için 8 root'un sağına eklenir.
Step 5:     3 < 6 için 3 root'un soluna eklenir.
Step 6:     0 < 6 için 0 root'un soluna eklenir.
Step 7:     9 > 6 için 9 root'un sağına eklenir.
Step 8:     4 < 6 için 4 root'un soluna eklenir.                        
Step 9:     2 < 6 için 2 root'un soluna eklenir.                         
```
