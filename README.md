# Selection-Sort-Projesi
Veri yapıları ve algoritmalar konusu kapsamında yapılan ilk proje/ödevdir. 
# Proje 1
## Soru 1: [22,27,16,2,18,6]
### Yukarı verilen dizinin insertion sort türüne göre aşamalarını yazınız.

Insertion sort, yani araya sokma sıralaması, düzensiz bir dizideki elemanları tek tek ele alarak her birini dizideki sıralı kısma uygun yere yerleştirme esasına dayanır. 
İkinci elemandan başlanarak kendisinden önceki elemanla karşılaştırılır ve küçükse sola, büyükse sağa kaydırılır.

Problemimizdeki dizide 2. sıradaki 27 elemanından başlayacaktır. 27>22 olduğundan dizide bir değişiklik olmayacak.

1- [22,27,16,2,18,6]

3.sırada 16'ya bakıldığında 16>27'dir. İlk önce ikisinin yerini değiştirir. [22,16,27,2,18,6] Sonra ilk sıradaki elemana bakar. 16>22 olduğundan onların da yerini değiştirir. Bu durumda:

2- [16,22,27,2,18,6]

Artık ilk 3 eleman sıralıdır. 4. eleman olan 2 için de yukarıdaki gibi sırayla bir öncekiyle kıyaslayarak yer değiştirmeye devam eder. 

3- [2,16,22,27,18,6]

Bu mantıkla:

4- [2,16,18,22,27,6]
5- [2,6,16,18,22,27] dizinin küçükten büyüğüe doğru sıralanmış halidir.

### Big-O gösterimini yazınız.

O(n^2)

### Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? 

18, dizi sıralandıktan sonra tam ortadaki eleman olduğundan **average case** olacaktır.

## [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

Selection sort yani seçmeli sıralamada, dizideki elemanlara sırasıyla bakılır, en küçük olanı tespit eder ve onu en başa alıp baştaki elemanı da onun yerine yazar.

Verilen diziye bakıldığında en küçük eleman 2'dir. O yüzden ilk aşamada 2 en başa alınacak, onun olduğu yere 7 gelecektir; yani 2 ile 7 yer değiştirecektir.

1- [2,3,5,8,7,9,4,15,6]

2'den sonra en küçük eleman 3 olup olması gereken sıradadır. Değişiklik olmayacaktır. Ondan sonraki küçük sayı ise 4'tür. Bu sebeple, 4 ile 5 yer değiştirecektir.

2- [2,3,4,8,7,9,5,15,6]

3- [2,3,4,5,7,9,8,15,6]

4- [2,3,4,5,6,9,8,15,7]

5- [2,3,4,5,6,7,8,15,9]

.
.
.




