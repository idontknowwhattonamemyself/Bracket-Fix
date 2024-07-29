# Bracket-V2

<p align="center">
I'm releasing a UI my friend made like a month back. https://v3rmillion.net/member.php?action...uid=746442

<p align="center">
original release thread: https://v3rmillion.net/showthread.php?tid=1116477
<p align="center">
This used to be a private lib, but I was given permission to release the ui

<p align="center">
Example of how the ui looks:

<p align="center">
  <img width="542" height="533" src="https://user-images.githubusercontent.com/71396088/118593186-1ad56900-b75c-11eb-9a4e-897dbaadc83f.png">
</p>

<p align="center">
Video of me showing off the ui: https://www.youtube.com/watch?v=wHn6xTdsiiU
<p align="center">
Example usage of the ui: 

```
local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/idontknowwhattonamemyself/Bracket-Fix/main/src.lua"))()

-- Window
local Window, MainGUI = Library:CreateWindow("Bracket-V2")

-- Tabs
local Tab1 = Window:CreateTab("Tab 1")
local Tab2 = Window:CreateTab("Tab 2")

local Groupbox1 = Tab1:CreateGroupbox("Groupbox 1", "Left")
local Groupbox2 = Tab1:CreateGroupbox("Groupbox 2", "Right")

local Groupbox3 = Tab2:CreateGroupbox("Groupbox 1", "Left")
local Groupbox4 = Tab2:CreateGroupbox("Groupbox 2", "Right")

-- Groupbox 1
local ExampleToggle = Groupbox1:CreateToggle("Example toggle", function(state)
   print(state)
end)

local ExampleToggle2 = Groupbox1:CreateToggle("Example keybind", function(state)
   print(state)
end)

local ExampleButton = Groupbox1:CreateButton("Example Button", function()
    print("Pressed")
end)

ExampleToggle2:CreateKeyBind()

local ExampleSlider = Groupbox1:CreateSlider("Example slider", 0, 25, 0, function(value)
   print(value)
end)

local ExampleDropdown = Groupbox1:CreateDropdown("Example Dropdown", {"Option 1", "Option 2", "Option 3"}, function(state)
   print(state)
end)

local ExampleColorPicker = Groupbox1:CreateColorPicker("Color", Color3.fromRGB(0, 0, 0), function(state)
   print(state.R, state.G, state.B)
end)

-- Groupbox 2
local ExampleToggle2 = Groupbox2:CreateToggle("Example toggle", function(state)
   print(state)
end)

local ExampleToggle3 = Groupbox2:CreateToggle("Example keybind", function(state)
   print(state)
end)

local ExampleButton2 = Groupbox2:CreateButton("Example Button", function()
    print("Pressed")
end)

ExampleToggle3:CreateKeyBind()

local ExampleSlider2 = Groupbox2:CreateSlider("Example slider", 0, 25, 0, function(value)
   print(value)
end)

local ExampleDropdown2 = Groupbox2:CreateDropdown("Example Dropdown", {"Option 1", "Option 2", "Option 3"}, function(state)
   print(state)
end)

local ExampleColorPicker2 = Groupbox2:CreateColorPicker("Color", Color3.fromRGB(0, 0, 0), function(state)
   print(state.R, state.G, state.B)
end)

-- Groupbox 3
local ExampleToggle4 = Groupbox3:CreateToggle("Example toggle", function(state)
   print(state)
end)

local ExampleToggle5 = Groupbox3:CreateToggle("Example keybind", function(state)
   print(state)
end)

local ExampleButton3 = Groupbox3:CreateButton("Example Button", function()
    print("Pressed")
end)

ExampleToggle5:CreateKeyBind()

local ExampleSlider3 = Groupbox3:CreateSlider("Example slider", 0, 25, 0, function(value)
   print(value)
end)

local ExampleDropdown3 = Groupbox3:CreateDropdown("Example Dropdown", {"Option 1", "Option 2", "Option 3"}, function(state)
   print(state)
end)

local ExampleColorPicker3 = Groupbox3:CreateColorPicker("Color", Color3.fromRGB(0, 0, 0), function(state)
   print(state.R, state.G, state.B)
end)

-- Groupbox 4
local ExampleToggle5 = Groupbox4:CreateToggle("Example toggle", function(state)
   print(state)
end)

local ExampleToggle6 = Groupbox4:CreateToggle("Example keybind", function(state)
   print(state)
end)

local ExampleButton4 = Groupbox4:CreateButton("Example Button", function()
    print("Pressed")
end)

ExampleToggle6:CreateKeyBind()

local ExampleSlider4 = Groupbox4:CreateSlider("Example slider", 0, 25, 0, function(value)
   print(value)
end)

local ExampleDropdown4 = Groupbox4:CreateDropdown("Example Dropdown", {"Option 1", "Option 2", "Option 3"}, function(state)
   print(state)
end)

local ExampleColorPicker4 = Groupbox4:CreateColorPicker("Color", Color3.fromRGB(0, 0, 0), function(state)
   print(state.R, state.G, state.B)
end)
```
