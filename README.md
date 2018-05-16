# Apama editor syntax files

## License
Copyright (c) 2018 Software AG, Darmstadt, Germany and/or its licensors

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this
file except in compliance with the License. You may obtain a copy of the License at
http://www.apache.org/licenses/LICENSE-2.0
Unless required by applicable law or agreed to in writing, software distributed under the
License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND,
either express or implied. 
See the License for the specific language governing permissions and limitations under the License.


## VIM syntax hilighting for Apama EPL
The file [monitorscript.vim](monitorscript.vim) contains syntax hilighting
rules for editing Apama EPL (.mon) files in the VIM editor.

To install the syntax rules, copy the file to $HOME/.vim/syntax/monitorscript.vim 
and add the following lines to $HOME/.vim/filetype.vim

au BufRead,BufNewFile *.mon set filetype=monitorscript
au BufRead,BufNewFile *.evt set filetype=monitorscript


## EMACS syntax hilighting for Apama EPL
The file [monitorscript.el](monitorscript.el) contains syntax hilighting 
rules for editing Apama EPL (.mon) files in the EMACS editor.

To install the syntax rules, copy the file to $HOME/.emacs.d/monitorscript.el
and add the following lines to $HOME/.emacs

(add-to-list 'load-path "~/.emacs.d/")
(load "monitorscript")

