# Project1
for Kodluyoruz - IBM Training

Insertion Sort aşamaları:

[22] -> (Başlangıçta tek eleman olduğu için herhangi bir değişiklik yapılmaz)
[22,27] -> (27, 22'den büyük olduğu için bir sağa kaydırılır)
[16,22,27] -> (16, 22'den küçük olduğu için başa yerleştirilir)
[2,16,22,27] -> (2, 16 ve 22'den küçük olduğu için başa yerleştirilir)
[2,16,18,22,27] -> (18, 16 ve 22'den büyük olduğu için araya yerleştirilir)
[2,6,16,18,22,27] -> (6, 2 ve 16'dan küçük, 18 ve 22'den büyük olduğu için araya yerleştirilir)
Big-O gösterimi: O(n^2)

Time Complexity:

Average case: Aradığımız sayının ortada olması -> O(n/2)
Worst case: Aradığımız sayının sonda olması -> O(n)
Best case: Aradığımız sayının dizinin en başında olması -> O(1)

Proje 2:

Selection Sort aşamaları:

[2,3,5,8,7,9,4,15,6] -> (Minimum elemanı 2 olduğu için ilk eleman ile değişim yapmaz)
[2,3,4,8,7,9,5,15,6] -> (Minimum elemanı 4 olduğu için ikinci eleman ile değişim yapılır)
[2,3,4,5,7,9,8,15,6] -> (Minimum elemanı 5 olduğu için üçüncü eleman ile değişim yapılır)
[2,3,4,5,6,9,8,15,7] -> (Minimum elemanı 6 olduğu için dördüncü eleman ile değişim yapılır)
