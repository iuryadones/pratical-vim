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

![Delete inside brackets](https://github.com/iuryxavier/pratical-vim/blob/master/gifs/vokoscreen-2018-03-08_16-05-51.gif "delete inside brackets")

cmd: `di[` or `di]`

![Delete inside square brackets](https://github.com/iuryxavier/pratical-vim/blob/master/gifs/vokoscreen-2018-03-08_16-53-14.gif "delete inside square brackets")

cmd: `diB` or `di{` or `di}`

![Delete inside curly brackets](https://github.com/iuryxavier/pratical-vim/blob/master/gifs/vokoscreen-2018-03-09_12-31-59.gif "delete inside curly brackets")

cmd: ``di` ``

![Delete inside backquotes](https://github.com/iuryxavier/pratical-vim/blob/master/gifs/vokoscreen-2018-03-08_16-36-07.gif "delete inside backquotes")

cmd: `di'`

![Delete inside apostrophes](https://github.com/iuryxavier/pratical-vim/blob/master/gifs/vokoscreen-2018-03-08_16-25-26.gif "delete inside apostrophes")

cmd: `di"`

![Delete inside quotation marks](https://github.com/iuryxavier/pratical-vim/blob/master/gifs/vokoscreen-2018-03-09_11-57-58.gif "delete inside quotation marks")

cmd: `dit`

![Delete inside tags](https://github.com/iuryxavier/pratical-vim/blob/master/gifs/vokoscreen-2018-03-09_12-40-33.gif "delete words inside tags")

## Modo Visual

### UTILIZANDO O CORRETOR E ATUALIZANDO O DICIONÁRIO
Em modo visual os comandos:
 - `]s` vai para a próxima palavra;
 - `[s` vai para a palavra anterior;
 - `z=` mostra a lista de sugestões para a palavra;
 - `zg` adiciona a palavra sob o cursor no dicionário, assim ela não será mais marcada como errada;
 - `zug` desfaz a última palavra adicionada;
 - `zw` remove a palavra sob o cursor do dicionário, assim ela será marcada como errada;
 - `zuw` desfaz a última palavra removida.


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
