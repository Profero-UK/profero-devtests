# JavaScript // Mid Weight Developer // Test 1 #

### Test Overview ###

Implement the functions outlined in index.html using the script.js file for your implementations.

#### OO Javascript ####

Firstly you'll need to implement a JavaScript class (using vanilla JavaScript only), that 
allows the following code to work:

		var dog = new petshop.Dog( "Fido" );
		console.log( dog.speak() );
	
The Dog class should expect a name variable when instantiating the object, it should store this value
and should also implement a 'speak' function that returns a string saying "Woof! My Name is: <name>" 
e.g: "Woof! My Name is: Fido". The Dog Class should belong to a global namespace named 'petshop', 
ensuring the class implementation does not conflict with any other classes.

##### Bonus Points ######

* Implement JSDoc compliant documentation
* Implement the module pattern to wrap and allow dependencies to be passed to your class
* Create a second class extending the dog class to a breed of dog (i.e West Highland Terrier) and override the speak function to say something else i.e: "Woof! Me name is <name> and I'm a Westy"

#### Algorithms ####

Secondly, you'll need to implement a JavaScript sort method (again using vanilla JavaScript only),
that sorts an array into numerical order.

The function 'sortArray' has already been implemented in the script.js file, the task is to complete 
this function so that the array is properly sorted and returned.

##### Bonus Points ######

* Instead of using Javascript's .sort method, implement a design pattern and explain why you chose it.
* Build a sorting function that can sort strings as well as integers

### Expected Response ###

You should provide 2 source files, index.html & script.js, as well as a README.md file outlining your approach.