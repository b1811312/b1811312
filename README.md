n = int(input())
k = 1
a = 0
for i in range(n):
    for j in range(i+1):
        print(k, end=' ')
        k=k+1
    print()
for i in range(n-1):
    for j in range(n-i-1):
        print(k+a, end=' ')
        a=a+1
    print()
