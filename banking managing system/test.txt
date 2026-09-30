#my banking program
# i want to check merge commit 
<<<<<<< HEAD
balance=500
=======
balance=100
>>>>>>> 27e4b9106d2bc34cfceb079066223ef9a0b9c73c
while True:
    print("-----BANKING MANAGEMENT SYSTEM------")
    print("1. Deposit ")
    print("2. Withdraw ")
    print("3. Check Balance")
    print("4. Exit")

    choice=int(input("Enter Your Choice :"))
    if choice==1:
        amount=int(input("Enter deposit amount :"))
        balance+=amount
        print("Your amount has deposited successfully")
    elif choice==2:
        amount=int(input("Enter  amount you want to withdraw :"))
        if amount<=balance:
            balance-=amount
            print("Amount withdraw successfully")
        else:
            print("Insufficient Balance")
    elif choice==3:
        print("Current Balance :",balance)
    elif choice==4:
        print("Thnak You for Using the banking mangement system")
    else:
        print("Invalid Input")
        print("wrong Input")
        print("test from github")

