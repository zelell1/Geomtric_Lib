# Geometric_lib
```
This library implemented methods for finding the perimeter (length for a circle) and area for 4 geometric figures. For this purpose, 4 files were created for each shape: triangle, square, rectangle and circle. Each of them has functions for finding perimeter (length for a circle) and area.
```
# Math formulas
## Area
- Circle: S = πR²
- Rectangle: S = ab
- Square: S = a²
- Triangle: S = (ah)/2


## Perimeter
- Circle: P = 2πR
- Rectangle: P = 2a + 2b
- Square: P = 4a
- Triangle: S = a + b + c

# Description of the functions
##    1. Circle.py
       - Area
         - def area(r)
            r(radius): float, int
            area(r) -> float: area(4) ~ 50.2654824574
       - Perimetr
         - def perimetr(r)
            r(radius): float, int
            perimetr(r) -> float: perimetr(4) ~ 25.1327412287
##    2. Triangle.py
       - Area
         - def area(a, h)
            a(base): float, int
            h(height): float, int
            area(a, h) -> float, int: area(4, 5) = 10
       - Perimetr
         - def perimetr(a, b, c)
            a: float, int
            b: float, int
            c: float, int
            perimetr(a, b, c) -> float, int: perimetr(3, 4, 5) = 12
##    3. Square.py
       - Area
         - def area(a)
            a: float, int
            area(a) -> float, int: area(5) = 25
       - Perimetr
         - def perimetr(a)
            a: float, int
            perimetr(a) -> float, int: perimetr(6) = 24
##    4. Rectangle.py
       - Area
         - def area(a, b)
            a: float, int
            b: float, int
            area(a, b) -> float, int: area(5, 11) = 55
       - Perimetr
         - def perimetr(a, b)
            a: float, int
            b: float, int
            perimetr(a, b) -> float, int: perimetr(22, 49) = 142

        

# Grapgh of commits
```bash
    * cb15eb1 (HEAD -> main) comments_for_functions
    * 9c16267 fix_rectangle&adding_triangle
    * 171c226 new_rectangle
    | * 86edb1c (origin/release) L-05: Update Docs. Add user agreement info
    | * 438b89a L-05: Add user agreement
    | * 6adb962 L-03: Docs added
    | | * 3049431 (origin/feature) L-04: Add rectangle.py
    | |/  
    |/|   
    | | * b5b0fae (origin/develop) L-04: Update docs for calculate.py
    | | * d76db2a L-04: Add calculate.py
    | | * 51c40eb L-04: Doc updated for triangle
    | | * d080c78 L-04: Triangle added
    | |/  
    |/|   
    * | d078c8d (origin/main, origin/HEAD) L-03: Docs added
    |/  
    * 8ba9aeb L-03: Circle and square added
```
