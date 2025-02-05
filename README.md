# Mystery Function

What does the `mystery()` function in the following piece of code do? Add your
answer to this markdown file.

```javascript
function mystery(a) {
    if(a.length == 1) return a[0];
    var foo = mystery(a.slice(1, a.length))
    if(foo > a[0]) return foo;
    else return a[0];
}
```

## My Answer
The function above returns the greatest value in the inputed array. First, it checks if the input size is one. If so, it returns the only element in the array (making it the greatest). If the input is of a length greater than one, the function recursively splits the array without the first input, continuing until only one element remains in the new array. The function then checks every array element against the first, until it returns the greatest value.

## Sources and Plagarism
I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice.
