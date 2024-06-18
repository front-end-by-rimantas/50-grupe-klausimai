## Kaip veikia toks sprendimo budas? 
https://www.codewars.com/kata/55e7280b40e1c4a06d0000aa/train/javascript
```js
function chooseBestSum(t, k, ls) {
    let r = null;
    function helper(start, currentCount, currentSum) {
        if (currentCount === k) {
            if (currentSum <= t && (r === null || currentSum > r)) {
                r = currentSum;
            }
            return;
        }
        for (let i = start; i < ls.length; i++) {
            helper(i + 1, currentCount + 1, currentSum + ls[i]);
        }
    }
    helper(0, 0, 0);
    return r;
}
```
