# INSERTION SORT PROJESİ

- [22,27,16,2,18,6]

- Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.
- Big-O gösterimini yazınız.
- Time Complexity:

* Average case: Aradığımız sayının ortada olması,
* Worst case: Aradığımız sayının sonda olması,
* Best case: Aradığımız sayının dizinin en başında olması.

- Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

## CEVAPLAR

### 1. Insertion Sort Aşamaları

- Temel Durum: [22,27,16,2,18,6]

* A1: [22|,27,16,2,18,6]
* A2: [22,27|,16,2,18,6]
* A3: [16,22,27|,2,18,6]
* A4: [2,16,22,27|,18,6]
* A5: [2,16,18,22,27|,6]
* A6: [2,6,16,18,22,27]

### 2. Big O Notation Gösterimi

- Worst Case : o(n^2)
- Avarage Case: o(n^2)
- Best Case : o(n)

### 3. Time Complexity

- Best Case : [2,6,16,18,22,27]
- Worst Case : [27,22,18,16,6,2]

### 4. 18 Sayısının Case Durumu

- Dizi sıralandıktan sonra [2,6,16,18,22,27] halini alır. Bu durumda "18" sayısı ortada olarak sayılabilir. Bu nedenle avarage case kapsamında yer alır.

### [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

- Temel Durum: [7,3,5,8,2,9,4,15,6]

- Dizinin ilk dört aşaması:

* A1:[7|,3,5,8,2,9,4,15,6]
* A2:[3,7|,5,8,2,9,4,15,6]
* A3:[3,5,7|,8,2,9,4,15,6]
* A4:[3,5,7,8|,2,9,4,15,6]
