Add your answers to the Algorithms exercises here.

Exercise I.

a) O(n)

b) O(log n)

c) O(sqrt(n))

d) O(n log n)

e) O(n^3)

f) O(n)

g) O(n)

Exercise II.

a)

```js
function maxDifference(arr) {
  let minVal = arr[0];
  let maxDiff = 0;

  for (let i = 0; i < arr.length; i++) {
    minVal = Math.min(minVal, arr[i]);
    maxDiff = Math.max(maxDiff, arr[i] - minVal);
  }

  return maxDiff;
}
```

b) Binary Search

Exercise III.

a) O(n^2)

b) O(n log n)
