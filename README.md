# nvim-and-all-else

## exclude file types coc search
since coc search is rg underneath 

use --type file_extenstion, like below

rg --type html header


add to fzf config

  \   'rg --column --line-number --hidden --smart-case --no-heading  --glob="!{.git}" --glob="!package-lock.json" --color=always '.shellescape(<q-args>), 1,
