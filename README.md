# Vimfiles


## Como usar

Clone o repositorio para o seguinte diretorio `~/.vim` e instale os plugins

    git clone git://github.com/mrato/myvim.git ~/.vim
    git clone https://github.com/gmarik/vundle.git ~/.vim/bundle/vundle
    ln -s ~/.vim/vimrc ~/.vimrc
    vim +PluginInstall +qall

**Opcional:**

(OS X) Copie a font Monaco:

    cp ~/.vim/fonts/Monaco+for+Powerline.otf ~/Library/Fonts/

Instale jshint:

    sudo npm install -g jshint

## Color Schemes

* base16-ocean *(current)*
* Other ["base16" themes](http://chriskempson.github.io/base16/)

## Fontes

* Monaco *(my current one)*
* Anonymous Pro
* Inconsolata-dz
* Bitstream Vera Sans Mono

## Plugins

| Plugin                                                              | Description                                                         | Interesting links                  |
| :------------------------------------------------------------------ | :------------------------------------------------------------------ | :--------------------------------- |
| [Ag.vim](https://github.com/rking/ag.vim)                           | Plugin for ag (the_silver_searcher)                                 |                                    |
| [Base16](https://github.com/chriskempson/base16-vim)                | Amazing colorschema                                                 |                                    |
| [Colorizer](https://github.com/lilydjwg/colorizer)                  | Colorize all text in the form #rrggbb or #rgb                       |                                    |
| [CtrlP](https://github.com/kien/ctrlp.vim)                          | Full path fuzzy file, buffer, mru and tag finder                    | [Website](http://goo.gl/nUQ1lA)    |
| [Dockerfile.vim](https://github.com/ekalinin/Dockerfile.vim)        | Vim syntax file & snippets for Docker's Dockerfile                  |                                    |
| [Extradite](https://github.com/int3/vim-extradite)                  | A git commit browser. Extends fugitive.vim                          |                                    |
| [Fugitive](https://github.com/tpope/vim-fugitive)                   | A git wrapper so awesome, it should be illegal                      |                                    |
| [Matchit.zip](https://github.com/vim-scripts/matchit.zip)           | Extended % matching for HTML, LaTeX, and many other languages       |                                    |
| [Multiple Cursors](https://github.com/terryma/vim-multiple-cursors) | True Sublime Text style multiple selections                         |                                    |
| [Nerdtree](https://github.com/scrooloose/nerdtree)                  | A tree explorer plugin                                              |                                    |
| [Rename](https://github.com/danro/rename.vim)                       | Basically does a ":saveas <newfile>" then removes the old filename  |                                    |
| [Smartpairs](https://github.com/gorkunov/smartpairs.vim)            | Fantastic selection, replaces hard keys combination like vi{ or va" |                                    |
| [Snipmate](https://github.com/msanders/snipmate.vim)                | Implements some of TextMate's snippets                              |                                    |
| [Sparkup (Zen-coding)](https://github.com/rstacruz/sparkup)         | A parser for a condensed HTML format                                | [Zen coding](http://goo.gl/E4BVWd) |
| [Syntastic](https://github.com/scrooloose/syntastic)                | Syntax checking hacks                                               |                                    |
| [Tabular](https://github.com/godlygeek/tabular)                     | Text filtering and alignmentClone                                   |                                    |
| [Tcomment](https://github.com/tomtom/tcomment_vim)                  | An extensible & universal comment vim-plugin                        |                                    |
| [Vim Abolish](https://github.com/tpope/vim-abolish)                 | Easily search for, substitute, and abbreviate variants of a word    | [Vim Casts](http://goo.gl/CsfUJ6)  |
| [Vim Airline](https://github.com/bling/vim-airline)                 | Lean & mean status / tabline                                        |                                    |
| [Vim Coffee Script](https://github.com/kchmck/vim-coffee-script)    | CoffeeScript support for Vim                                        |                                    |
| [Vim Easymotion](https://github.com/Lokaltog/vim-easymotion/)       | It provides a much simpler way to use some motions in Vim           |                                    |
| [Vim Endwise](https://github.com/tpope/vim-endwise)                 | Wisely add "end" in ruby                                            |                                    |
| [Vim Gitgutter](https://github.com/airblade/vim-gitgutter)          | Shows a git diff in the gutter (sign column)                        |                                    |
| [Vim Rails](https://github.com/tpope/vim-rails)                     | Ruby on Rails power tools                                           |                                    |
| [Vim Ruby Runner](https://github.com/henrik/vim-ruby-runner)        | Execute Ruby into an output buffer                                  |                                    |



Visit the following sites to learn more about Vim:

* [Screencast "17 tips for Vim" (in Portuguese)](http://blog.lucascaton.com.br/?p=1081)
* [Learn Vim Progressively](http://yannesposito.com/Scratch/en/blog/Learn-Vim-Progressively/)
* [Vim Adventures](http://vim-adventures.com/)
* [Vimcasts](http://vimcasts.org)
* [Using Vim as a Complete Ruby on Rails IDE](http://biodegradablegeek.com/2007/12/using-vim-as-a-complete-ruby-on-rails-ide/)
* [Why, oh WHY, do those #?@! nutheads use vi?](http://www.viemu.com/a-why-vi-vim.html)
* [Byte of Vim](http://www.swaroopch.com/notes/Vim)

## Other dotfiles

You can find my dotfiles here: [lucascaton/dotfiles](https://github.com/lucascaton/dotfiles).

## Credits

Created and maintained by [Lucas Caton](https://lucascaton.com.br).

* [My blog](http://blog.lucascaton.com.br/)
* [My twitter](http://twitter.com/lucascaton)

## License

**The MIT License (MIT)**

**Copyright (c) 2010 - 2016 Lucas Caton**

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
