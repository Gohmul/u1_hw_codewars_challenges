## Return Negative

```js

function makeNegative(num) {
    return -Math.abs(num);
}


```

## Sum of Positive

```js

function positiveSum(arr) {
  let sum = 0;
  for(var index = 0; index < arr.length; index++) {
    if (arr[index] > 0) {
      sum += arr[index];
    }
  }
  return sum;
}

```

## Function 2

```js

function square(number) {
  return number ** 2
}

```

## Sum Arrays

```js

// Sum Numbers
function sum (numbers) {
    "use strict";
  return numbers.reduce((resolution,total) => resolution+total,0);
};

```

## Reversed Strings

```js

function solution(str) {
  const reverseStr = str.split('').reverse('').join('')
  return reverseStr
}

```
