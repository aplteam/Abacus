# Prompt

Shows a modal prompt box that asks the user for a value.

~~~
R←D Prompt W
~~~

`D` is the Document. `W` is a namespace (or shortcut list) of properties — `Title`, `Label`,
`Value`, `OnOK`, `OnCancel`. `Prompt` does not wait; the entered value is handled in the
`OnOK` callback.
