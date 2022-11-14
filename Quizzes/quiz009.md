# Quiz009
Create a function that receives as input a string and returns the string ciphered with shift 13.

## Solution
### Code
```.py
string = input("Enter a string: ")
ciphered = ""
def shift13():
    for i in range(len(string)):
        number = ord(string[i])
        if number >109:
            num = number-13
            letter = chr(num)
            print(letter, end = "")
        else:
            num = number+13
            letter = chr(num)
            print(letter, end = "")
    return letter

print(shift13())
```

### Proof of work

<img width="601" alt="Screen Shot 2022-10-20 at 10 07 17 PM" src="https://user-images.githubusercontent.com/113830571/196957200-07e3a43a-3b47-4448-9233-5d1eaeb97d00.png">

