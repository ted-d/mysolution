# mysolution
решение задачи на Python
Напишите программу, на вход которой подаётся прямоугольная матрица в виде последовательности строк. После последней строки матрицы идёт строка, содержащая только строку "end" (без кавычек, см. Sample Input).

Программа должна вывести матрицу того же размера, у которой каждый элемент в позиции i, j равен сумме элементов первой матрицы на позициях (i-1, j), (i+1, j), (i, j-1), (i, j+1). У крайних символов соседний элемент находится с противоположной стороны матрицы.

В случае одной строки/столбца элемент сам себе является соседом по соответствующему направлению.

входные данные:

 

Кейс 1 :
Вход - 1
Выход - 4
 
Кейс 2:
Вход - 15 -4 8 3
Выход - 29 15 15 29
 
Кейс 3:
Вход - 
0
7
9
12
Выход -
19
23
37
33
 
Кейс 4:
Вход -
2 2 2 3 0 5
8 -4 3 5 1 0
Выход -
23 -4 11 12 10 2
0 15 5 10 5 19
 
Кейс 5:
Вход -
2 2
3 5
-1 7
0 1
Выход -
7 10
11 15
17 4
3 9
 
Кейс 6 :
Вход -
9 5 3
0 7 -1
-5 2 9
Выход -
3 21 22
10 6 19
20 16 -1
Кейс 1 :
Вход - 1
Выход - 4
 
Кейс 2:
Вход - 15 -4 8 3
Выход - 29 15 15 29
 
Кейс 3:
Вход - 
0
7
9
12
Выход -
19
23
37
33
Кейс 4:
Вход -
2 2 2 3 0 5
8 -4 3 5 1 0
Выход -
23 -4 11 12 10 2
0 15 5 10 5 19
 
Кейс 5:
Вход -
2 2
3 5
-1 7
0 1
Выход -
7 10
11 15
17 4
3 9
