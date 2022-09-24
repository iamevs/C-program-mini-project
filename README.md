## C program Mini project
A mini project - University/College simple voting system using file handling.

<hr>

## Code-Overview

## Files

1. ELECTION.h
2. Main.c
      
## Election.h

<p>A header file that includes all the function which will the main.c file needs to access.</p>

## Main.c

<p>The main file to excutite all the functions accordind to the users input.</p>

<hr>

## Instalization

1. Clone this repository 

``` 
git clone https://github.com/iamevs/C-program-mini-project.git
```

2. locate to the folder where the repo extracted

3. comple and run the C program

#### Compile

```
gcc main.c -o election
```

#### Run

```
.\election.exe
```

## Explanation 

At first when compiling and run the program you will able to see the out as to choose the options like <br>

1. Student
2. Admin 
3. Exit

### Initate the Election

 1. Enter the option as 2 and go ahead to the admin pannel <br>
 
 ``` 
 Username is Admin
 Password id admin
 
 Note : It is case sensitive
 ```
 
 2. After a successfull Login choose the option to initate the election. (Option 1)
 
 3. Enter the Year of election, The last two digits of the year will be the First two digits of the student's roll number.

 ```
 Year : 2022  

 Student's roll number : 22XXXXXX.
 ```
 
 4. Enter the Branch Code, This Branch code should be of three characters. So this three characters will be the next three of the student's roll number.
 
 
 ```
 Branch code : MBA   
 
 Student's Roll number : 22MBAXXX.
 ```
 
 
 5. Enter the Total number of students, so by this number will be the remaining of the student's roll number.
 
 
 ```
 NO.of students : 127
 
 Student's roll number : 22MBA001 to 22MBA127
 ```

 6. Enter the number of candidates, and enter their datails and Logout from the admin pannel.
 
