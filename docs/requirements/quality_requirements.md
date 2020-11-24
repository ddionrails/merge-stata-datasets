# Quality Requirements

# Python components

- should pass `pylint` analysis.
- should be typed and pass `mypy` analysis.
- should be unit-tested with `unittest` library.
- Functional system tests, for all components regardless of language,
  should be implemented in Python.

# R components

- should pass [`lintr`](https://github.com/jimhester/lintr) analysis.
- should be unit-tested with [`testthat`](https://github.com/r-lib/testthat/) library.


# Stata components

- should keep a consistent style in naming, indentation, comments etc.
- Line length should be kept under 80 and needs to be kept under 90 characters.
- Whitespace should be used to visualize cohesion of code blocks.
- Naming of entities should carry meaning and names should not be abbreviated.
- Stata commands should not be abbreviated or sensibly abbreviated.

  - `sum` can be used, `su` should not be used.

- Paths should be relative to a "home" directory that is set through the user or
  a Python wrapper.

- Dummy `.dta` datasets should exist for testing.
- should be tested through the functional tests implemented in Python.

  - This needs to be separable, to test on systems without stata installation.
