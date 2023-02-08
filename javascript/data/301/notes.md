# JavaScript Data 301
## Understanding Immutablility comes down to understanding how data is stored in memory.

**Definition of Immutability**
Primitive data types are immutable. Immutability means that whenever a variable is declared, it lives at a unique address in memory and if it is later reinitialized, it will live at a new unique address. If a variable is initialized by reference, instead of by value, its unique address points to the referred address.

**List of primitive data types**
* strings
* booleans
* numbers
* null
* undefined

**Example**
```
let age = 32;   // Initializes by value, it gets a unique address (e.g. Hx78)
let maryAge = age;  // Initializes by reference, it gets a unique address (e.g. Rw33) but this address doesn't hold a value, it points to Hx78
age = 33;   // reinitialization creates a new storage address (e.g. Xa15)
```

**Definition of Mutability**
Collections of primitive data typs ARE mutable. Which means that when they are modified or updated, the data is not stored at a new address, but remains at the original address when the variable was first declared. Reinitializing makes a new address. 
They start as pointers, so more pointer to it do the same.

**List of collections**
* arrays
* objects