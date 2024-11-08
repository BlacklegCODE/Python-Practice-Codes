# user input manipulation practice

#assignment for user input :

a = input("Enter username :")


if len(a) > 12:
    print("Username must be less than 12 digits !!")
elif not a.find(" ") == -1:
    print("Username must not contain spaces !")
elif not a.isalpha():
    print("It cant have digits !!")
else:
    print(f"Welcome {a} !!")
