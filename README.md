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
 #Triangle Angle Validation
 A = int(input())
B = int(input())
C = int(input())
if A + B + C == 180 and A > 0 and B > 0 and C > 0 :
    print("VALID")
    if A == B == C:
      print("EQUILATERAL")
    elif A == B or B == C or A == C:
      print("ISOSCELES")
    else:
      print("SCALENE")
else:
   print("NOT VALID")
#Number to Word
n=int(input())
match n:
  case 0:
    print("zero")
  case 1:
    print("one")
  case 2:
    print("two")
  case 3:
    print("three")
  case 4:
    print("four")
  case 5:
    print("five")
  case 6:
    print("six")
  case 7:
    print("seven")
  case 8:
    print("eight")
  case 9:
    print("nine")
  case _:
    print("invalid")
  #Vowel or Consonant
  ch = input().lower()
match ch:
    case 'a' | 'e' | 'i' | 'o' | 'u':
        print("vowel")
    case _:
        print("consonant")
 #Leap Year Checker
 n= int(input())
if year % 400 == 0:
    print("yes")
elif year % 100 == 0:
    print("no")
elif year % 4 == 0:
    print("yes")
else:
    print("no")
#Fun Grade Calculator
a=int(input())
b=int(input())
c=int(input())
d=int(input())
e=int(input())
total=a+b+c+d+e
Average=total/5
if Average >= 90:
  print("Excellent!")
elif Average >= 80 and  Average < 90:
  print("Great Job!")
elif Average >= 70 and  Average < 80:
  print("Good Effort!")
elif Average >= 50 and  Average <70:
  print("Keep Trying!")
else:  
  print("Better Luck Next Time!")
  #Train Berth Type Finder
  seat=int(input())
seatnumber=seat%8
match seatnumber:
  case 1:
    print("LB")
  case 2:
    print("MB")
  case 3:
    print("UB")
  case 4:
    print("LB")
  case 5:
    print("MB")
  case 6:
    print("UB")
  case 7:
    print("SL")  
  case 0:
    print("SU")  
  case _:
    print("INVALID")
#Electricity Bill Calculator
  units=float(input())
amount=0.0
if units>=0 and units<=50:
   amount=units*1
elif units>=51 and units<=150:
   amount=50+(units-50)*2
elif units>=151 and units<=250:
   amount=50+200+(units-150)*3
else:
  amount=50+200+300+(units-250)*4
if amount>150:
  print(int(amount*0.2+amount))
else:
  print(int(amount))
  #Thala vs Thalapathy Game
  n = int(input())
if n % 3 == 0 and n % 5 == 0:
    print("ThalaThalapathy")
elif n % 3 == 0:
    print("Thala")
elif n % 5 == 0:
    print("Thalapathy")
else:
    print(n)
#Train Fare Calculator
age = int(input())
distance = int(input())
fare = distance * 5
if age < 12:
    fare = fare * 0.5
elif age <= 59:
    fare = fare
else:
    fare = fare * 0.75
print(int(fare))
#Average Marks Calculator
a=int(input())
b=int(input())
c=int(input())
d=int(input())
e=int(input())
avg = (a + b + c + d + e) / 5
if avg == int(avg):
    print(int(avg))
else:
    print(f"{avg:.2f}")
#Fun Character Case Converter
ch = input()
if ch.islower():
    print(ch.upper())
elif ch.isupper():
    print(ch.lower())
else:
    print("abcd theriyatha?")
    

            
            
            

