# Uncommon HTML Bug: Incorrect Access to Element Content

This repository demonstrates a common mistake when working with HTML and JavaScript: incorrectly accessing the content of an HTML element.  The bug arises from attempting to access the element directly without first using `document.getElementById()` or a similar method to obtain a reference to it in the DOM.

The `bug.html` file showcases the erroneous code, while `bugSolution.html` provides the corrected version. The solution emphasizes the importance of using `document.getElementById()` to correctly select the element before manipulating its properties. This is crucial for avoiding runtime errors and ensuring proper functionality.