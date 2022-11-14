# Quiz016
Create a function that produces the output given the input shown
 
## Solution
### Code
```.py
def blackBoxThree(given="hello world")->str:
    output = ""
    count = []
 
    for letter in given.lower():
        if letter.isalpha():
            included = False
            for item in count:
                if item in count:
                    item[1] += 1
                    included = True
                    output += str(item[1])
            if included == False:
                count.append([letter, 1])
        else:
            output += letter
    return output
 
 
first = blackBoxThree("Hello World")
print(first)
second = blackBoxThree("aaaaAABB")
print(second)
third = blackBoxThree("abABabAB")
print(third)
fourth = blackBoxThree("Create a function")
print(fourth)
```
