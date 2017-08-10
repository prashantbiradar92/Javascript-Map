## Understanding Map in Javascript 


JavaScript’s map function is extremely useful, but it can also be a bit confusing when you’re just starting out with programming.


### What,Why,When Map?

### What ?
The Map object holds key-value pairs. Any value (both objects and primitive values) may be used as either a key or a value.

### Why?
  It is datastructure to solve real world problems.
### When ?
  

  

### creating Map 
```
   let map =  new Map();  // Here creating map object and map methods to iterate over map
   
     
   
```
### Methods

### 1. Map.prototype.clear()
       Removes all key/value pairs from the Map object.

### 2. Map.prototype.delete(key)
     Removes any value associated to the key and returns the value that Map.prototype.has(key) would have previously returned.

### 3. Map.prototype.has(key) 
    will return false afterwards.

### 4. Map.prototype.entries()
     Returns a new Iterator object that contains an array of [key, value] for each element in the Map object in insertion order.

### 5. Map.prototype.forEach(callbackFn[, thisArg])
    Calls callbackFn once for each key-value pair present in the Map object, in insertion order. If a thisArg parameter is provided to forEach, it will be used as the this value for each callback.

### 6. Map.prototype.get(key)
    Returns the value associated to the key, or undefined if there is none.
    Map.prototype.has(key)
   Returns a boolean asserting whether a value has been associated to the key in the Map object or not.

### 7. Map.prototype.keys()
    Returns a new Iterator object that contains the keys for each element in the Map object in insertion order.

### 8. Map.prototype.set(key, value)
     Sets the value for the key in the Map object. Returns the Map object.

### 9. Map.prototype.values()
     Returns a new Iterator object that contains the values for each element in the Map object in insertion order.

### 10. Map.prototype[@@iterator]()
    
 
