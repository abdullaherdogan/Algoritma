# Algoritma
Veri Yapıları ve Algoritma Ödevleri

## Insertion Sort Homework

[22,27,16,2,18,6] -> dizisinin Insertion Sort'a göre aşamaları
1- 22 ve 27 karşılaştırılır 27 büyük olduğundan yer değişimi yapılmaz
2- 22, 27 ve 16 ya bakılır 16 en küçük olduğundan en başa alınır.
3- 22, 27, 16'ya 2 de eklenir ve aralarında en küçük 2 olduğu için başa alınır.
4- 22, 27, 16, 2 dizisine 18 eklenir. 22 ve 27'den küçük olduğu için onların önüne alınır.
5- Son olarak 6 tüm dizi ile karşılaştırılıp yerine konur.

### Bu Yöntemin BigO Notasyonu O(n^2)'dir

## PROJE 2
### **[16, 21, 11, 8, 12, 22] -> Merge Sort**

#### 1 -  Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.
             [16, 21, 11, 8, 12, 22]
                  /            \ 
        [16, 21, 11]          [8, 12, 22]
          /      \             /        \ 
      [16, 21]    [11]       [8, 12]     [22]
        /   \       |         /   \        |  
    [16]    [21]   [11]     [8]    [12]   [22]
      \      /      |         \     /      | 
      [16, 21]    [11]        [8, 12]    [22]
        \   |      /           \   |     /                 
        [11, 16, 21]           [8, 12, 22]
           \   \    \          /   /   /
              [8, 11, 12, 16, 21, 22]
    
#### 2 - Big-O gösterimini yazınız.
    O(nlogn)
   
## PROJE 3
#### [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.
    [0, 1, 2, 3, 4, 5, 6, 7, 8, 9]
    Root: 5
    Root'un sağında: 7
    Root'un solounda: 3
     
                      5 
                  /       \
                3          7
              /   \      /   \
             1     4    6     8
            / \               | 
           0   2              9
