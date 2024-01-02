# Command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Prompt the user to enter the filename and store it in the variable filename .
### Step 2:
Open a python file using with statement.
### Step 3:
Read the file in a variable called 'a'
### Step 4:
Use split statement to seperate the contents given in the file and store it in a variabe called 'b'
### Step 5:
print len(b) to get the word count.
## PROGRAM:
```
'''
Program to find the Word Count using command line arguments
Developed by: Vikaash K S
Register Number: 23013426
'''
filename=input("Enter filename:")
with open(filename,"r") as file:
   a=f.read()
   b=a.split()
print("Number of words in file:",len(b))
```
### OUTPUT:
![exp 5b op](https://github.com/Vikaash19/command-line-arguments-to-count-word/assets/148514589/5b4a3b12-c7e5-45bc-b9e8-e4f2f48b931e)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
