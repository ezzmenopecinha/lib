# About
Asrua UI is a short example of a roblox ui library!

![](https://github.com/Astralic62/AstralicPrototypeUI/assets/140242928/ef4d58b8-93a2-434b-963e-a93e20432faf)
# Usage
Load and Create Executon UI
```lua
local Lib = loadstring(game:HttpGet(""))():MakePrototypeLibrary("Execution UI")
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
