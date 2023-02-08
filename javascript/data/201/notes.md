# JavaScript Data 201
## Data types can be collected in other structures like objects and arrays.

### Objects
And object describes something. It lives inside of opening and closing curly braces `{}` and is organized as key value pairs seperated by commas `,`. The key and the value are themselves seperated by a colon `:`.
```
const car = {
    color: 'green',
    mileage: 16302,
    isNew: false
};
```


### Arrays
An array is a list of items. It's defined by opening and closing square brackets `[]`. The items in the array are seperated by commas. Each item in an array is indexed with a number. Arrays can contain all other data types as well as objects.
```
const shoppingList = ['apples', 'celery', 'bread'];
const ages = [17, 7, 8, 8, 7.5];
const cars = [
    {
    color: 'green',
    mileage: 16302,
    isNew: false
    },
    {
    color: 'red',
    mileage: 1630,
    isNew: false
    },
        {
    color: 'blue',
    mileage: 163020,
    isNew: false
    }
];
```

JavaScript considers arrays to be objects. So the shopping list above looks like this to JavaScript.
```
const shoppingList = {
    0: 'apples',
    1: 'celer',
    2: 'bread'
}
```