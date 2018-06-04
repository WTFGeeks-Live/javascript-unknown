**Day 5: Inheritance** <br>

**Task**<br>

We provide the implementation for a *Rectangle* class in the editor. Perform the following tasks:

1. Add an *area* method to *Rectangle*'s prototype.
2. Create a *Square* class that satisfies the following:
	- It is a subclass of *Rectangle*.
    - It contains a constructor and no other methods.
    - It can use the *Rectangle* class' *area* method to print the area of a *Square* object.
    
Locked code in the editor tests the class and method implementations and prints the *area* values to STDOUT.

<br>**Day 5: Template Literals**<br>

**Task**

The code in the editor has a tagged template literal that passes the area and perimeter of a rectangle to a tag function named *sides*. Recall that the first argument of a tag function is an array of string literals from the template, and the subsequent values are the template's respective expression values. 

1. Finds the initial values of s<sub>1</sub> and s<sub>2</sub> by plugging the *area* and *perimeter* values into the formula:
	![self explanatory](https://raw.githubusercontent.com/WTFGeeks-Live/javascript-unknown/master/Day%205/formula.png) 
<br>where A is the rectangle's area and P is its perimeter.<br>
2. Creates an array consisting of s<sub>1</sub> and s<sub>2</sub> and sorts it in ascending order.<br>
3. Returns the sorted array.<br>
