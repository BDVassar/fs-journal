# Application Architecture, MVC Design Pattern

**1.** What are the Pillars of Object Oriented Programming (`OOP`)?
<!-- enter you answer in the space below -->
```
encapsulation, inheritance, and polymorphism
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
let staffMember = staff.find(s => s.name == property)
```
**3.** What is Encapsulation?
<!-- enter you answer in the space below -->
```
Encapsulation is process by how we structure our code to ensure only pertinent information is available to the end user. 
```
**4.** What does the S stand for in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Single Responsibility 
```
**5.** What the difference between a `class` and an instance of a `class`?
<!-- enter you answer in the space below -->
```
A class is the model we create that we want our objects to look like.
A instance of a class is an object that has been created using the class. 
```
**6.** What is a `Proxy` object?
<!-- enter you answer in the space below -->
```
a Proxy object is one that modifies another object by creating a target and modifying the operation of the target with its own function. 
```

**7.** What is the purpose of the `MVC` pattern?
<!-- enter you answer in the space below -->
```
The purpose of MVC is to separate different operation of a program. It is great for encapsulating information that you do not want the end user to have access too. 
```
**8.** What is the job of the `Controller` in the `MVC` Pattern?
<!-- enter you answer in the space below -->
```
The controller listens for changes on you DOM. It is also responsible for updating the DOM. 
```

**9.** What is the job of the `Service` in `MVC`?
<!-- enter you answer in the space below -->
```
The service is responsible for all of the logic that goes into your program. It is not accessible to you end user. 
```
**10.** What is the job of the `Model` in `MVC`?
<!-- enter you answer in the space below -->
```
The Model is like a blue print for what you want your object to look like. it is also not accessible to the end user. 
```
