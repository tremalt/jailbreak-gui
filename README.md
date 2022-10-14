local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("jailbreak gui", "Sentinel")
-- LOCAL PLAYER 
local Player = Window:NewTab("Player")
local PlayerSection = Player:NewSection("Player")

PlayerSection:NewSlider("Walk speed", "makes u walk more fast", 500, 16, function(s) -- 500 (MaxValue) | 16 (MinValue)
    game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = s
end)

PlayerSection:NewSlider("Jumppower", "makes u jump more high", 350, 50, function(s) -- 350 (MaxValue) | 50 (MinValue)
    game.Players.LocalPlayer.Character.Humanoid.JumpPower = s
end)

PlayerSection:NewButton("God Mode", "God Mode", function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/trem2goated/god-mode-/main/README.md'))()
end)

PlayerSection:NewButton("fly", "fly", function()
    loadstring(game:HttpGet('https://pastebin.com/raw/BBgANpmH'))()
end)

--CAR
local Car = Window:NewTab("Car")
local CarSection = Car:NewSection("Car")

CarSection:NewButton("inf nitro", "inf nitro", function()
    loadstring(game:HttpGet('https://pastebin.com/raw/HbkLvTnX'))()
end)


--CRIME 
local Crime = Window:NewTab("Crime")
local CrimeSection = Crime:NewSection("Crime")

CrimeSection:NewButton("Auto rob", "it well auto rob ", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/wawsdasdacx/ohascriptnrrewading/main/jbsaxcriptidk1"))()
end)


CrimeSection:NewButton("get keycard", "u well get a keycard", function()
    loadstring(game:HttpGet('https://pastebin.com/raw/W6CVZarN'))()
end)



--Police 
local Police = Window:NewTab("Police")
local PoliceSection = Police:NewSection("Police")


--AIMBOT
local Aimbot = Window:NewTab("Aimbot")
local AimbotSection = Aimbot:NewSection("Aimbot")

AimbotSection:NewButton("Aimbot", "Aimbot", function()
    loadstring(game:HttpGet('https://pastebin.com/raw/UhtQSzgP'))()
end)


AimbotSection:NewButton("esp", "esp", function()
    loadstring(game:HttpGet('https://pastebin.com/raw/Ev9H4bxT'))()
end)


--TP
local Tp = Window:NewTab("Tp")
local TpSection = Tp:NewSection("Tp")


TpSection:NewButton("Tp to bank", "Tp to bank", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-0.676, 18.77, 802.952)
end)
