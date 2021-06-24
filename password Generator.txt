#importing necessary modules:-
import random
import string

#Greeting the user:-
print("Hello, Welcome to Random Password Generator\n")

#Asking password length:-
length=int(input("Enter password length - "))

#Creating password:-
all = string.ascii_letters + string.digits + string.punctuation
pwd = "".join(random.sample(all,length))

#Printing password:-
print("Your ",length," character password is -",pwd)