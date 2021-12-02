
# Binary Search Tree Projesi

1. [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

---
- Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.
---
1.  [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] 

                    7
                  /   \
                 5     8
                / \      \
               1   6      9 
              / \
             0   3
                / \
               2   4

- root 7dir. 
- 5, 7 den küçük olduğu için soldadır.
- 1, 7 den küçük olduğu için sola gider, 5den küçük olduğu için 5in solunda yer alır.
- 8, 7den büyük olduğu için sağdadır.
- 3, 7den küçük olduğu için sola gider,5den küçük olduğu için sola gider, 1den büyük olduğu için sağa gider.
- 6, 7den küçük olduğu için sola gider, 5den büyük olduğu için 5in sağına gider.
- 0, 7den küçük olduğu için sola gider, 5den küçük olduğu için sola gider, 1denküçük olduğu için 1in solunda yer alır.
- 9, 7 den büyük olduğu için sağa gider, 8den büyük olduğu için 8in sağında yer alır.
- 4, 7den küçük olduğu için sola gider,5den küçük olduğu için sola gider, 1den büyük olduğu için sağa gider,3den büyük olduğu için 3ün sağında yer alır.
- 2, 7den küçük olduğu için sola gider,5den küçük olduğu için sola gider, 1den büyük olduğu için sağa gider,3den küçük olduğu için 3ün solunda yer alır.                 
