# Lab 7 - Check for Understanding

## 1 Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.
Within a Github action that runs whenever code is pushed to iteratively check if code is up to quality and working, preventing pull requests that might negatively impact the main code.

## 2 Would you use an end to end test to check if a function is returning the correct output? (yes/no)
No, because you use end to end tests to simulate the user experience, not just for simple function

## 3 What is the difference between navigation and snapshot mode?
Navigation mode analyzes when you first open the page and the loading of contents of the page. Snapshot mode analyzes after everything on the page has already loaded. They differ in the different point of times that they measure.

## 4 Name three things we could do to improve the CSE 110 shop site based on the Lighthouse results.
Three things we could improve are serving images in next-gen formats, including a [lang] attribute to html, and including a "viewport" tag with with width or initial-scale to increase performance.


