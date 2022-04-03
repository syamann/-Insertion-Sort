# -Insertion-Sort

Insertion Sort Projesi
Proje 1
[22,27,16,2,18,6] -> Insertion Sort

1.Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
2.Big-O gösterimini yazınız.
3.Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
4.Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.


5.[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız

1.Cevap
1.Adım (22,27,16,2,18,6)
27 ile 22'yi karşılaştırırız ve 27 22'den büyük olmadığı için yer değiştirmeyiz.

2.Adım (16,22,27,2,18,6)
Bu sefer key değerimiz 16 ve 16 ile solundaki değerleri teker teker karşılaştırırız. 27 ve 22'den küçük olduğunu için en başa alırız.

3.Adım (2,16,22,27,18,6)
Key değerimiz 2. Solundaki değerler ile karşılaştırırız ve hepsinden küçük olduğu için en başa alırız.

4.Adım (2,16,18,22,27,6)
Key değerimiz 18. Solundaki değerler ile karşılaştırırız ve 16'dan büyük olduğu için 16'nın sağına yazarız.

5.Adım (2,6,16,18,22,27)
Key değerimiz 6. Solundaki değerler ile karşılatırırız ve 2'den büyük olduğu için 2. sıraya yazarız.

2.Cevap

O(n^2)'dir.

3.Cevap

Worst Case: 1'den N'e kadar tüm verilerin dolaşılması bunun için n(n+1)/2 -- n^2+n olur bu da Big O Notation  O(n^2) olarak verir.

Avarage Case: Veri dizisi kısmen karışık olması. Big O Notation O(n^2) olur.

Best Case: Veri dizisi sıralı ise ve dizi sadece n kadar kontrol edilir bu durumda da Big O Notation  O(n) olur.


4.Cevap

18 Sayısı veri dizisinin ortasında olduğu için Avarage Case kapsamına girer.

5.Cevap
1.Adım (3,7,5,8,2,9,4,15,6)
3 ile 7'yi karşılaştırırız ve 3 7'den küçük olduğu için yer değiştiririz.

2.Adım (3,5,7,8,2,9,4,15,6)
Bu sefer key değerimiz 5 ve 5 ile solundaki değerleri teker teker karşılaştırırız. 7'den küçük olduğunu için 7'nin soluna alırız.

3.Adım (3,5,7,8,2,9,4,15,6)
Key değerimiz 8. Solundaki değerler ile karşılaştırırız ve hiçbirinden küçük olmadığı için olduğu yerde bırakırız.

4.Adım (2,3,5,7,8,9,4,15,6)
Key değerimiz 2. Solundaki değerler ile karşılaştırırız ve solundaki tüm değerlerden küçük olduğu için 3'ün soluna yazarız.
