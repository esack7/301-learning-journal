# Day 10
## Code Fellows 301 Learning Journal

I was quite content today as I feel that my understanding, as a general term, of the server finally fell into place. I do find the SQL Database facinating and would like to learn more. I also like the new syntax of the arrow functions, but it might take me a bit to get used to it.

## Lecture Notes

* Declarative Programming - Creates clean, readable code.  Not imparative. It is functional programming.
* Imparative Programming - Step by step programming (good for teaching and understanding the logic
* Mutability -
* Immutability - It's best not to mutate a value in your code.

* Pure functions and higher order functions.  Pure function is a function that takes in an immutable value, copy it and then return the modified copy.

* Arrow function - no global scope inside.

	- doctors.forEach(function(ele, idx, arr) {
	  //this is in local scope
	  })

	- doctors. forEach((ele, idx, arr) => {
	  // this => refers to the global scope
	  })

	- if function only has one parameter, you don't have to use parenthesis.
		doctors.filter(ele => {

		})

* Using an immutable function, you need to "return" the new data.

* forEach, filter, map, and reduce should replace all need for 'for' loops.

* reduce is kind of the catch all function
		.reduce((acc,curr) => acc + curr, 0)

* Number constructor is a function:
	- let stringOfNums = ['1','2','3','4']
	stringOfNums.map(Numbers) => {
	}
	returns [1,2,3.4]

* functions can continue to be chained one on top of the other
* .filter(ele => yearsPlayed > 3)
	implied return "(.filter(ele => return yearsPlayed > 3)"
