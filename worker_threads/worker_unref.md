<!-- YAML
added: v10.5.0
-->

Calling `unref()` on a worker will allow the thread to exit if this is the only
active handle in the event system. If the worker is already `unref()`ed calling
`unref()` again will have no effect.



























































