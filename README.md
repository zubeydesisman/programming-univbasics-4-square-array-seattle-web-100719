# Square Array

## Learning Goals

- Apply the `.each` method to iterate over an array

## Introduction

You will build a method, `square_array`, that squares each element in an array of numbers and returns a new array of these squared numbers.

## Apply the `.each` Method to Iterate Over an Array

Use an iterator and implement your own logic, *don't* use any built-in array methods other than `.each` (e.g. `.collect`, `.inject`).

Example:

```ruby
numbers = [1,2,3]

square_array(numbers)
# => [1,4,9])

new_numbers = [9,10,16,25]

square_array(new_numbers)
# => [81,100,256,625]
```

A couple of questions that you can ask yourself are:

* What is the return value of calling `.each` on an array?
* How can I operate on each element of an array and also collect or store those elements?
* How can I square a number? **Hint:** There is more than one way to do it! Google Ruby's exponent operator or refer back to the earlier lesson on simple math.

## Conclusion

Once you have the tests passing, see if you can implement this with a higher level iterator such as `.collect`.

## Resources
* [Ruby Docs](http://www.ruby-doc.org/core-2.1.2/) - [Each Method](http://www.ruby-doc.org/core-2.1.2/Array.html#method-i-each)