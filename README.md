# PRAK-ALPRO-6
Struktur Kontrol Kompleks
n=int(input("Masukkan n: "))
x=list(input("Masukkan karakter: "))
k=n-1
for i in range(n):
    for j in range(0,k):
        print(end="")
    k=k-1
    for j in range(0,i+1):
        if j==0:
            c=0
        if c>=len(x):
            c=0
        print(x[c], end="")
        c=c+1
    print()
