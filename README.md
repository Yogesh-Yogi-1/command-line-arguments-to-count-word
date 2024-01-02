# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Get the file name from the user.
### Step 2: 
Assign num_words equal to 0. 
### Step 3: 
open the file by with open(fname,"r") as f: for handling.
### Step 4:  
Iterate through each line in the file and separate them into words using space('')
### Step 5: 
Find the number of words using num_words+=len(words)
### Step 6: 
End the program by orinting the output.
## PROGRAM:
```
\*
# program to find the word count using command line argument
# Developed by: V. Yogesh
# register number: 212223230250
\*
fname=input("Enter the file name: ")
num_words=0
with open(fname,"r") as f:
  for line in f:
    words=line.split()
    num_words+=len(words)
print("Number of words: ",num_words)
```
### OUTPUT:
![Screenshot 2024-01-02 210345](https://github.com/Yogesh-Yogi-1/command-line-arguments-to-count-word/assets/148514598/b1c76044-248b-417b-aecc-6780e2b08b4f)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
