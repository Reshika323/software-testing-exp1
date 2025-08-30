# Experiment-1
##  Write programs in Python Language to demonstrate the working of
followingconstructs with possible test cases: a) do…while b) while…do c)
if …else d) switch e) for

## a) Aim
To write python programs for do…while, while, for, switch and if…else and test with possible test
cases.

## Algorithm
1.	Start the program.
2. Create separate files for each given program.
3. Write simple program for each construct.
4. Test the program with possible test cases.
5. Stop the program. 

## Program

## 1.do while:
  ```
   def display():
    start = input("Enter a positive value for START: ")
    end = input("Enter a positive value for END: ")

    if start.isnumeric() and end.isnumeric():
        start = int(start)
        end = int(end)

        while True:
            print(start, end=' ')  # Corrected quote

            if start < end:
                start += 1
            else:
                break
    else:
        print("Enter a valid positive number.")
        display()'
```
## Output:
<img width="1136" height="85" alt="Screenshot 2025-08-30 100330" src="https://github.com/user-attachments/assets/256b8edd-a914-4656-ac8e-bdd9f626536d" />



## while do :

```

start = input("Enter a positive value for START: ") 
end = input("Enter a positive value for END: ") 

if start.isnumeric() and end.isnumeric():
    start = int(start)
    end = int(end)

    while start < end:
        print(start)
        start += 1
else:
    print("Enter a valid positive number.")

```
## Output:
<img width="1138" height="147" alt="image" src="https://github.com/user-attachments/assets/38485a60-0b44-4533-8683-972a19f91f6e" />



## if else:
```

def compare():
    a = input("Enter a value for A: ")
    b = input("Enter a value for B: ")
    
    try:
        a = int(a)
        b = int(b)

        if a > b:
            print("A is greater than B")
        elif a < b:
            print("B is greater than A")
        else:
            print("A is equal to B")
    
    except ValueError:
        print("Enter a valid number.")
compare()
```
## Output:
<img width="1128" height="87" alt="image" src="https://github.com/user-attachments/assets/145f0dce-c1cc-481a-8ff6-101583cbece4" />


## switch:

```
'def switch():
    switcher = {
        0: "even",
        1: "odd"
    }

    n = input("Enter a value for N: ")
    try:
        n = int(n)
        print(switcher[n % 2])
    except ValueError:
        print("Enter a valid number.")
switch()
```
## Output:
<img width="1125" height="66" alt="image" src="https://github.com/user-attachments/assets/667907d3-5277-415b-86f8-dd29630e7065" />


## for:
```
def iterate():
    string = input("Enter a string: ")  
    for i in string:
        print(ord(i), end=" ")

iterate()
```
## Output:
<img width="1122" height="61" alt="image" src="https://github.com/user-attachments/assets/08aebc0c-bb46-4a44-b4e7-f94b2bd85b20" />


## Result
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.



