# Python-Training
python program for practice and learning
#Python program for print hello world. 
print("hello world")
#Store your name in a variables and print it.
name="kowshi"
print(name)
#store your name, age, and city on separate variables and print them.
name="kowshi"
age="19"
city="mannargudi"
print(name,age,city)
#create two variables and print their values before and after swapping.
a=10
b=20
print(a,b,sep="-")
#swap two variables and print their values before and after swapping.
a=10
b=20
a,b=b,a
print(a,b)
#A customer buys two products. Get their prices as input and print the total bill, the higher price, and the lower price.
a=1000
b=2000
total=a+b
print("total:",total)
print("higher price:",max(a,b))
print("lower price:",min(a,b))
#print mark and percentage of the student
name="kowshi"
print("student name:",name)
tamil=90
english=88
maths=89
science=75
social=86
total=tamil+english+maths+science+social
print("total marks:",total)
average=total/5
print("average marks:",f"{average:.2f}")
#Area and Perimeter
length=25.67
breadth=76.35
print("Area:",length*breadth)
print("perimeter:",2*(length+breadth))
print(f"{length*breadth:.2f}")
print(f"{2*(length+breadth):.2f}")
#Input and Output Practice
a=int(input())
b=float(input())
c=str(input())
d=int(input())
e=float(input())
print(a)
print(b)
print(c)
print(d)
print(e)
#Progressive Float Execution
import struct
a=float(input())
a=struct.unpack('f',struct.pack('f',a))[0]
print("%.5f"%a)
print("%.4f"%a)
print("%.3f"%a)
print("%.2f"%a)
print("%.1f"%a)
print("%.0f"%a)
#Sum, Difference, Product, Division and Modulo.
a,b=map(int,input().split())
print(a+b)
print(a-b)
print(a*b)
print(int(a/b))
if a<0 or b<0:
  c=abs(a)%abs(b)
  print(-1*c)
else:
    print(a%b)
#ASCII
a=int(input())
print(chr(a))
#Update Counter
a=int(input())
print((a+5)*2-3)
#ODDor EVEN
a=int(input())
print("Even" if a% 2 == 0 else "Odd")
#Greatest Among Three Numbers
a=int(input())
b=int(input())
c=int(input())
greatest = a if a > b and a > c else (b if b > c else c)
print(greatest)
#Character Digit to Integer
char=input()
print(char)
#Personalized Greeting
name=input()
print("Hi "+name+", welcome to the programming class!")
#Shape Area Calculation
area=int(input())
length=int(input())
breadth=int(input())
radius=int(input())
base=int(input())
height=int(input())
print("Area of Square=%d"%(area*area))
print("Area of Rectangle=%d"%(length*breadth))
print("Area of Circle=%.2f"%(3.14*radius*radius))
print("Area of Triangle=%d"%(int((0.5)*base*height)))
#Shape Perimeter Calculation Program
a= int(input())
length= int(input())
width= int(input())
radius= int(input())
side1= int(input())
side2= int(input())
base= int(input())
print(4*a)
print(2*(length+width))
print("%.2f"%(2*3.14*radius))
print(side1+base+side2)
#Shape Perimeter Calculation Program
a= int(input())
length= int(input())
width= int(input())
radius= int(input())
side1= int(input())
side2= int(input())
base= int(input())
print(4*a)
print(2*(length+width))
print("%.2f"%(2*3.14*radius))
print(side1+base+side2)
#Handling Mixed Inputs
a=int(input())
b= input()
print(a)
print(b)
#Identify the Nature of a Number
a=int(input())
if(a>=2):
 print("POSITIVE")
elif(a<=-1):
 print("NEGATIVE")
else:
 print("ZERO")
#Explore Math Functions
import math
a=float(input())
b=int(input())
base=int(input())
power=int(input())
print(math.floor(a))
print(math.ceil(a))
print(int(round(a,0)))
print (int(math.sqrt(b)))
print(int(math.pow(base,power)))
#Smallest of Four Numbers
a=int(input())
b=int(input())
c=int(input())
d=int(input()) 
print(min(a,b,c,d))
#Truncate to Two Decimal Places
import math
a=float(input())
print(f"{math.trunc(a*100)/100}")
#Find Second Maximum Number
a = int(input())
b = int(input())
c = int(input())
if a > b:
    if b > c:
        print(b)
    else:
        if a > c:
            print(c)
        else:
            print(a)
else:
    if a > c:
        print(a)
    else:
        if b > c:
            print(c)
        else:
            print("No second max")
            
