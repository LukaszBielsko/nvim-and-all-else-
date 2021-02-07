# nvim-and-all-else

## exclude file types coc search
since coc search is rg underneath 

use --type file_extenstion, like below

rg --type html header

## more lines in coc search results
-A lines_count will do it

rg --type html -A 20 header



# add to vim config

  \   'rg --column --line-number --hidden --smart-case --no-heading  --glob="!{.git}" --glob="!package-lock.json" --color=always '.shellescape(<q-args>), 1,


nnoremap <leader>psf :CocSearch <C-R>=expand("<cword>")<CR> --type 
  
nnoremap \<c-g>\<c-g> :Rg<CR>
  
  execute 'inoremap \<buffer> \<silent> \<BS> \<C-R>=AutoPairsDelete()\<CR>'



