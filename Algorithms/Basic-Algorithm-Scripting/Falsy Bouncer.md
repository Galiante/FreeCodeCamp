# Falsy Bouncer

Remove all falsy values from an array.

Falsy values in JavaScript are false, null, 0, "", undefined, and NaN.

Remember to use Read-Search-Ask if you get stuck. Write your own code.

### Here are some helpful links:

+ [Boolean Objects](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean)
+ [Array.filter()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/filter)

### Task

+ bouncer([7, "ate", "", false, 9]) should return [7, "ate", 9].
+ bouncer(["a", "b", "c"]) should return ["a", "b", "c"].
+ bouncer([false, null, 0, NaN, undefined, ""]) should return [].
+ bouncer([1, null, NaN, 2, undefined]) should return [1, 2].

### Solution

```javascript
function bouncer(arr) {
  // Don't show a false ID to this bouncer.
var filtered = arr.filter(Boolean);
  return filtered;
}

bouncer([7, "ate", "", false, 9]);
```
