--script by: gabriel 
--discord:PAISEN#7002

--]

local ScreenGui = Instance.new("ScreenGui")
local main = Instance.new("Frame")
local rotulo = Instance.new("TextLabel")
local ScrollingFrame = Instance.new("ScrollingFrame")
local deletealldoors = Instance.new("TextButton")
local walkspeed = Instance.new("TextButton")
local criminal = Instance.new("TextButton")
local police = Instance.new("TextButton")
local TextLabel = Instance.new("TextLabel")
local FECHAR = Instance.new("TextButton")


ScreenGui.Parent = game.CoreGui
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

main.Name = "main"
main.Parent = ScreenGui
main.BackgroundColor3 = Color3.new(0.290196, 0.290196, 0.290196)
main.Position = UDim2.new(0.696239114, 0, 0.387673944, 0)
main.Size = UDim2.new(0, 257, 0, 209)
main.Active = true
main.Draggable = true


rotulo.Name = "rotulo"
rotulo.Parent = main
rotulo.BackgroundColor3 = Color3.new(0.419608, 0.419608, 0.419608)
rotulo.Position = UDim2.new(0, 0, -0.00478468835, 0)
rotulo.Size = UDim2.new(0, 257, 0, 30)
rotulo.Font = Enum.Font.Cartoon
rotulo.LineHeight = 1.3200000524521
rotulo.Text = "PRISON LIFE GUI V1"
rotulo.TextColor3 = Color3.new(1, 1, 1)
rotulo.TextSize = 18

ScrollingFrame.Parent = main
ScrollingFrame.Active = true
ScrollingFrame.BackgroundColor3 = Color3.new(0.282353, 0.282353, 0.282353)
ScrollingFrame.Position = UDim2.new(0.0505836569, 0, 0.181818187, 0)
ScrollingFrame.Size = UDim2.new(0, 234, 0, 112)

deletealldoors.Name = "deletealldoors"
deletealldoors.Parent = ScrollingFrame
deletealldoors.BackgroundColor3 = Color3.new(0.392157, 0.392157, 0.392157)
deletealldoors.Position = UDim2.new(0.277777791, 0, 0.0342617929, 0)
deletealldoors.Size = UDim2.new(0, 117, 0, 38)
deletealldoors.Font = Enum.Font.SourceSans
deletealldoors.Text = "delete all doors"
deletealldoors.TextColor3 = Color3.new(0, 0, 0)
deletealldoors.TextSize = 14
deletealldoors.MouseButton1Down:connect(function()
	game.Workspace['Doors']:Destroy()
end)

walkspeed.Name = "walkspeed"
walkspeed.Parent = ScrollingFrame
walkspeed.BackgroundColor3 = Color3.new(0.392157, 0.392157, 0.392157)
walkspeed.Position = UDim2.new(0.277777791, 0, 0.184979498, 0)
walkspeed.Size = UDim2.new(0, 117, 0, 38)
walkspeed.Font = Enum.Font.SourceSans
walkspeed.Text = "walkspeed 100"
walkspeed.TextColor3 = Color3.new(0, 0, 0)
walkspeed.TextSize = 14
walkspeed.MouseButton1Down:connect(function()
	local plr = game.Players.LocalPlayer
	local char = plr.Character

	char.Humanoid.WalkSpeed = 100
end)

criminal.Name = "criminal"
criminal.Parent = ScrollingFrame
criminal.BackgroundColor3 = Color3.new(0.392157, 0.392157, 0.392157)
criminal.Position = UDim2.new(0.277777791, 0, 0.354835957, 0)
criminal.Size = UDim2.new(0, 117, 0, 38)
criminal.Font = Enum.Font.SourceSans
criminal.Text = "teleportbasecriminal"
criminal.TextColor3 = Color3.new(0, 0, 0)
criminal.TextSize = 14
criminal.MouseButton1Down:connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = 

CFrame.new(-921.434875, 95.3272018, 2138.42749, -0.0522505306, 3.58332408e-09, 

-0.998633981, -2.93570901e-09, 1, 3.74182774e-09, 0.998633981, 3.12721138e-09, 

-0.0522505306)
end)

police.Name = "police"
police.Parent = ScrollingFrame
police.BackgroundColor3 = Color3.new(0.392157, 0.392157, 0.392157)
police.Position = UDim2.new(0.277777791, 0, 0.491199613, 0)
police.Size = UDim2.new(0, 117, 0, 38)
police.Font = Enum.Font.SourceSans
police.Text = "teleporte.policebase"
police.TextColor3 = Color3.new(0, 0, 0)
police.TextSize = 14
police.MouseButton1Down:connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = 

CFrame.new(832.646118, 99.9900055, 2304.19653, -0.998547852, -1.20054054e-07, 

-0.0538700037, -1.22286707e-07, 1, 3.81488512e-08, 0.0538700037, 4.46810411e-08, 

-0.998547852)
end)

TextLabel.Parent = main
TextLabel.BackgroundColor3 = Color3.new(0.392157, 0.392157, 0.392157)
TextLabel.BorderColor3 = Color3.new(0.392157, 0.392157, 0.392157)
TextLabel.Position = UDim2.new(0.0505836569, 0, 0.775119603, 0)
TextLabel.Size = UDim2.new(0, 234, 0, 24)
TextLabel.Font = Enum.Font.SourceSans
TextLabel.Text = "criado por : PAISEN#7002"
TextLabel.TextColor3 = Color3.new(0, 0, 0)
TextLabel.TextSize = 14

FECHAR.Name = "FECHAR"
FECHAR.Parent = main
FECHAR.BackgroundColor3 = Color3.new(0, 0, 0)
FECHAR.Position = UDim2.new(0.848249018, 0, 0, 0)
FECHAR.Size = UDim2.new(0, 39, 0, 29)
FECHAR.Font = Enum.Font.Cartoon
FECHAR.Text = "X"
FECHAR.TextColor3 = Color3.new(1, 1, 1)
FECHAR.TextSize = 49


local function KRLEI_fake_script() -- FECHAR.LocalScript 
	local script = Instance.new('LocalScript', FECHAR)

	script.Parent.MouseButton1Click:Connect (function()
		script.Parent.Parent.Visible = false
	
	end)
end
coroutine.wrap(KRLEI_fake_script)()



