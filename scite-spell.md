It is simplified spell check tool orthospell installation for scite.

Based on: Urs Eberle's orthospell http://tools.diorama.ch/orthospell.html (GNU GPL v2).

## download spell-check bundle
download [scite-spell.zip](https://github.com/robertluwang/scite-setting/blob/master/scite-spell.zip), it includes:
```
scite_lua\orthospell.lua
en_US.aff  
en_US.dic  
extman.lua  
hunspell.dll   
shell.dll
```
extract and copy above stuff to scite root folder, only needs default US English dictionary. 

## spell check config in scite
spell check setting in SciTEGlobal.properties or SciTEUser.properties.
```
#  spell check
ext.lua.startup.script=$(SciteDefaultHome)\extman.lua
file.patterns.spell=*.txt;*.html;*.htm;*.tex;*.latex;*.md
```

## turn on spell checker
F9 to Toggle Spelling, will see red underline for word, you can double check it, small pop up windows show up the possible correct word list, you click good one, will replace in scite editor.
