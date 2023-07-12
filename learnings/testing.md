# testingProject: Bullet Journal

A to-do list application, in the style of a bullet journal, built using test driven development.

All Founders and Coders projects are collaborative between two people. My partner for this project was Dylan Cobb.

View web page here: https://georgeklemperer.github.io/bulletJournal/.

## 1. Check that passing a given input into our tests returns the expected output

<img width="100%" alt="image" src="https://github.com/GeorgeKlemperer/george-portfolio/assets/124908931/74dbb78e-76ca-4871-bd8a-556de8f179ab">

We used the above functions as a testing framework to compare actual and expected results. Below is an example of a test utilising the equal function:

<img width="100%" alt="image" src="https://github.com/GeorgeKlemperer/george-portfolio/assets/124908931/c3e8b2a0-09fd-40c4-974f-785ac9eb2e30">

The actual and expected results can be viewed in the console log as in the screenshot below:

<img width="100%" alt="image" src="https://github.com/GeorgeKlemperer/george-portfolio/assets/124908931/669a4d1b-cd5f-4c5b-ae6d-85d828a1e8b6">


## 2. Write tests to mimic the behaviour of a user performing different actions

This below integrated test simulates a user adding multiple tasks:

<img width="100%" alt="image" src="https://github.com/GeorgeKlemperer/george-portfolio/assets/124908931/02255326-464a-494f-b90f-6f1c33a4b5e6">

## 3. Write testable, modular functions

All functions were written in a testable modular format. For example:
<div align='center'>
<img width="567" alt="image" src="https://github.com/GeorgeKlemperer/george-portfolio/assets/124908931/5cc54a59-f302-4dfa-98d0-75c5c4886721">
</div>

## 4. Write functions that add, remove or modify DOM nodes
The addItemUsingTemplate() function clones a html <template> and appends it to the to-do list when the user submits a task.<br>

<img width="100%" alt="image" src="https://github.com/GeorgeKlemperer/george-portfolio/assets/124908931/f8813212-33c7-4be6-9659-b6ef2e6e546f">

## 5. Apply event listeners to HTML form elements

the above addItemUsingTemplate() function also adds event listeners to to-do list tasks that enable them to be striked through or crossed off.

## 6. Use scope to control what variables are accessible inside functions and blocks

We delineated a number of global variables, so that they could be accessed by different functions. Meanwhile, other varables were made specific to functions, so local in scope, by being declared inside the functions. 

## 7. Use CSS grid to create complex layouts

CSS grid was used to precisely layout the layouts elements. This was especially required so that the to-do list tasks would be written exactly between the bullets, like in a real bullet journal.

<img width="100%" alt="image" src="https://github.com/GeorgeKlemperer/george-portfolio/assets/124908931/2b4c4fb1-63b9-4689-9910-236207973915">

This is the result:

<img width="100%" alt="image" src="https://github.com/GeorgeKlemperer/bulletJournal/assets/124908931/10f8f4f5-ecd5-4e80-a13f-ff93ecef6581">

## 8. Use CSS grid to make layouts that adapt to the viewport size

@media queries were used to make the application responsive for mobile phones.

<div align=center>
<img width="533" alt="image" src="https://github.com/GeorgeKlemperer/george-portfolio/assets/124908931/3537a275-184d-45b7-8af1-b6be54e0633b">
</div>

This is the result:

<div align=center>
<img width="408" alt="image" src="https://github.com/GeorgeKlemperer/george-portfolio/assets/124908931/be6dd50a-73f3-4102-882e-a029e2f2cc4b">
</div>

