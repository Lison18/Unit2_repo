# Quiz011
Create a function that shows the days of your birthday’s month for the year 2022.

## Solution
### Code
```.py
def powerTen(number: int) -> str:
    """..."""
    lenght_msg = 20
    units = ["unit", "kilo", "mega", "giga", "tera"]
    out = ""
    for power in range(5):
        number = f"{number} {'0'*(3*power)}"
        out += f"{number} {units[power]}\n"
    return out

test1 = powerTen(1)
print(test1)``
```
### Proof of work

<img width="704" alt="Screen Shot 2022-10-20 at 10 13 46 PM" src="https://user-images.githubusercontent.com/113830571/196958569-dde52116-d78e-4233-b5f5-76f94aaada74.png">

