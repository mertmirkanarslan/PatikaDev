# Insertion Sort Projesi

# Proje 1

**[22,27,16,2,18,6]** -> Insertion Sort

1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
2. Big-O gösterimini yazınız.
3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

<\hr >

```
1. Soru:
adım 1: [2,27,16,22,18,6] (0. indexteki eleman ele alınır, diğer elemanlarla kıyaslanır ve en küçük elemanla yer değiştirir.)
adım 2: [2,6,16,22,18,27] (1. indexteki eleman ele alınır, 0. index daha önce dikkate alındığı için 2. indexten başlayarak en küçük eleman kıyaslaması yapılır. )
adım 3: [2,6,16,22,18,27] (2. indexteki eleman yine benzer işlemlerle ele alınır, burada en küçük o olduğu için aynen devam eder.)
adım 4: [2,6,16,18,22,27] (3. indexteki eleman 4 ve 5. indexteki elemanlarla karşılaştırılır ve 3. index ile 4. index yer değiştirmiş olur.)
adım 5: [2,6,16,18,22,27] (4. index son indexle kıyaslandı. sonuç değişmedi fakat yine de bu işlem arka planda yapıldı.)
--> bu işlemler kısaca n elemanlı bir dizide n-1 kadar devam eder.
```

```
2. Soru:Insertion Sort algoritmasında, Big-O Notation n^2'dir.
```

```
3. Soru: Time Complexity: Burada aradığımız spesifik bir sayı yok. O nedenle bu case bir worst case'dir diyebiliriz.
```

```
4. Soru: 18 sayısı 5 indexli dizide 3. sırada bulunuyor. Bu nedenle average-worst arasındadır.
```