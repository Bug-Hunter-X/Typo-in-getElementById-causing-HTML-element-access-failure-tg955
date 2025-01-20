# Uncommon HTML Bug: Typo in getElementById

This repository demonstrates a subtle bug that can occur in HTML when using JavaScript to manipulate the DOM.  The bug involves a simple typo in the `getElementById` method.

## The Bug

The `bug.html` file contains a typo in the JavaScript code.  Instead of using `document.getElementById()`, it uses `document.getElementByIdx()`, which is incorrect and will result in an error. 

## The Solution

The `bugSolution.html` file demonstrates the correct way to access the div element using `document.getElementById()`.