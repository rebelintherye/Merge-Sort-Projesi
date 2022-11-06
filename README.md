# Merge-Sort-Projesi
[patika.dev](www.patika.dev)

[16,21,11,8,12,22] -> Merge Sort

1.Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
2.Big-O gösterimini yazınız.
---
1.
```
Merge Sort'a göre diziyi tek eleman kalana dek ikiye bölme işlemi yapıyoruz. Böldükten sonra sıralı bir şekilde sunuyoruz.

  [16,21,11]             [8,12,22]

[16]  [21,11]           [8,12]   [22]

[16]  [21] [11]        [8] [12]  [22]

[16]  [11,21]          [8,12]    [22]

[11,16,21]             [8,12,22]

        [8,11,12,16,21,22]
        
```

---
2.
```
Merge Sort'un Big-O gösterimi O(nlogn)
n=6
2ˣ=6
log6=x
O(6log6)
```
