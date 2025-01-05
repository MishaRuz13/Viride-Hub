local Noclip = nil
local Clip = nil

function noclip()
    Clip = false
    local function Nocl()
        if Clip == false and game.Players.LocalPlayer.Character ~= nil then
            for _,v in pairs(game.Players.LocalPlayer.Character:GetDescendants()) do
                if v:IsA('BasePart') and v.CanCollide and v.Name ~= floatName then
                    v.CanCollide = false
                end
            end
        end
        wait(0.21) -- basic optimization
    end
    Noclip = game:GetService('RunService').Stepped:Connect(Nocl)
end

function clip()
    if Noclip then Noclip:Disconnect() end
    Clip = true
end

local Fluent = loadstring(game:HttpGet("https://github.com/dawid-scripts/Fluent/releases/latest/download/main.lua"))()
local SaveManager = loadstring(game:HttpGet("https://raw.githubusercontent.com/dawid-scripts/Fluent/master/Addons/SaveManager.lua"))()
local InterfaceManager = loadstring(game:HttpGet("https://raw.githubusercontent.com/dawid-scripts/Fluent/master/Addons/InterfaceManager.lua"))()

local Window = Fluent:CreateWindow({
    Title = "Viride Hub | Break In 2",
    SubTitle = "By Misharuz13",
    TabWidth = 160,
    Size = UDim2.fromOffset(580, 460),
    Acrylic = true,
    Theme = "Darker",
    MinimizeKey = Enum.KeyCode.LeftControl
})

local Tabs = {
    Main = Window:AddTab({ Title = "Main | In Lobby", Icon = "home" }),
    Items = Window:AddTab({ Title = "Get Items", Icon = "cookie" }),
    Misc = Window:AddTab({ Title = "Misc", Icon = "circle-ellipsis" }),
    Settings = Window:AddTab({ Title = "Settings", Icon = "settings" })
}

local Options = Fluent.Options

