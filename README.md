# usig-coditio-statement
------------ATM Process-----------------
pin=int(input("enter the 4-digit pin"))
spin=****
balance=12000
if pin==spin:
    print("Access granted")
    withdraw=int(input("Enter Amount"))
    if withdraw>balance:print("isufficiet funds")
    else:
        print("amount withdraw")
        print("available balance",balance-withdraw)
        print("thank you")
else:
    print("Access denaid")
    print("try again")
    print("thank you")
OUTPUT:
enter the 4-digit pin ****
Access granted
Enter Amount 2500
amount withdraw
available balance 9500
thank you
