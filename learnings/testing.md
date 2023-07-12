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

## 7. Use CSS grid to create complex layouts

## 8. Use CSS grid to make layouts that adapt to the viewport size
