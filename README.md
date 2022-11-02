# LOGO
#Python
python script to display Hackerrank logo
n=int(input())
c="H"
for i in range (1,2*n,2):
    print((c*i).center((2*n)-1," "))
for j in range(1,n+2):
    print((c*n).center((n*2)," ")+((c*n).center((n*6)," ")))
for k in range(1,n//2+2):
    print((c*(n*5)).center((n*6)," "))
for z in range(1,n+2):
    print((c*n).center((n*2)," ")+((c*n).center((n*6)," ")))
for a in range ((2*n)-1,0,-2):
    print((c*a).center((n*10)-1," "))
