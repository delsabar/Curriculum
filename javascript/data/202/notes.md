# JavaScript Data 202
## The syntax to read data from memory can be done with indices, bracket notation or dot notation.

### Indices (Arrays)
We use an index to read data from an array by enclosing the index value within square brackets `[]`.
```
const shoppingList = ['apples', 'celery', 'bread'];
console.log(shoppingList[0]);  // --> apples
```

### Bracket/Dot Notation (Objects)
We use bracket or dot notation to read data from an object.
```
const cars = {
    color: 'green',
    mileage: 16302,
    isNew: false
    };
console.log(car['mileage']);  // --> 16302
console.log(car.mileage);     // --> 16302
```

### Simple data types
Refer to variable name to read it.
```
const name = 'Paul';
console.log(name);   // --> Paul
```