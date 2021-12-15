
" start directory
:cd C:\Users\Evgeny Bardin

" Mapping to reload configuration
let mapleader = " "
nmap <leader>so :source $HOME\.vimrc<CR>

"default window size
set lines=30 columns=150

set guifont=Consolas:h11
set guioptions-=T
set encoding=utf8

" Включение поддержки русского языка
set keymap=russian-jcukenwin
set iminsert=0
set imsearch=0
highlight lCursor guifg=NONE guibg=Cyan

" Показывать положение курсора всё время.
set ruler

set number relativenumber
set tabstop=4 softtabstop=4
set shiftwidth=4
set expandtab
set smartindent
set ignorecase
set smartcase

nnoremap gb gT

" Включить подсветку синтаксиса
syntax on
colo evening

" delete over line breaks, or automatically-inserted indentation, or the place where insert mode started
set backspace=indent,eol,start

" share clipboard with OS
set clipboard=unnamed
" vnoremap <C-c> "*y

set hidden
set incsearch
set scrolloff=5

" ==================================
" ========   PlugIns      ==========
" ==================================

" Specify a directory for plugins
call plug#begin('~/.vim/plugged')
call plug#end()
