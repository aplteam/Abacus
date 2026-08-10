# FQP

Returns the fully qualified path of a callback name — used when wiring event handlers.

~~~
R←{L} FQP Name
~~~

`Name` is the (relative) function name. `L` is an optional number of levels up the calling
stack to qualify against (default `0`). If `Name` already starts with `#` or a space it is
returned unchanged. `R` is the fully qualified name.
