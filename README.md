# Pick Activity

# Goal
Gather input from the user and then suggest an activity

```
TEMPERATURE     IS RAINING?     ACTIVITY CHOOSEN
>= 80              false             play vollyball
>= 80              true              see a movie
<80 and >=32       false             go running
<80 and >=32       true              try yoga
<32                true or false     read a book
```

# Steps

1. Use cout to ask the user for the current temperature
    - Store their response in an integer variable in main()
2. Use cout to ask the user if it is raining (yes or no)
    - Store their response in a string variable in main()
    - (assume the user will only ever enter "yes", otherwise assume "no")
3. Based on their answers, suggest an outdoor activity based on the table shown below
    - Use if / else chains to select the correct activity and print it for the user
4. TEST!  Be sure to test your code with every combination possible to verify that it prints the correct result

# Considerations
- What other variables will you need? (will you need to convert their response to a boolean? )
- Have we covered every possible case?  why/why not?
- Is there more than one way to develop the logic using if/else chains?

