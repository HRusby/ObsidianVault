#Keybindings


## General Bindings
|Mode|Binding|Purpose|Category|
|------|-------|-------|--------|
|Normal|\<Space\>|Leader||
|Normal|\<C-h\>|Switch Window Left|#Navigation|
|Normal|\<C-j\>|Switch Window Down|#Navigation|
|Normal|\<C-k\>|Switch Window Up|#Navigation|
|Normal|\<C-l\>|Switch Window Right|#Navigation|
|Normal|\<Leader\>e|Toggle NvimTree Open/Close|#Navigation#NvimTree|
|Normal|\<Leader\>ff|Treesitter Find Files|#Navigation#TreeSitter|
|Normal|\<Leader\>gf|Treesitter Live Grep|#Navigation#TreeSitter|
|Normal|\<Leader\>p|Treesitter Project View|#Navigation#TreeSitter|
|Normal|\<Leader\>kf|Format File|#NullLs|
|Normal|\\|Show Registers||
|Normal|\<C-Up\>|Resize Window Up|#Navigation|
|Normal|\<C-Down\>|Resize Window Down|#Navigation|
|Normal|\<C-Left\>|Resize Window Left|#Navigation|
|Normal|\<C-Right\>|Resize Window Right|#Navigation|
|Normal|\<S-l\>|Next Buffer|#Buffers|
|Normal|\<S-h\>|Previous Buffer|#Buffers|
|Normal|\<A-j\>|Move Line Down||
|Normal|\<A-k\>|Move Line Up||
|Insert|jk|Exit Insert Mode||
|Visual|<|Indent Left||
|Visual|>|Indent Right||
|Visual|p|Paste over Selection||
|Visual Block|J<br/>\<A-j\>|Move Block Down||
|Visual Block|K<br/>\<A-k\>|Move Block Up||
|Terminal|\<Esc\>|Enter Normal Mode in Terminal||
|Terminal|jk|Enter Normal Mode in Terminal||
|Normal|\<C-\\\>|Open Terminal||


## Telesope Bindings
|Mode|Binding|Purpose|Category|
|----|-------|-------|--------|
|Insert|\<C-n\>|Cycle History Next||
|Insert|\<C-p\>|Cycle History Previous||
|Insert|\<C-j\>|Move Selection Next||
|Insert|\<C-k\>|Move Selection Previous||
|Insert|\<C-c\>|Close||
|Insert|\<Down\>|Move Selection Next||
|Insert|\<Up\>|Move Selection Previous||
|Insert|\<CR\>|Select Default||
|Insert|\<C-x\>|Select Horizontal||
|Insert|\<C-v\>|Select Vertical||
|Insert|\<C-t\>|Select Tab||
|Insert|\<C-u\>|Preview Scrolling Up||
|Insert|\<C-d\>|Preview Scrolling Down||
|Insert|\<PageUp\>|Result Scrolling Up||
|Insert|\<PageDown\>|Result Scrolling Down||
|Insert|\<Tab\>|Toggle Selection & Move Selection Worse||
|Insert|\<S-Tab\>|Toggle Selection & Move Selection Better||
|Insert|\<C-q\>|Send to Quick Find List & Open Quick Find List||
|Insert|\<M-q\>|Send Selected to Quick Find List & Open Quick Find List||
|Insert|\<C-l\>|Complete Tag||
|Insert|\<C-\_\>|Which Key||
|Normal|\<Esc\>|Close||
|Normal|\<CR\>|Select Default||
|Normal|\<C-x\>|Select Horizontal||
|Normal|\<C-v\>|Select Vertical||
|Normal|\<C-t\>|Select Tab||
|Normal|\<Tab\>|Toggle Selection & Move Selection Worse||
|Normal|\<S-Tab\>|Toggle Selection & Move Selection Better||
|Normal|\<C-q\>|Send to Quick Find List & Open Quick Find List||
|Normal|\<M-q\>|Send Selected to Quick Find List & Open Quick Find List||
|Normal|j|Move Selection Next||
|Normal|k|Move Selection Previous||
|Normal|H|Move to Top||
|Normal|M|Move to Middle||
|Normal|L|Move to Bottom||
|Normal|\<Down\>|Move Selection Next||
|Normal|\<Up\>|Move Selection Previous||
|Normal|gg|Move to Top||
|Normal|G|Move to Bottom||
|Normal|\<C-u\>|Preview Scrolling Up||
|Normal|\<C-d\>|Preview Scrolling Down||
|Normal|\<PageUp\>|Results Scrolling Up||
|Normal|\<PageDown\>|Results Scrolling Down||
|Normal|?|Which Key||

## LSP Bindings
|Mode|Binding|Purpose|Category|
|----|-------|-------|--------|
|Normal|gD|Go to Declaration||
|Normal|gd|Go to Definition||
|Normal|gi|Go to Implementation||
|Normal|gr|Show References||
|Normal|gl|Show Diagnostics||
|Normal|K|Show info on Cursor||
|Normal|\<C-k\>|Show Signature Help||
|Normal|\<Leader\>rn|Rename Symbol||
|Normal|\<Leader\>ca|Code Action||
|Normal|\#d|Go to Previous||
|Normal|\d|Go to Next||
|Normal|\<Leader\>q|Set Loc List||

## CMP Bindings
|Mode|Binding|Purpose|Category|
|------|-------|-------|--------|
|\<C-k\>|Select Previous Item||
|\<C-j\>|Select Next Item||
|\<C-b\>|Scroll Docs Backwards||
|\<C-f\>|Scroll Docs Forwards||
|\<C-Space\>|Complete the Mapping||
|\<C-e\>i|Abort Mapping||
|\<C-b\>c|Close Mapping||
|\<CR\>|Confirm Mapping||
|\<Tab\>|Select Next Item||
|\<S-Tab\>|Select Previous Item||

## NvimTree Bindings
|Mode|Binding|Purpose|Category|
|------|-------|-------|--------|
|Normal|l<br/>\<CR\><br/>o|Open File Under Cursor||
|Normal|h|Close Node||
|Normal|v|Open in Vertical Split||