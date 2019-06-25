## Prerequisites
* Programming fundamentals assignments about data types, variables, conditionals, functions, collections, iteration
* Programming fundamentals assignments about OOP
## Exercise
Create a `Location` class with a `name`.

Create a `Trip` class with a list of `Location` instances (called `stops` or `destinations` or something similar). Define a method that lets you add locations to the trip's list of destinations.

Make several instances of `Location`s and add them to an instance of `Trip`.

Define a method in the `Trip` class that iterates through the list of locations and prints something similar to the following:
```
"Began trip."
"Travelled from Toronto to Ottawa."
"Travelled from Ottawa to Montreal."
"Travelled from Montreal to Quebec City."
"Travelled from Quebec City to Halifax."
"Travelled from Halifax to St. John's."
"Ended trip."
```