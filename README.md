# Project3BinarySearchTree

Binary-Search-Tree

## Proje 3

### [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

1. Root: İlk eleman olan 7, ağacın kök (root) düğümü olur.

```
    7
```

2. 5 sayısını ekleme: 5, 7'den küçük olduğu için soluna yerleştirilir.

```
    7
   /
  5
```

3. 1 sayısını ekleme: 1, 7'den küçük ve 5'ten de küçük olduğu için 5'in soluna yerleştirilir.

```
    7
   /
  5
 /
1
```

4. 8 sayısını ekleme: 8, 7'den büyük olduğu için 7'nin sağına yerleştirilir.

```
    7
   / \
  5   8
 /
1
```

5. 3 sayısını ekleme: 3, 7'den küçük, 5'ten küçük ama 1'den büyük olduğu için 1'in sağına yerleştirilir.

```
    7
   / \
  5   8
 /
1
 \
  3
```

6. 6 sayısını ekleme: 6, 7'den küçük, 5'ten büyük olduğu için 5'in sağına yerleştirilir.

```
    7
   / \
  5   8
 / \
1   6
 \
  3
```

7. 0 sayısını ekleme: 0, 7'den küçük, 5'ten küçük, 1'den de küçük olduğu için 1'in soluna yerleştirilir.

```
      7
     / \
    5   8
   / \
  1   6
 / \
0   3
```

8. 9 sayısını ekleme: 9, 7'den ve 8'den büyük olduğu için 8'in sağına yerleştirilir.

```
      7
     / \
    5   8
   / \   \
  1   6   9
 / \
0   3
```

9. 4 sayısını ekleme: 4, 7'den küçük, 5'ten küçük, 1'den büyük ve 3'ten büyük olduğu için 3'ün sağına yerleştirilir.

```
      7
     / \
    5   8
   / \   \
  1   6   9
 / \
0   3
     \
      4
```

10. 2 sayısını ekleme: 2, 7'den küçük, 5'ten küçük, 1'den büyük ve 3'ten küçük olduğu için 3'ün soluna yerleştirilir.

```
      7
     / \
    5   8
   / \   \
  1   6   9
 / \
0   3
   / \
  2   4
```

### Sonuç

- **Root**: 7
- **7'nin solunda**: 5
- **5'in solunda**: 1
- **1'in solunda**: 0
- **1'in sağında**: 3
- **3'ün solunda**: 2
- **3'ün sağında**: 4
- **5'in sağında**: 6
- **7'nin sağında**: 8
- **8'in sağında**: 9
