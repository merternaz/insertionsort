# Insertion Sort
- [22,27,16,2,18,6] 
- [22] < [27] değil [22,27,16,2,18,6]
- [16] < [27] ve [16] < [22] == [16,22,27,2,18,6]
- [2] < [27]  ve 16,22 sırasındanda küçük olduğundan == [2,16,22,27,18,6]
- [18] < [27] ve [18] < [22] olduğundan == [2,16,18,22,27,6]
- [6] < [16]  ve 16,18,22 olduğundan == [2,6,16,18,22,27] son olur.

# BigO
- n(n+1)/2 = (n^2+n)/2 == O(n^2)

# Time Complexity
- 18 sayısı dizinin ortasında kaldığı için Average case 

# Selection Sort
[7,3,5,8,2,9,4,15,6]

- 1.Adım : min değer 2 ==> [2,3,5,8,7,9,4,15,6]
- 2.Adım : 3 değerinin yeri doğru ==> [2,3,5,8,7,9,4,15,6]
- 3.Adım : 5 değeri ile 4 yer değişir ==> [2,3,4,8,7,9,5,15,6]
- 4.Adım : 8 değeri ile 5 yer değişir ==> [2,3,4,5,7,9,8,15,6]
