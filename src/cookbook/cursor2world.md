# Convert cursor to world coordinates

{{#include ../include/links.md}}

[Click here for the full example code.][cbexample::cursor2world]

---

Bevy does not yet provide built-in functions to help with finding out what
the cursor is pointing at.

## 3D games

There is a good (unofficial) plugin:
[`bevy_mod_picking`][project::bevy_mod_picking].

## 2D games

Simple hacky solution, for a game using the default Bevy 2d orthographic camera:

```rust,no_run,noplayground
{{#include ../code/examples/cursor2world.rs:example}}
```
