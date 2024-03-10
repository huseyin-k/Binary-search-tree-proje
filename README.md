# Binary-search-tree-proje
Proje 3 [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

Başlangıç: Dizi: [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] İlk eleman olan 7, BST'nin kökü olacaktır.

Adım: Kök eleman: 7 5, 1, 8, 3, 6, 0, 9, 4, 2 elemanları sırasıyla eklenir.

Adım: 5, 7'nin solunda yer alır çünkü 5 < 7. 1, 5'in solunda yer alır çünkü 1 < 5. 8, 7'nin sağına yerleştirilir çünkü 8 > 7.

Adım: 3, 5'in sağında yer alır çünkü 3 > 1 (1. adımda eklenen). 6, 5'in sağına yerleştirilir çünkü 6 > 5 (2. adımda eklenen).

Adım: 0, 1'in solunda yer alır çünkü 0 < 1 (2. adımda eklenen). 9, 8'in sağına yerleştirilir çünkü 9 > 8 (3. adımda eklenen).

Adım: 4, 3'ün sağına yerleştirilir çünkü 4 > 3 (3. adımda eklenen). 2, 1'in sağına yerleştirilir çünkü 2 > 1 (4. adımda eklenen). Bu adımları takip ederek, verilen diziden Binary Search Tree oluşturulmuş olur. Oluşturulan ağaç şu şekilde gösterilebilir:

 7
/ \
5 8 / \
1 6 9 / \ / 0 3 4 / 2
