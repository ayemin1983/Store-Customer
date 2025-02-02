import os, random
os.system('cls')

Customer_Name = input("Customer Name:")
Production = input("Product:")
Quantity = int(input("Quantity:"))
Price= float(input("Price:"))
Total_Amount=Price*Quantity


Customer_Name2 = input("Customer Name:")
Production2 = input("Product:")
Quantity2 = int(input("Quantity:"))
Price2 = float(input("Price:"))
Total_Amount2=Price2*Quantity2

cont = input("Do you want to continue?(y/n):")

if cont != "y":
    print("the process for new customer")
else:
    print("terminate the program")

