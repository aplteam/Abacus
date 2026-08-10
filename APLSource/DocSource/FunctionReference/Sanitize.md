# Sanitize

Escapes a string so it is safe to embed inside a single-quoted JavaScript string: it drops
carriage returns and replaces `'` with `&#39;`.

~~~
R←Sanitize S
~~~

`S` is a character vector (or vector of character vectors). `R` is the sanitized text.
