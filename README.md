# addalias
simple shell script to quickly add aliases to zshrc (or similar) file

## configurable items
the following are also included in comments in the code for ease of reference:

1. **rcfile** - change to wherever you store your aliases (default: ~/.zshrc)
   - nb: do not enclose path with quotation marks

2. **how/where to add to alias file** - simply uncomment the preferred method (default: first line of file)
   -  <u>opt1:</u> end of file
   -  <u>opt2:</u> beginning of file (default)
   -  <u>opt3:</u> at specific line of file (particularly useful if your file begins/ends with some control code)
      - nb: must change `#` to the appropriate line number: e.g., `3`
