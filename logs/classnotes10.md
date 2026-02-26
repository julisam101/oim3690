# Class Notes 2/24/26 

- selector - is where we want to put specific colors 
    - some examples of selectors: element, class, ID, combining 


# Review Questions: 
- You found a website you love. How do you figure out what fonts and colors they're using? 
    - right click, inspect, on the right hand side it generates all the fonts, size, etc. 
    - the section of computed is the final say of waht color, style, box model fit, etc. 

- Your external CSS says h1 { color : blue; } but your headings show up red. What are the possible explanations? 
    - internal CSS comes last
    - inline will always have the highest priority 
    - higher specificity wins as in the selectors 
    - wrong file is linked 

- why do we recommend external CSS files over inline styles, even though inline styles win in specifcity? 
    - easier to read and change 
    - allows you you to apply to different sheets 

Review Selectors: 
- ![alt text](image.png)


- div : will create block containers ( sections, cards, warppers) 
- span: highlights at the specific word

Display Type: 
- Block: 
    - div, p , h1, ul, li
-Inline type: elemts flow side by side, like words in a sentence
    - ex: span, a, strong, img


 - how to display images in the middle: disply : block 
        - put it into a block 

- when adding a hover to it, it hovers over the link and it changes the color to indicate that it's a link