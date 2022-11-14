# Quiz013
Create a function that receives one input and produces the output shown

## Solution
### Code
```.py
def mystery(a:int,b:int)->int:
    result = ((a*b) - (abs(a-b)))
    return result
first = mystery(2,6)
second = mystery(4, 10)
third = mystery(10, 10)
fourth = mystery(70, 50)
print(first)
print(second)
print(third)
print(fourth)
```
### Proof of work

<img width="612" alt="Screen Shot 2022-10-20 at 10 25 15 PM" src="https://user-images.githubusercontent.com/113830571/196961130-9668c095-a076-4b0e-a69d-afa0ba5add1a.png">

