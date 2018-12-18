# Assignment-2
Python session 2 Assignment
1. Write a program which accepts a sequence of comma-separated numbers from console and
generate a list.

Value = input("input accept a sequence of comma separated delimeter: ")
list = Value.split(",")
print(list)

2. Create the below pattern using nested for loop in Python.

n=5;
for i in range(n):
    for j in range(i):
        print ('* ', end="")
    print('')

for i in range(n,0,-1):
    for j in range(i):
        print('* ', end="")
    print('')
    
3.Write a Python program to reverse a word after accepting the input from the user.

word = input("Input a word to reverse: ")

for char in range(len(word) - 1, -1, -1):
     print(word[char], end="")
     

4. print("WE, THE PEOPLE OF INDIA, \n\thaving solemnly resolved to constitute India into a SOVEREIGN,\n\t\tSOCIALIST, SECULAR, DEMOCRATIC REPUBLIC \n\t\tand to secure to all its citizens")
