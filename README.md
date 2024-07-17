# Source
```lua
local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/MinhNghia2k11/Ui-Library/main/Source"))()
```

# Make Windows
```lua
local Windows = Library:MakeWindow({
	Name = "Sitink Hub", 
	Description = "By ! Nightx", 
	LogoInfo = "rbxassetid://18448428761",
	NameInfo = "Owner Info",
    NamePlayers = "! Nightx",
    InfoColor = Color3.fromRGB(255, 38, 42),
    LogoPlayers = "rbxassetid://18448428761",
	InfoDesc = "Name : Lương Minh Nghĩa | Birthday : 12/08/2011 | discord.gg/JURvkuHr28"
})
```

# Make Notification
```lua
Library:MakeNotify({
    Title = "Sitink Hub",
    Content = "Notification",
    Description = "Nah i'd Win",
    Time = 5 
})
```

# Make Tab
```lua
local Tab = Windows:MakeTab({Name = "Tab"})
```

# Make Section Tab
```lua
local SectionTab = Tab1:MakeSection({
    Title = "Tab",
    Content = "Nigga"
})
```

# Make Section
```lua
SectionTab:Section("Cocaiconcac")
```

# Make Paragraph
```lua
SectionTab:MakeParagraph({
    Title = "Paragraph",
    Description = "This Is Paragraph"
})
```

# Make Button
```
SectionTab:MakeButton({
    Name = "Button",
    Description = "Is This Button",
    Callback = function()
        print("Hello World")
    end
})
```

# Make Toggle
```lua
local Toggle = SectionTab:MakeToggle({
    Name = "Toggle",
    Description = "Is This Toggle",
    Default = false,
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
