# insertion-sort-project
1- [22,27,16,2,18,6] 

[22, 27, 16, 2, 18, 6]  
[16, 22, 27, 2, 18, 6]  
[2, 16, 22, 27, 18, 6]  
[2, 16, 18, 22, 27, 6]  
[2, 6, 16, 18, 22, 27]  

2- Big-O gösterimini yazınız.
  n(n+1)/2 O(n^2)
  
3- Dizi sıralandıktan sonra 18 sayısı average case kapsamına girer.
  
4- [7,3,5,8,2,9,4,15,6]  dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
  
 1- [3,7,5,8,2,9,4,15,6]
 2- [3,5,7,8,2,9,4,15,6]
 3- [3,5,7,8,2,9,4,15,6]
 4- [3,5,7,2,8,4,9,15,6]
 
 
 # Merge Sort Projesi
 
[16,21,11,8,12,22] -> Merge Sort

# Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
     [16,21,11]                           [8,12,22]                                           
     [16,21]       [11]                     [8,12]  [22] 
      [16] [21]      [11]                      [8] [12] [22]
      [16,21] [11]                                [8,12] [22]
      [11,16,21]                                [8,12,22]
                          [8,11,12,16,21,22]

# Big-O gösterimini yazınız.
            O(nlogn)

#Binary Search Tree Projesi

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.  
root 7



               ```         7  
                          / \           
                         5   8          
                        / \   \   
                       1   6   9  
                      / \
                     0   3  
                         /\
                        2  4 
                 ```  
5 küçük mü büyük mü baktık, küçük olduğu için sola yazıldı.  1, 7 ve 5'ten küçük 5'in soluna yaz.  şeklinde aşamaları yapıldı.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.
