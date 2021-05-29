Keys | Explanation
--- | ---
`qa` | start recording macros into `a` regester
`q` | stop recording macros
`qA` | Append to regester `a` 
`"a` | use regester `a`
`"Ayaw` | Append "a word" to regester `a` (also work with delete)
`%s/foo/bar/gc` | `%` in all documemt search and replace from `foo` to `bar` in `g` in all line with `c` confirmation. % is a range. There are few another range. `number, number` of `number, $`. `$` means last line. `%` means all lines. Also possible use marks form range `'t,'bs/foo/bar/gc`. Simbol `.` means current line, `:.+3,$-5` - is relatite range
