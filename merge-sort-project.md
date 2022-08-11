[16,21,11,8,12,22] -> Merge Sort


1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

Başlangıçta dizimizi ikiye bölüyoruz. Bölünen dizileri sonra tekrar bölüyoruz. Tek eleman kalana kadar bu işleme devam ediyoruz.

1) [16, 21, 11,]    [8, 12, 22]
2) [16, 21]    [11]    [8]   [12, 22]
3) [16]   [21]   [11]   [8]   [12]   [22] 
4) [16, 21]    [11]    [8]   [12, 22]
5) [11, 16, 21]  [8, 12, 22]
6) [8, 11, 12, 16, 21, 22]



2. Big-O gösterimini yazınız: 
O(n*(logn)) --> O(6*(log6))