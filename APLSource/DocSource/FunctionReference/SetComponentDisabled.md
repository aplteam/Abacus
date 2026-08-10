# SetComponentDisabled

Enables or disables a component.

~~~
R←{N} SetComponentDisabled W
~~~

`N` is an optional DOM node to look the component up from. `W` is `(component)(boolean)` — the
component, given by name or reference, and `1` to disable or `0` to enable.
