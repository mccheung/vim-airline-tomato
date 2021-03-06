vim-airline-tomato
==================
  
##Introduction
This is vim-airline extension to display [Pomodoro Technique](http://en.wikipedia.org/wiki/Pomodoro_Technique)
  
##Required
* [Airline](https://github.com/bling/vim-airline): This is a extension of airline (like powerline, but more fast and KISS)
* [powerline-font](https://github.com/Lokaltog/powerline-fonts): if you use chinese font, you may need install powerline font

##Optional
* [pomicons](https://github.com/gabrielelana/pomicons): This is a font with 8 symbols to talk about the "Pomodoro Technique"® (You can use these special symbol to change the configuration). You can use one of the [awesome-terminal-fonts](https://github.com/gabrielelana/awesome-terminal-fonts) that contains both powerline and pomicons symbols
   
##Configuration
* If you want to change the working time:
> let g:tomato#interval = 60 * 60
  
* If you wat to change rest time:
> let g:tomato#rest_time = 20 * 60
  
* If you want to change language(english or chinese):
> let g:tomato#lang = 'chinese'
  
* If you want to change working text:
> let g:tomato#remind = "☻"  (" \uf003 " if you are using [awesome-terminal-fonts](https://github.com/gabrielelana/awesome-terminal-fonts))
  
* If you want to change rest text:
> let g:tomato#restinfo = "☺" (" \ue1f1 " if you are using [awesome-terminal-fonts](https://github.com/gabrielelana/awesome-terminal-fonts))

## Screenshot
![pomicons](https://github.com/gabrielelana/vim-airline-tomato/raw/pomicons-configuration/.screenshot/pomicons.png)

##Thanks
> Gabriele Lana <gabriele.lana@gmail.com> (provide awesome fonts)
  
==============================================================================
vim:tw=78:ts=8:ft=help:norl:noet:fen:fdl=0:
  
##License
MIT
