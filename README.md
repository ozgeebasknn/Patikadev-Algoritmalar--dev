# Patikadev Algoritmalar Ödev
 Insertion sort, merge sort, binary search tree
# Insertion Sort
[22,27,16,18,6] için sort türüne göre aşamalarını yazınız.
2,27,16,22,18,6
2,6,16,22,18,27
2,6,16,18,22,27
2,6,16,18,22,27

Big-O gösterimini yapınız.
O(n^2)

Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.

Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer?
Average case kapsamına girer.

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

2,3,5,8,7,9,4,15,6

2,3,5,8,7,9,4,15,6

2,3,4,8,7,9,5,15,6

2,3,4,5,7,9,8,15,6

# Merge Sort
[16,21,11,8,12,22]  dizisinin sort türüne göre aşamalarını yazınız.
16,21,11 8,12,22

16 21,11 8 12,22

16 21 11 8 12 22

16 11,21 8 12,22

11,16,21 8,12,22

8,11,12,16,21,22

Big-O gösterimini yazınız.
O(n(logn))

# Binary Search Tree
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.
Root:7



                          7
                         / \
                        5   8
                       / \   \
                      1   6   9
                     / \
                    0   3
                       / \
                      2   4


