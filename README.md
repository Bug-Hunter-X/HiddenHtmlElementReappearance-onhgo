# Hidden HTML Element Bug

This repository demonstrates a common yet easily missed bug in HTML.  An element is hidden using JavaScript, but there's no mechanism to show it again, leading to a persistent visual error.

## Bug Description

The `bug.html` file contains a simple HTML structure with a div and a button.  Clicking the button hides the div using JavaScript's `style.display = "none";`. However, there is no provision to reverse this action, leaving the div permanently hidden.

## Solution

The `bugSolution.html` file corrects the issue by adding a mechanism to restore the visibility of the div.  This demonstrates a simple, effective solution to a common coding oversight.

## How to reproduce the bug:
1. Open `bug.html` in your browser.
2. Click the button.  Observe that the div disappears and does not reappear.

## How to use the solution:
1. Open `bugSolution.html` in your browser.
2. Click the button. Observe that the div disappears.
3. Click the button again. Observe that the div reappears. This demonstrates the correct way of managing the visibility of HTML elements.