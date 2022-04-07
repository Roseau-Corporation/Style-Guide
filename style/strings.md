# Strings
Use double parenthesis (``"``)
Do not use the concatenation operator. (``..``) For example, instead of using
```lua
Player.Name.." joined!"
```
use 
```lua
string.format("%s joined!", Player.Name)
```  

Implement ``string.format()`` support in commonly used functions that take a string as an argument, such as a custom logging function.