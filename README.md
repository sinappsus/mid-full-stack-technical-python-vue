# mid-full-stack-technical-python-vue
This is the official mid level technical test provided for mid level full stack developers focussed on python and vuejs

## Task overview
your task is to create a simple task manager or kanban board.
user story:
the user can register and login to a secure interface where they can define a task and assign it
  -a start and end date
  -select a task type
  -a priority level
  -a status/progress 
  -add additional notes
  -they can also add additional taks types
the user should have another interface where they can manage and organise their tasks - (think basic kanban board again)

# Rules
you must seperate the front end from the backend
Backend must be build using django framework - python
Front end must be build using vuejs - javascript
you may use any additional libraries to support your build
before you begin you must submit your project plan with timeline to jacques@sinappsus.co.za
when completed you will submit a pull request to this repo and send a notification to the same development email address.

# Challanges
there are 3 challanges your code must solve

## Challange 01
provide a project plan with timelines on the above defined task and execute based on this.
## Challange 02
Create a function that takes an array of numbers and return "Boom!" if the digit 7 appears in the array. Otherwise, return "there is no 7 in the array".
Example
sevenBoom([1, 2, 3, 4, 5, 6, 7]) ➞ "Boom!"
// 7 contains the number seven.

sevenBoom([8, 6, 33, 100]) ➞ "there is no 7 in the array"
// None of the items contain 7 within them.

sevenBoom([2, 55, 60, 97, 86]) ➞ "Boom!"
// 97 contains the number seven.

## Challange 03
Create a function that takes two numbers as arguments and adds them together to get a new number. The function then repeatedly multiplies the digits of the new number by each other, yielding a new number, until the product is only 1 digit long. Return the final product.
Example
sumDigProd(0) ➞ 0

sumDigProd(1, 2, 3, 4, 5, 6) ➞ 2
