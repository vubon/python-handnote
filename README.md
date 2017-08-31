## Welcome to Python Hand Notes

We are trying to help new commer who has no knowledge about Python. If you are a Pythonist. You can also contribute this repository. So don't wait share your knowledge all over in the world.. 

> Knowledge is a shareable object. It helps to increase knowledge, who shares knowledge to everyone.
>  -Vubon Roy


### Short Description about Python
---
Python is scripting, General Purpose, High-Level Programming lanaguage and many more. Python created by [Guido van Rossum](https://en.wikipedia.org/wiki/Guido_van_Rossum)


### Installation 
Firstly you need to install Python software in your machine. Go to Python website [Python.org](https://python.org) 

You can install any OS . So don't worry. 

All right. After install the Python software. You will get IDLE . If you are using Windows machine. Don't worry if you are using Linux machine. you can directly run the Python program via Terminal and also Windows users can run by CMD. 


### Example
---
Let's write a sample example. create a text file and change that text file extension .txt to .py . Suppose your file name is hello.txt then you need to make the file hello.py . Now open your cmd(Windows machine) or terminal(Linux machine) and run below command 

python hello.py 

```
print("Hello World!")
```
N.B. Default Linux machine has Python 2.x version . If you installed Python 3.x version then please run this way 
python3 hello.py

### Control Flow 
---
Python has two types of control flow. 
1. If statement 
2. Loops

### If Statement Structure with Example 

##### Structure
```
if (condition):
  #Do something here
else:
   # also here 

```
If you have more conditions
```
if (condition):
 # Apply your login here
elif (second condition):
# also here 
else: 
# if you have nothing. Do not need to write else statement 
```

##### Example
A basic example of our daily life.
```
if 4 > 3:
  print('Yes, 4 is greater than 3.')
else:
  print('Sorry')

``` 
##### Loops
Python loops basically two types 
1. For Loop
2. While Loop

##### For Loop
 Let's find 1 to 10 sequence 
```
for x in range(1,10+1):
  print(x)

#### Output
1
2
3
4
5
6
7
8
9
10
```
Here x is variable of foor loop and range is a function who defined from where to where need to find . 
