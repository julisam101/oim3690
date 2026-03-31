## Class Notes 3/31 

## Review Questions: 

- DOMCotentLoaded: this will do everything afterwards 
- You wrote const=total = price + tax and got 1005 instead of 15. What happened and how do you fix it? 
    - price was set to 10 
    - tax was set to 05 
    - the inputs were put as string and so they need to be changed to integers! 
    - "paseFloat" converts numbers that are in string into numbers integers 
- Your code has const counter = 0 and later counter = counter + 1. It crashes. Why and what's the one-worded fix? 
    - would have to use "let" b/c if you expect the variable to change in the future then use LET 
- Rewrite template: "hello" + "name" + "! you have" + "count" + "items" 
    - $$ one of those are for the holder
- Why does 5 == 5 true but 5 === "5" returns false? 
    - == : just checks the value 
    - === : checks the value & the types 

## Function: 

- function is a reusable block of code that performs a task
        - can use the same function without having to continuing rewriting it, once its establish you can simply use it 

- by adding values/parameters, we are making our code more functional 

- " function greet (name)
        console.log ('Hello, ${Name}!') 
               - OUTPUT  -> Hello, Charles! 
              - name is the parameter and then it's acting as a placeholder
              - input is charles, output is hello charles 
              - we are taking 'Charles' and replacing it 

- console.log : just prints out results 
- return: you want to hold results and want to use it later --> use it when you think the output will be resuable 

## Conditions: 

- conditions let your code makes decisions 
- ** once the condition finds it's "place" in the list of if else conditions, then anything below it gets "ignored" it no long reads it 

- if ....
    - else...
- if... 
            - the code will read this as two separate blocks and it would return both values b/c the third line doesn't have the else 