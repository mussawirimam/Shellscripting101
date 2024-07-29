# Shellscripting101
**To display the history without the numbers**
```
$ history | cut -c 8-
```
**To display the history without the numbers**
```
history | sed 's/^ *[0-9]* *//'
```
