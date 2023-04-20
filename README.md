# PB Assessment II

[Google Forms Template](https://docs.google.com/forms/d/1KC1a8XXR6HptGJtdmGsrl4Bis8b7zI1hxpLHbYeuli4/edit)

## Answer the following questions

1.  (multiple choice) We use conditional statements in our code when we want it to perform:

    - [x] different actions based on different decisions
    - [ ] the same action in every situation
    - [ ] a function
    - [ ] all of the above

2.  (multiple choice) The `substring()` method:

    - [ ] outputs a message to the console
    - [ ] checks if a string includes a specific text
    - [ ] joins two or more strings
    - [x] extracts characters from a string between two indices
    - [ ] All of the above

3.  (T/F) JavaScript is a multi-paradigm language.

    - [x] True
    - [ ] False

4.  (multiple choice) What is the final value of `obj` in the following example?

    ```js
    const obj = { foo: 1 };
    obj.bar = 2;
    ```

    - [ ] `[foo = 1], [bar = 2]`
    - [ ] `{bar:2}`
    - [x] `{foo:1, bar:2}`
    - [ ] None of the above

5.  (multiple choice) What is a constructor?

    - [ ] an object created from a class
    - [ ] a factory function
    - [x] a method for creating and initializing an instance of a class
    - [ ] an array method

6.  (multiple choice) Given the object below, how can we know how many properties it contains?

    ```js
    const animal = {
        type: "cat",
        name: "Ruphus",
        color: "orange"
    }
    ```

    - [ ] `animal.length`
    - [ ] `animal.size`
    - [ ] `animal.length()`
    - [x] none of the above

7.  (multiple choice) In the example below, what is `item` at every iteration of the loop?

    ```js
    let letters = ["a", "b", "c"];
    for (let item of letters) {
      console.log(item);
    }
    ```  

    - [ ] the index of an element in the array
    - [ ] a number
    - [x] an element of the array
    - [ ] an object

8.  (multiple choice) What is the maximum number of arguments that we can pass to the callback of the array method `sort`?

    - [ ] 0
    - [ ] 1
    - [x] 2
    - [ ] 3

9. (multiple choice) What is the output of the code below?

    ```js
    const fn = () => {};
    console.log(typeof fn);
    ```

    - [ ] string
    - [ ] object
    - [x] function
    - [ ] integer

10. (multiple choice) What can we use to iterate through the keys of an object?

    - [ ] forEach()
    - [ ] for...of loop
    - [x] for...in loop
    - [ ] while loop

11. (multiple choice) Assuming we have a class called Employee, how do we create an instance of that class?

    ```js
    class Employee {
        constructor(name, salary) {
            this.name = name;
            this.salary = salary;
        }
    }
    ```

    - [x] `new Employee("Jeff Smith", 45000)`
    - [ ] `create Employee("Jeff Smith", 45000)`
    - [ ] `Employee.constructor("Jeff Smith", 45000)`
    - [ ] `instanceof Employee("Jeff Smith", 45000)`

12. (multiple choice) Which method can we use to copy the properties from one object to another?

    - [ ] `copy()`
    - [ ] `Object.copy()`
    - [x] `Object.assign()`
    - [ ] `Object.new()`

13. (multiple choice) What is the output of the code below?

    ```js
    class Vehicle {
      constructor(model, color, year, country) {
        this.model = model;
        this.color = color;
        this.year = year;
        this.country = country;
      }
    }
    let car = new Vehicle('Honda', 'white', '2010', 'UK');
    console.log(car);
    ```

    - [ ] `undefined`
    - [ ] `ReferenceError`
    - [ ] `null`
    - [x] `{model: "Honda", color: "white", year: "2010", country: "UK"}`

14. (multiple choice) We have an array of numbers `[12, 30, 9.99, 74.5, 47]`. Which array method can we use to calculate the sum of the numbers?

    - [ ] `map`
    - [ ] `filter`
    - [ ] `sort`
    - [x] `reduce`

15. (multiple choice) What is the output of the code below?

    ```js
    const animal = {
        type: "cat",
        name: "Ruphus",
        color: "orange"
    };

    console.log(Object.keys(animal));
    ```

    - [ ] ['cat', 'Ruphus', 'orange']
    - [ ] 3
    - [ ] 'type, name, color'
    - [x] ['type', 'name', 'color']

16. (multiple choice) What is a callback?

    - [ ] an array method
    - [x] a function that we pass as an argument to another function
    - [ ] a way to sort arrays
    - [ ] a function that is used inside of a loop

17. (T/F) A function in JavaScript creates a scope for variables declared using let and const.

    - [x] True
    - [ ] False

18. (T/F) The values inside of a `const` array (`const myCities = ['Rome', 'Berlin']`) can be changed. We can push new elements to a `const` array. We can remove elements from a `const` array.

    - [x] True
    - [ ] False

19. (multiple choice) What is the output of the code below?

    ```js
    const animal = {
        type: "cat",
        name: "Ruphus",
        color: "orange"
    };

    console.log(animal.age);
    ```

    - [ ] The property age is not defined
    - [ ] Error
    - [ ] age
    - [x] undefined






