JSON APIs and Ajax: Get JSON with the JavaScript XMLHttpRequest Method
You can also request data from an external source. This is where APIs come into play.

Remember that APIs - or Application Programming Interfaces - are tools that computers use to communicate with one another. You'll learn how to update HTML with the data we get from APIs using a technology called AJAX.

Most web APIs transfer data in a format called JSON. JSON stands for JavaScript Object Notation.

JSON syntax looks very similar to JavaScript object literal notation. JSON has object properties and their current values, sandwiched between a { and a }.

These properties and their values are often referred to as "key-value pairs".

However, JSON transmitted by APIs are sent as bytes, and your application receives it as a string. These can be converted into JavaScript objects, but they are not JavaScript objects by default. The JSON.parse method parses the string and constructs the JavaScript object described by it.


our code should create a new XMLHttpRequest.
Passed
Your code should use the open method to initialize a "GET" request to the freeCodeCamp Cat Photo API.
Passed
Your code should use the send method to send the request.
Passed
Your code should have an onload event handler set to a function.
Passed
Your code should use the JSON.parse method to parse the responseText.
Passed
Your code should get the element with class message and change its inner HTML to the string of JSON data.