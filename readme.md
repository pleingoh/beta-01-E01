# The pilot
If you haven't done it already, learn about [the tools](https://nan.ci/js-tools/)
to understand more about what you will be using.

Then `fork` this repository and `clone` **your fork** to start working on it.
To get started read the [Standard procedure](https://nan.ci/js-standard-procedure)

------

Get a grasp of JavaScript syntax by reading the 
[commented code examples](https://nan.ci/js-examples)

------

If you have a question, do these in order:
 - Search in the example
 - Search in the documentation
 - Search online
 - keep looking *(~15 minutes is a good balance, less would show poor efforts, more you start to just being stubborn / loosing your time)*
 - Ask for help from any inhert object nearby
  ([rubber duck debugging](https://en.wikipedia.org/wiki/Rubber_duck_debugging))
 - Ask your nearest peer
 - Ask another peer
 - Ask on discord
  ([don't ask to ask, just ask](http://sol.gfxile.net/dontask.html))

***Make sure you understand how your problem was solved***


## TESTS
#### test `str`
export a string `str` with the value `"42"`

#### test `num`
export a number `num` with the value `42`

#### test `bool`
export a boolean `bool` with the value `false`

#### test `escapeStr`
export a string `escapeStr` containing the characters \\, /, ', ", and `

#### test `spaced key`
export a boolean `'spaced key'` with the value `true`

#### test `arr`
exports an array of two element:
 - a number with the value `4` at the index 0
 - a string with the value `'2'` at the index 1

#### test `fn`
export a function `fn` that takes one argument and return it

#### test `get`
export a function `get` that takes one argument, a string
and return the corresponding value

#### test `obj`
export an object `obj` that contains all the key / values from `module.exports`
except for the spaced key, `obj.obj` should be a circular reference to itself



## BONUS
#### bonus `makeGet`
export a function `makeGet` that takes one argument and return a function that
takes no arguments but return the previously given argument

#### bonus `hideMe`
export a function `hideMe` that takes one object argument
and return a function that takes a string arguments and return the corresponding
values from the previously given object

#### bonus `safe`
export a function `safe` that takes no arguments  
and return an object that contain two functions, `set`, and `get`.  
The function `set` take any value argument, store it and return generated key  
If a second argument is given to set, it will be used as a key
and update the value at the given key  
The function `get` takes one of the generated key returned from `set`
and return the corresponding value  
The generated keys must be empty object references generated by `Math.random()`


#### bonus `superSafe`
export a function `superSafe` that work's exactly like `safe` but the generated
keys must be empty object references generated by `Object.create(null)`

#### bonus rule `no block statement`
You haven't made any blocks, only arrow functions.

#### bonus rule `no variable declarations`
Only functions and arguments

#### bonus rule `no repetition`
[DRY](https://en.wikipedia.org/wiki/Don%27t_repeat_yourself) my good fellas


TODO:
add the dry bonus rule, makeGet, hideMe and safe
