## Class 21 4/9/26

## Review Questions: 
- for (let i = 0; i <10; i ++>) how many time sodes it run? what's the last value of i inside the loop? 
    - runs 10 times 
    - last value is populates is 9 but it runs 10 
- your friend wrote a loop to sum an array but result is not what we expect?  what's probably wrong? 
        - let total = 0
        - const nums =[10,20,30]
        -{let total = 0; sum += nums[i];}
    - you are reseting the total in every duration b/c let sum second time around restarts it 
- what does for (const item of items) do differently than for (let i=0;....)
    - const is much easier to understand but there is no difference between the two 
    - it's stating for each color in the array called colors 


## Objects 
- can ovreall term for a complex data type (complex as in multiple values)
- ojbects group related data together
- example: 
    const person ={ name : "Alice",
                    age: 25,
                    isStudent: true};

## Intro to API's 
- API : application programming interface 
    - it's a way for programs to talk to each other 
- think of it like a restaurant: 
    - menu (api documentation): shows what you can order 
    - waiter (api): takes your request, brings back food 
    - kitchen (server): prepares what your ordered 

- step 1: you request data
- step 2: server processes request
- step 3: server reponds with data (javascript object notation) 

- JSON: a text format for data
    - keys must be double quotes 
    - values can be : strings, numbers, booleans, arrays, objects, null

- await:  fetching data takes time (network delay)
        - it says "wait here until the data arrives

- three steps: fetch the URL, conver to JSON, use the data

- even if you have a function written below the async, what will populate is the function first then async bc async takes a while to generate 

- await can only be used inside an async function

- always wrap fetch in try/catch: which will catch the code 

- you can have an array of X amounts of objects 