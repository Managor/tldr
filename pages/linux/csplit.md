# csplit

> Split a file into pieces.
> This generates files named "xx00", "xx01", and so on.
> More information: <https://www.gnu.org/software/coreutils/manual/html_node/csplit-invocation.html>.

- Split a file at lines 5 and 23:

`csplit {{path/to/file}} 5 23`

- Split a file every 5 lines (this will fail if the total number of lines is not divisible by 5):

`csplit {{path/to/file}} 5 {*}`

- Split a file every 5 lines, ignoring exact-division error:

`csplit {{[-k|--keep-files]}} {{path/to/file}} 5 {*}`

- Split a file at line 5 and use a custom prefix for the output files:

`csplit {{path/to/file}} 5 {{[-f|--prefix]}} {{prefix}}`

- Split a file at a line matching a `regex`:

`csplit {{path/to/file}} /{{regex}}/`
