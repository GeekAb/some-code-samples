* Removes non-unique elements
* Does not change the source array

```javascript
function unique(arr) {
  return Array.from(new Set(arr));
}
```
