n=int(input("Enter Number of elements:"))
x=[]
print('"Enter value for X-axis:"')
for i in range(n):
    a=int(input())
    x.append(a)

print("X=",x)


y=[]
print('"Enter value for Y-axis"')
for i in range(n):
    b=int(input())
    y.append(b)
print("Y=",y)    
import matplotlib.pyplot as pg
pg.plot(x,y)
pg.xlabel("X-axis")
pg.ylabel("Y-axis")
pg.show()
