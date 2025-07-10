# Python-Functions-
'''Function with parameters'''
def add(student1,student2):
    return student1+student2
student1=int(input("enter the money:"))
student2=int(input("enter the money:"))
total=add(student1,student2)
print("Total amount:",total)

------OUTPUT--------
enter the money: 100
enter the money: 500
Total amount: 600




def add(student1,student2):
    print("Total:",student1+student2)
student1=int(input("enter the money:"))
student2=int(input("enter the money:"))
add(student1, student2)


------OUTPUT-------
enter the money: 345
enter the money: 890
Total: 1235


def hi(name):
    print("Hello",name)
hi("Jyothika")

-----OUTPUT-----
Hello Jyothika




def value():
    return 3.14159
result=value()
print("value in the function is",result)



------OUTPUT-------
value in the function is 3.14159





def get_name():
    name=input("enter your name:")
    return name
username=get_name()
print("welcome",username)


-------OUTPUT---------
Enter your name:  jyothika koliki
welcome jyothika koliki







a=100
def value(a):
    return a+20
op=value(a)
print(op)

--------OUTPUT--------
    120



    def hi(name):
    print("Hello",name)
a=input("Enter data")
hi(a)

-----OUTPUT------
Enter data jyothika
Hello jyothika



def hi(name='Guest'):
    print("Hello",name)
a=input("Enter data")
hi()
hi(a)

-----OUTPUT-----
Enter data jyothika
Hello Guest
Hello jyothika





def cal(a,b):
    return a+b,a-b,a*b,a/b
a=int(input("enter a:"))
b=int(input("enter b:"))
sum,diff,pro,div=cal(a,b)
print("sum=",sum)
print("Subtract=",diff)
print("product=",pro)
print("divide=",div)

------OUTPUT------
enter a: 34
enter b: 22
sum= 56
Subtract= 12
product= 748
divide= 1.5454545454545454


# Python-Functions-maximum and minimum
def max_min(a,b,c):
    return max(a,b,c),min(a,b,c)
a=int(input("enter a:"))
b=int(input("enter b:"))
c=int(input("enter c:"))
maxi,mini=max_min(a,b,c)
print("maximum:",maxi)
print("minimum:",mini)

------OUTPUT-------
enter a: 4
enter b: 7
enter c: 9
maximum: 9
minimum: 4



# Python-Functions-EVEN COUNT AND ODD COUNT    
def eo(numbers):
    e=0
    o=0
    for n in numbers:
        if n % 2==0:
            e+=1
        else:
            o+=1
    return e,o
num=input("enter the number as space seperated")
num_list=list(map(int,num.split()))
e,o=eo(num_list)
print("Even count:",e)
print("Odd count:",o)

------  OUTPUT---------
enter the number as space seperated 4 7 2 3 11 18 54 67 80
Even count: 5
Odd count: 4

    





