## [22,27,16,2,18,6] -> Insertion Sort
## Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.

1. Asama: En kucuk sayi birinci sayiyla yer degistirilir.
2,[27,16,22,18,6]

2. Asama: Geriye kalan sayilara bakilir ve en kucuk sayi ikinci sayiyla yer degistirilir.
2,6,[16,22,18,27]

3. Asama: Geriye kalan sayilara bakilir ve en kucuk sayi ucuncu sayiyla yer degistirilir.
2,6,16,[22,18,27]

4. Asama: Geriye kalan sayilara bakilir ve en kucuk sayi dorduncu sayiyla yer degistirilir.
2,6,16,18,[22,27]

5. Asama: Geriye kalan sayilara bakilir ve en kucuk sayi besinci sayiyla yer degistirilir ve sona en buyuk sayi kalmis olur. 
2,6,16,18,22,[27]

## Big-O gösterimini yazınız. 

Insertion Sort oldugundan dolayi formulu n + (n-1) + (n-2) … +1’dir. Yani, n. (n+1) / 2 yani n2 + n / 2 olur. Big-O gosterimi de O (n2) seklinde olur. 

## Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız.
### 1. Average case: Aradığımız sayının ortada olması 
### 2. Worst case: Aradığımız sayının sonda olması
### 3. Best case: Aradığımız sayının dizinin en başında olması.

18 sayisi ortada oldugu icin average case kapsamina girmektedir.

## [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız. 

1. Asama: En kucuk sayi birinci sayiyla yer degistirilir.
2,[3,5,8,7,9,4,15,6]

2. Asama: Geriye kalan sayilara bakilir ve en kucuk sayi ikinci sayiyla yer degistirilir.
2,3,[5,8,7,9,4,15,6]

3. Asama: Geriye kalan sayilara bakilir ve en kucuk sayi ucuncu sayiyla yer degistirilir.
2,3,4,[8,7,9,5,15,6]

4. Asama: Geriye kalan sayilara bakilir ve en kucuk sayi dorduncu sayiyla yer degistirilir.
2,3,4,5,[7,9,8,15,6]
