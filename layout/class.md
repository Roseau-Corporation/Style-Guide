```lua
-- Class Name
-- Class Description
-- Username

-- Class Creator
local ClassCreator = { }

-- Class
local Class = { }
Class.__index = Class

-- Types
type Properties = { }

-- Constants
local DefaultProperties = { }

function ClassCreator.new(Properties: Properties)
    local self = setmetatable({ }, Class)

    if(Properties) then
        for Property, Value in pairs(DefaultProperties) do
            Properties[Property] = Properties[Property] or Value
        end
    end
    Properties = Properties or DefaultProperties

    return self
end

return ClassCreator
```
