# Quiz012
Create a function that receives integer 2<N<10, and returns the multiplication table for the number up to 9.

## Solution
### Code
```.py
def multiplication_2(table=""):
    for i in range(1, 11):
        table += f"{2} * {i} = {2 *i }\n"
    return table
print(multiplication_2())

```

### Proof of work

<img width="600" alt="Screen Shot 2022-10-20 at 10 20 15 PM" src="https://user-images.githubusercontent.com/113830571/196959969-006bea7e-f122-4a29-b318-ae3fea2d292d.png">
