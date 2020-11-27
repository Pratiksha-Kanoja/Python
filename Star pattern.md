print("Enter no. of rows:")
n=int(input())
print("Enter 0 or 1:")
b=int(input())
if(b == 0):
    i=n
    while(i!=0):
        count = 1
        while(count<=i):
          print("*",end="")
          count = count+1
        print(" ")
        i=i-1
else:
    i = 1
    while (i <= n):
        count = 1
        while (count <= i):
            print("*", end="")
            count = count + 1
        print(" ")
        i = i + 1