do
    Tabs.Main:AddSection("Free Gamepass")
    Tabs.Main:AddParagraph({
        Title = "Tip",
        Content = "The Free Hacker's Phone Doesn't Work"
    })



    Tabs.Main:AddButton({
        Title = "Free Hacker",
        Description = "",
        Callback = function()
            local args = {
                [1] = "Phone",
                [2] = true,
                [3] = false
            }
            game:GetService("ReplicatedStorage").RemoteEvents.OutsideRole:FireServer(unpack(args))
        end
    })
    Tabs.Main:AddButton({
        Title = "Free Nerd",
        Description = "",
        Callback = function()
            local args = {
                [1] = "Book",
                [2] = true,
                [3] = false
            }
            game:GetService("ReplicatedStorage").RemoteEvents.OutsideRole:FireServer(unpack(args))
        end
    })


    Tabs.Items:AddSection("Food")
    Tabs.Items:AddButton({
        Title = "Apple",
        Description = "",
        Callback = function()
            local args = {
                [1] = "Apple"
            }
            game:GetService("ReplicatedStorage").Events.GiveTool:FireServer(unpack(args))
        end
    })
    Tabs.Items:AddButton({
        Title = "Cookie",
        Description = "",
        Callback = function()
            local args = {
                [1] = "Cookie"
            }
            game:GetService("ReplicatedStorage").Events.GiveTool:FireServer(unpack(args))
        end
    })
    Tabs.Items:AddButton({
        Title = "Pizza",
        Description = "",
        Callback = function()
            local args = {
                [1] = "Pizza"
            }
            game:GetService("ReplicatedStorage").Events.GiveTool:FireServer(unpack(args))
        end
    })
    Tabs.Items:AddButton({
        Title = "Bloxy Cola",
        Description = "",
        Callback = function()
            local args = {
                [1] = "BloxyCola"
            }
            game:GetService("ReplicatedStorage").Events.GiveTool:FireServer(unpack(args))
        end
    })
    Tabs.Items:AddButton({
        Title = "Golden Apple",
        Description = "",
        Callback = function()
            local args = {
                [1] = "GoldenApple"
            }
            game:GetService("ReplicatedStorage").Events.GiveTool:FireServer(unpack(args))
        end
    })
    Tabs.Items:AddButton({
        Title = "Gold Pizza",
        Description = "",
        Callback = function()
            local args = {
                [1] = "GoldPizza"
            }
            game:GetService("ReplicatedStorage").Events.GiveTool:FireServer(unpack(args))
        end
    })
    Tabs.Items:AddButton({
        Title = "Rainbow Pizza",
        Description = "",
        Callback = function()
            local args = {
                [1] = "RainbowPizza"
            }
            game:GetService("ReplicatedStorage").Events.GiveTool:FireServer(unpack(args))
        end
    })


    Tabs.Items:AddSection("Weapons And Armor")
    Tabs.Items:AddButton({
        Title = "Bat",
        Description = "",
        Callback = function()
            local player = game.Players.LocalPlayer
            local args = {
                [1] = 3,
                [2] = "Bat",
                [3] = "Weapons",
                [4] = player.Name 
            } 
            game:GetService("ReplicatedStorage").Events.Vending:FireServer(unpack(args))
        end
    })
    Tabs.Items:AddButton({
        Title = "Wrench",
        Description = "",
        Callback = function()
            local player = game.Players.LocalPlayer
            local args = {
                [1] = 3,
                [2] = "Wrench",
                [3] = "Weapons",
                [4] = player.Name 
            } 
            game:GetService("ReplicatedStorage").Events.Vending:FireServer(unpack(args))
        end
    })
    Tabs.Items:AddButton({
        Title = "Pitchfork",
        Description = "",
        Callback = function()
            local player = game.Players.LocalPlayer
            local args = {
                [1] = 3,
                [2] = "Pitchfork",
                [3] = "Weapons",
                [4] = player.Name,
                [5] = 0
            }
            game:GetService("ReplicatedStorage").Events.Vending:FireServer(unpack(args))
        end
    })
    Tabs.Items:AddButton({
        Title = "Hammer",
        Description = "",
        Callback = function()
            local player = game.Players.LocalPlayer
            local args = {
                [1] = 3,
                [2] = "Hammer",
                [3] = "Weapons",
                [4] = player.Name,
                [5] = 0
            }
            game:GetService("ReplicatedStorage").Events.Vending:FireServer(unpack(args))
        end
    })
    Tabs.Items:AddButton({
        Title = "Broom",
        Description = "",
        Callback = function()
            local player = game.Players.LocalPlayer
            local args = {
                [1] = 3,
                [2] = "Broom",
                [3] = "Weapons",
                [4] = player.Name,
                [5] = 0
            }
            game:GetService("ReplicatedStorage").Events.Vending:FireServer(unpack(args))
        end
    })
    Tabs.Items:AddButton({
        Title = "Armor",
        Description = "",
        Callback = function()
            local player = game.Players.LocalPlayer
            local args = {
                [1] = 3,
                [2] = "Armor2",
                [3] = "Armor",
                [4] = player.Name,
                [5] = 1
            }
            game:GetService("ReplicatedStorage").Events.Vending:FireServer(unpack(args))
        end
    })


    Tabs.Items:AddSection("Strength And Speed")
    Tabs.Items:AddButton({
        Title = "Strength",
        Description = "",
        Callback = function()
            local args = {
            [1] = "Strength"
            }
            game:GetService("ReplicatedStorage").Events.RainbowWhatStat:FireServer(unpack(args))
        end
    })
    Tabs.Items:AddButton({
        Title = "Speed",
        Description = "",
        Callback = function()
            local args = {
            [1] = "Speed"
            }
            game:GetService("ReplicatedStorage").Events.RainbowWhatStat:FireServer(unpack(args))
        end
    })


    Tabs.Items:AddSection("Other Items")
    Tabs.Items:AddButton({
        Title = "Medkit",
        Description = "",
        Callback = function()
            local args = {
            [1] = "Medkit"
            }
            game:GetService("ReplicatedStorage").Events.GiveTool:FireServer(unpack(args))
        end
    })


    local Slider = Tabs.Misc:AddSlider("PlrSlider", {
        Title = "Player Speed",
        Description = "",
        Default = 16,
        Min = 16,
        Max = 160,
        Rounding = 0,
        Callback = function(Value)
            game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = Value
        end
    })
    local Toggle = Tabs.Misc:AddToggle("Noclip", {Title = "Noclip", Default = false })
    
    Toggle:OnChanged(function()
        if Options.Noclip.Value == true then
            noclip()
        else
            clip()
        end
    end)
end


-- Addons:
-- SaveManager (Allows you to have a configuration system)
-- InterfaceManager (Allows you to have a interface managment system)

-- Hand the library over to our managers
SaveManager:SetLibrary(Fluent)
InterfaceManager:SetLibrary(Fluent)

-- Ignore keys that are used by ThemeManager.
-- (we dont want configs to save themes, do we?)
SaveManager:IgnoreThemeSettings()

-- You can add indexes of elements the save manager should ignore
SaveManager:SetIgnoreIndexes({})

-- use case for doing it this way:
-- a script hub could have themes in a global folder
-- and game configs in a separate folder per game
InterfaceManager:SetFolder("FluentScriptHub")
SaveManager:SetFolder("FluentScriptHub/specific-game")

InterfaceManager:BuildInterfaceSection(Tabs.Settings)
SaveManager:BuildConfigSection(Tabs.Settings)


Window:SelectTab(1)

Fluent:Notify({
    Title = "Viride Hub",
    Content = "The script has been loaded.",
    Duration = 8
})

-- You can use the SaveManager:LoadAutoloadConfig() to load a config
-- which has been marked to be one that auto loads!
SaveManager:LoadAutoloadConfig()
