Author @melangyun

Date : July 22, 2020

# Attempt 1

```javascript
/**
 * @param {number} num
 * @return {number}
 */
var numberOfSteps  = function(num) {
    let count = 0;
    while(num){
        num = num % 2 !== 0 ? num -1 : num / 2;
        count += 1;
    }
    return count;
};
```

Time complexity: O(1)

Space complexity: O(1)