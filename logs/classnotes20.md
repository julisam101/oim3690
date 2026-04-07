## Class Notes  4/7/2026

## Review Question
- const items = ['a','b','c']. what does items.push['d'] return? What does the array look like after? 
    - it adds the item to the array 
- your friend wrote const colors = ['red','blue']; colors =['green'] and it crashed. Why? How would you add 'green' without crashing? 
    - would use colors.push('green') to incorporate it into the array but if you wanted to change what colors stood for then you would use 'let'
- what is the difference between items.indexOf('x') and items items.includes('x')? When would you use each? 
    - indexOf : returns the position in where the variable is standing in
    - includes: returns true/false
    - there are duplicates in the array, then when using indexOf, it will spit out the first position in which it matches 


## Loops 

- Common Loop Patterns 
    - start with total = 0 then add each element 
- Forward Loop: using iternations to repetite things multiple times 

- for (initialization; condition; afterthought)

- for (let i=0; i<5; i++){
    if (i% == 0)
    console.log(i)} 
    
- use BREAK to exit the loop once you find what you're looking for
- use FOR ... OF when you just need each value
- use class FOR wehn you need the index
