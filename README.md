# MERGE Sort

### Proje 2

> [16,21,11,8,12,22] -> Merge Sort

> Q: Yukarıdaki dizinin sort türüne göre aşamalarını yazınız. 

> Q: Big-O gösterimini yazınız.

```
<-- Merge Sort Steps -->
1 => [16,21,11,8,12,22]                          
2 => [16,21,11]              [8,12,22]
3 => [16,21] <-> [11]        [8,12] <-> [22]
4 => [16] <-> [21] <-> [11]  [8] <-> [12] <-> [22]
5 => [16,21] <-> [11]        [8,12] <-> [22]
6 => [11,16,21]              [8,12,22]
7 => [8,11,12,16,21,22]
```

> <-- Big O -->

**1. Bölme Aşaması**

```
Dizi sürekli olarak ikiye bölünür. Bir dizi n elemanlı ise:

İlk bölme: n eleman
İkinci bölme: n/2 eleman
Üçüncü bölme: n/4 eleman
...
K. bölme: n/(2^k) eleman

Bu, diziyi log(n) adımda tek elemanlı parçalara böleceğimiz anlamına gelir. Her bölme adımında O(1) süre alır. Bu nedenle bölme aşamasının toplam karmaşıklığı O(log(n)) olur.
```

**2. Birleştirme Aşaması**

```
Birleştirme aşamasında, her iki alt diziyi birleştiririz. Her iki alt dizi sıralıdır ve birleşme işlemi O(n) sürede yapılır.

İlk birleştirme: n eleman
İkinci birleştirme: n eleman
Üçüncü birleştirme: n eleman
...
K. birleştirme: n eleman

Her birleştirme adımı O(n) sürede tamamlanır ve Bölme Aşamasında log(n) adım vardır. Bu nedenle, bölme ve birleştirme aşamasının toplam karmaşıklığı O(n * log(n)) olur.
```

> Örnek bir Merge Sort:

<img width="400" height="480" src="https://upload.wikimedia.org/wikipedia/commons/c/cc/Merge-sort-example-300px.gif"></img>



### Hakkımda

- 💻 Yazılım Geliştirici
- 🌱 Şu anda yeni teknolojiler öğreniyorum
- 🤝 Açık kaynak projelere katkıda bulunmayı seviyorum

## İletişim

- [LinkedIn](https://www.linkedin.com/in/eraycan-sivri-827997226/)
- [E-posta](mailto:eraycansivri@hotmail.com)
