The layout of a normal Roseau service is as following:
```lua
-- Service Name
-- Service Description
-- Username

-- Services
local Players = game:GetService("Players")

-- Modules
local GripEffect = require(script.Effects.Grip)
local AeroSignalModule

-- Module
local RoseauService = { }

-- Types
export type Settings = { }

-- Constants
local DefaultSettings = { }

-- Variables
local Cache = { } -- Set variables in self if possible so external scripts can read and write to it.

-- Client functions
function RoseauService.Client:DoSomething()

end

function RoseauService:Start()

end

function RoseauService:Init()

end

return RoseauService
```
