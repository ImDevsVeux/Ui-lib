
# This Is A Skidded ui lib From Forsaken!!! it's same as Forsaken 🤤

*it only have dropdown, slider , toggle, paragraph, Textbox no buttons yettt*


Make the window  
`local lib = loadstring(game:HttpGet("https://raw.githubusercontent.com/zijvxfmzjv-droid/Snsns/refs/heads/main/Bsnsn"))()  

local win = lib:CreateWindow({Title = "Name idk"})`

Tab -  
`local tab = win:CreateTab({Title = "a tab"})`

Toggle -  
`tab:Toggle({
    Title = "Toggle",
    Desc = "Example toggle",
    Callback = function(val)
        print(val)
    end
})`

Slider -  
`tab:Slider({
    Title = "Slider",
    Desc = "Example slider",
    Min = 16,
    Max = 100,
    Callback = function(val)
        print(val)
    end
})`

Textbox -  
`tab:Textbox({
    Title = "Textbox",
    Desc = "Example textbox",
    Callback = function(val)
        print(val)
    end
})`

Dropdown -  
`tab:Dropdown({
    Title = "Dropdown",
    Desc = "Example dropdown",
    Options = {"Option 1", "Option 2", "Option 3"},
    Callback = function(pick)
        print(pick)
    end
})`


The Ui lib is open sourced at  
https://raw.githubusercontent.com/zijvxfmzjv-droid/Snsns/refs/heads/main/Bsnsn  

And used many plugins to make it.
