# Pratical Vim and Neovim

from pipeline to your make commands
- Quantity | Verbs (modifier of object)
- Quantity | Verbs | Modifiers | Nouns
- Quantity | Verbs | Nouns

Quantity:
 - Integer [-Inf < number (not is Zero) < Inf]
 - Percente (1% -> 100%)

Verbs:
 - `c` (change)
 - `d` (delete)
 - `h` (move left)
 - `j` (move down)
 - `k` (move up)
 - `l` (move right)
 - `p` (paste)
 - `v` (visual)
 - `y` (yank/copy)

Modifiers:
 - `/` (search the string or regex)
 - `a` (around)
 - `f` (find the character)
 - `i` (inside)
 - `t` (find till the character)

Nouns:
 - `b` (block/parentheses)
 - `p` (paragraph)
 - `s` (sentence)
 - `t` (tag of html/xml)
 - `w` (word)

# Commands

## Modo Normal

cmd: `dib` or `di(` or `di)`
 - (word1 word2) -> ()

cmd: `di[` or `di]`
 - [word1 word2] -> []

cmd: `diB` or `di{` or `di}`
 - {word1 word2} -> {}

cmd: ``di` ``
 - \`word1 word2\` -> \`\`

cmd: `di'`
 - 'word1 word2' -> ''

cmd: `di"`
 - "word1 word2" -> ""

cmd: `dit`
 - `<div>Delete inner Tag</div>` -> `<div></div>`

## Commands - Others:

### Modo Normal:

 - `<Ctrl+a>` (Increment)
 - `<Ctrl+i>` (Decrement)

### Modo Insert:
 - `<Ctrl+x><Ctrl+n>` (Autocomplete word)
 - `<Ctrl+x><Ctrl+l>` (Autocomplete line)
 - `<Ctrl+x><Ctrl+f>` (Autocomplete file system)
 - `<Ctrl+x><Ctrl+k>` (Autocomplete dictionary)
 - `<Ctrl+y>` (Yank from line above and paste)

## Comands - Done:

### Modo Normal:

 - `di"`
 - `di'`
 - `di(`
 - `di)`
 - `diB`
 - `di[`
 - ``di` ``
 - `di]`
 - `dib`
 - `dit`
 - `di{`
 - `di}`


## Comands - Backlog:

### Modo Normal:
 - `A`
 - `I`
 - `P`
 - `a`
 - `dW`
 - `da(`
 - `da)`
 - `daB`
 - `da[`
 - ``da` ``
 - `da]`
 - `dab`
 - `dap`
 - `dat`
 - `da{`
 - `da}`
 - `dd`
 - `dw`
 - `i` (modo insert)
 - `p`
 - `yE`
 - `yW`
 - `ye`
 - `yw`
 - `yy`
 - `[s` (Nav match spell)
 - `]s` (Nav match spell)
