### note

I'm using now this setup for months:
```vim
Plug 'pangloss/vim-javascript', { 'for': ['javascript', 'javascript.jsx'] }
Plug 'mxw/vim-jsx', { 'for': ['javascript', 'javascript.jsx'] }
```
and I'm very happy with it.

If I remember correctly the initial necessity for this plugin was some problems with the combination of [yajs](https://github.com/othree/yajs.vim) and the [jsx plugin](https://github.com/mxw/vim-jsx), by using just [pangloss JS plugin](https://github.com/pangloss/vim-javascript) I'm having no problems at all now and all the new ES stuff just works, including the semicolon-less style.

Yajs was kind of nice on the eyes but was getting slower and slower for me after every update, and the colouring was not much consistent IMHO.

Hope this helps. 

# vim-js-indent
JavaScript indentation for VIM

This project just hosts the 'indent' part from the (excellent) [vim-javascript](https://github.com/pangloss/vim-javascript) plugin by [Darrick Wiebe (*pangloss*)](https://github.com/pangloss).

The `vim-javascript` plugin is not very actively maintained any more and it's lacking all the new JSX/ES6 language features. Most JS developers out there are switching to [yajs](https://github.com/othree/yajs.vim) or [vim-javascript-syntax](https://github.com/jelera/vim-javascript-syntax) but both of those, even tho they are inspired and/or forked from `vim-javascript`, lack the indentation that `vim-javascript` provided.

So here it goes, `vim-js-indent` providing just this piece of functionality.

Installation is straightforward, just clone it in your *~/.vim/bundle* or use any plugin manager out there, like [pathogen](https://github.com/tpope/vim-pathogen), [vundle](https://github.com/VundleVim/Vundle.vim), [neobundle](https://github.com/Shougo/neobundle.vim).
There is no need for any `make` or `build` steps, just plain clone will do the work.
