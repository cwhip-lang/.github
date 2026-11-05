## Cwhip Compiler Project👋

`cwhip` is the Cwhip compiler: a statically typed language with classes,
inheritance, managed strings and collections, exceptions, and native bindings.
The frontend is C++17 and the runtime is C. Source files use the `.cw`
extension. Source: [github.com/chucktilbury/cwhip](https://github.com/chucktilbury/cwhip).
The project website is [cwhip.org](https://cwhip.org).

This directory contains the compiler in `src/`, runtime headers in `include/`,
the built-in `String` class in `builtin/`, standard-library packages in
`stdlib/`, runnable examples in `examples/`, tests in `tests/`, and user
documentation in `doc/`. Local CMake outputs use `build/`, `bin/`, `lib/`, and
`share/`.

With a current checkout, run `scripts/setup [--clean] [debug|release|profile]`
from the repository, then `build` in the project shell. Use `rebuild` for a
clean-first build, or `clean` to remove generated outputs; exit the shell before
running setup again. The compiler is `bin/cwhip`.
