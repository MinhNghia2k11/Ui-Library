# Source
```lua
local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/MinhNghia2k11/Ui-Library/main/Source"))()
```

# Make Windows
```lua
local Windows = Library:MakeWindow({Title = "Sitink Lib", Creator = "Your Name", LogoHub = "rbxassetid://18374900760"})
```

# Make Notification
```lua
Library:CreateNotify({
    Title = "Notification",
    Content = "Sitink Hub moi duoc co 3% ma ncc",
    Time = 5
})
```

# Make Tab
```lua
local Tab = Windows:MakeTab({Name = "Tab", Logo = "rbxassetid://18394523673"})
```

# Make Section
```lua
Tab:MakeSection({Title = "Section"})
```

# Make Label
```lua
Tab:MakeLabel({Title = "Label"})
```

# Make Paragraph
```lua
Tab:MakeParagraph({
    Title = "Paragraph",
    Description = "This Is Paragraph"
})
```

# Make Button
```
Tab:MakeButton({
    Name = "Button",
    Description = "Is This Button",
    Callback = function()
        print("Hello World")
    end
})
```

# Make Toggle
```lua
local Toggle = Tab:MakeToggle({
    Name = "Toggle",
    Description = "Is This Toggle",
    Default = false,
    Setting = false,
    Callback = function(Value)
        print(Value)
    end
})
```

# Make Settings For Toggle
```lua
Toggle:MakeSetting({
    Name = "Settings Toggle",
    Default = false,
    Callback = function(Value)
        print(Value)
    end
})
```

# Make Dropdown
```lua
local Dropdown = Tab:MakeDropdown({
    Name = "Dropdown",
    Description = "I'm a Dropdown",
    List = {"1", "2"},
    Default = "1",
    Callback = function(Value)
        print(Value)
    end
})
```

# Make Slider
```lua
Tab:MakeSlider({
    Name = "Slider",
    Max = 300,
    Min = 50,
    Default = 100,
    Callback = function(Value)
        print(Value)
    end
})
```

# Make TextBox
```lua
Tab:MakeTextBox({
    Name = "Textbox",
    Default = "...",
    Callback = function(Value)
        print(Value)
    end
}
```
