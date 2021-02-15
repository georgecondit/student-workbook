# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?
<!-- enter you answer in the space below -->
```
Keywords are const, var, let. "const" is for variable that will never change. "var" is more 
for declaring globally scoped variables.
```
**2.** What is the definition of a function?
<!-- enter you answer in the space below -->
```
A function is a repeatable instruction that performs and operation based on the information it is given. It uses the keyword function, or is declared as a variable
```
**3.** What are the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Single Responsibility, Open/Closed Principles, Liskov Substitution Principle, Interface Segregation PRinciple, Dependency Inversion Principle. 
  S == A class should have only one responsibility and should only affect only one change to what it acts on.
  O == Open for extention closed for modification
  L == objects in a program should be replaceable with instances of their subtype without changing the correctness of said program
  I == Users should not be dependent on interfaces they don't use
  D == higher level functions should not depend on lower functions, but should depend on abstraction


```
**4.** Given this array: 
```js
let fruit = ['apple', 'banana', 'pineapple',  'orange', 'strawberry']
``` 
What index is the pineapple's current position? How do you know?
<!-- enter you answer in the space below -->
```
Pinapple is in the #2 position. Arrays are zero indexed.

```
**5.** With these two objects: 
```js
let you = { name:"You", hair: true, friends: [] }
let them = { name:"Them", hair: false, friends: [] }
```
how would you .push the `them` object into the `you` object's array of friends?
<!-- enter you answer in the space below -->
```
you.friends.push(them)
```

**6.** Give an example of a JavaScript `Conditional`:
<!-- enter you answer in the space below -->
```
 if(george == finished) { goerge.grade = "passed"}
 else return "failed"
```
**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "______" space? What would you put here to increase `i` by one on every iteration?
```js
for ( let i = 0; i < arr.length; _______ ) {
  //...
```
<!-- enter you answer in the space below -->
```
i++ (this is the incrementor)
```
**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?
<!-- enter you answer in the space below -->
```
Display Object Model. The HTML file is first accessed.
```

**9.** What are the `9` ECMAScript types as defined by MDN?
<!-- enter you answer in the space below -->
```
They are object, array, number, boolean, string, undefined, null, symbol and Nan(not a number). 
```
**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?
<!-- enter you answer in the space below -->
```
A parameter is a name for a variable that is needed by the function or method to work properly, and the argument is the actual value of that variable
```
**11.** What is the difference between a `primitive` value and a `reference` value?
<!-- enter you answer in the space below -->
```
 primitives are declared in a "let" statement. a reference is inside the 
```