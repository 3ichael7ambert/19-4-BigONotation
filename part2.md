## **Step Two: Calculating Time Complexity**

Determine the time complexities for each of the following functions. If you’re not sure what these functions do, copy and paste them into the console and experiment with different inputs!

```jsx
function logUpTo(n) {
  for (let i = 1; i <= n; i++) {
    console.log(i);
  }
}
```

Time Complexity: O(n)



```jsx
function logAtLeast10(n) {
  for (let i = 1; i <= Math.max(n, 10); i++) {
    console.log(i);
  }
}
```

Time Complexity: O(n)



```jsx
function logAtMost10(n) {
  for (let i = 1; i <= Math.min(n, 10); i++) {
    console.log(i);
  }
}
```

Time Complexity: <!-- O(n) --> O(1)

I put O(n) at first thinking we would be looping for the size of n.


```jsx
function onlyElementsAtEvenIndex(array) {
  let newArray = [];
  for (let i = 0; i < array.length; i++) {
    if (i % 2 === 0) {
      newArray.push(array[i]);
    }
  }
  return newArray;
}
```

Time Complexity: <!--O(n^2)--> O(n)

I put O(n^2) at first due to the if and modulo inside of the for loop, however, it loops at the n.length
 



```jsx
function subtotals(array) {
  let subtotalArray = [];
  for (let i = 0; i < array.length; i++) {
    let subtotal = 0;
    for (let j = 0; j <= i; j++) {
      subtotal += array[j];
    }
    subtotalArray.push(subtotal);
  }
  return subtotalArray;
}
```

Time Complexity: O(n^2) <!--or O(n^n)-->

I put "O(n^2) or O(n^n)" due to the nested arrays, the first loop is n.length, it seemed expontially growing so I wasn't sure if it would be n^2 n^n




```jsx
function vowelCount(str) {
  let vowelCount = {};
  const vowels = "aeiouAEIOU";

  for (let char of str) {
    if(vowels.includes(char)) {
      if(char in vowelCount) {
        vowelCount[char] += 1;
      } else {
        vowelCount[char] = 1;
      }
    }
  }

  return vowelCount;
}
```

Time Complexity: O(n) <!--O(n*2) O(n^2)-->

I put 'O(n) O(n*2) O(n^2)", three guesses due to the nested if statements I wasn't sure. However there is only one loop which will make it O(n)