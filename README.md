#Project made by ***Iordache Christian Andrei***
#Project made at date of 23/01/2024
#Questions at e-mail addrres : iordache.christian.andrei@gmail.com
#Github:chrand267
#Arduino Project Hub:iftechspeaks
#Project language is Romanian
#Project in English on Github



def calculator():
    operatie = input("Alege operația (+, -, *, /): ")
    numar1 = float(input("Primul număr: "))
    numar2 = float(input("Al doilea număr: "))

    if operatie == '+':
        rezultat = numar1 + numar2
    elif operatie == '-':
        rezultat = numar1 - numar2
    elif operatie == '*':
        rezultat = numar1 * numar2
    elif operatie == '/':
        rezultat = numar1 / numar2
    else:
        print("Operație invalidă.")
        return

    print(f"Rezultatul: {rezultat}")

calculator()
