# Quiz021

Using the function that produces the table of Truth for 3 inputs, add a column for the boolean equation
AB+(not B)+(notB C)

# Solution
## Code
<img width="1440" alt="Screen Shot 2022-11-25 at 10 31 07 AM" src="https://user-images.githubusercontent.com/116609563/203882737-ab47cbfd-7efb-44f2-80ff-8c6d87fee76a.png">

## Testing code 

<img width="368" alt="Screen Shot 2022-11-25 at 10 31 35 AM" src="https://user-images.githubusercontent.com/116609563/203882804-51f5a70c-88c4-4bb1-bb35-151947654fab.png">

## truth table and boolen circuit

<img width="673" alt="Screen Shot 2022-11-25 at 10 33 26 AM" src="https://user-images.githubusercontent.com/116609563/203883059-a3a48f9a-cdcb-4a27-8174-a93f648c9884.png">

| W | X | Y | Z | not W | Y(not W) | Z ⊕ Y(not W)| ZW | ZW ⊕ (Z ⊕ Y(not W)) |
|---|---|---|---|-------|----------|--------------|----|------------------------|
| 0 | 0 | 0 | 0 | 1     | 0        | 0            | 0  | 0                      |
| 0 | 0 | 0 | 1 | 1     | 0        | 1            | 0  | 1                      |
| 0 | 0 | 1 | 0 | 1     | 1        | 1            | 0  | 1                      |
| 0 | 0 | 1 | 1 | 1     | 1        | 0            | 0  | 0                      |
| 0 | 1 | 0 | 0 | 1     | 0        | 0            | 0  | 0                      |
| 0 | 1 | 0 | 1 | 1     | 0        | 1            | 0  | 1                      |
| 0 | 1 | 1 | 0 | 1     | 1        | 1            | 0  | 1                      |
| 0 | 1 | 1 | 1 | 1     | 1        | 0            | 0  | 0                      |
| 1 | 0 | 0 | 0 | 0     | 0        | 0            | 0  | 0                      |
| 1 | 0 | 0 | 1 | 0     | 0        | 1            | 1  | 0                      |
| 1 | 0 | 1 | 0 | 0     | 0        | 0            | 0  | 0                      |
| 1 | 0 | 1 | 1 | 0     | 0        | 1            | 1  | 0                      |
| 1 | 1 | 0 | 0 | 0     | 0        | 0            | 0  | 0                      |
| 1 | 1 | 0 | 1 | 0     | 0        | 1            | 1  | 0                      |
| 1 | 1 | 1 | 0 | 0     | 0        | 0            | 0  | 1                      |
| 1 | 1 | 1 | 1 | 0     | 0        | 1            | 1  | 1                      |
### Boolen circuit for ZW ⊕ (Z ⊕ Y(not W))
