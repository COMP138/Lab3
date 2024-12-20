# Pick Activity

# Goal
Gather input from the user and then suggest an activityGather input from the user and then suggest an activity based on the temperature and whether or not it is raining

```
TEMPERATURE     IS RAINING?               ACTIVITY CHOSEN
>= 80              no                      play volleyball
>= 80              yes                     see a movie
<80 and >=32       no                      go running
<80 and >=32       yes                     try yoga
<32                yes or no               read a book
```

# Steps
1. Initialize a variable called isRaining to a default value of boolean False using the bool() function

2. Initialize a variable called userResponse to a default string value of "no" using the str() function

3. prompt the user for the temperature using input(), then store the integer result in a variable called temp using input() and int()

4. prompt the user if it is raining "yes or no"

5. use the input() function to collect a response from the user and assign that response to a variable called userResponse

6. if userResponse is equal to "yes" then change the value of isRaining to True, else change the value of isRaining to False

7. Use if elif else "logic chains" to suggest and print an activity based on the variables temp and isRaining variables, using the table above


# HINTS
- When you collect input, if you want it to be an intger, you must also use int() like this:
```
print ("give me an integer! ")
myInteger = int( input() )
print( "you entered: ", myInteger )
```
- you can also combine these two statements in one like this:
```
myInteger = int( input("give me an integer! ") )
print( "you entered: ", myInteger )
```

# Concepts Covered
- Using print() to print a message
- Using input() to collect a response from a user
- converting the string type return value of the input() function to an integer
- Assigning the string type return value of the input() function to a variable
- Setting a boolean value to True or False using a "if else" statement
- Building an "if elif else" logic chain based on two different variables
