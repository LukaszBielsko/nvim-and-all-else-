# nvim-and-all-else

## exclude file types coc search
since coc search is rg underneath 

use --type file_extenstion, like below

rg --type html header

## more lines in coc search results
-A lines_count will do it

rg --type html -A 20 header





