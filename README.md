# Selection-Sort-Projesi
Patika.dev-Sort
# [22,27,16,2,18,6] -> Insertion Sort

## Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

### Big-O gösterimini yazınız.

#### Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız


## Insertion Sort
### - [22, **27**, 16, 2, 18, 6] 27 Anahtar olarak seçilir

### - [**22, 27**, 16, 2, 18, 6] 27 > 22 

### - [22, 27, **16**, 2, 18, 6] 16 Anahtar olarak seçilir

### - [22, **27, 16**, 2, 18, 6] 16 < 27 - 16 sola kayar

### - [**22, 16**, 27, 2, 18 ,6] 16 < 22 - sola kayar

### - [16, 22, 27, **2**, 18, 6]  2 Anahtar olarak seçilir

### - [16, 22, **27, 2**, 18, 6]  2 < 27 sola kayar

### - [16, **22, 2**, 27, 18, 6]  2 < 22 sola kayar

### - [**16, 2**, 22, 27,18,6]  2 < 16 sola kayar

### - [2, 16, 22, 27, **18**, 6] 18 Anahtar olarak seçilir

### - [2, 16, 22, **27, 18**, 6] 18 < 27 sola kayar

### - [2, 16, **22, 18**, 27, 6] 18 < 22 sola kayar

### - [2, 16, 18, 22, 27, **6**]  6 Anahtar olarak seçilir

### - [2, 16, 18, 22, **27, 6**]  6 < 27 sola kayar

### - [2, 16, 18, **22, 6**, 27]  6 < 22 sola kayar

### - [2, 16, **18, 6**, 22, 27]  6 < 18 sola kayar

### - [2, **16, 6**, 18, 22, 27]  6 < 16 sola kayar

### - [2, 6, 16, 18, 22, 27] DONE 


## Big-O gösterimi
O(n)


## Time Complexity:
Average Case

## [7, 3, 5, 8, 2, 9, 4, 15, 6] -> Selection Sort'a göre ilk 4 adımını

### - 1 -> [**7**, 3, 5, 8, **2**, 9, 4, 15, 6] 2 dizi de en küçük eleman **2 - 7** yer değiştirir

### - 2 -> [2, 3, **5**, 8, 7, 9, **4**, 15, 6]  **4 - 5** yer değiştirir

### - 3 -> [2, 3, 4, **8**, 7, 9, **5**, 15, 6]  **8 - 5** yer değiştirir

### - 4 -> [2, 3, 4, 5, **7**, 9, 8, 15, **6**]  **6 - 7** yer değiştirir

### - [2, 3, 4, 5, 6, 9, 8, 15, 7]
