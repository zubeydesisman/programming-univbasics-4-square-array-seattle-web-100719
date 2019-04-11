# Square Array

## Learning Goals

- Apply the `.each` method to iterate over an array

## Introduction

In this lab we will be building a method, `square_array`, that
[squares](https://en.wikipedia.org/wiki/Square_(algebra)) each element in an
array of numbers and returns a new array of these squared numbers.

**Hint:** There is more than one way to square numbers! Google Ruby's exponent
operator or refer back to the earlier lesson on simple math.

## Apply the `.each` Method to Iterate Over an Array

To build this method, use the iterator `.each` and implement your own logic. *Do
not* use any built-in array methods other than `.each` (e.g. `.collect`,
`.inject`). Passing the first test requires `.each` to be used.

Example:

```ruby
numbers = [1,2,3]

square_array(numbers)
# => [1,4,9])

new_numbers = [9,10,16,25]

square_array(new_numbers)
# => [81,100,256,625]
```
Once you have the tests passing, see if you can implement this with a higher
level iterator such as `.collect`.

## Conclusion

As demonstrated, Ruby gives us a number of shortcuts to complete iterative tasks
with ease. Instead of manually writing loops, you can achieve the same results
with fewer lines of code.

## Resources
* [Ruby Docs](http://www.ruby-doc.org/core-2.1.2/)
* [Each Method](http://www.ruby-doc.org/core-2.1.2/Array.html#method-i-each)