## Spread & Rest Operators

> Spread
> Used to split up array elements OR object properties

> const newArray = [...oldArray, 1,2]
> const newObject = {...oldObject, newProp: 5}

> const numbers = [1,2,3] <br>
> const newNumbers = [...numbers, 4] <br>
> console.log(newNumbers); // [1,2,3,4]<br>

> const person = { name: 'Max'} <br>
> const newPerson = {...person, age: 28} <br>
> console.log(newPerson) // { name: 'Max', age: 28}

---

> Rest
> Used to merge a list of function arguments into an array <br>
> function sortArgs(...args) { <br> > &nbsp; return args.sort() <br>
> }
