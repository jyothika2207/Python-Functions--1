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



