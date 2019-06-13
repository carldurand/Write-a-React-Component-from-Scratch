You can use a forEach method to loop through the data since the cat photo objects are held in an array. As you get to each item, you can modify the HTML elements.

First, declare an html variable with var html = "";.

Then, loop through the JSON, adding HTML to the variable that wraps the key names in strong tags, followed by the value. When the loop is finished, you render it.


Your code should store the data in the html variable
Passed
Your code should use a forEach method to loop over the JSON data from the API.
Passed
Your code should wrap the key names in strong tags.