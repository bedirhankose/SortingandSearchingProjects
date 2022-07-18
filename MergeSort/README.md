# MERGE SORT PROJESİ

[16,21,11,8,12,22]

1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
2. Big-O gösterimini yazınız.

# CEVAP

## 1. Merge Sort Aşamaları

**[16,21,11,8,12,22]** ilk önce sayı dizisini ikiye bölünür.

- **[16,21,11]** **[8,12,22]**

Daha sonra bölünen diziler tekrar ikiye bölünür.

- **[16,21]** **[11]** **[8,12]** **[22]**

---

Dizi tekli elemanlar kalana dek parçalanır ve bölme işlemi sonlandırılır.

- **[16]** **[21]** **[11]** **[8]** **[12]** **[22]**

---

Elemanlar tekrar birleştirmeye başlanır ve ikili gruplar halindeyken sıralanır.

- **[16,21]** **[11]** **[8,12]** **[22]**

---

İkili olarak sıraya uygun bir şekilde diziler birleştirilir.

- **[11,16,21]** **[8,12,22]**

---

Elde edilen diziler uygun bir şekilde bir kez daha birleştirilir. Dizi son halinde sıralanmış olur.

- **[8,11,12,16,21,22]**

---

## 2. Big-O Notation Gösterimi

- Worst case : O(n\*logn)
- Average case : O(n\*logn)
- Best case : O(n\*logn)

---
