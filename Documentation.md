# Shadow UI
This documentation is for Shadow UI Credit To The Owner

## Booting the Shadow UI Library
```lua
local library = loadstring(game:HttpGetAsync("https://raw.githubusercontent.com/ShaddowScripts/Main/main/Library"))()
```




## Creating a Shadow UI Window
```lua
local Main = library:CreateWindow("Main","Crimson")
```

## Creating a Tab
```lua
local tab = Main:CreateTab("Cheats")
```

## Creating a Tab 2 (Optional To Use A Second Tab For The UI)
```lua
local tab2 = Main:CreateTab("Misc")
```

## Creating a Button
```lua
tab:CreateButton("Hi",function()
print("clicked")
end)
```

## Creating a Toggle
```lua
tab:CreateToggle("Farm",function(a)
print(a)
end)
```

## Creating a Slider
```lua
tab:CreateSlider("Wow",1,16,function(a)
print(a)
end)
```

## Creating a Checkbox
```lua
tab:CreateCheckbox("Aimbot",function(a)
print(a)
end)
```

## Creating a Dropdown
```lua
tab:CreateDropdown("Word",{"Sung","Jin","Woo"},function(a)
print(a)
end)
```

## Creating a keybind
```lua
Section:NewKeybind("KeybindText", "KeybindInfo", Enum.KeyCode.F, function()
	print("You just clicked the bind")
end)
```

## Creating a Button 2 (Optional For Creating Secondary Buttons In Tabs)
```lua
tab2:CreateButton("Hello",function()
print("clicked")
end)
```

## Creating Tab Show
```lua
tab:Show()
```
