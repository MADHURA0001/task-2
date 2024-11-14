# task-2
memory=[]
def storage():
    print("Enter Two Numbers")
    for i in range(0,2):
        elements = int(input(" "))
        memory.append(elements)
    print("Two Numbers Entered By User Are :")
    print(memory)
storage()   
def addition():
    print("sum of two numbers is : ")
    sum=memory[0]+memory[1]
    print(sum)
def subtraction():
    print("differrence between two numbers is : ")
    difference=memory[0]-memory[1]
    print(difference)
def multiplication():
    print("product of two numbers is : ")
    product=memory[0]*memory[1]
    print(product)
def division():
    print("division of two numbers is : ")
    div=memory[0]/memory[1]
    print(div)
k=int(input("enter no of times you want to do operations"))
def choice():
    print("enter 1 for addition")
    print("enter 2 for subtraction")
    print("enter 3 for multiplication")
    print("enter 4 for division")
choice() 
def operations():
    choice = int(input(" "))
    if (choice==1):
        addition()
    if (choice==2):
     subtraction()
    if (choice==3):
        multiplication()
    if (choice==4):
        division()
operations()
for i in range (0,k):
    print("enter 69 to continue or enter 96 to discontinue")
    to_continue = int(input(" "))
    if (to_continue == 69):
        choice()
        operations()
    if (to_continue == 96):
        print("operations are over")
        break
