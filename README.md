#act-lab 3

def check_number(num):
    if num % 2 == 0:
        print(f"{num} Even yan boi.")
    else:
        print(f"{num} Odd yan boi.")


print("Odd or Even number ba yan kupal!")

try:
    boyet = int(input("ano number gusto mo par: "))
    check_number(boyet)  
except ValueError:
    print("hindi yan kupal.")


    
