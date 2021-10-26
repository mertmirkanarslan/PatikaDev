# Merge Sort Projesi

# Proje 2

**[16,21,11,8,12,22]** -> Merge Sort

```
1. Soru: Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
array = [16,21,11,8,12,22]
adım 1: [16,21,11] - [8,12,22] (arrayimizi ikiye böldük.)
adım 2: [16,[21,11]] - [8,[12,22]] (tekrar böldüğümüz dizileri aynı kuralla bölüyoruz.)
adım 3: [16],[21],[11] - [8],[12],[22] (tek elemana kadar bu bölme işlemi aynı kuralla devam eder.)
adım 4: [11,16],[21] - [8,12],[22] (concat işlemi yapıldı.)
adım 5: [11,16,21] - [8,12,22] (concat işlemi yapıldı.)
adım 6: [8,11,12,16,21,22] (sonuca ulaşıldı.)
--> bu işlemler insertion sort'a göre daha az maliyetli ve daha hızlı olarak gerçekleştirilmiş oldu.
```

```
2. Soru: Merge Sort Algoritmasında, dizi veya list n/2 kez bölünüyor, aynı şekilde n/2 kez de concat oluyor. 
2^x=n 
x=log(n) oluyor. Biz burada n/2+n/2=n kadar işlem yaptığımız için:
İşlem = n*log(n)
Big-O Notation= O(nlogn)
```

