# Merge Sort Projesi

[16,21,11,8,12,22] - Merge Sort
## 1.Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

![Merge-Sort](https://i.hizliresim.com/3qa0to6.png)

## 2.Big-O gösterimini yazınız.

Merge Sort algoritmasının karmaşıklığına bakıldığında O(nlogn) olarak bulunur. Çünkü üzerinde çalışılan dizi her adımda 2'ye bölünmüştür. 
Böylece sonuç dizisi olan 2'şer elemanlı dizilere log2n adımda ulaşılabilir. Daha sonra her n eleman için sıralama yapıldığı ve her n eleman üzerinden
geçildiği için bu değer çarpan olarak gelmekte ve sonuç nlog2n olarak bulunmaktadır.

Worst Case : nlogn 

Average Case : nlogn

Best Case : nlogn
