## Class Notes for 3/26 

## Review Questions: 

- wrote "const btn = document.querySelector('button')" but clicking the button does nothing. What line of code is missing? 
        - will need to add the "addEventListener" 

- "document.querySelector('button')" returns NULL, but "button id = 'myButton">" is right there in the HTML. What's wrong? 
        - need to include a # in front of mybutton as it's an id 

- you changed a heading's color in the Console and it worked. After refreshing the page, it's gone. Why? 
        - you aren't changing an files, when using Console it's only temporary 

- What does refresh page do? it sends a request to the original HTML, to the backend 

- You see "onclick = 'doSomething()" in someone's HTML. What's a better way to set up that event in JavaScript, and why? 
        - the preffered method for handling events is "addEventListener" 


## Declaring Variables 

- use "let" for values that change, "const" for values that stay the same

- we are assigning the right side to the left side so x = x + 10 reads as the value of x will be x + 10 

## Variable Naming: 
- Rules: 
    - start with letter, _ , & 
    - no spaces or special characters
    - case sensitive 

## Conventions: 
    - camelCase for variables: userName, totalScore
    - UPPER_CASE for constants: MAX_Size, API KEY 

## Data Types: 
- string
- number (decimals & integers)
- boolean (true/false)
- undefined (no value assigned)
- null (intentionally empty)

## Checking Types: 
- use "typeof" to check what type of value is

- all numbers & letters will be stored as a binary 

## Comparsion Operators 
- always use === (strict equality) in JavaScript to avoid unexpected typer conversaion 

- == means loose equality, converts types
- === means strict equality, on version