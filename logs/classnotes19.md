## Class Notes 4/2 

## Review Questions: 
- You wrote function getGrade(score) but calling getGrade(85) returns undefined. What's most likely missing inside the function? 
    - you have to make sure there to add a "return" section undernearth the function, b/c without it you aren't calling it
    - you have to use return in order to store the data!! 

- Your function checks if score=60 first, then else if  score >90. What would a student with 95 get? Why? 
    - it will get whatever return the 60 has bc the statement hold as true so it ignores the other options
    - even if you have several "ifs", if there is a return then it will immediately stop the function

What does this arrow function do? const f = x => x **2
    - function square (x) {return x **2} --- mean and does the same thing

- You wrote let username = prompt ("enter your name"); and the user clicked OK without typing anything. Does if (username) run? 
    - yes it does run
    - it's going to show simply hello, with not name 
    - if (! username) : if username does not exist or not not empty then it will either leave it back or if you have a if function then it will populate the name you used 

- ! (xxxx) mean if not that input then....

- AND (&&)
    - when you incorporate this with the other function, the both conditions must be true 
    - AND means that everything must be true, if one thing is false then everything is false

- OR (||)
    - using this means that at least one condition must be true 

- form validation: the user must sent the info in order to follow the rules
- alert: this must be completed before it can proceed 


## Java Arrays 
- an array stores multiple values in a single variable 

- 0 counts as a number, so if you have red, blue, yellow, it reads at 0, 1, 2 
    - it starts at 0 

- Modifying Arrays 
    - push(): adds to the end 
    - unshift(): add to the beginning 
    -- you can change an item, add an item to the end, or add to the beginning 
    - last(): remove from the end
    - first(): remove from the beginning 

- Searching Arrays: 
    - indexOf: finds the index of an item 

- Array vs String
    - string: are immutable (cannot be changed)
    - array: are mutable (can be changed)