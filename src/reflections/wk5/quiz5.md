# Intro to Server side concerns with JavaScript

**1.** What do the letters of the acronym `CRUD` stand for?
<!-- enter you answer in the space below -->
```
Create, Read, Update, & Delete
```
**2.** Each action that `CRUD` represents maps to an HTTP request. What HTTP request does each `CRUD` action correspond to?
<!-- enter you answer in the space below -->
```
.Post = create, .get = read, .edit = update, and .delete = delete. 

```
**3.** What does `ORM` stand for? Which `ORM` do we use when interacting with MongoDB
<!-- enter you answer in the space below -->
```
NOTE ORM stands for Object Relational Mapping. It is used to translate data between incompatible type systems with the use of OOP languages, like Js.
In MongoDB ORM is 
```
**4.** Which two `HTTP` request types include a body?
<!-- enter you answer in the space below -->
```
A post and an edit request both use body in the function. If you want to create an entry you post it, and put is an edit request.
```
**5.** In a/an _______ coding model, when you call a function, it returns only when the action has finished and stops your program for the time the action takes. Likewise in a/an _______ coding model, multiple things are allowed to happen at one time. When you perform an action, your program continues to run.  Fill in the blanks.
<!-- enter you answer in the space below -->
```Synchronuos, Asynchronous
```

**6.** Fill in the missing piece of this snippet of code.
```js
import ______ from "_______"
let Schema = ________.Schema;
```
<!-- enter you answer in the space below -->
```
express express
mongoose
```
**7.** What is middleware?
<!-- enter you answer in the space below -->
```
It is the interface between you and the database. It sets up the protocols and rules for dealing with the database in the 
testing sandbox and in real time usage.
```
**8.** The ______ pipeline delivers information from the client while the ______ pipeline returns it. Fill in the blanks. 
<!-- enter you answer in the space below -->
```
request pipeline, response pipeline
```
**9.** 
Demonstrate the pattern that is used to include a request query with the client's `HTTP` request providing the property `tag` and the value `winter`.
<!-- enter you answer in the space below -->
```
api/christmas/?tag=winter
```