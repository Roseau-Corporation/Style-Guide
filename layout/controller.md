# Controller
The layout of a normal Roseau controller is as following:
```lua
-- Controller Name
-- Controller Description
-- Username

-- Services
local Players = game:GetService("Players")

-- Modules
local GripEffect = require(script.Effects.Grip)
local AeroSignalModule

-- Module
local RoseauController = { }

-- Types
export type Settings = { }

-- Constants
local DefaultSettings = { }

-- Variables
local Cache = { } -- Set variables in self if possible so external scripts can read and write to it.

function RoseauController:Start()

end

function RoseauController:Init()

end

return RoseauController
```