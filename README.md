local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("TITLE", "DarkTheme")

-- MAIN
local Main = Window:NewTab("TabName")
local MainSection = Main:NewSection("REtard")

MainSection:NewButton("Nigga CHicken", "Bad kid", function()
    print("Clicked")
end)
