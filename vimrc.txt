  1 syntax on
  2 colorscheme atomified
  3 set termguicolors
  4 
  5 set exrc
  6 set secure
  7 
  8 highlight LineNr ctermfg=grey ctermbg=black
  9 set statusline="%f%m%r%h%w [%Y] [0x%02.2B]%< %F%=%4v,%4l %3p%% of %L"
 10 set number
 11 set autoindent
 12 set shiftwidth=4
 13 set softtabstop=4
 14 set noexpandtab
 15 set wrap
 16 set showmode
 17 set hlsearch
 18 set matchpairs+=<:>
 19 set ttyfast
 20 
 21 augroup project
 22     autocmd!
 23     autocmd BufRead,BufNewFile *.h,*.c set filetype=c.doxygen
 24 augroup END
 25 
 26 set colorcolumn=110
 27 highlight ColorColumn ctermbg=darkgray
~
~
~
~
~
~
~
~
~
~
~
~
~
~
-- INSERT --

