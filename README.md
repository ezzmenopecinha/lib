# About
Execution is a simple library []()
# Usage
Load and Create Executon UI
```lua
local Lib = loadstring(game:HttpGet("https://raw.githubusercontent.com/ezzmenopecinha/lib/main/v1.lua"))():MakePrototypeLibrary("Execution UI")
```
Make a Tab
```lua
local CuteTab = Lib:MakeTab("my cute tab", false) -- true to make it open by default (optional)
```
Make a Comment (Info Text)
```lua
CuteTab:Info("i love cute cats")
```
Make a Button
```lua
CuteTab:Button("click for a cookie", function()
print("biscuit")
end)
```
Make a Toggle
```lua
CuteTab:Toggle("press me", function(value)
print(value)
end)
```
