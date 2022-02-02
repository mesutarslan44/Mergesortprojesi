## Merge Sort
# Proje İkinci Ödev
- [16,21,11,8,12,22] -> Merge Sort

1. aşamada [16,21,11] ve [8,12,22] 

2. aşamada [16],[21,11] ve [8], [12,22] 

3. aşamada [16],[21],[11] ve [8],[12],[22] 

4. aşamada [11,16],[21] ve [8,12],[22] 

5. aşamada [11,16,21] ve [8,12,22] 

6. aşamada [8,11,12,16,21,22] 


# Big-O gösterimi

2^x = n ve x = logn oluyor. Bölme ve birleştirme yaparak n işlem yapıyoruz ve bu durumda Big-O Notationumuz O(nlogn) olarak ortaya çıkıyor.