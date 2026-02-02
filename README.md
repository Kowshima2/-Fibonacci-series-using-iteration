# -Fibonacci-series-using-iteration
a = 0
b = 1
n = int(input("Enter the number of terms in the sequence: "))

print(a, b, end=" ")

while n - 2 > 0:
    c = a + b
    a, b = b, c
    print(c, end=" ")
    n = n - 1

output:
Enter the number of terms in the sequence: 6
0 1 1 2 3 5 
