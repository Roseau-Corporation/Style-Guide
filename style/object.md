# Object
## Regular
All elements in an object must have a comma after, unless they are the last element in the object.
```lua
{
    ElementOne = "Value1",
    ElementTwo = "Value2",
    "Value3",
    ElementFour = "LastValue"
}
```
## Inline
If an object has 2 or fewer elements, it must be inline
```lua
{ 1, 2 }
```
All inline objects must have spaces surrounding the elements
```lua
{ 1, 2 }
```
If an object is empty, it must have only a single space
```lua
{ }
```
## Comments
If an object has consecutive comments (a comment per 1-2 elements) then the comments must be aligned
```lua
{
    1,      -- The number 1
    "Two",  -- The word 2
    "hi",
    "Three" -- The word 3
}
```