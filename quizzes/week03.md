# Application Architecture, MVC Design Pattern

**1.** What are the Pillars of Object Oriented Programming (`OOP`)?
<!-- enter you answer in the space below -->
```
Abstraction
Encapsulation
Inheritance
Polymorphism
```
**2.** How would you access the `name` of the below object using the `property` variable?
```js
let staff = {
  name: "Tim",
  age: 26,
  job: "Code Monkey"
  }
let property = 'name'
```
<!-- enter you answer in the space below -->
```
staff[property]
```
**3.** What is Encapsulation?
<!-- enter you answer in the space below -->
```
this is to encapsulate variable and code acting on data method together as one. from here cannot be accessed from anywhere but its current class
```
**4.** What does the S stand for in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Single-responsibility principle. every class should have one responsibility.
```
**5.** What the difference between a `class` and an instance of a `class`?
<!-- enter you answer in the space below -->
```
a class: object properties and values.
Instance contains data and behavior  described by the class and also an object itself.
```
**6.** What is a `Proxy` object?
<!-- enter you answer in the space below -->
```
 this is an object that allows you to create and object used in the place of the original object.this happens in the service pattern.

 example:
 const CreatureService = new CreatureService 

```

**7.** What is the purpose of the `MVC` pattern?
<!-- enter you answer in the space below -->
```
the purpose for mvc a pattern for software design to help implement user interfaces, controlling logic and data. it shows and emphasizes the separation between the business logic and display.
```
**8.** What is the job of the `Controller` in the `MVC` Pattern?
<!-- enter you answer in the space below -->
```
the controller is for users to draw information to the dom
```

**9.** What is the job of the `Service` in `MVC`?
<!-- enter you answer in the space below -->
```
the service is the business logic. when you need to modify data, that happens here.
```
**10.** What is the job of the `Model` in `MVC`?
<!-- enter you answer in the space below -->
```
the job for Model in MVC is to model what your project or app should look like to base from there. No information is stored here.
```
