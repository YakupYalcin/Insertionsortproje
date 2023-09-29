**Insertion Sort** aşamaları ve Big-O gösterimi aşağıdaki gibidir:

Verilen dizi: [22, 27, 16, 2, 18, 6]

1. İlk adım (Başlangıç): [**22**, 27, 16, 2, 18, 6]
2. İkinci adım: [**22**, **27**, 16, 2, 18, 6]
3. Üçüncü adım: [**16**, **22**, **27**, 2, 18, 6]
4. Dördüncü adım: [**2**, **16**, **22**, **27**, 18, 6]
5. Beşinci adım: [**2**, **16**, **18**, **22**, **27**, 6]
6. Altıncı adım: [**2**, **6**, **16**, **18**, **22**, **27**]

Dolayısıyla Insertion Sort'un Big-O gösterimi O(n^2) olur.

Verilen dizi sıralandıktan sonra 18 sayısı **Average case** kapsamına girer, yani aradığınız sayının ortada olması durumunda beklenen performansı sergiler.

Şimdi **Selection Sort** ile verilen dizi [7, 3, 5, 8, 2, 9, 4, 15, 6]'nın ilk 4 adımını gösterelim:

1. İlk adım: [**2**, 3, 5, 8, 7, 9, 4, 15, 6]
2. İkinci adım: [**2**, **3**, 5, 8, 7, 9, 4, 15, 6]
3. Üçüncü adım: [**2**, **3**, **4**, 8, 7, 9, 5, 15, 6]
4. Dördüncü adım: [**2**, **3**, **4**, **5**, 7, 9, 8, 15, 6]

Bu adımlar Selection Sort'un ilk 4 adımını temsil eder. Bu algoritma, her adımda dizinin en küçük elemanını seçerek sıralama işlemi gerçekleştirir.