# VIM

## Inserting text in multiple lines

### Search and replace

`:s/^/new text/` insert "new text" at the *beginning* of the line.

`:s/$/new text/` insert "new text" at the *end* of the line.

`:s/green/bright &/g` replace each *"green"* with *"bright green"* in the line.

`:s/green/& bright/g` replace each *"green"* with *"green bight"* in the line.

ref : http://vim.wikia.com/wiki/Inserting_text_in_multiple_lines