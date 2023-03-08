# Let's write a UART driver

```rust,editable,compile_fail
{{#include examples/src/pl011.rs:Example}}
```

<details>

The QEMU 'virt' machine has a PL011 UART, so let's write a driver for that.

</details>
