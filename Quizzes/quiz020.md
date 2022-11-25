# Quiz020
Create a function that produces the table of Truth for 3 inputs:

# Solution
## Code
<img width="1440" alt="Screen Shot 2022-11-25 at 10 28 29 AM" src="https://user-images.githubusercontent.com/116609563/203882499-c8d74ff7-0223-46d1-8964-3481d9eeacb7.png">


## Testing code 

<img width="264" alt="Screen Shot 2022-11-25 at 10 28 48 AM" src="https://user-images.githubusercontent.com/116609563/203882567-85a7c45e-c34e-4ea1-b4fa-f9739aebc719.png">

## truth table and boolen circuit

<img width="671" alt="Screen Shot 2022-11-25 at 10 29 35 AM" src="https://user-images.githubusercontent.com/116609563/203882636-e486519d-2206-4924-a231-4e2ae43d0573.png">




| S1 | S2 | S3 | S1S2 | not S1 | S3(notS1) | S2+S3(notS1) | (S2+S3(notS1))S1 | S1S2+(S2+S3(notS1))S1 |
|----|----|----|------|--------|-----------|--------------|------------------|-----------------------|
| 0  | 0  | 0  | 0    | 1      | 0         | 0            | 0                | 0                     |
| 0  | 0  | 1  | 0    | 1      | 1         | 1            | 0                | 0                     |
| 0  | 1  | 0  | 0    | 1      | 0         | 1            | 0                | 0                     |
| 0  | 1  | 1  | 0    | 1      | 1         | 1            | 0                | 0                     |
| 1  | 0  | 0  | 0    | 0      | 0         | 0            | 0                | 0                     |
| 1  | 0  | 1  | 0    | 0      | 0         | 0            | 0                | 0                     |
| 1  | 1  | 0  | 1    | 0      | 0         | 1            | 1                | 1                     |
| 1  | 1  | 1  | 1    | 0      | 0         | 1            | 1                | 1                     |
