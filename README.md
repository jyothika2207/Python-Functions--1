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
