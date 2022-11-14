# Quiz015
There are N closed doors in a school and N students present. The first student opens each door. The second student flips (open⇆close) every second door. The third student flips every third door, and so on. 
[SL]Create a function that shows the doors after 5 students.
 
## Solution
### Code
```.py
def open_doors():
    N = 5
    doors = []
    for n in range(N):
        doors.append(False)
 
    for d in range(1,N+1):
       for student in range(1, N+1):
           if d % student == 0:
               doors[d-1] = not doors[d-1]
               sum = doors.count(True)
 
    print(sum)
 
test1 = open_doors()
 
def open_doors_choice():
    N = int(input("Enter en number"))
    doors = []
    for n in range(N):
        doors.append(False)
 
    for d in range(1,N+1):
       for student in range(1, N+1):
           if d % student == 0:
               doors[d-1] = not doors[d-1]
               sum = doors.count(True)
