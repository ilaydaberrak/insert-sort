# insert-sort
# Insertion ve Selection Sort Projesi

Bu proje Insertion Sort ve Selection Sort algoritmalarının Python ile implementasyonlarını içerir.

## Big-O Analizi
- Insertion Sort: Best O(n), Average & Worst O(n²)
- Selection Sort: O(n²)

## Kullanım
Python dosyalarını çalıştırmak için:

# Insertion Sort Aşamaları

Dizi: [22, 27, 16, 2, 18, 6]

1. Başlangıç: [22, 27, 16, 2, 18, 6]  
2. 27, 22’den büyük, yer değiştirme yok: [22, 27, 16, 2, 18, 6]  
3. 16, 27 ve 22’den küçük, uygun yere yerleşir: [16, 22, 27, 2, 18, 6]  
4. 2, dizinin başına yerleşir: [2, 16, 22, 27, 18, 6]  
5. 18, 27 ve 22’den küçük, 16’dan büyük: [2, 16, 18, 22, 27, 6]  
6. 6, 27, 22, 18, 16’dan küçük, 2’den büyük: [2, 6, 16, 18, 22, 27]

---

# Big-O Analizi

- Best Case: O(n)  
- Average Case: O(n²)  
- Worst Case: O(n²)

---

# 18 Sayısı İçin Case

18 sayısı dizinin ortasında olduğundan **Average Case** kapsamındadır.

---

# Selection Sort İlk 4 Adımı

Dizi: [7, 3, 5, 8, 2, 9, 4, 15, 6]

1. En küçük 2 ile 7 yer değiştirir: [2, 3, 5, 8, 7, 9, 4, 15, 6]  
2. En küçük 3 zaten doğru yerde: [2, 3, 5, 8, 7, 9, 4, 15, 6]  
3. En küçük 4 ile 5 yer değiştirir: [2, 3, 4, 8, 7, 9, 5, 15, 6]  
4. En küçük 5 ile 8 yer değiştirir: [2, 3, 4, 5, 7, 9, 8, 15, 6]
