# PB - Classes - Basics

This task is all about practicing the very basic concepts of classes. Let's practice using the `Date` class that is built into JavaScript!

Add your answers directly into this file.

```js
const now = new Date();
const test = new Date();
```

1. In the code above, what is the `now` variable?

- object

2. What is the type of the `now` variable?

- object

3. In the code above, what is the `Date`?

- class

4. What is the type of `Date`?

- function

5. What do you get when you do `console.log(now)`?

- current date time

6. What do you get when you do `console.log(Date)`?

- [Function: Date]

7. What do you get when you do `console.log(new Date())`?

- current date time

8. Is `now` truthy?
   -yes
9. What do you get when you do `console.log(now === test)`? Why?
   -false Because // two different instances
10. What do you get when you do `console.log(now === Date)`?
    -false // now is an instance, Date is a class
11. What do you get when you do `console.log(now === new Date())`?
    -false // two different instances
12. What do you get when you do `console.log(new Date() === new Date())`? Why?
    -false // two different instances
