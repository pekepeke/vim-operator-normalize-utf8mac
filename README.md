operator-normalize-utf8mac
==========================

Operator to replace normalized utf8-mac text.
Version: 0.0.1
Author : pekepeke <pekepekesamurai+vim@gmail.com>
License: MIT
         <http://opensource.org/licenses/MIT>

*operator-normalize-utf8mac* is a Vim plugin to provide an operator mapping
to normalize utf8-mac text.

Requirement:
	- |operator-user| (Recommend latest version at https://github.com/kana/vim-operator-user)

Latest version:
	https://github.com/pekepeke/vim-operator-normalize-utf8mac

## CUSTOMIZE

### KEY MAPPINGS

##### <Plug>(operator-normalize_utf8mac){motion}

		Replace text that {motion} moves over with normalized texts.

### EXAMPLES


	nmap <expr> ,n <Plug>(operator-normalize_utf8mac)

