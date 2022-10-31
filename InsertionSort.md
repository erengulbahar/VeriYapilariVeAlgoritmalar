# Insertion Sort Projesi 

# 1. Soru

[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

# 1.Cevap

1. [22,27,16,2,18,6]
2. [16,22,27,2,18,6] (27>16 olduğu için yer değiştirdiler. Daha sonra 22>16 olduğu için yer değiştirirler.)
3. [2,16,22,27,18,6] (27>2 olduğu için yer değiştirdiler. Daha sonra 22>2 olduğu için yer değiştirdiler. 16>2 olduğu için yer değiştirdiler.)
4. [2,16,18,22,27,6] (27>18 olduğu için yer değiştirdiler. Daha sonra 22>18 olduğu için yer değiştirdiler.)
5. [2,6,16,18,22,27] (27>6 olduğu için yer değiştirdiler. Daha sonra 22>6 olduğu için yer değiştirdiler. 18>6 olduğu için yer değiştirdiler. 16>6 olduğu için yer değiştirdiler)

# 2. Soru

Big-O gösterimini yazınız.

# 2. Cevap

**Worst Case:** O(n^2)

**Average Case:** O(n^2)

**Best Case:** O(n)

# 3. Soru

Time Complexity: Average case: Aradığımız sayının ortada olması, Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

**Worst Case:**  [27,22,18,16,6,2]
<br/>
**Average Case:** [6,16,22,2,18,27]
<br/>
**Best Case:** [2,6,16,18,22,27]

# 4. Soru

Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

# 4. Cevap

Sıralamada ortada bulunduğu için **Average Case** durumuna girer.

# 5. Soru

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

# 5. Cevap

1. [3,7,5,8,2,9,4,15,6] (7>3 olduğu için yer değişirler.)
2. [3,5,7,8,2,9,4,15,6] (7>5 olduğu için yer değişirler.)
3. [2,3,5,7,8,9,4,15,6] (8>2 olduğu için yer değişirler. 7>2 olduğu için yer değişirler. 5>2 olduğu için yer değişirler. 3>2 olduğu için yer değişirler.)
4. [2,3,4,5,7,8,9,15,6] (9>4 olduğu için yer değişirler. 8>4 olduğu için yer değişirler. 7>4 olduğu için yer değişirler. 5>4 olduğu için yer değişirler.)
