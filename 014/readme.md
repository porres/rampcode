# Rampcode

RC is a bytebeat inspired livecoding language written in pd. Everything is a function of one time ramp (phasor~).
This is still very beta, full doc soon. Check the examples.

# Setup

## /usr/share/vim/vimrc

Add
`autocmd BufNewFile,BufRead *.gede nnoremap <buffer> <c-e> :silent exec '!./sendline.sh ' . shellescape(getline('.'), 1)<CR>:redraw!<CR>`

## Syntax suggestion
`:set filetype=haskell`

# New:

- Line evaluation in vim
- New syntax with regex stuff
- Handle FXs by name separately
- Sample&Hold effect
- Random time can be set

# Soon:

- Instrument presets 
- Full documentation