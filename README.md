# Homework-4

###### Exercise 1:

```py
numbers = []

for index in range(10):
    numbers.append(int(input("Enter a number: ")))

up_flag = True
down_flag = True

for index in range(8):
    if (numbers[index] > numbers[index + 1]): 
        up_flag = False
    if (numbers[index] < numbers[index + 1]): 
        down_flag = False

if not (up_flag or down_flag): print("MIXED")
elif (up_flag and down_flag): print("All numbers are equal")
elif up_flag: print("UP")
elif (down_flag): print("DOWN")
```
