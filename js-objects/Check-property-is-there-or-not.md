```ngMeta
name: Check property is there or not
```

You can check whether property exists or not in an object. We can use the .hasOwnProperty(propname) method of objects to determine if that object has the given property name. .hasOwnProperty() returns true or false if the property is found or not.

```javascript

var myDetails={
   "name":"kumar",
   "age":24
}
console.log(myDetails.hasOwnProperty("name"));
// output 
// True

```