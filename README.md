Insertion Sort Projesi
Bu proje patika.dev 'Veri Yapıları ve Algoritmalar' dersi Insertion Sort projesi ödevidir.

[22,27,16,2,18,6]
1. Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.

22 | 27 16 2 18 6

22 27 | 16 2 18 6

22 16 27 | 2 18 6

16 22 27 | 2 18 6

16 22 2 27 | 18 6
16 2 22 27 | 18 6

2 16 22 27 | 18 6

2 16 22 18 27 | 6
2 16 18 22 27 | 6

2 16 18 22 6 27 |
2 16 18 6 22 27 |

2 16 6 18 22 27 |

2 6 16 18 22 27
2. Big-O gösterimini yazınız.

O(n²)
3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

2 6 16 18 22 27

Son dizine göre 18 sayısı Average case kapsamına girmektedir.
[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

7 | 3 5 8 2 9 4 15 6

7 3 | 5 8 2 9 4 15 6

3 7 | 5 8 2 9 4 15 6

3 7 5 | 8 2 9 4 15 6
3 5 7 | 8 2 9 4 15 6

3 5 7 8 | 2 9 4 15 6

3 5 7 8 2 | 9 4 15 6

3 5 7 2 8 | 9 4 15 6

3 5 2 7 8 | 9 4 15 6

3 2 5 7 8 | 9 4 15 6

2 3 5 7 8 9 4 15 6


www.patika.dev
