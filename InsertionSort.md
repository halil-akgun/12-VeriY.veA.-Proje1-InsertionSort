# Insertion Sort
## [22,27,16,2,18,6]
- ### Write the stages of the given array according to the sort type
1. [**22,27**,16,2,18,6]
1. [22,**16,27**,2,18,6]
2. [**16,22**,27,2,18,6]
2. [16,22,**2,27**,18,6]
2. [16,**2,22**,27,18,6]
2. [**2,16**,22,27,18,6]
2. [2,16,22,**18,27**,6]
2. [2,16,**18,22**,27,6]
2. [2,**16,18**,22,27,6]
2. [2,16,18,22,**6,27**]
2. [2,16,18,**6,22**,27]
2. [2,16,**6,18**,22,27]
2. [2,**6,16**,18,22,27]
2. [**2,6**,16,18,22,27]


- ### Big-O Notation ->O($n^2$)

- ### 18 -> Average case

<br />
<br />

# Selection Sort
## [7,3,5,8,2,9,4,15,6]
- ### Write the stages of the given array according to the sort type
1. [**2**,3,5,8,**7**,9,4,15,6]
2. [2,**3**,5,8,7,9,4,15,6]
3. [2,3,**4**,8,7,9,**5**,15,6]
4. [2,3,4,**5**,6,9,**8**,15,7]
5. ...