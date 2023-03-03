# Selection-Sort-Project

Verilen dizi: [22, 27, 16, 2, 18, 6]

İlk adımda, 22, 27 arasındaki elemanlar karşılaştırılır ve dizi aşağıdaki hale gelir:

[22, 27, 16, 2, 18, 6]

Sıradaki eleman 16'dır. Bu elemanı dizinin önceki elemanlarıyla karşılaştıralım ve uygun pozisyona yerleştirelim:

[16, 22, 27, 2, 18, 6]

Sıradaki eleman 2'dir. Bu elemanı uygun pozisyona yerleştirelim:

[2, 16, 22, 27, 18, 6]

Sıradaki eleman 18'dir. Bu elemanı uygun pozisyona yerleştirelim:

[2, 16, 18, 22, 27, 6]

Sıradaki eleman 6'dır. Bu elemanı uygun pozisyona yerleştirelim:

[2, 6, 16, 18, 22, 27]

Dizi artık sıralıdır.

Big-O gösterimi: O(n^2)

Dizi sıralandıktan sonra 18 sayısı aşağıdaki durumların hangisine girer:

Average case: Aradığımız sayının ortada olması. 18, [2, 6, 16, 18, 22, 27] dizisinde ortada yer aldığı için average case kapsamındadır
