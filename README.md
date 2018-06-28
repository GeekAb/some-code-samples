* Removes non-unique elements
* Does not change the source array

```javascript
function unique(arr) {
  return Array.from(new Set(arr));
}
```

or 
```javascript
function unique(arr) {
  return [...new Set(arr)];
}
```
