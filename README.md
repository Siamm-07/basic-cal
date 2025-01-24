# basic-cal
#Basic calculator
#Amina Sidhyc
#Roll No. 11

def calculator():
    print("Select Operation")
    print("1. Addition")
    print("2. Subtraction")
    print("3. Multiplication")
    print("4. Division")
    print("5. Modulus")
    print("6. Square")
    print("7. Cube")

    choice = int(input("Enter a choice (1/2/3/4/5/6/7): "))

    if choice in(1,2,3):
        a=int(input("Enter 1st number"))
        b=int(input("Enter 2nd number"))
        c=int(input("Enter 3rd number"))

        if choice==1:
            print(f"The sum of {a},{b} and {c} = {a+b+c}")
        elif choice==2:
            print(f"The difference of {a},{b} and {c} = {a-b-c}")
        elif choice==3:
            print(f"The product of {a},{b} and {c} = {a*b*c}")
        else:
            print("Invalid input")
        
    if choice in(4,5):
        d=int(input("Enter 1st number"))
        e=int(input("Enter 2nd number"))
        if choice==4:
            print(f"The quotient of {d} and {e} = {d//e}")
        elif choice==5:
            print(f"The remainder of {d} and {e} = {d%e}") 
        else:
            print("Check if 2nd number is 0")
        
    if choice in(6,7):
        f=int(input("Enter a number"))

        if choice==6:
            print(f"The square of {f} = {f**2}")
        elif choice==7:
            print(f"The cube of {f} = {f**3}")
        else:
            print("Invalid input")
calculator()
        
