# zsh-vi-search
Adds support for searching the current line (in normal vi mode) to zsh.

## Install
Download [zsh-vi-search.zsh](https://raw.githubusercontent.com/soheilpro/zsh-vi-search/master/src/zsh-vi-search.zsh) and source it somewhere in your .zshrc file.

## Usage
+ <kbd>/</kbd> Search forward
+ <kbd>?</kbd> Search backward
+ <kbd>n</kbd> Repeat last search
+ <kbd>N</kbd> Repeat last search in the opposite direction

## Version History
+ 1.0.2
	+ Fixed [#3](https://github.com/soheilpro/zsh-vi-search/issues/3): Always search starting after/before $CURSOR, not on it. (Thanks [comex](https://github.com/comex))
+ 1.0.1
	+ Fixed [#2](https://github.com/soheilpro/zsh-vi-search/issues/2): Not working when "sh_word_split" enabled (Thanks [aoyama-val](https://github.com/aoyama-val))
+ 1.0
	+ Initial release.

## Author
Soheil Rashidi

+ http://soheilrashidi.com
+ http://twitter.com/soheilpro
+ http://github.com/soheilpro

## Copyright and License
Copyright 2018 Soheil Rashidi.

Licensed under the The MIT License (the "License");
you may not use this work except in compliance with the License.
You may obtain a copy of the License in the LICENSE file, or at:

http://www.opensource.org/licenses/mit-license.php

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
