# Selection-Sort-Project

Verilen dizi: [22, 27, 16, 2, 18, 6]

İlk adımda, 22, 27 arasındaki elemanlar karşılaştırılır ve dizi aşağıdaki hale gelir:

[22, 27, 16, 2, 18, 6]

Sıradaki eleman 16'dır. Bu elemanı dizinin önceki elemanlarıyla karşılaştıralım ve uygun pozisyona yerleştiririz:

[16, 22, 27, 2, 18, 6]

Sıradaki eleman 2'dir. Bu elemanı uygun pozisyona yerleştiririz:

[2, 16, 22, 27, 18, 6]

Sıradaki eleman 18'dir. Bu elemanı uygun pozisyona yerleştiririz:

[2, 16, 18, 22, 27, 6]

Sıradaki eleman 6'dır. Bu elemanı uygun pozisyona yerleştiririz:

[2, 6, 16, 18, 22, 27]

Dizi sıralıdır.

Big-O gösterimi O(n^2) seklindedir.


Average case: Aradığımız sayının ortada olması. 18, [2, 6, 16, 18, 22, 27] dizisinde ortada yer aldığı için average case kapsamındadır




 İlk adımda minimum eleman bulunduğu için, bu eleman dizinin başına yerleştirilir.

1. adım:
 
[2, 3, 5, 8, 7, 9, 4, 15, 6]

2. adım: Dizinin kalan en küçük elemanını bulup 2. sıraya  yerleştiririz: 

[2, 3, 5, 8, 7, 9, 4, 15, 6]

3. adım: Dizinin kalan en küçük elemanını bulup 3. sıraya  yerleştiririz:

[2, 3, 4, 8, 7, 9, 5, 15, 6]

4. adım: Dizinin kalan en küçük elemanını bulup 4. sıraya  yerleştiririz:

[2, 3, 4, 5, 7, 9, 8, 15, 6]



