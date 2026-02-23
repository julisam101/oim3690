# Class Notes 09 - 02/19 

3 Ways to Add CSS: 
- external (recommended)
- internal 
- inline (add style into tag) 

Cascading Style Sheets:
- when it's internal vs external, whichever comes last will have the priority 
- inline will always override internal and external 
- the more partiuclar it is, the more priority it has 

- What if you want only the first two paragraphs one color from the rest? 
        - would give the section a class name 
        - in the CSS folder, you would put p. then the color 

- you can name the class  whatever you want and on the CSS file you can put the color to the class name 

- using ID is more specific than class

- dot for class name 
- hashtag for ID 
- using * will put the elements in the same color, font, size, etc. so everything is universal

- to remove the gaps within the elements, you would use margin 0 

- Selector Specificity
        - from lowest to highest priority

    1. Element selectors: p,div,h1
    2. Class selectors
    3. ID selectors
    4. Inline Styles 

- Colors: 
    - Named colors
    - Hex colors 
    - RGB 

- Typography:
    - font family 
    - ..size
    - ..weight
    - ..style
    - ..align
    
    
- Box Model (shows you how much space it takes) 
    - every element is a box 
            - content: the actual content
            - padding: space inside the border
            - border: the edge
            - margin: space outside the border
