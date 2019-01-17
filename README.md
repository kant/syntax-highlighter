# syntax-highlighter
Red syntax/expressions highligting

## Current limitations / problems
1. Expressions highlighting works for predefined functions only. User-defined functions are TBD
2. `op!` scope is correctly found when treated as argument. Arguments highlighting for `op!` itself is TBD
3. If function is in beginning of block or parens, then block scope is shown on hovering, not expression scope. TBD
4. Its's not editable. TBD
5. Not resizable. TBD
6. No error-handling. TBD
7. No comments :). TBD
8. No code execution. Also incremental execution TBD.
9. Navigation by scroller only. Wheeling and arrow-nav TBD.
10. Layout is done according to W10. It can show with defects on other platforms/versions.
11. Hovering works for limited range. After ~1.5 pages hovering stops working. Reason is not yet clear. Can be a Red bug or something wrong with my code.
12. Using `bold` in syntax highlighting style definitions has no effect on `caret-to-offset` calculations, which causes misplacement of hover-reactive boxes on layer above rich-text. Red bug?
