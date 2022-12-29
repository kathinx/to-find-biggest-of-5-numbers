# to-find-biggest-of-5-numbers
to find biggest of 5 numbers

def No(n1,n2,n3,n4,n5):
    if(n1>n2)and (n1>n3)and(n1>n4)and(n1>n5):
        return n1
    elif(n2>n3)and(n2>n4)and(n2>n5):
        return n2
    elif(n3>n4)and(n3>n5):
        return n3
    elif(n4>n5):
        return n4
    else:
        return n5

n1=input("Enter the No:  ")
n2=input("Enter the No:  ")
n3=input("Enter the No:  ")
n4=input("Enter the No:  ")
n5=input("Enter the No:  ")
result=No(n1,n2,n3,n4,n5)
print(result , "is biggest")
