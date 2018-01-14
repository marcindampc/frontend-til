## truthyness
* 0 and `null` are falsy

## control structures
* for in
```\
var person = {
	name: "Amory Blaine",
	age: 102
	};
var result = "";
// for in enumerates the property names of an object
for (var property_name in person) {
result = result + property_name;
}
```
* ternary operator
```
var fruit = false ? "apple" : "orange";
equal("orange", fruit, 'now what is the value of fruit?');
```
* switch
```
var result = 0;
	switch (2) {
		case 1:
			result = 1;
			break;
		case 1+1:
			result = 2;
			break;
	}
	equal(2, result, 'what is the value of result?');
  ```
  * NaN != NaN
  * adding properties from strings
  ```
  var person = {};
  person["name"] = "Amory Blaine";
  person["age"] = 102;
  equal("Amory Blaine", person.name, "what is the person's name?");
  equal(102, person.age, "what is the person's age?");
```
* Array.prototype.splice()
  * The splice() method changes the contents of an array by removing existing elements and/or adding new elements.
  ```
  var myFish = ['angel', 'clown', 'mandarin', 'sturgeon'];
var removed = myFish.splice(2, 0, 'drum');

// myFish is ["angel", "clown", "drum", "mandarin", "sturgeon"] 
// removed is [], no elements removed
```

* The shift() method removes the first element from an array and returns that removed element. This method changes the length of the array.

## Prototypes
...
