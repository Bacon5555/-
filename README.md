local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("Bacon HUB", "BloodTheme")
local Tab = Window:NewTab("เมนูวาป")
local Section = Tab:NewSection("วาป")
Section:NewButton("วาปไปอตอมมิก", "ButtonInfo", function()
    print("Clicked")
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1062.6312255859375, 150.7750244140625, 23016.40234375)
end)
Section:NewButton("วาปไปพื้นที่ว่าง", "ButtonInfo", function()
    print("Clicked")
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1072.7833251953125, 405.9889221191406, 23015.5390625)    
end)
Section:NewButton("วาปไปใต้แมพ", "ButtonInfo", function()
    print("Clicked")
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(100.5487289428711, 111.74861145019531, 15.233039855957031)    
end)
Section:NewButton("วาปไปในแมพ", "ButtonInfo", function()
    print("Clicked")
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(142.25596618652344, 443.60308837890625, -111.68585205078125)    
end)
Section:NewButton("วาปไปหมัดไซตามะ", "ButtonInfo", function()
    print("Clicked")
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-86.36270904541016, 29.253990173339844, 20346.0546875)
end)
local Tab = Window:NewTab("วิ่งไว")
local Section = Tab:NewSection("ปรับspeed")
Section:NewSlider("ปรับspeed", "SliderInfo", 1000, 0, function(s) -- 1000 (MaxValue) | 0 (MinValue)
    game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = s
end)
