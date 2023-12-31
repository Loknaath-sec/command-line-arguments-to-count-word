# Exp-5b-Command line arguments to count word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
1.PC
2.Anaconda - Python 3.7
## ALGORITHM: 
1.Get filename
2.Read the contents
3.Split the text into words
4.Count and print the words

## PROGRAM:
~~~
# Program to find the Word count
# Developed by : P.LOKNAATH
# Register Number : 212223240080
fname=input("Enter the file name : ")
num=0
with open(fname,"r") as f1:
    word_count=f1.read()
    word=word_count.split()
    num=len(word)
print("The number of words are in the file : ",num)

~~~

### OUTPUT:
![5b-i](https://github.com/Loknaath-sec/command-line-arguments-to-count-word/assets/145742558/8f73a348-76ed-4114-98e0-0952dfe0794e)

![5b-ii](https://github.com/Loknaath-sec/command-line-arguments-to-count-word/assets/145742558/8d867de2-8bba-4251-8c74-6c027a2b4b80)
<br/>

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
