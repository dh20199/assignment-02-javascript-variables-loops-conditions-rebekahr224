# Reflection

## Question 1 (50 words)
#### When and why should you use a function like `carefulSubract` rather than `subtract`? 

You should use a function like `carefulSubract` rather than `subtract` because it is more specific with what the parameter can be. This way if you account for the parameter to be an integer, then it will be able to complete the function mathematically rather than any other variable that is input.


## Question 2 (100 words)
#### What are `data types`, and how does data typing work in JavaScript? Name at least 4 built-in data JS data types. 
 
Data types in JavaScript include: string, array, boolean, and number etc. A string is comprised of characters that resembles text. An array is a list, which can sometimes contain numbers or other strings. A boolean designates whether something is true or false and allows for the creation of loops. Lastly, a number is a type of numeric date. Data types are essentially building blocks to use within Javascript to get the program to run functions. Data typing in Javascript works by having set structures in the programming language to build other more complex elements within the code to tackle different problems.


## Question 3 (100 words)
#### What is the advantage to storing information as an object (`{firstName: 'Italo', lastName: 'Calvino', profession: 'novelist' }`) rather than as an array (`['Italo', 'Calvino', 'novelist']`)? Are there any disadvantages?
Storing information as an object is advantageous in order to be more specific as to what the variables are being set. It can allow it late complex functions to make things change for specific variables rather than altogether like the array does. The object could also be useful when comparing multiple outputs for these different variables where the variables are specific and carry extra meaning for the outputs. A disadvantage from not using the array would be not being able to use the pop function to remove elements from this list. Instead, object elements would need to be hidden or removed using a different process. 

## Question 4 (150 words)
#### The function `sentences` transforms a data structure (in this case, a list of object literals) into a sequence of sentences. If the data structure were less predictable (e.g., if some properties of each object were occasionally missing, or if their data type was not always the same), what programming techniques could you use to ensure that your function produced a coherent output? Also, can you think of a more interesting "transform" that could be done with the same data structure?

A programming technique that could be used to ensure that a function produced a coherent output given that the data structure were less predictable would be to be to produce a string that would include the parameters plus some helping words to form a sentence. This would be considered less predictable because if the parameter’s input changed in the function then the output would also be changed, but it would still be output in a similar format. Additionally, this coherent output comprised of parameter could also be transformed more interestingly through complex conditional statements. By changing the conditional statements and making them more complex, a sentence could still be formed with less predictable data structures. Lastly, if some properties of each object were occasionally missing, then inside the function would need to be a condition that accounts for the missing properties and returns another message. There are various ways to have the output of a sentence function to return a sequence of sequences; the various types of data structures can make these sentences more or less specific. 
