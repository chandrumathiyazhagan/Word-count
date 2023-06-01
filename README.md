# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
Step 1:
Open the file in read mode and handle it in test mood.

Step 2:
Read the text using read() function.

Step 3:
Split the text using space separator.We assume that words in a sentance are separted by a space character.

Step 4:
The length of the split list should equal the numbers of words in the test file.

Step 5:
You can refine the count by cleaning the string prior to splitting or validating the words after splitting.

Step 6:
End the program.
## PROGRAM:
```
Program to count the words in a file
Reg No:212222230026
Name:CHANDRU.M

fname=input("enter the file name:")
num_words=0
with open(fname,'r') as f:
  for line in f:
    words=line.split()
    num_words+=len(words)
print('Number of words:',num_words)
```
### OUTPUT:
![WhatsApp Image 2023-06-01 at 09 20 01](https://github.com/chandrumathiyazhagan/Word-count/assets/119393023/00f45105-cb9e-4b3d-8e8e-a5cb324657e4)



## RESULT:
Thus the program is written to find the word count from a text.
