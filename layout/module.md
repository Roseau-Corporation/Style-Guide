The layout of a normal Roseau module is as following:
```lua
-- Module Name
-- Module Description
-- Username

-- Services
local Players = game:GetService("Players")

-- Modules
local GripEffect = require(script.Effects.Grip)
local AeroSignalModule

-- Module
local RoseauModule = { }

-- Types
export type Settings = { }

-- Constants
local DefaultSettings = { }

-- Variables
local Cache = { } -- Set variables in self if possible so external scripts can read and write to it.

function RoseauModule:Start()

end

function RoseauModule:Init()

end

return RoseauModule
```
