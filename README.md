# JuliaFormatter.vim

Plugin for formatting Julia code in (n)vim using [JuliaFormatter.jl](https://github.com/domluna/JuliaFormatter.jl).

### Install

Use any plugin manager:

**[vim-plug](https://github.com/junegunn/vim-plug)**

```vim
Plug 'kdheepak/JuliaFormatter.vim'
```

**[dein.vim](https://github.com/Shougo/dein.vim)**

```vim
call dein#add('kdheepak/JuliaFormatter.vim')
```

**[Vundle.vim](https://github.com/junegunn/vim-plug)**

```vim
Plugin 'kdheepak/JuliaFormatter.vim'
```

### Run JuliaFormatter

Open any Julia file, type `:` to open the command prompt and type the following:

```vim
:call JuliaFormatter#Format()
```

You can remap this to a keyboard shortcut as well.

```vim
" normal mode mapping
nnoremap <localleader>f :<C-u>call JuliaFormatter#Format(0)<CR>
" visual mode mapping
vnoremap <localleader>f :<C-u>call JuliaFormatter#Format(1)<CR>
```
