# Instrumental Quiz: Classes and Instances

## Learning Goals

- Identify `class` objects and their instances

## Questions

```js
class Tree {
  constructor(type) {
    this.type = type;
  }
}
```

1.  How would we create an instance of the above `class`?

2.  Once that instance is created, how would we access the `type` property?

3.  Once that instance is created, how would we modify the `type` property?

```js
class House {
  constructor(address, owner) {
    this.address = address;
    this.owner = owner;
  }
}

let house1 = new House('22 Elm St', 'Dr. Howser');
let house2 = new House('11 Main St', 'Mrs. Tanner');
house1.owner = 'Dr. McCoy';
house2.address = '138 Mayflower Ave';
```

4.  Given the code above, what is the `address` value of `house1`?

5.  What is the `address` value of `house2`?
