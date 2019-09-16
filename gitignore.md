# leading slash
match the beginning of the pathname

# two consecutive asterisks
## **/
- match in all directories
- `**/foo` is equivaltent to `foo`

## /**
match everything inside

## /**/
match zero or more directories

# re-include not possible
It is not possible to re-include a file if a parent directory of that file is excluded.
