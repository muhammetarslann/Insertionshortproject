# Merge Short Projesi

[Patika.dev Profilim](https://app.patika.dev/alfalander)
---
[16,21,11,8,12,22] -> Merge Sort
### 1.Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
* [16,21,11,8,12,22]
* [16,21,11] - [8,12,22]
* [16] - [21,11] - [8] - [12,22]
* [16] - [21] - [11] - [8] - [12] - [22]
* [16] - [11,21] - [8] - [12,22]
* [11,16,21] - [8,12,22]
* [8,11,12,16,21,22]
### 2. Big-O gösterimini yazınız.
* Sürekli kendini çağırarak diziyi hep ikiye bölmektedir. Her bölünmüş dizinin Merge işlemi için de dizinin uzunluğu olan n işlem yapılır. Gösterimi şu şekildedir:  O(n*(logn)) 