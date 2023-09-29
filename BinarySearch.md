Verilen diziyi bir Binary Search Tree (BST) olarak sıralamak için sıralanan her elemanın BST'ye nasıl eklediğini aşamalarla açıklayalım:

Verilen dizi: [7, 5, 1, 8, 3, 6, 0, 9, 4, 2]

1. Başlangıçta, BST boş olduğunu varsayalım.
2. İlk eleman olan 7, kök düğüm olur. (root 7'dir)
3. Sıradaki eleman 5, root olan 7'nin solunda bulunur: 
   ```
   root 7
    \
     5
   ```
4. Bir sonraki eleman 1, root olan 7'nin solunda ve 5'in solunda bulunur:
   ```
   root 7
    \
     5
    /
   1
   ```
5. Sıradaki eleman 8, root olan 7'nin sağındadır:
   ```
   root 7
    \
     5
    / \
   1   8
   ```
6. Eleman 3, root olan 7'nin solunda ve 5'in sağında bulunur:
   ```
   root 7
    \
     5
    / \
   1   8
    \
     3
   ```
7. Eleman 6, root olan 7'nin solunda, 5'in sağında ve 3'ün solundadır:
   ```
   root 7
    \
     5
    / \
   1   8
    \
     3
      \
       6
   ```
8. Eleman 0, root olan 7'nin solunda, 5'in solunda ve 1'in solundadır:
   ```
   root 7
    \
     5
    / \
   1   8
  / \
 0   3
      \
       6
   ```
9. Eleman 9, root olan 7'nin sağındadır ve 8'in sağındadır:
   ```
   root 7
    \
     5
    / \
   1   8
  / \   \
 0   3   9
      \
       6
   ```
10. Son olarak, eleman 4, root olan 7'nin solunda, 5'in sağında, 3'ün sağındadır:
    ```
    root 7
      \
       5
      / \
     1   8
    / \   \
   0   3   9
        \
         6
          \
           4
    ```

Bu, verilen dizinin bir Binary Search Tree (BST) olarak sıralanma aşamalarını gösterir. BST, her düğümün solundaki düğümlerden daha küçük ve sağındaki düğümlerden daha büyük olan bir veri yapısıdır.