loadstring(game:HttpGet(('https://raw.githubusercontent.com/ttjy9808/themimickey-/main/README.md')))()
if _G.Key == KEY then
local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()
local Window = OrionLib:MakeWindow({Name = "THE MIMIC SCRIPT BY TTJY", HidePremium = false, SaveConfig = true, ConfigFolder = "OrionTest"})

local tpg = Window:MakeTab({
	Name = "Teleport Game",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

tpg:AddButton({
	Name = "The Mimic lobby",
	Callback = function()
	game:GetService("TeleportService"):Teleport(6243699076, game:GetService("Players").LocalPlayer)
end
})

tpg:AddButton({
	Name = "Jigoku",
	Callback = function()
	game:GetService("TeleportService"):Teleport(7618863566, game:GetService("Players").LocalPlayer)
end
})

tpg:AddButton({
	Name = "Chapter 1",
	Callback = function()
	game:GetService("TeleportService"):Teleport(6296321810, game:GetService("Players").LocalPlayer)
end
})

tpg:AddButton({
	Name = "Chapter 1 nightmare",
	Callback = function()
	game:GetService("TeleportService"):Teleport(6479231833, game:GetService("Players").LocalPlayer)
end
})


local Jigoku = Window:MakeTab({
	Name = "Jigoku",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})	

Jigoku:AddButton({
	Name = "TP to red guy",
	Callback = function()
    if workspace:FindFirstChild("IdleNPC") then
      	OrionLib:MakeNotification({
		Name = "Jigoku",
		Content = "FOUND IT!",
		Image = "rbxassetid://4483345998",
		Time = 5
})
for i, v in pairs(Workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart")  then
	game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(310.32,3.23,323.65)
        wait(0.3)
        fireproximityprompt(v)
    end
end
	else
	    OrionLib:MakeNotification({
		Name = "Jigoku",
		Content = "Change server bro,i cant find it",
		Image = "rbxassetid://4483345998",
		Time = 5
})
  	end 
  	end
})

Jigoku:AddButton({
	Name = "Auto win",
	Callback = function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(607.54,11.91,1080)
        task.wait(11)
for i, v in pairs(Workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart")  then
game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = v.Parent.CFrame
        wait(0.3)
        fireproximityprompt(v)
    end
end
  	end
})








local Chapter1 = Window:MakeTab({
	Name = "Chapter1",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

local Section = Chapter1:AddSection({
	Name = "map1"
})

Chapter1:AddButton({
	Name = "Auto win",
	Callback = function()
      	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(3507,37.65,-1539.45)
  	end    
})

local Section = Chapter1:AddSection({
	Name = "map2"
})

Chapter1:AddButton({
	Name = "Auto win",
	Callback = function()
      	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1274.95,199.54,-2537.93)
  	end    
})



local Chapter2 = Window:MakeTab({
	Name = "Chapter 2",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

local Section = Chapter2:AddSection({
	Name = "map1"
})

Chapter2:AddButton({
	Name = "Auto win",
	Callback = function()
      	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(64.88,55.28,-1590)
  	end    
})

local Section = Chapter2:AddSection({
	Name = "map2"
})

Chapter2:AddButton({
	Name = "Auto win",
	Callback = function()
      	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(235.17,101.94,-590)
  	end    
})

local Section = Chapter2:AddSection({
	Name = "map3"
})

Chapter2:AddButton({
	Name = "Auto win",
	Callback = function()
      	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(829.97,72.49,-353.46)
  	end    
})


local Chapter3 = Window:MakeTab({
	Name = "Chapter 3",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

local Section = Chapter3:AddSection({
	Name = "map1"
})

Chapter3:AddButton({
	Name = "Auto win",
	Callback = function()
      	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(2411.93,-23.03,2300)
  	end    
})

local Section = Chapter3:AddSection({
	Name = "map2"
})

Chapter3:AddButton({
	Name = "Auto win",
	Callback = function()
      	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(245.69,31.72,450)
  	end    
})

local Section = Chapter3:AddSection({
	Name = "map3"
})

Chapter3:AddButton({
	Name = "Auto win",
	Callback = function()
      	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-651,648.99,-1014.35)
      	task.wait(5)
      	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-644.07,947.82,-1490)
  	end    
})

local Chapter4 = Window:MakeTab({
	Name = "Chapter 4",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

local Section = Chapter4:AddSection({
	Name = "map1"
})

Chapter4:AddButton({
	Name = "Auto win",
	Callback = function()
      	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(91,-48.35,-1416.24)
  	end    
})

local Section = Chapter4:AddSection({
	Name = "map2"
})

Chapter4:AddButton({
	Name = "Auto win",
	Callback = function()
      	for i, v in pairs(Workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart")  then
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.Parent.CFrame
        wait(0.5)
        fireproximityprompt(v)
    end
end
  	end    
})

local Section = Chapter4:AddSection({
	Name = "map3"
})

Chapter4:AddButton({
	Name = "Auto win",
	Callback = function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(665.63,18.17,2108.62)
task.wait(0.3)
for i, v in pairs(Workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart")  then
        fireproximityprompt(v)
    end
end
task.wait()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(620.22,17.87,2340.73)
task.wait(0.3)
for i, v in pairs(Workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart")  then
        fireproximityprompt(v)
    end
end
task.wait()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(756.75,16.39,2538.24)
task.wait(0.3)
for i, v in pairs(Workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart")  then
        fireproximityprompt(v)
    end
end
task.wait()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(860.18,24.85,2548.28)
task.wait(0.3)
for i, v in pairs(Workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart")  then
        fireproximityprompt(v)
    end
end
task.wait()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(855.96,15.47,2388.36)
task.wait(0.3)
for i, v in pairs(Workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart")  then
        fireproximityprompt(v)
    end
end
task.wait()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(836.29,19.01,2247.34)
task.wait(0.3)
for i, v in pairs(Workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart")  then
        fireproximityprompt(v)
    end
end
task.wait()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(688.41,28.37,2251.57)
task.wait(0.3)
for i, v in pairs(Workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart")  then
        fireproximityprompt(v)
        fireproximityprompt(v)
        fireproximityprompt(v)
        fireproximityprompt(v)
        fireproximityprompt(v)
        fireproximityprompt(v)
    end
end
  	end    
})

local Section = Chapter4:AddSection({
	Name = "map4"
})

local Section = Chapter4:AddSection({
	Name = "recommend to anti sama and break heart"
})
local Section = Chapter4:AddSection({
	Name = "then use kToll to auto kill saigomo"
})

Chapter4:AddButton({
	Name = "Anti sama",
	Callback = function()
		local part = game.workspace.GameAI.Sama.KILL_BOX
local distance = 50

while true do
    local character = game.Players.LocalPlayer.Character
    local position = part and part.Position or nil 
    
    if position and (position - character.HumanoidRootPart.Position).Magnitude <= distance then
        character.HumanoidRootPart.CFrame = CFrame.new(2932.52,132.13,1639.49)
    end
    
    wait(0.1)
end
  	end    
})

Chapter4:AddButton({
	Name = "KToll",
	Callback = function()
		loadstring(game:HttpGet('https://raw.githubusercontent.com/KTollT/KTollT/main/README.md'))()
  	end    
})



local Chapter1b2 = Window:MakeTab({
	Name = "Chapter 1 book 2",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

local Section = Chapter1b2:AddSection({
	Name = "If normal mode click this first"
})

Chapter1b2:AddButton({
	Name = "Start",
	Callback = function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1778,9.72,-4294.29)
	end
})	

local Section = Chapter1b2:AddSection({
	Name = "----------------------------------------------------------"
})

local Section = Chapter1b2:AddSection({
	Name = "recommend to use KToll 'until' ship"
})

local Section = Chapter1b2:AddSection({
	Name = "my pc is so trash can't even open dex ._."
})

Chapter1b2:AddButton({
	Name = "KToll",
	Callback = function()
		loadstring(game:HttpGet('https://raw.githubusercontent.com/KTollT/KTollT/main/README.md'))()
  	end    
})

local Section = Chapter1b2:AddSection({
	Name = "tp to ship"
})

Chapter1b2:AddButton({
	Name = "Tp To ship",
	Callback = function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1250,4,6299.65)
  	end    
})












local Chapter2b2 = Window:MakeTab({
	Name = "Chapter 2 book 2",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

local Section = Chapter2b2:AddSection({
	Name = "part1 (laser eye?)"
})

Chapter2b2:AddButton({
	Name = "Auto win",
	Callback = function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-550,30,-87.29)
  	end    
})

local Section = Chapter2b2:AddSection({
	Name = "part2 (someone eat meat)"
})

Chapter2b2:AddButton({
	Name = "Auto win(it doesnt press E for you wtf)",
	Callback = function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-3953.17,594.22,317.07)
		task.wait()
		for i, v in pairs(Workspace:GetDescendants()) do
    	if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart")  then
        fireproximityprompt(v)
        fireproximityprompt(v)
        fireproximityprompt(v)
        fireproximityprompt(v)
        fireproximityprompt(v)
        fireproximityprompt(v)
    end
end
		
  	end    
})


local Section = Chapter2b2:AddSection({
	Name = "part3 (meat)"
})
local Section = Chapter2b2:AddSection({
	Name = "Leave cabin before press again"
})
Chapter2b2:AddButton({
	Name = "Talk",
	Callback = function()
		for i, v in pairs(Workspace:GetDescendants()) do
    	if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart")  then
    	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-4443.11,711.37,1163.78)
    	wait(0.3)
        fireproximityprompt(v)
		task.wait()
    	end
		end
		local time = 0.1  -- Change to 0 for no wait.
		local clickCount = 0

    	repeat
        mouse1click()
        wait(time)
        clickCount = clickCount + 1
        until clickCount == 10
  	end    
})

Chapter2b2:AddButton({
	Name = "Auto win",
	Callback = function()
		for i, v in pairs(Workspace:GetDescendants()) do
    	if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart")  then
    	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.Parent.CFrame
    	wait(0.3)
        fireproximityprompt(v)
    	end
		end
	end    
})

local Section = Chapter2b2:AddSection({
	Name = "Press before run"
})
Chapter2b2:AddButton({
	Name = "Auto win",
	Callback = function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-4590,843.64,-35.54)
	end    
})

local Section = Chapter2b2:AddSection({
	Name = "AUTO RUN"
})
Chapter2b2:AddButton({
	Name = "Auto win",
	Callback = function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-5364,682.12,29.63)
	end    
})

local Section = Chapter2b2:AddSection({
	Name = "Before lever"
})
Chapter2b2:AddButton({
	Name = "Auto win",
	Callback = function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-11035,-81.4,-12.56)
	end    
})

local Section = Chapter2b2:AddSection({
	Name = "lever"
})
Chapter2b2:AddButton({
	Name = "Auto win",
	Callback = function()
		for i, v in pairs(Workspace:GetDescendants()) do
    	if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent == "Lever" then
    	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.Parent.CFrame
    	wait(0.3)
        fireproximityprompt(v)
    	end
		end
		task.wait(3)
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-10060,484.1,-9.52)
	end    
})

local Section = Chapter2b2:AddSection({
	Name = "skip cooking and number puzzle"
})
Chapter2b2:AddButton({
	Name = "Auto win",
	Callback = function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-3347.32,1205,-6824)
	end    
})

local Section = Chapter2b2:AddSection({
	Name = "tp to here and you dont have to do cursed 1"
})
Chapter2b2:AddButton({
	Name = "teleport to cursed 2",
	Callback = function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-4079.71,613.7,-968.13)
	end    
})


local Section = Chapter2b2:AddSection({
	Name = "remove monster(click before do puzzle)"
})

Chapter2b2:AddButton({
	Name = "remove monster trigger",
	Callback = function()
		for i, v in pairs(workspace:GetDescendants()) do
            if v.Parent:IsA("BasePart") and v.Parent.Name == "GAMESTART" then
                v:Destroy()
            end
        end
	end    
})

local Section = Chapter2b2:AddSection({
	Name = "auto find child(press again after found once)"
})
Chapter2b2:AddButton({
    Name = "Fix Auto Kidnap(dont have to press again)",
    Callback = function()
    	for i,v in pairs(workspace:GetDescendants()) do
  		if v.Name == "SquidGames" then
     	v:Destroy()
     	end
	end
    end
})

Chapter2b2:AddButton({
    Name = "Auto Kidnap",
    Callback = function()
        for i,v in pairs(workspace:GetDescendants()) do
  if v:IsA("BasePart") and v.Name == "IndicatorPic" then
     game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = v.CFrame
     end
end
    end
})

Chapter2b2:AddButton({
    Name = "tp to gate",
    Callback = function()
        for i,v in pairs(workspace:GetDescendants()) do
  if v:IsA("BasePart") and v.Name == "Formation" then
     game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = v.CFrame
     end
end
    end
})

Chapter2b2:AddButton({
    Name = "Auto Get Note",
    Callback = function()
        for i, v in pairs(workspace:GetDescendants()) do
            if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Name == "Note" then
                game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = v.Parent.CFrame
                wait(0.3)
                fireproximityprompt(v)
            end
        end
    end
})

local Section = Chapter2b2:AddSection({
	Name = "idk but this for nagisa"
})


Chapter2b2:AddButton({
    Name = "Anti Nagisa laser",
    Callback = function()
    while true do
		for i, v in pairs(workspace:GetDescendants()) do
            if v.Name == "POISON" then
local distance = 100

while true do
	localplayer = game.Players.LocalPlayer 
 	Char = localplayer.Character or workspace:FindFirstChild(localplayer.Name)
         HRP = Char and Char:FindFirstChild("HumanoidRootPart")
        if not Char or not HRP then
           
        end
         p = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
         hrd = game.Players.LocalPlayer.Character.HumanoidRootPart
         py = game.Players.LocalPlayer.Character.HumanoidRootPart.Position.y
         
    local character = game.Players.LocalPlayer.Character
    local position = v and v.Position or nil
    currentPos = Vector3.new(p.x, 100, p.z)
    if position and (position - character.HumanoidRootPart.Position).Magnitude <= distance then
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1982.58,100,-4780.12)
    end
    
    wait(0.1)
end
end
	end
	end
	end
})

Chapter2b2:AddButton({
    Name = "Auto get cannon ball",
    Callback = function()
    while task.wait() do
		for i, v in pairs(workspace:GetDescendants()) do
            if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Parent.Name == "BallGiver" and game.Players.LocalPlayer.PlayerGui.BossFight.Ammo.Text == "0" then
                game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = v.Parent.CFrame
                wait(0.3)
                fireproximityprompt(v)
                fireproximityprompt(v)
                fireproximityprompt(v)
                fireproximityprompt(v)
                fireproximityprompt(v)
                task.wait()
            end
end
	end
	end
})








	
	
	
	
	
	
	
	


local thewithctrail = Window:MakeTab({
	Name = "the witch trial",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

local Section = thewithctrail:AddSection({
	Name = "map 1"
})

thewithctrail:AddButton({
	Name = "Auto win",
	Callback = function()
		for i, v in pairs(Workspace:GetDescendants()) do
    if v.Parent:IsA("BasePart") and v.Parent.Name == "Game Teleporter" then
	game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = v.Parent.CFrame
        wait(0.3)
        fireproximityprompt(v)
    		end
		end
	end
})

local Section = thewithctrail:AddSection({
	Name = "map 2"
})

thewithctrail:AddButton({
	Name = "Auto win",
	Callback = function()
		for i, v in pairs(Workspace:GetDescendants()) do
    if v.Parent:IsA("BasePart") and v.Parent.Name == "Game Teleporter" then
	game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = v.Parent.CFrame
        wait(0.3)
        fireproximityprompt(v)
    		end
		end
	end
})

local Section = thewithctrail:AddSection({
	Name = "map 3"
})

thewithctrail:AddButton({
	Name = "Auto win",
	Callback = function()
		for i, v in pairs(Workspace:GetDescendants()) do
    if v.Parent:IsA("BasePart") and v.Parent.Name == "Game Teleporter" then
	game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = v.Parent.CFrame
        wait(0.3)
        fireproximityprompt(v)
    		end
		end
	end
})

local Section = thewithctrail:AddSection({
	Name = "imagine play online"
})
local Section = thewithctrail:AddSection({
	Name = "here auto get butterfly"
})

thewithctrail:AddButton({
	Name = "Auto Butterfly",
	Callback = function()

local function teleportAndFirePrompt(part)
    local player = game:GetService("Players").LocalPlayer
    local character = player.Character
    local humanoidRootPart = character and character:FindFirstChild("HumanoidRootPart")
    
    if humanoidRootPart and humanoidRootPart:IsA("BasePart") then
        local targetCFrame = part.CFrame + (part.CFrame.LookVector * -9)  -- Teleport 10 units behind the part
        humanoidRootPart.CFrame = targetCFrame
    end
end

for i, v in pairs(workspace.GameAI:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Name == "Cube.001" then
        teleportAndFirePrompt(v.Parent)
        wait(0.3)
        fireproximityprompt(v)
    end
end

task.wait()

		
	end    
})

thewithctrail:AddButton({
	Name = "tp to fireplace1",
	Callback = function()
		game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(2621.90186, 111.203804, 1453.71765, -0.0025562048, -0.0233752616, 0.999723434, 0.000763676129, 0.999726415, 0.0233772844, -0.999996424, 0.000823224895, -0.00253772736)
	end    
})

thewithctrail:AddButton({
	Name = "tp to fireplace2",
	Callback = function()
		game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(2426.72583, 185.146057, 1457.37292, -0.0025562048, -0.0233752616, 0.999723434, 0.000763676129, 0.999726415, 0.0233772844, -0.999996424, 0.000823224895, -0.00253772736)
	end    
})

local christmas = Window:MakeTab({
	Name = "Christmas trial",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

local Section = christmas:AddSection({
	Name = "oh yeah all of this will auto talk to elf"
})
local Section = christmas:AddSection({
	Name = "repair santa sleigh(how do i spell it)"
})

christmas:AddButton({
	Name = "Auto win",
	Callback = function()
      	for i, v in pairs(Workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Name == "RootPart" then
	game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = v.Parent.CFrame
        wait(0.3)
        fireproximityprompt(v)
    end
end


for i, v in pairs(Workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Name == "Extinguisher" then
	game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = v.Parent.CFrame
        wait(0.3)
        fireproximityprompt(v)
    end
end


for i, v in pairs(Workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Name == "Ropes" then
	game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = v.Parent.CFrame
        wait(0.3)
        fireproximityprompt(v)
    end
end

for i, v in pairs(Workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Name == "Controls" then
	game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = v.Parent.CFrame
        wait(0.3)
        fireproximityprompt(v)
    end
end

for i, v in pairs(Workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Name == "RepairPoint" then
	game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = v.Parent.CFrame
        wait(0.3)
        fireproximityprompt(v)
    end
end

wait(0.3)
game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-176.64,4.8,-328.34)
  	end    
})


local Section = christmas:AddSection({
	Name = "Get toys"
})

christmas:AddButton({
	Name = "Auto win",
	Callback = function()
      	for i, v in pairs(Workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Name == "RootPart" then
	game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = v.Parent.CFrame
        wait(0.3)
        fireproximityprompt(v)
    end
end

for i, v in pairs(Workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Name == "toy" then
	game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = v.Parent.CFrame
        wait(0.3)
        fireproximityprompt(v)
    end
end
  	end    
})

local Section = christmas:AddSection({
	Name = "Get toys"
})

christmas:AddButton({
	Name = "Auto win",
	Callback = function()
		for i, v in pairs(Workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Name == "RootPart" then
	game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = v.Parent.CFrame
        wait(0.3)
        fireproximityprompt(v)
    end
end

local function teleportAndFirePrompt(part)
    local player = game:GetService("Players").LocalPlayer
    local character = player.Character
    local humanoidRootPart = character and character:FindFirstChild("HumanoidRootPart")
    
    if humanoidRootPart and humanoidRootPart:IsA("BasePart") then
        local targetCFrame = part.CFrame + (part.CFrame.LookVector * -9)  -- Teleport 10 units behind the part
        humanoidRootPart.CFrame = targetCFrame
    end
end

for i, v in pairs(workspace.GameAI:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Name == "HumanoidRootPart" then
        teleportAndFirePrompt(v.Parent)
        wait(0.3)
        fireproximityprompt(v)
    end
end

task.wait()

for i, v in pairs(Workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Name == "RootPart" then
	game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = v.Parent.CFrame
        wait(0.3)
        fireproximityprompt(v)
    end
end



	end    
})




local halloween = Window:MakeTab({
	Name = "Halloween Trial",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

local Section = halloween:AddSection({
	Name = "Map1"
})

halloween:AddButton({
	Name = "Auto win",
	Callback = function()
		for i, v in pairs(workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Name == "GrabItem" then
	game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = v.Parent.CFrame
        wait(0.3)
        fireproximityprompt(v)
    end
end
task.wait(1)
for i, v in pairs(workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Name == "Burner" then
	game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = v.Parent.CFrame
        wait(0.3)
        fireproximityprompt(v)
        fireproximityprompt(v)
        fireproximityprompt(v)
        fireproximityprompt(v)
        fireproximityprompt(v)
    end
end

	end    
})

local Section = halloween:AddSection({
	Name = "Map2"
})
halloween:AddButton({
	Name = "Auto win",
	Callback = function()
		success = false

spawn(function()
    repeat
        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(168.59, 45, -119.63)
        task.wait()
    until success == true
end)

for i, v in pairs(workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Parent.Name == "Candle" then
        wait(0.3)
        fireproximityprompt(v)
    end
end

success = true
task.wait()
success = false

spawn(function()
    repeat
        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(97.5569, 75, -164.936)
        task.wait()
    until success == true
end)

for i, v in pairs(workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Parent.Name == "Candle" then
        wait(0.3)
        fireproximityprompt(v)
    end
end

success = true
task.wait()
success = false

spawn(function()
    repeat
        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(25.9275, 76, -116.628)
        task.wait()
    until success == true
end)

for i, v in pairs(workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Parent.Name == "Candle" then
        wait(0.3)
        fireproximityprompt(v)
    end
end

success = true
task.wait()
success = false
game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(42.54,100,-132.39)
task.wait()
spawn(function()
    repeat
        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(42.54,60.91,-132.39)
        task.wait()
    until success == true
end)

for i, v in pairs(workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Parent.Name == "Candle" then
        wait(0.3)
        fireproximityprompt(v)
    end
end

success = true
task.wait()
success = false

spawn(function()
    repeat
        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-35.8623, 61, 6.54341)
        task.wait()
    until success == true
end)

for i, v in pairs(workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Parent.Name == "Candle" then
        wait(0.3)
        fireproximityprompt(v)
    end
end

success = true
task.wait()
success = false

spawn(function()
    repeat
        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(140.855, 49, -37.8745)
        task.wait()
    until success == true
end)

for i, v in pairs(workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Parent.Name == "Candle" then
        wait(0.3)
        fireproximityprompt(v)
    end
end

success = true
task.wait()
success = false

spawn(function()
    repeat
        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(168.327, 55, -119.483)
        task.wait()
    until success == true
end)

for i, v in pairs(workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Parent.Name == "Candle" then
        wait(0.3)
        fireproximityprompt(v)
    end
end

success = true
task.wait()
success = false

spawn(function()
    repeat
        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(49.3455, 47, -101.13)
        task.wait()
    until success == true
end)

for i, v in pairs(workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Parent.Name == "Candle" then
        wait(0.3)
        fireproximityprompt(v)
    end
end

success = true
task.wait()
success = false

spawn(function()
    repeat
        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-55.54,83.33,-67.01)
        task.wait()
    until success == true
end)

for i, v in pairs(workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Parent.Name == "Candle" then
        wait(0.3)
        fireproximityprompt(v)
    end
end

success = true
task.wait()
game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(180.72, 46, -100.54)


	end
})

halloween:AddButton({
	Name = "Auto win(Full)",
	Callback = function()
	OrionLib:MakeNotification({
	Name = "bug report",
	Content = "it not bug dont be dumb,we set it to 1:30",
	Image = "rbxassetid://4483345998",
	Time = 5
})

		repeat
game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(180.72, 46, -100.54)
task.wait()
until game.Players.LocalPlayer.PlayerGui.ScreenGui.TextLabel.Text == "1:30"
success = false

spawn(function()
    repeat
        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(168.59, 45, -119.63)
        task.wait()
    until success == true
end)

for i, v in pairs(workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Parent.Name == "Candle" then
        wait(0.3)
        fireproximityprompt(v)
    end
end

success = true
task.wait()
success = false

spawn(function()
    repeat
        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(97.5569, 75, -164.936)
        task.wait()
    until success == true
end)

for i, v in pairs(workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Parent.Name == "Candle" then
        wait(0.3)
        fireproximityprompt(v)
    end
end

success = true
task.wait()
success = false

spawn(function()
    repeat
        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(25.9275, 76, -116.628)
        task.wait()
    until success == true
end)

for i, v in pairs(workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Parent.Name == "Candle" then
        wait(0.3)
        fireproximityprompt(v)
    end
end

success = true
task.wait()
success = false
game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(42.54,100,-132.39)
task.wait()
spawn(function()
    repeat
        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(42.54,60.91,-132.39)
        task.wait()
    until success == true
end)

for i, v in pairs(workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Parent.Name == "Candle" then
        wait(0.3)
        fireproximityprompt(v)
    end
end

success = true
task.wait()
success = false

spawn(function()
    repeat
        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-35.8623, 61, 6.54341)
        task.wait()
    until success == true
end)

for i, v in pairs(workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Parent.Name == "Candle" then
        wait(0.3)
        fireproximityprompt(v)
    end
end

success = true
task.wait()
success = false

spawn(function()
    repeat
        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(140.855, 49, -37.8745)
        task.wait()
    until success == true
end)

for i, v in pairs(workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Parent.Name == "Candle" then
        wait(0.3)
        fireproximityprompt(v)
    end
end

success = true
task.wait()
success = false

spawn(function()
    repeat
        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(168.327, 55, -119.483)
        task.wait()
    until success == true
end)

for i, v in pairs(workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Parent.Name == "Candle" then
        wait(0.3)
        fireproximityprompt(v)
    end
end

success = true
task.wait()
success = false

spawn(function()
    repeat
        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(49.3455, 47, -101.13)
        task.wait()
    until success == true
end)

for i, v in pairs(workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Parent.Name == "Candle" then
        wait(0.3)
        fireproximityprompt(v)
    end
end

success = true
task.wait()
success = false

spawn(function()
    repeat
        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-55.54,83.33,-67.01)
        task.wait()
    until success == true
end)

for i, v in pairs(workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Parent.Name == "Candle" then
        wait(0.3)
        fireproximityprompt(v)
    end
end

success = true
task.wait()
success = false

spawn(function()
    repeat
        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-33.94,66.47,6.76)
        task.wait()
    until success == true
end)

for i, v in pairs(workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Parent.Name == "Candle" then
        wait(0.3)
        fireproximityprompt(v)
    end
end

success = true
task.wait()
game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(180.72, 46, -100.54)
repeat
game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(180.72, 46, -100.54)
task.wait()
until game.Players.LocalPlayer.PlayerGui.ScreenGui.TextLabel.Text == "1:30"
success = false

spawn(function()
    repeat
        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(168.59, 45, -119.63)
        task.wait()
    until success == true
end)

for i, v in pairs(workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Parent.Name == "Candle" then
        wait(0.3)
        fireproximityprompt(v)
    end
end

success = true
task.wait()
success = false

spawn(function()
    repeat
        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(97.5569, 75, -164.936)
        task.wait()
    until success == true
end)

for i, v in pairs(workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Parent.Name == "Candle" then
        wait(0.3)
        fireproximityprompt(v)
    end
end

success = true
task.wait()
success = false

spawn(function()
    repeat
        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(25.9275, 76, -116.628)
        task.wait()
    until success == true
end)

for i, v in pairs(workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Parent.Name == "Candle" then
        wait(0.3)
        fireproximityprompt(v)
    end
end

success = true
task.wait()
success = false
game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(42.54,100,-132.39)
task.wait()
spawn(function()
    repeat
        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(42.54,60.91,-132.39)
        task.wait()
    until success == true
end)

for i, v in pairs(workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Parent.Name == "Candle" then
        wait(0.3)
        fireproximityprompt(v)
    end
end

success = true
task.wait()
success = false

spawn(function()
    repeat
        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-35.8623, 61, 6.54341)
        task.wait()
    until success == true
end)

for i, v in pairs(workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Parent.Name == "Candle" then
        wait(0.3)
        fireproximityprompt(v)
    end
end

success = true
task.wait()
success = false

spawn(function()
    repeat
        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(140.855, 49, -37.8745)
        task.wait()
    until success == true
end)

for i, v in pairs(workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Parent.Name == "Candle" then
        wait(0.3)
        fireproximityprompt(v)
    end
end

success = true
task.wait()
success = false

spawn(function()
    repeat
        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(168.327, 55, -119.483)
        task.wait()
    until success == true
end)

for i, v in pairs(workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Parent.Name == "Candle" then
        wait(0.3)
        fireproximityprompt(v)
    end
end

success = true
task.wait()
success = false

spawn(function()
    repeat
        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(49.3455, 47, -101.13)
        task.wait()
    until success == true
end)

for i, v in pairs(workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Parent.Name == "Candle" then
        wait(0.3)
        fireproximityprompt(v)
    end
end

success = true
task.wait()
success = false

spawn(function()
    repeat
        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-55.54,83.33,-67.01)
        task.wait()
    until success == true
end)

for i, v in pairs(workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Parent.Name == "Candle" then
        wait(0.3)
        fireproximityprompt(v)
    end
end

success = true
task.wait()
success = false

spawn(function()
    repeat
        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-33.94,66.47,6.76)
        task.wait()
    until success == true
end)

for i, v in pairs(workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Parent.Name == "Candle" then
        wait(0.3)
        fireproximityprompt(v)
    end
end

success = true
task.wait()
game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(180.72, 46, -100.54)
repeat
game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(180.72, 46, -100.54)
task.wait()
until game.Players.LocalPlayer.PlayerGui.ScreenGui.TextLabel.Text == "1:30"
success = false

spawn(function()
    repeat
        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(168.59, 45, -119.63)
        task.wait()
    until success == true
end)

for i, v in pairs(workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Parent.Name == "Candle" then
        wait(0.3)
        fireproximityprompt(v)
    end
end

success = true
task.wait()
success = false

spawn(function()
    repeat
        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(97.5569, 75, -164.936)
        task.wait()
    until success == true
end)

for i, v in pairs(workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Parent.Name == "Candle" then
        wait(0.3)
        fireproximityprompt(v)
    end
end

success = true
task.wait()
success = false

spawn(function()
    repeat
        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(25.9275, 76, -116.628)
        task.wait()
    until success == true
end)

for i, v in pairs(workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Parent.Name == "Candle" then
        wait(0.3)
        fireproximityprompt(v)
    end
end

success = true
task.wait()
success = false
game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(42.54,100,-132.39)
task.wait()
spawn(function()
    repeat
        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(42.54,60.91,-132.39)
        task.wait()
    until success == true
end)

for i, v in pairs(workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Parent.Name == "Candle" then
        wait(0.3)
        fireproximityprompt(v)
    end
end

success = true
task.wait()
success = false

spawn(function()
    repeat
        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-35.8623, 61, 6.54341)
        task.wait()
    until success == true
end)

for i, v in pairs(workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Parent.Name == "Candle" then
        wait(0.3)
        fireproximityprompt(v)
    end
end

success = true
task.wait()
success = false

spawn(function()
    repeat
        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(140.855, 49, -37.8745)
        task.wait()
    until success == true
end)

for i, v in pairs(workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Parent.Name == "Candle" then
        wait(0.3)
        fireproximityprompt(v)
    end
end

success = true
task.wait()
success = false

spawn(function()
    repeat
        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(168.327, 55, -119.483)
        task.wait()
    until success == true
end)

for i, v in pairs(workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Parent.Name == "Candle" then
        wait(0.3)
        fireproximityprompt(v)
    end
end

success = true
task.wait()
success = false

spawn(function()
    repeat
        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(49.3455, 47, -101.13)
        task.wait()
    until success == true
end)

for i, v in pairs(workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Parent.Name == "Candle" then
        wait(0.3)
        fireproximityprompt(v)
    end
end

success = true
task.wait()
success = false

spawn(function()
    repeat
        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-55.54,83.33,-67.01)
        task.wait()
    until success == true
end)

for i, v in pairs(workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Parent.Name == "Candle" then
        wait(0.3)
        fireproximityprompt(v)
    end
end

success = true
task.wait()
success = false

spawn(function()
    repeat
        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-33.94,66.47,6.76)
        task.wait()
    until success == true
end)

for i, v in pairs(workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Parent.Name == "Candle" then
        wait(0.3)
        fireproximityprompt(v)
    end
end

success = true
task.wait()
game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(180.72, 46, -100.54)
repeat
game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(180.72, 46, -100.54)
task.wait()
until game.Players.LocalPlayer.PlayerGui.ScreenGui.TextLabel.Text == "1:30"
success = false

spawn(function()
    repeat
        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(168.59, 45, -119.63)
        task.wait()
    until success == true
end)

for i, v in pairs(workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Parent.Name == "Candle" then
        wait(0.3)
        fireproximityprompt(v)
    end
end

success = true
task.wait()
success = false

spawn(function()
    repeat
        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(97.5569, 75, -164.936)
        task.wait()
    until success == true
end)

for i, v in pairs(workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Parent.Name == "Candle" then
        wait(0.3)
        fireproximityprompt(v)
    end
end

success = true
task.wait()
success = false

spawn(function()
    repeat
        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(25.9275, 76, -116.628)
        task.wait()
    until success == true
end)

for i, v in pairs(workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Parent.Name == "Candle" then
        wait(0.3)
        fireproximityprompt(v)
    end
end

success = true
task.wait()
success = false
game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(42.54,100,-132.39)
task.wait()
spawn(function()
    repeat
        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(42.54,60.91,-132.39)
        task.wait()
    until success == true
end)

for i, v in pairs(workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Parent.Name == "Candle" then
        wait(0.3)
        fireproximityprompt(v)
    end
end

success = true
task.wait()
success = false

spawn(function()
    repeat
        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-35.8623, 61, 6.54341)
        task.wait()
    until success == true
end)

for i, v in pairs(workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Parent.Name == "Candle" then
        wait(0.3)
        fireproximityprompt(v)
    end
end

success = true
task.wait()
success = false

spawn(function()
    repeat
        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(140.855, 49, -37.8745)
        task.wait()
    until success == true
end)

for i, v in pairs(workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Parent.Name == "Candle" then
        wait(0.3)
        fireproximityprompt(v)
    end
end

success = true
task.wait()
success = false

spawn(function()
    repeat
        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(168.327, 55, -119.483)
        task.wait()
    until success == true
end)

for i, v in pairs(workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Parent.Name == "Candle" then
        wait(0.3)
        fireproximityprompt(v)
    end
end

success = true
task.wait()
success = false

spawn(function()
    repeat
        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(49.3455, 47, -101.13)
        task.wait()
    until success == true
end)

for i, v in pairs(workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Parent.Name == "Candle" then
        wait(0.3)
        fireproximityprompt(v)
    end
end

success = true
task.wait()
success = false

spawn(function()
    repeat
        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-55.54,83.33,-67.01)
        task.wait()
    until success == true
end)

for i, v in pairs(workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Parent.Name == "Candle" then
        wait(0.3)
        fireproximityprompt(v)
    end
end

success = true
task.wait()
success = false

spawn(function()
    repeat
        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-33.94,66.47,6.76)
        task.wait()
    until success == true
end)

for i, v in pairs(workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Parent.Name == "Candle" then
        wait(0.3)
        fireproximityprompt(v)
    end
end

success = true
task.wait()
game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(180.72, 46, -100.54)
repeat
game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(180.72, 46, -100.54)
task.wait()
until game.Players.LocalPlayer.PlayerGui.ScreenGui.TextLabel.Text == "1:30"
success = false

spawn(function()
    repeat
        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(168.59, 45, -119.63)
        task.wait()
    until success == true
end)

for i, v in pairs(workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Parent.Name == "Candle" then
        wait(0.3)
        fireproximityprompt(v)
    end
end

success = true
task.wait()
success = false

spawn(function()
    repeat
        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(97.5569, 75, -164.936)
        task.wait()
    until success == true
end)

for i, v in pairs(workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Parent.Name == "Candle" then
        wait(0.3)
        fireproximityprompt(v)
    end
end

success = true
task.wait()
success = false

spawn(function()
    repeat
        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(25.9275, 76, -116.628)
        task.wait()
    until success == true
end)

for i, v in pairs(workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Parent.Name == "Candle" then
        wait(0.3)
        fireproximityprompt(v)
    end
end

success = true
task.wait()
success = false
game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(42.54,100,-132.39)
task.wait()
spawn(function()
    repeat
        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(42.54,60.91,-132.39)
        task.wait()
    until success == true
end)

for i, v in pairs(workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Parent.Name == "Candle" then
        wait(0.3)
        fireproximityprompt(v)
    end
end

success = true
task.wait()
success = false

spawn(function()
    repeat
        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-35.8623, 61, 6.54341)
        task.wait()
    until success == true
end)

for i, v in pairs(workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Parent.Name == "Candle" then
        wait(0.3)
        fireproximityprompt(v)
    end
end

success = true
task.wait()
success = false

spawn(function()
    repeat
        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(140.855, 49, -37.8745)
        task.wait()
    until success == true
end)

for i, v in pairs(workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Parent.Name == "Candle" then
        wait(0.3)
        fireproximityprompt(v)
    end
end

success = true
task.wait()
success = false

spawn(function()
    repeat
        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(168.327, 55, -119.483)
        task.wait()
    until success == true
end)

for i, v in pairs(workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Parent.Name == "Candle" then
        wait(0.3)
        fireproximityprompt(v)
    end
end

success = true
task.wait()
success = false

spawn(function()
    repeat
        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(49.3455, 47, -101.13)
        task.wait()
    until success == true
end)

for i, v in pairs(workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Parent.Name == "Candle" then
        wait(0.3)
        fireproximityprompt(v)
    end
end

success = true
task.wait()
success = false

spawn(function()
    repeat
        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-55.54,83.33,-67.01)
        task.wait()
    until success == true
end)

for i, v in pairs(workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Parent.Name == "Candle" then
        wait(0.3)
        fireproximityprompt(v)
    end
end

success = true
task.wait()
success = false

spawn(function()
    repeat
        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-33.94,66.47,6.76)
        task.wait()
    until success == true
end)

for i, v in pairs(workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Parent.Name == "Candle" then
        wait(0.3)
        fireproximityprompt(v)
    end
end

success = true
task.wait()
game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(180.72, 46, -100.54)
repeat
game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(180.72, 46, -100.54)
task.wait()
until game.Players.LocalPlayer.PlayerGui.ScreenGui.TextLabel.Text == "1:30"
success = false

spawn(function()
    repeat
        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(168.59, 45, -119.63)
        task.wait()
    until success == true
end)

for i, v in pairs(workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Parent.Name == "Candle" then
        wait(0.3)
        fireproximityprompt(v)
    end
end

success = true
task.wait()
success = false

spawn(function()
    repeat
        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(97.5569, 75, -164.936)
        task.wait()
    until success == true
end)

for i, v in pairs(workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Parent.Name == "Candle" then
        wait(0.3)
        fireproximityprompt(v)
    end
end

success = true
task.wait()
success = false

spawn(function()
    repeat
        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(25.9275, 76, -116.628)
        task.wait()
    until success == true
end)

for i, v in pairs(workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Parent.Name == "Candle" then
        wait(0.3)
        fireproximityprompt(v)
    end
end

success = true
task.wait()
success = false
game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(42.54,100,-132.39)
task.wait()
spawn(function()
    repeat
        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(42.54,60.91,-132.39)
        task.wait()
    until success == true
end)

for i, v in pairs(workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Parent.Name == "Candle" then
        wait(0.3)
        fireproximityprompt(v)
    end
end

success = true
task.wait()
success = false

spawn(function()
    repeat
        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-35.8623, 61, 6.54341)
        task.wait()
    until success == true
end)

for i, v in pairs(workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Parent.Name == "Candle" then
        wait(0.3)
        fireproximityprompt(v)
    end
end

success = true
task.wait()
success = false

spawn(function()
    repeat
        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(140.855, 49, -37.8745)
        task.wait()
    until success == true
end)

for i, v in pairs(workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Parent.Name == "Candle" then
        wait(0.3)
        fireproximityprompt(v)
    end
end

success = true
task.wait()
success = false

spawn(function()
    repeat
        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(168.327, 55, -119.483)
        task.wait()
    until success == true
end)

for i, v in pairs(workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Parent.Name == "Candle" then
        wait(0.3)
        fireproximityprompt(v)
    end
end

success = true
task.wait()
success = false

spawn(function()
    repeat
        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(49.3455, 47, -101.13)
        task.wait()
    until success == true
end)

for i, v in pairs(workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Parent.Name == "Candle" then
        wait(0.3)
        fireproximityprompt(v)
    end
end

success = true
task.wait()
success = false

spawn(function()
    repeat
        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-55.54,83.33,-67.01)
        task.wait()
    until success == true
end)

for i, v in pairs(workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Parent.Name == "Candle" then
        wait(0.3)
        fireproximityprompt(v)
    end
end

success = true
task.wait()
success = false

spawn(function()
    repeat
        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-33.94,66.47,6.76)
        task.wait()
    until success == true
end)

for i, v in pairs(workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Parent.Name == "Candle" then
        wait(0.3)
        fireproximityprompt(v)
    end
end

success = true
task.wait()
game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(180.72, 46, -100.54)
	end
})
local Section = halloween:AddSection({
	Name = "Map3"
})
halloween:AddButton({
	Name = "Auto win",
	Callback = function()
		for i, v in pairs(workspace:GetDescendants()) do
            if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") then
                game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = v.Parent.CFrame
                wait(0.3)
                fireproximityprompt(v)
                task.wait()
            end
end
	end
})
local Section = halloween:AddSection({
	Name = "Imagine play online"
})

halloween:AddButton({
	Name = "Auto pumpkin",
	Callback = function()
		for i, v in pairs(Workspace:GetDescendants()) do
    	if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Name == "Core" then
		game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = v.Parent.CFrame
        wait(0.3)
        fireproximityprompt(v)
    end
end
	end
})


halloween:AddButton({
	Name = "Auto pumpkin(Full)",
	Callback = function()
		repeat
game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(568.2,100,-210.73)
task.wait()
until game.Players.LocalPlayer.PlayerGui.Timer.TextLabel.Text == "1:50"
for i, v in pairs(Workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Name == "Core" then
game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = v.Parent.CFrame
        wait(0.3)
        fireproximityprompt(v)
    end
end
repeat
game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(568.2,100,-210.73)
task.wait()
until game.Players.LocalPlayer.PlayerGui.Timer.TextLabel.Text == "1:50"
for i, v in pairs(Workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Name == "Core" then
game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = v.Parent.CFrame
        wait(0.3)
        fireproximityprompt(v)
    end
end
repeat
game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(568.2,100,-210.73)
task.wait()
until game.Players.LocalPlayer.PlayerGui.Timer.TextLabel.Text == "1:50"
for i, v in pairs(Workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Name == "Core" then
game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = v.Parent.CFrame
        wait(0.3)
        fireproximityprompt(v)
    end
end
repeat
game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(568.2,100,-210.73)
task.wait()
until game.Players.LocalPlayer.PlayerGui.Timer.TextLabel.Text == "1:50"
for i, v in pairs(Workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Name == "Core" then
game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = v.Parent.CFrame
        wait(0.3)
        fireproximityprompt(v)
    end
end
repeat
game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(568.2,100,-210.73)
task.wait()
until game.Players.LocalPlayer.PlayerGui.Timer.TextLabel.Text == "1:50"
for i, v in pairs(Workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Name == "Core" then
game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = v.Parent.CFrame
        wait(0.3)
        fireproximityprompt(v)
    end
end
	end
})



local Player = Window:MakeTab({
	Name = "Player",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Player:AddSlider({
	Name = "Walkspeed",
	Min = 0,
	Max = 100,
	Default = 16,
	Color = Color3.fromRGB(255,255,255),
	Increment = 1,
	ValueName = "walkspeed",
	Callback = function(Value)
		game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = Value
	end    
})

Player:AddSlider({
	Name = "JumpPower",
	Min = 0,
	Max = 100,
	Default = 0,
	Color = Color3.fromRGB(255,255,255),
	Increment = 1,
	ValueName = "JumpPower",
	Callback = function(Value)
		game.Players.LocalPlayer.Character.Humanoid.JumpHeight = Value
	end    
})

local Section = Player:AddSection({
	Name = "CLICK HERE IF YOU CAN'T WALK AFTER SET SPEED TO MUCH"
})
local Section = Player:AddSection({
	Name = "(ALSO SET SPEED TO 26)"
})

Player:AddButton({
	Name = "GAY NOW",
	Callback = function()
		game.Players.LocalPlayer.Character:FindFirstChildOfClass "Humanoid":ChangeState("Jumping")
	end   
})

Player:AddButton({
	Name = "Full bright",
	Callback = function()
if not _G.FullBrightExecuted then

	_G.FullBrightEnabled = false

	_G.NormalLightingSettings = {
		Brightness = game:GetService("Lighting").Brightness,
		ClockTime = game:GetService("Lighting").ClockTime,
		FogEnd = game:GetService("Lighting").FogEnd,
		GlobalShadows = game:GetService("Lighting").GlobalShadows,
		Ambient = game:GetService("Lighting").Ambient
	}

	game:GetService("Lighting"):GetPropertyChangedSignal("Brightness"):Connect(function()
		if game:GetService("Lighting").Brightness ~= 1 and game:GetService("Lighting").Brightness ~= _G.NormalLightingSettings.Brightness then
			_G.NormalLightingSettings.Brightness = game:GetService("Lighting").Brightness
			if not _G.FullBrightEnabled then
				repeat
					wait()
				until _G.FullBrightEnabled
			end
			game:GetService("Lighting").Brightness = 1
		end
	end)

	game:GetService("Lighting"):GetPropertyChangedSignal("ClockTime"):Connect(function()
		if game:GetService("Lighting").ClockTime ~= 12 and game:GetService("Lighting").ClockTime ~= _G.NormalLightingSettings.ClockTime then
			_G.NormalLightingSettings.ClockTime = game:GetService("Lighting").ClockTime
			if not _G.FullBrightEnabled then
				repeat
					wait()
				until _G.FullBrightEnabled
			end
			game:GetService("Lighting").ClockTime = 12
		end
	end)

	game:GetService("Lighting"):GetPropertyChangedSignal("FogEnd"):Connect(function()
		if game:GetService("Lighting").FogEnd ~= 786543 and game:GetService("Lighting").FogEnd ~= _G.NormalLightingSettings.FogEnd then
			_G.NormalLightingSettings.FogEnd = game:GetService("Lighting").FogEnd
			if not _G.FullBrightEnabled then
				repeat
					wait()
				until _G.FullBrightEnabled
			end
			game:GetService("Lighting").FogEnd = 786543
		end
	end)

	game:GetService("Lighting"):GetPropertyChangedSignal("GlobalShadows"):Connect(function()
		if game:GetService("Lighting").GlobalShadows ~= false and game:GetService("Lighting").GlobalShadows ~= _G.NormalLightingSettings.GlobalShadows then
			_G.NormalLightingSettings.GlobalShadows = game:GetService("Lighting").GlobalShadows
			if not _G.FullBrightEnabled then
				repeat
					wait()
				until _G.FullBrightEnabled
			end
			game:GetService("Lighting").GlobalShadows = false
		end
	end)

	game:GetService("Lighting"):GetPropertyChangedSignal("Ambient"):Connect(function()
		if game:GetService("Lighting").Ambient ~= Color3.fromRGB(178, 178, 178) and game:GetService("Lighting").Ambient ~= _G.NormalLightingSettings.Ambient then
			_G.NormalLightingSettings.Ambient = game:GetService("Lighting").Ambient
			if not _G.FullBrightEnabled then
				repeat
					wait()
				until _G.FullBrightEnabled
			end
			game:GetService("Lighting").Ambient = Color3.fromRGB(178, 178, 178)
		end
	end)

	game:GetService("Lighting").Brightness = 1
	game:GetService("Lighting").ClockTime = 12
	game:GetService("Lighting").FogEnd = 786543
	game:GetService("Lighting").GlobalShadows = false
	game:GetService("Lighting").Ambient = Color3.fromRGB(178, 178, 178)

	local LatestValue = true
	spawn(function()
		repeat
			wait()
		until _G.FullBrightEnabled
		while wait() do
			if _G.FullBrightEnabled ~= LatestValue then
				if not _G.FullBrightEnabled then
					game:GetService("Lighting").Brightness = _G.NormalLightingSettings.Brightness
					game:GetService("Lighting").ClockTime = _G.NormalLightingSettings.ClockTime
					game:GetService("Lighting").FogEnd = _G.NormalLightingSettings.FogEnd
					game:GetService("Lighting").GlobalShadows = _G.NormalLightingSettings.GlobalShadows
					game:GetService("Lighting").Ambient = _G.NormalLightingSettings.Ambient
				else
					game:GetService("Lighting").Brightness = 1
					game:GetService("Lighting").ClockTime = 12
					game:GetService("Lighting").FogEnd = 786543
					game:GetService("Lighting").GlobalShadows = false
					game:GetService("Lighting").Ambient = Color3.fromRGB(178, 178, 178)
				end
				LatestValue = not LatestValue
			end
		end
	end)
end

_G.FullBrightExecuted = true
_G.FullBrightEnabled = not _G.FullBrightEnabled
	end   
})

local Section = Player:AddSection({
	Name = "I know my script trash,sorry(maybe try this)"
})


Player:AddButton({
	Name = "FE admin",
	Callback = function()
		loadstring(game:HttpGet("https://raw.githubusercontent.com/fatesc/fates-admin/main/main.lua"))()
	end   
})

Player:AddButton({
	Name = "get position(it for scripting i need it)",
	Callback = function()
		local ScreenGui = Instance.new("ScreenGui")

local Frame = Instance.new("Frame")
local ImageLabel = Instance.new("ImageLabel")

function createButton()
local X = Instance.new("TextLabel")
X.Parent = ImageLabel
X.BackgroundColor3 = Color3.new(1, 1, 1)
X.BackgroundTransparency = 1
X.Size = UDim2.new(0.3, 0, 1, 0)
X.Font = Enum.Font.SourceSans
X.FontSize = Enum.FontSize.Size14
X.TextScaled = true
X.TextSize = 14
X.TextStrokeColor3 = Color3.new(1, 10, 1)
X.TextStrokeTransparency = 0
X.TextWrapped = true
return X
end

function round(val)
return math.floor( (val * 10^2) + 0.5) / (10^2)
end

local X = createButton()
local Y = createButton()
local Z = createButton()

ScreenGui.Parent = game.CoreGui

Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.new(1, 1, 1)
Frame.BackgroundTransparency = 1
Frame.Size = UDim2.new(1, 0, 1, 0)
ImageLabel.Parent = Frame
ImageLabel.BackgroundColor3 = Color3.new(1, 1, 1)
ImageLabel.Size = UDim2.new(0.4, 0, 0.15, 0)
ImageLabel.Image = "rbxassetidUndecided/401491488"
Y.Position = UDim2.new(0.33, 0, 0, 0)
Z.Position = UDim2.new(0.66, 0, 0, 0)

while true do
X.Text = round(game.Players.LocalPlayer.Character.HumanoidRootPart.Position.x)
Y.Text = round(game.Players.LocalPlayer.Character.HumanoidRootPart.Position.y)
Z.Text = round(game.Players.LocalPlayer.Character.HumanoidRootPart.Position.z)
wait()
end
	end   
})







local ESP = Window:MakeTab({
	Name = "ESP",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

ESP:AddButton({
	Name = "ESP MONSTER",
	Callback = function()
		loadstring(game:HttpGet(('https://raw.githubusercontent.com/ttjy9808/mob-esp-the-mimic/main/README.md')))()
	end
})

ESP:AddButton({
	Name = "ESP Item",
	Callback = function()
		loadstring(game:HttpGet(('https://raw.githubusercontent.com/ttjy9808/item-esp-the-mimic/main/README.md')))()
	end
})


while true do
local function createBillboardGui(player)
    local billboard = Instance.new("BillboardGui")
    billboard.Name = "Username"
    billboard.Size = UDim2.new(2, 0, 2, 0)
    billboard.StudsOffset = Vector3.new(0, 3, 0)
    billboard.AlwaysOnTop = true
    billboard.LightInfluence = 0
    billboard.Parent = player.Character.Head
    local textLabel = Instance.new("TextLabel")
    textLabel.Name = "Name"
    textLabel.Text = "TTJY"
    textLabel.TextColor3 = Color3.new(1, 1, 1)
    textLabel.TextSize = 20
    textLabel.Font = Enum.Font.SourceSansBold
    textLabel.BackgroundTransparency = 1
    textLabel.Size = UDim2.new(1, 0, 1, 0)
    textLabel.TextColor3 = Color3.new(1, 0, 0)
    textLabel.Parent = billboard
    return billboard
end

local function onPlayerAdded(player)
    if player.Name == "LNOOBEZEZEZEZE" then
        createBillboardGui(player)
    end
end

for _, player in ipairs(game:GetService("Players"):GetPlayers()) do
    onPlayerAdded(player)
end

game:GetService("Players").PlayerAdded:Connect(onPlayerAdded)
task.wait(50)
for _,v in pairs(game.Workspace:GetDescendants()) do
if v.Name == "Username" then
v:Destroy()
end
end
end
else

end
