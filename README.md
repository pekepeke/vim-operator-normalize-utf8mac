operator-normalize-utf8mac
==========================

Operator to replace normalized utf8-mac text.

Version: 0.0.1  
Author : pekepeke <pekepekesamurai+vim@gmail.com>  
License: MIT <http://opensource.org/licenses/MIT>
	Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:  
	The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.  
	HE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

## INTRODUCTION

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

