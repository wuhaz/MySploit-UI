  # MySploit UI

## Booting the Library
```lua
local UILibrary = loadstring(game:HttpGet("https://raw.githubusercontent.com/wuhaz/UI-Librarys/main/MySploit.lua"))()
```

## Creating a Window
```lua
local MainUI = UILibrary.Load("MySploit")
```

## Creating a Tab
```lua
local FirstPage = MainUI.AddPage("Home")
```

## Creating a Label
```lua
local FirstLabel = FirstPage.AddLabel("Label")
```

## Creating a Button
```lua
local FirstButton = FirstPage.AddButton("Hello", function()
print("MySploit")
end)
```

## Creating a Toggle
```lua
local FirstToggle = FirstPage.AddToggle("Hello", false, function(V)
print(V)
end)
```

## Creating a Slider
```lua
local FirstSlider = FirstPage.AddSlider("Hello", {Min = 0, Max = 250, Def = 50}, function(V)
print(Value)
end)
```

## Creating a Corlor Picker
```lua
local FirstPicker = FirstPage.AddColourPicker("Hello", "white", function(V)
print(V)
end)
```

## Creating a Dropdown Menu
```lua
local FirstDropdown = FirstPage.AddDropdown("Hello", {"Hello","Goodbye"}, function(V)
print(V)
end)
```
