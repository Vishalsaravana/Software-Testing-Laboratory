# Ex.No: 1 Write programs in Python Language to demonstrate the working of followingconstructs with possible test cases: a) do…while b) while…do c) if …else d) switch e) for 

### DATE: 24-09-2024                                                                          
### REGISTER NUMBER : 212222040181

### AIM:  
To write python programs for do…while, while, for, switch and if…else and test with possible test 
Cases 

### Algorithm:
1. Start the program.
2. Create separate files for each given program.
3. Write simple program for each construct.
4.  the program with possible test cases.
5. Stop the program.
### Program:

### i.)do…while: 

```
def display():
     start=input("Enter a positive value for START: ")
      end=input("Enter a positive value for END: ")
      if start.isnumeric() and end.isnumeric():
        while True:
            start=int(start)
            end=int(end)
            print(start,end=‘ ‘)
            if start<end:
                start+=1
            else:
                break
      else:
        print("Enter a valid positive number.") 
  display() 
```

### ii.) while…do 

```
start=input("Enter a positive value for START: ") 
end=input("Enter a positive value for END: ")
if start.isnumeric() and end.isnumeric():
     start=int(start)
     end=int(end)
     while start<end:
          print(start)
          start+=1
else:
   print("Enter a valid positive number.")

```

### iii.) switch 

```
def switch():
    switcher={
 0:"even",
  1:"odd"
}
n=input('Enter a value for N: ') try:
  n=int(n)
  print(switcher[n%2])
except ValueError:
   print("Enter a valid number.")
switch() 

```

### iv.) if else

```
def compare():
  a=input("Enter a value for A: ")
  b=input("Enter a value for B: ")
  try:
     a=int(a)
     b=int(b)
     if a>b:
        print("A is greater than")
     elif a<b:
        print("B is greater than")
     else:
        print("A is equal to B")
  except ValueError:
        print(“Enter a valid number.”) 

```

### v.) for

```
def iterate():
    string=input("Enter a string: ") for
    i in string:
       print(ord(i),end=" ")
iterate() 
```














### Output:

### i.)do…while: 
```
Positive numbers
Enter a positive value for START: 1
Enter a positive value for END: 4
1 2 3 4 

Negative numbers
Enter a positive value for START: -10
Enter a positive value for END: 5 Enter
a valid positive number. 

Character and string input
Enter a positive value for START: hello
Enter a positive value for END: y
Enter a valid positive number. 

Null input
Enter a positive value for START:
Enter a positive value for END:
Enter a valid positive number. 
```


### ii.) while…do 
```
Positive numbers
Enter a positive value for START: 1
Enter a positive value for END: 4
1 2 3 4 


Negative numbers
Enter a positive value for START: -10
Enter a positive value for END: 5 Enter
a valid positive number. 


Character and string input
Enter a positive value for START: abc
Enter a positive value for END: 100
Enter a valid positive number. 


Null input
Enter a positive value for START:
Enter a positive value for END:
Enter a valid positive number. 


```


### iii.) switch 
```
Positive numbers
Enter a value for N: 1
odd

Negative numbers
Enter a value for N: -10
even


Character and string input
Enter a value for N: hello
Enter a valid number.


Null input
Enter a value for N:
Enter a valid number. 

```

### iv.) if else
```

Positive numbers
Enter a value for A: 1
Enter a value for B: 1
A is equal to B.


Negative numbers
Enter a value for A: -10
Enter a value for B: 5 B
is greater than A.


Character and string input
Enter a value for A: hello
Enter a value for B: y
Enter a valid number.


Null input
Enter a value for A:
Enter a value for B:
Enter a valid number. 
```


### v.) for 
```
Characters
Enter a string: say
115 97 121

Number
Enter a string: 1543
49 53 52 51

Null input
Enter a string: 
```




### Output:

![dowhilecode](https://github.com/user-attachments/assets/2b195db1-81d9-435e-a0c0-0b53353a6a33)![dowhileres](https://github.com/user-attachments/assets/61b0b908-0e0f-41fe-b625-6efdeeb235c4)
![forcode](https://github.com/user-attachments/assets/d05d8866-8ff9-40c2-8761-0f2e5b7bc877)![forres](https://github.com/user-attachments/assets/a21a4ba0-01ad-4eaa-8589-ab5046401f97)
![ifelsecode](https://github.com/user-attachments/assets/27858ca9-92dc-4839-af2e-4ab21f8f7667)![ifelseres](https://github.com/user-attachments/assets/1dd819ed-072d-4385-90da-9f9778a9ad1f)
![switchcode](https://github.com/user-attachments/assets/3a9f279e-9adc-4073-b183-72a3081df314)![switchres](https://github.com/user-attachments/assets/5f89c54b-b1e1-41c1-aad6-ae139d8c2ce5)
![whiledocode](https://github.com/user-attachments/assets/39284c95-b0a9-4d84-8110-d420a8e4cf25)![whiledores](https://github.com/user-attachments/assets/1208a77f-d828-4997-b58f-a0d5cd331e92)
