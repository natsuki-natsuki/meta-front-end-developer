## push()
```javascript
var fruits = [];
fruits.push("apple"); // ['apple']
fruits.push('pear'); // ['apple', 'pear']
```

## pop()
```javascript
var fruits = [];
fruits.pop();
console.log(fruits); // ['apple']
```

## arrayBuilder()
```javascript
function arrayBuilder(one, two, three) {
  var arr = [];
  arr.push(one);
  arr.push(two);
  arr.push(three);
  console.log(arr);

arrayBuilder('apple', 'pear', 'plum'); // ['apple', 'pear', 'plum']
```
```javascript
function arrayBuilder(one, two, three) {
  var arr = [];
  arr.push(one);
  arr.push(two);
  arr.push(three);
  return arr;
```

## simpleArr
```javascript
var simpleArr = arrayBuilder('apple', 'pear', 'plum');
console.log(simpleArr); // ['apple', 'pear', 'plum']
```
