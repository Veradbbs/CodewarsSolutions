*Reversed Strings*
* https://www.codewars.com/kata/reversed-strings/train/javascript
```javascript
function solution(str) {
  let reversed = '';
  for (let i = str.length - 1; i >= 0; i--) {
    reversed += str[i];
  }
  return reversed;
}
```
*Who Is Paying*
* https://www.codewars.com/kata/who-is-going-to-pay-for-the-wall/train/javascript
```javascript
function whoIsPaying(name) {
  let arr = [name];
  if (name.length > 2) {
  let str = name.substring(0, 2);
  arr.push(str)
  }
  return arr;
}
```
*Array Plus Array*
* https://www.codewars.com/kata/array-plus-array/train/javascript
```javascript
function arrayPlusArray(arr1, arr2) {
  let sum = 0;
  for (let i = 0; i < arr1.length; i++) {
  sum += arr1[i];
  }
  for (let i = 0; i < arr2.length; i++) {
  sum += arr2[i];
  }
  return sum;
}
```
*Final Grade*
* https://www.codewars.com/kata/students-final-grade/train/javascript
```javascript
function finalGrade (exam, projects) {
  if(exam > 90 || projects > 10) return 100;
  if(exam > 75 && projects >= 5) return 90;
  if(exam > 50 && projects >= 2) return 75;
  return 0;
}
```
*Personalized Message*
* https://www.codewars.com/kata/grasshopper-personalized-message/train/javascript
```javascript
function greet (name, owner) {
  if (name === owner) {
  return 'Hello boss';
  } else {
  return 'Hello guest';
  }
}
```
*Count Sheep*
* https://www.codewars.com/kata/if-you-cant-sleep-just-count-sheep/train/javascript
```javascript
function countSheep(num) {
  let newString = '';
    for (let i = 1; i <= num; i++) {
    newString = newString + i + ' sheep...';
    }
  return newString;
}
```
*Man In The West*
* https://www.codewars.com/kata/man-in-the-west/train/javascript
```javascript
function checkTheBucket(bucket) {
    let gold = 'gold';
    for (let i = 0; i < bucket.length; i++) {
      if (bucket[i] === 'gold') {
          return true;
        }
      }
      return false;
    }
```
*String Repeat*
* https://www.codewars.com/kata/string-repeat/train/javascript
```javascript
function repeatStr (n, string) {
  return string.repeat(n);
}
```
*Count of positives / sum of negatives*
* https://www.codewars.com/kata/count-of-positives-slash-sum-of-negatives/train/javascript
```javascript
function countPositivesSumNegatives(input) {
  let posCount = 0;
  let negSum = 0;
  if (input == null || input.length === 0) {
    return [];
  }
  for (let i = 0; i < input.length; i++) {
    if (input[i] > 0) {
      posCount++;
    } else {
      negSum += input[i];
    }
  }
  return [posCount, negSum];
}
```
*Reverse List Order*
* https://www.codewars.com/kata/reverse-list-order/train/javascript
```javascript
function reverseList(list) {
  let arr = [];
  for(let i = list.length - 1; i >= 0; i--) {
  arr.push(list[i]);
  }
  return arr;
}
```
*Even Or Odd*
* https://www.codewars.com/kata/even-or-odd/train/javascript
```javascript
function even_or_odd(number) {
  if (number % 2 === 0) return "Even";
  else return "Odd";
}
```
*A Needle In The Haystack*
* https://www.codewars.com/kata/a-needle-in-the-haystack/train/javascript
```javascript
function findNeedle(haystack) {
  return 'found the needle at position ' + haystack.indexOf('needle');
}
```
*Variable Assignment Debug*
* https://www.codewars.com/kata/grasshopper-variable-assignment-debug/train/javascript
```javascript
let a = 'dev';
let b ='Lab';
let name = a + b;
```
*MakeUpperCase*
* https://www.codewars.com/kata/makeuppercase/train/javascript
```javascript
function makeUpperCase(str) {
  return str.toUpperCase();
}
```
*Basic Variable Assignment*
* https://www.codewars.com/kata/basic-variable-assignment/train/javascript
```javascript
let a = 'code';
let b = 'wa.rs';
let name = a + b;
```
*Opposite Number*
* https://www.codewars.com/kata/opposite-number/train/javascript
```javascript
function opposite(number) {
  return(-number);
}
```
*Man In The West*
* https://www.codewars.com/kata/man-in-the-west/train/javascript
```javascript
function checkTheBucket(bucket) {
    let gold = 'gold';
    for (let i = 0; i < bucket.length; i++) {
      if (bucket[i] === 'gold') {
          return true;
        }
      }
      return false;
    }
```
*Return The Day*
* https://www.codewars.com/kata/return-the-day/train/javascript
```javascript
function whatday(num) {
  switch(num) {
    case 1:
      return "Sunday";
    case 2:
      return "Monday";
    case 3:
      return "Tuesday";
    case 4:
      return "Wednesday";
    case 5:
      return "Thursday";
    case 6:
      return "Friday";
    case 7:
      return "Saturday";
    default:
      return 'Wrong, please enter a number between 1 and 7';
  }
}
```
*Short Long Short*
* https://www.codewars.com/kata/short-long-short/train/javascript
```javascript
 function solution(a, b) {
  return a.length < b.length ? a + b + a : b + a + b;
}
```
*Returning Strings*
* https://www.codewars.com/kata/returning-strings/train/javascript
```javascript
function greet(name) {
  return `Hello, ${name} how are you doing today?`;
}
```