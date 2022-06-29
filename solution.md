## Return Negative

```js
function makeNegative(num) {
  return num > 0 ? -num : num;
}
```

## Sum of Positive

```js
function positiveSum(arr) {
  let sumArr = 0;
  for (let i=0; i<arr.length; i++){
    if (arr[i]>0) {
      sumArr += arr[i];
    }
  }
  return sumArr;
}
```

## Function 2

```js
const square = (num) => {
  return Math.pow(num,2);
}
```

## Sum Arrays

```js
// Sum Numbers
function sum (numbers) {
    "use strict";
  let sumArr = 0;
  for (let i=0; i<numbers.length; i++){
    sumArr += numbers[i];
  }
  return sumArr; 
};
```

## Reversed Strings

```js
function solution(str) {
  const strArr = str.split("");
  let bkwrdStr = "";
  for (let i = strArr.length-1; i>=0; i--) {
    bkwrdStr += strArr[i];
  }
  return bkwrdStr;
};
```

