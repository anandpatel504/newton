```ngMeta
name: Object
```

## Object Datatype

Think of a dictionary. It has people’s names and their phone numbers. If we have to store this type of data, i.e. people’s names and phone numbers, then we will use something called the Object data type.

The object is a complex data type that allows you to store collections of data.
The following example will show you the simplest way to create an object in JavaScript.

```javascript
var emptyObject = {};

var person = {"name": "Nayak", "surname": "Kumar", "age": "24"};

// For better reading
var scooty = {
"modal": "Ampere Rio",
"color": "white",
"Speed": "35 km"
}
```

An object contains properties, defined as a key-value pair. In the example above, name, surname and age are keys, and Nayak, Kumar and 24 and their corresponding values.

You can omit the quotes around property name if the name is a valid JavaScript name. That means quotes are required around "first-name", "first name" but are optional around firstname. So the car object in the above example can also be written as:
 
```javascript
var scooty = {
modal: "Ampere Rio",
colour: "white",
Speed: "35 km"
}
```
