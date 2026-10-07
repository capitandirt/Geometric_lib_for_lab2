# Description for Geometric lib  

## A general description  

**geometric lib** is a small pack of obvious functions related to flat figures  
like triangles, squares, circles and rectangles

## Function description  

### Circle functions ○
[Example](#circle)  

`def area(r)` returns area of circle and depends on its radius   
`def perimeter` returns length of a circle edge, depends on its radius  

### square functions □  
[Example](#square)  

`def area(a)` returns area of a square  
`def perimeter(a)` returns perimeter of a square   

### rectangle functions ▭   
[Example](#rectangle)  

`def area(a, b)` returns area of a rectangle by multiplying length and width  
`def perimeter(a, b)` returns perimeter of a rectangle and depends on its width and height  

### triangle functions △  
[Example](#triangle)  

`def area(a, h)` returns area of a triangle by formula ***S = a * h / 2***  
`def perimeter(a, b, c)` returns perimeter of a triangle by summing up all given sides  

## function call examples  

### circle
area(2) -> 12.566370614359172  
perimeter(3) -> 18.84955592153876  

### square  
area(17) -> 289  
perimeter(6) -> 24  

### rectangle  
area(9, 3) -> 27  
perimeter(2, 14) -> 32  

### triangle
area(10, 3) -> 15  
perimeter(3, 4, 5) -> 12  

## project history  
07.10.2026 first commit with added documentation for functions and this file  