Voici la liste des fonctions pour manipuler des tableaux en JavaScript avec des exemples d'usage :

1. **Array.from()**
   ```javascript
   let str = 'hello';
   let arr = Array.from(str);
   console.log(arr); // ["h", "e", "l", "l", "o"]
   ```

2. **Array.isArray()**
   ```javascript
   console.log(Array.isArray([1, 2, 3])); // true
   console.log(Array.isArray('hello')); // false
   ```

3. **Array.of()**
   ```javascript
   let arr = Array.of(1, 2, 3, 4);
   console.log(arr); // [1, 2, 3, 4]
   ```

### Prototypes Methods

4. **concat()**
   ```javascript
   let arr1 = [1, 2, 3];
   let arr2 = [4, 5, 6];
   let arr3 = arr1.concat(arr2);
   console.log(arr3); // [1, 2, 3, 4, 5, 6]
   ```

5. **copyWithin()**
   ```javascript
   let arr = [1, 2, 3, 4, 5];
   arr.copyWithin(0, 3);
   console.log(arr); // [4, 5, 3, 4, 5]
   ```

6. **entries()**
   ```javascript
   let arr = ['a', 'b', 'c'];
   let iterator = arr.entries();
   for (let entry of iterator) {
     console.log(entry);
   }
   // [0, 'a']
   // [1, 'b']
   // [2, 'c']
   ```

7. **every()**
   ```javascript
   let arr = [1, 2, 3, 4, 5];
   let allEven = arr.every(num => num % 2 === 0);
   console.log(allEven); // false
   ```

8. **fill()**
   ```javascript
   let arr = [1, 2, 3, 4];
   arr.fill(0, 2, 4);
   console.log(arr); // [1, 2, 0, 0]
   ```

9. **filter()**
   ```javascript
   let arr = [1, 2, 3, 4, 5];
   let even = arr.filter(num => num % 2 === 0);
   console.log(even); // [2, 4]
   ```

10. **find()**
    ```javascript
    let arr = [1, 2, 3, 4, 5];
    let found = arr.find(num => num > 3);
    console.log(found); // 4
    ```

11. **findIndex()**
    ```javascript
    let arr = [1, 2, 3, 4, 5];
    let index = arr.findIndex(num => num > 3);
    console.log(index); // 3
    ```

12. **flat()**
    ```javascript
    let arr = [1, 2, [3, 4, [5, 6]]];
    let flatArr = arr.flat(2);
    console.log(flatArr); // [1, 2, 3, 4, 5, 6]
    ```

13. **flatMap()**
    ```javascript
    let arr = [1, 2, 3, 4];
    let mappedArr = arr.flatMap(num => [num * 2]);
    console.log(mappedArr); // [2, 4, 6, 8]
    ```

14. **forEach()**
    ```javascript
    let arr = [1, 2, 3];
    arr.forEach(num => console.log(num * 2));
    // 2
    // 4
    // 6
    ```

15. **includes()**
    ```javascript
    let arr = [1, 2, 3];
    console.log(arr.includes(2)); // true
    console.log(arr.includes(4)); // false
    ```

16. **indexOf()**
    ```javascript
    let arr = [1, 2, 3, 2, 1];
    console.log(arr.indexOf(2)); // 1
    console.log(arr.indexOf(4)); // -1
    ```

17. **join()**
    ```javascript
    let arr = [1, 2, 3];
    let str = arr.join('-');
    console.log(str); // "1-2-3"
    ```

18. **keys()**
    ```javascript
    let arr = ['a', 'b', 'c'];
    let iterator = arr.keys();
    for (let key of iterator) {
      console.log(key);
    }
    // 0
    // 1
    // 2
    ```

19. **lastIndexOf()**
    ```javascript
    let arr = [1, 2, 3, 2, 1];
    console.log(arr.lastIndexOf(2)); // 3
    console.log(arr.lastIndexOf(4)); // -1
    ```

20. **map()**
    ```javascript
    let arr = [1, 2, 3];
    let doubled = arr.map(num => num * 2);
    console.log(doubled); // [2, 4, 6]
    ```

21. **pop()**
    ```javascript
    let arr = [1, 2, 3];
    let last = arr.pop();
    console.log(last); // 3
    console.log(arr); // [1, 2]
    ```

22. **push()**
    ```javascript
    let arr = [1, 2];
    arr.push(3);
    console.log(arr); // [1, 2, 3]
    ```

23. **reduce()**
    ```javascript
    let arr = [1, 2, 3, 4];
    let sum = arr.reduce((acc, num) => acc + num, 0);
    console.log(sum); // 10
    ```

24. **reduceRight()**
    ```javascript
    let arr = [1, 2, 3, 4];
    let sum = arr.reduceRight((acc, num) => acc + num, 0);
    console.log(sum); // 10
    ```

25. **reverse()**
    ```javascript
    let arr = [1, 2, 3];
    arr.reverse();
    console.log(arr); // [3, 2, 1]
    ```

26. **shift()**
    ```javascript
    let arr = [1, 2, 3];
    let first = arr.shift();
    console.log(first); // 1
    console.log(arr); // [2, 3]
    ```

27. **slice()**
    ```javascript
    let arr = [1, 2, 3, 4];
    let sliced = arr.slice(1, 3);
    console.log(sliced); // [2, 3]
    ```

28. **some()**
    ```javascript
    let arr = [1, 2, 3];
    let hasEven = arr.some(num => num % 2 === 0);
    console.log(hasEven); // true
    ```

29. **sort()**
    ```javascript
    let arr = [3, 1, 4, 1, 5];
    arr.sort();
    console.log(arr); // [1, 1, 3, 4, 5]
    ```

30. **splice()**
    ```javascript
    let arr = [1, 2, 3, 4];
    arr.splice(1, 2, 'a', 'b');
    console.log(arr); // [1, "a", "b", 4]
    ```

31. **toLocaleString()**
    ```javascript
    let arr = [1, 'a', new Date('21 Dec 1997 14:12:00 UTC')];
    let str = arr.toLocaleString('en-US');
    console.log(str); // "1,a,12/21/1997, 2:12:00 PM"
    ```

32. **toString()**
    ```javascript
    let arr = [1, 2, 3];
    let str = arr.toString();
    console.log(str); // "1,2,3"
    ```

33. **unshift()**
    ```javascript
    let arr = [2, 3];
    arr.unshift(1);
    console.log(arr); // [1, 2, 3]
    ```

34. **values()**
    ```javascript
    let arr = ['a', 'b', 'c'];
    let iterator = arr.values();
    for (let value of iterator) {
      console.log(value);
    }
    // "a"
    // "b"
    // "c"
    ```

Cette liste présente les principales fonctions disponibles pour la manipulation des tableaux en JavaScript, avec des exemples pour chacune d'entre elles.
