# Patika/Proje1-Insertion Short
[22,27,16,2,18,6] -> Insertion Sort
Verilen dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.
Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer?Yazınız
Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.

[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

# Insertion Sort Aşamaları

[22,27,16,2,18,6] - (n)

[2*,27,16,22,18,6] - (n-1)

[2,6*,16,22,18,27] - (n-2)

[2,6,16*,18,22,27] - (n-3)

# Big-O Gösterimi

Worst Case: O(n²) = n+(n-1)+(n-2)....+1
Average Case: O(n²)
Best Case: O(n)

# Time Complexity

Worst Case: [27,22,18,16,6,2]

Best Case: [2,6,16,18,22,27]

# 18 Sayısının Case Durumu

Dizi en küçük değerden en büyük değere doğru sıralanırsa [2,6,16,18,22,27] şeklinde olacak ve 18 sayısı bu dizinin medyan değeri olacaktır. Dolayısıyla average case olduğunu söyleyebiliriz.

# [7,3,5,8,2,9,4,15,6] Dizisinin Selection Sort'a Göre İlk 4 Adımı

[2*,3,5,8,7,9,4,15,6]

[2,3*,5,8,7,9,4,15,6]

[2,3,4*,8,7,9,5,15,6]

[2,3,4,5*,7,9,8,15,6]



