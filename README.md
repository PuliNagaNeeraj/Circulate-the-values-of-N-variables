# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
Step 1:

The code defines a function named circulate.

Step 2:

The program prompts the user to input a list and an integer value 'n' representing the number of positions to circulate.

Step 3:

Get the value from the user for the number of rotation.

Step 4:

Using the slicing concept rotate the list.

Step 5:

The result of the circular rotation is then printed.

Step 6:

Run the program, input a list and rotation value, and observe the rotated list.


## Program:
```
#Program to circulate N values.
#Developed by: Puli Naga Neeraj
#RegisterNumber: 23004033
def circulate():
    list1=eval(input())
    n=int(input())
    result=list1[n:]+list1[:n]
    print('After circulating the values are:',result)
```        
## Output:
![circulate-n-variables](https://github.com/PuliNagaNeeraj/Circulate-the-values-of-N-variables/assets/138849173/0b8de802-9c48-47c4-986b-aa7cbb30b812)

        
## Result:
The program for implementing for circulate the N variables is executed successfully.
