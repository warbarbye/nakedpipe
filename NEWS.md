# nakedpipe (development version)

* left to right assignment is now supported in side effects
* New pipes `%P.%`, `%<P.%`, `%V.%`,  and `%<V.%`, are introduced to `print()` or
`View()` the result of every step.
* We can use `if` and `else` to have conditional steps
* `%lapply..%` and `%sapply..%` are counterparts to `%lapply.%` and `%sapply.%`
* `%F.%` and `%F..%` reproduce magrittr's functional sequence feature. 
* When assigning to a dotted variable in side effects, the variable is available
during the call but is not copied in the calling environment. This is a clean
way to use temp variables.
* We propose two addins "nakedpipe to magrittr", and "magrittr to nakedpipe",
allowing one to select code in one syntax and replace it by the other.

# nakedpipe 0.0.0.9000

* Added a `NEWS.md` file to track changes to the package.
