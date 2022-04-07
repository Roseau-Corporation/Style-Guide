# Unused Variables
Unused variables are strictly disallowed, unless inside of a tuple or to ignore arguments.  

If they are used, define as following:
```lua
local _, _, Z = PartCFrame:ToEulerAnglesXYZ()
```