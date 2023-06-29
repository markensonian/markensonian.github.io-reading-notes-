# Programming with JavaScript

## Questions To Answer

What is control flow?

* Order that the computer executes statements in a script. For example, imagine a script used to validate user data from a webpage form. The script submits validated data, but if the user, say, leaves a required field empty, the script prompts them to fill it in. To do this, the script uses a conditional structure or if...else, so that different code executes depending on whether the form is complete or not more or less like:
  
if (isEmpty(field)) {
  promptUser();
} else {
  submitForm();
}

2. What is a JavaScript function?

* Code designed to perform a certain task more or less like // Function to compute the product of p1 and p2

function myFunction(p1, p2) {
  return p1 * p2;
}

3. What does it mean to invoke - or call - a function?

* Run the function.

4. What are the parenthesis () for when you define a function?

* They're to contain the parameters of the function more or less like

function name(parameter1, parameter2, parameter3) {
  // code to be executed
}
