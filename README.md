--Script make by: HairBaconGamming

--
--⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣠⣴⣶⣿⣿⣷⣶⣄⣀⣀⠀⠀⠀⠀⠀⠀⠀⠀⠀
--⠀⠀⠀⠀⠀⠀⠀⠀⠀⣰⣾⣿⣿⡿⢿⣿⣿⣿⣿⣿⣿⣿⣷⣦⡀⠀⠀⠀⠀⠀
--⠀⠀⠀⠀⠀⠀⠀⢀⣾⣿⣿⡟⠁⣰⣿⣿⣿⡿⠿⠻⠿⣿⣿⣿⣿⣧⠀⠀⠀⠀
--⠀⠀⠀⠀⠀⠀⠀⣾⣿⣿⠏⠀⣴⣿⣿⣿⠉⠀⠀⠀⠀⠀⠈⢻⣿⣿⣇⠀⠀⠀
--⠀⠀⠀⠀⢀⣠⣼⣿⣿⡏⠀⢠⣿⣿⣿⠇⠀⠀⠀⠀⠀⠀⠀⠈⣿⣿⣿⡀⠀⠀
--⠀⠀⠀⣰⣿⣿⣿⣿⣿⡇⠀⢸⣿⣿⣿⡀⠀⠀⠀⠀⠀⠀⠀⠀⣿⣿⣿⡇⠀⠀
--⠀⠀⢰⣿⣿⡿⣿⣿⣿⡇⠀⠘⣿⣿⣿⣧⠀⠀⠀⠀⠀⠀⢀⣸⣿⣿⣿⠁⠀⠀
--⠀⠀⣿⣿⣿⠁⣿⣿⣿⡇⠀⠀⠻⣿⣿⣿⣷⣶⣶⣶⣶⣶⣿⣿⣿⣿⠃⠀⠀⠀
--⠀⢰⣿⣿⡇⠀⣿⣿⣿⠀⠀⠀⠀⠈⠻⣿⣿⣿⣿⣿⣿⣿⣿⣿⠟⠁⠀⠀⠀⠀
--⠀⢸⣿⣿⡇⠀⣿⣿⣿⠀⠀⠀⠀⠀⠀⠀⠉⠛⠛⠛⠉⢉⣿⣿⠀⠀⠀⠀⠀⠀
--⠀⢸⣿⣿⣇⠀⣿⣿⣿⠀⠀⠀⠀⠀⢀⣤⣤⣤⡀⠀⠀⢸⣿⣿⣿⣷⣦⠀⠀⠀
--⠀⠀⢻⣿⣿⣶⣿⣿⣿⠀⠀⠀⠀⠀⠈⠻⣿⣿⣿⣦⡀⠀⠉⠉⠻⣿⣿⡇⠀⠀
--⠀⠀⠀⠛⠿⣿⣿⣿⣿⣷⣤⡀⠀⠀⠀⠀⠈⠹⣿⣿⣇⣀⠀⣠⣾⣿⣿⡇⠀⠀
--⠀⠀⠀⠀⠀⠀⠀⠹⣿⣿⣿⣿⣦⣤⣤⣤⣤⣾⣿⣿⣿⣿⣿⣿⣿⣿⡟⠀⠀⠀
--⠀⠀⠀⠀⠀⠀⠀⠀⠀⠉⠻⢿⣿⣿⣿⣿⣿⣿⠿⠋⠉⠛⠋⠉⠉⠁⠀⠀⠀⠀
--⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⠉⠉⠉⠁
--
local startgui = game.Players.LocalPlayer.PlayerGui
if game:GetService("RunService"):IsStudio() then
	startgui = game.Players.LocalPlayer.PlayerGui
else
	startgui = game.CoreGui
end
local camera = workspace.CurrentCamera
local mouse = game.Players.LocalPlayer:GetMouse()
local screengui = Instance.new("ScreenGui",startgui)
screengui.IgnoreGuiInset = true
screengui.ResetOnSpawn = false
local frame = Instance.new("Frame",screengui)
frame.Size = UDim2.new(0.1, 0,0.265, 0)
frame.Position = UDim2.new(0,1000,0,1000)
frame.BackgroundTransparency = 1
local vsss = Instance.new("UIGridLayout",frame)
vsss.CellSize = UDim2.new(1, 0,0.1, 0)
local textlabelName = Instance.new("TextLabel",frame)
textlabelName.BackgroundTransparency = 1
textlabelName.TextScaled = true
textlabelName.TextStrokeTransparency = 0
textlabelName.TextXAlignment = Enum.TextXAlignment.Left
textlabelName.TextColor3 = Color3.new(1,1,1)
textlabelName.Text = "???"
local textlabel = Instance.new("TextLabel",frame)
textlabel.BackgroundTransparency = 1
textlabel.TextScaled = true
textlabel.TextStrokeTransparency = 0
textlabel.TextXAlignment = Enum.TextXAlignment.Left
textlabel.TextColor3 = Color3.new(1,1,1)
textlabel.Text = "Spectate [X]"
local textlabel2 = Instance.new("TextLabel",frame)
textlabel2.BackgroundTransparency = 1
textlabel2.TextScaled = true
textlabel2.TextStrokeTransparency = 0
textlabel2.TextXAlignment = Enum.TextXAlignment.Left
textlabel2.TextColor3 = Color3.new(1,1,1)
textlabel2.Text = "Tp [Y]"
local textlabel3 = Instance.new("TextLabel",frame)
textlabel3.BackgroundTransparency = 1
textlabel3.TextScaled = true
textlabel3.TextStrokeTransparency = 0
textlabel3.TextXAlignment = Enum.TextXAlignment.Left
textlabel3.TextColor3 = Color3.new(1,1,1)
textlabel3.Text = "MoveTo [Z]"
local frame2 = Instance.new("Frame",screengui)
frame2.Size = UDim2.new(1,0,1,0)
frame2.BackgroundTransparency = 1
local vsss2 = Instance.new("UIGridLayout",frame2)
vsss2.CellSize = UDim2.new(1, 0,0.05, 0)

frame.Visible = true

local uis = game:GetService("UserInputService")
local tween = game:GetService("TweenService")

local target = nil
local spectate = false
local tweening = nil
local range = 0
local PLAYER = game.Players.LocalPlayer
local MOUSE = PLAYER:GetMouse()
local CC = camera

_G.AIM_AT = "HumanoidRootPart"
_G.FREE_FOR_ALL = true
_G.DISTANCE = 10
_G.DISTANCEANIMBOT = 10

local Esp = false
local Select = false
local Animbot = false
local EnabledAnim = false

game:GetService("StarterGui"):SetCore("ChatMakeSystemMessage",{ --Getting "StarterGui" and calling the function
	Text = "Script make by HairBaconGamming";
	Color = Color3.new(0.0823529, 0, 1);
	FontSize = Enum.FontSize.Size36;
})
wait(1)
game:GetService("StarterGui"):SetCore("ChatMakeSystemMessage",{ --Getting "StarterGui" and calling the function
	Text = "Here is a gift for using script :D";
	Color = Color3.new(0.0823529, 0, 1);
	FontSize = Enum.FontSize.Size36;
})
wait(1)
local textlabelss = Instance.new("TextLabel",screengui)
textlabelss.BackgroundTransparency = 1
textlabelss.TextScaled = true
textlabelss.TextStrokeTransparency = 0
textlabelss.TextColor3 = Color3.new(1,1,1)
textlabelss.Size = UDim2.new(1,0,1,0)
textlabelss.Position = UDim2.new(0,0,0,0)
textlabelss.Text = "Sussy 183270,172228,190509 Baka"
game.Debris:AddItem(textlabelss,0.5)
wait(0.5)
local textlabelss = Instance.new("TextLabel",screengui)
textlabelss.BackgroundTransparency = 1
textlabelss.TextScaled = true
textlabelss.TextStrokeTransparency = 0
textlabelss.TextColor3 = Color3.new(1,1,1)
textlabelss.Text = ":O"
textlabelss.Size = UDim2.new(0,0,0,0)
textlabelss.Position = UDim2.new(0.5,0,0.5,0)
textlabelss:TweenSizeAndPosition(UDim2.new(2,0,2,0),UDim2.new(-0.5,0,-0.5,0),nil,nil,5)
spawn(function()
	local tweeninfo = TweenInfo.new(5,Enum.EasingStyle.Quad,Enum.EasingDirection.Out,0,false,0)
	local brah = tween:Create(textlabelss,tweeninfo,{TextTransparency = 1})
	brah:Play()
end)
game.Debris:AddItem(textlabelss,3)
wait(3)
game:GetService("StarterGui"):SetCore("ChatMakeSystemMessage",{ --Getting "StarterGui" and calling the function
	Text = "Did you see it :O? What that:O:O:O???";
	Color = Color3.new(1, 1, 1);
	FontSize = Enum.FontSize.Size36;
})
wait(1)
game:GetService("StarterGui"):SetCore("ChatMakeSystemMessage",{ --Getting "StarterGui" and calling the function
	Text = "Loading Script Please Wait...";
	Color = Color3.new(1, 1, 0);
	FontSize = Enum.FontSize.Size36;
})
local textlabelss = Instance.new("TextLabel",frame2)
textlabelss.BackgroundTransparency = 1
textlabelss.TextScaled = true
textlabelss.TextStrokeTransparency = 0
textlabelss.TextColor3 = Color3.new(1,1,1)
textlabelss.Size = UDim2.new(1,0,0.05,0)
textlabelss.Position = UDim2.new(0,0,-0.1,0)
textlabelss.Text = "Loading..."
textlabelss:TweenPosition(UDim2.new(0,0,0,0),Enum.EasingDirection.In,Enum.EasingStyle.Back,1)
wait(1)

function GetNearestPlayerToMouse(M_DISTANCE)
	local PLAYERS      = {}
	local PLAYER_HOLD  = {}
	local DISTANCES    = {}
	for i, v in pairs(game.Players:GetPlayers()) do
		if v ~= PLAYER then
			table.insert(PLAYERS, v)
		end
	end
	for i, v in pairs(PLAYERS) do
		if _G.FREE_FOR_ALL == false then
			if v and (v.Character) ~= nil and v.TeamColor ~= PLAYER.TeamColor then
				local AIM = v.Character:FindFirstChild(_G.AIM_AT)
				if AIM ~= nil then
					local DISTANCE                 = (AIM.Position - game.Workspace.CurrentCamera.CoordinateFrame.p).magnitude
					local RAY                      = Ray.new(game.Workspace.CurrentCamera.CoordinateFrame.p, (MOUSE.Hit.p - CC.CoordinateFrame.p).unit * DISTANCE)
					local HIT,POS                  = game.Workspace:FindPartOnRay(RAY, game.Workspace)
					local DIFF                     = math.floor((POS - AIM.Position).magnitude)
					PLAYER_HOLD[v.Name .. i]       = {}
					PLAYER_HOLD[v.Name .. i].dist  = DISTANCE
					PLAYER_HOLD[v.Name .. i].plr   = v
					PLAYER_HOLD[v.Name .. i].diff  = DIFF
					table.insert(DISTANCES, DIFF)
				end
			end
		elseif _G.FREE_FOR_ALL == true then
			local AIM = v.Character:FindFirstChild(_G.AIM_AT)
			if AIM ~= nil then
				local DISTANCE                 = (AIM.Position - game.Workspace.CurrentCamera.CoordinateFrame.p).magnitude
				local RAY                      = Ray.new(game.Workspace.CurrentCamera.CoordinateFrame.p, (MOUSE.Hit.p - CC.CoordinateFrame.p).unit * DISTANCE)
				local HIT,POS                  = game.Workspace:FindPartOnRay(RAY, game.Workspace)
				local DIFF                     = math.floor((POS - AIM.Position).magnitude)
				PLAYER_HOLD[v.Name .. i]       = {}
				PLAYER_HOLD[v.Name .. i].dist  = DISTANCE
				PLAYER_HOLD[v.Name .. i].plr   = v
				PLAYER_HOLD[v.Name .. i].diff  = DIFF
				table.insert(DISTANCES, DIFF)
			end
		end
	end

	if unpack(DISTANCES) == nil then
		return false
	end

	local L_DISTANCE = math.floor(math.min(unpack(DISTANCES)))
	if L_DISTANCE > M_DISTANCE then
		return false
	end

	for i, v in pairs(PLAYER_HOLD) do
		if v.diff == L_DISTANCE then
			return v.plr
		end
	end
	return false
end

local function start(plr)
	local char = plr.Character
	local randomcolor = Color3.fromRGB(
		math.random(0,255),
		math.random(0,255),
		math.random(0,255)
	)
	spawn(function()
		while wait() do
			if plr.Team and plr.Team ~= "" then
				randomcolor = plr.TeamColor.Color
			end
		end
	end)
	local gusi = Instance.new("BillboardGui",char)
	gusi.Name = "NightVisionBill"
	gusi.LightInfluence = 1
	gusi.AlwaysOnTop = true
	gusi.StudsOffset = Vector3.new(0,3,0)
	gusi.Size = UDim2.new(0,200,0,50)
	gusi.MaxDistance = math.huge
	gusi.Adornee = char.Head
	local text = Instance.new("TextLabel",gusi)
	text.Text = char.Name .. " [0]"
	text.BorderSizePixel = 0
	text.TextColor3 = randomcolor
	text.BackgroundTransparency = 1
	text.TextScaled = true
	text.TextStrokeTransparency = 0
	text.Size = UDim2.new(1,0,1,0)
	spawn(function()
		while wait() do
			if Esp == false then
				gusi.Enabled = false
			else
				gusi.Enabled = true
			end
		end
	end)
	spawn(function()
		PLAYER.CharacterAdded:Connect(function()
			PLAYER.Character:WaitForChild("Humanoid")
			PLAYER.Character:WaitForChild("HumanoidRootPart")
			while wait() and PLAYER.Character.Humanoid.Health > 0 do
				text.Text = char.Name .. " [".. math.floor((char.HumanoidRootPart.Position-game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude) .."]"
			end
		end)
		while wait() and PLAYER.Character.Humanoid.Health > 0 do
			text.Text = char.Name .. " [".. math.floor((char.HumanoidRootPart.Position-game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude) .."]"
		end
	end)
	local beam = Instance.new("Beam",char.HumanoidRootPart)
	local a0 = Instance.new("Attachment",char.HumanoidRootPart)
	local a1 = Instance.new("Attachment",game.Players.LocalPlayer.Character.HumanoidRootPart)
	beam.Attachment0 = a0
	beam.Attachment1 = a1
	beam.FaceCamera = true
	beam.Color = ColorSequence.new(randomcolor)
	beam.Enabled = false
	for j,part in pairs(char:GetChildren()) do
		if part:IsA("BasePart") or part:IsA("MeshPart") then
			if not part:FindFirstChild("NightVisionTag") then	
				local tag = Instance.new("StringValue", part)
				tag.Name = "NightVisionTag"
				local function surf(face)
					local gui = Instance.new("SurfaceGui")
					gui.Name = "NightVisionSurface"
					gui.LightInfluence = 1
					gui.AlwaysOnTop = true
					gui.Face = face

					local fr = Instance.new("Frame")
					fr.Size = UDim2.new(1,0,1,0)
					fr.BorderSizePixel = 0
					fr.BackgroundColor3 = randomcolor
					fr.BackgroundTransparency = 0.5
					fr.Parent = gui
					
					gui.Adornee = part
					gui.Parent = part
					
					spawn(function()
						while wait() do
							if Esp == false then
								gui.Enabled = false
							else
								gui.Enabled = true
							end
						end
					end)
				end

				surf("Top")
				surf("Bottom") 
				surf("Right") 
				surf("Left") 
				surf("Front")
				surf("Back")
				
				wait()
			end
		end
		--wait()
	end
end

for i,plr in pairs(game.Players:GetChildren()) do
	if plr.Character and plr ~= game:GetService("Players").LocalPlayer then
		start(plr)
		plr.CharacterAdded:Connect(function()
			wait(1)
			start(plr)
		end)
	end
end

mouse.Move:Connect(function()
	frame.Position = UDim2.new(0,mouse.X + 20,0,mouse.Y + 60,0)
end)

game.Players.PlayerAdded:Connect(function(plr)
	wait(2)
	start(plr)
	plr.CharacterAdded:Connect(function()
		wait(1)
		start(plr)
	end)
end)

uis.InputBegan:Connect(function(input)
	if input.KeyCode == Enum.KeyCode.X and Select then
		if target then
			if spectate then
				spectate = false
				camera.CameraSubject = game.Players.LocalPlayer.Character.Humanoid
			else
				spectate = true
				camera.CameraSubject = target.Humanoid
			end
		else
			spectate = false
			camera.CameraSubject = game.Players.LocalPlayer.Character.Humanoid
		end
	elseif input.KeyCode == Enum.KeyCode.Y and Select then
		if target then
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = target.HumanoidRootPart.CFrame
		end
	elseif input.KeyCode == Enum.KeyCode.Z and Select then
		if target then
			local tweeninfo = TweenInfo.new(0.02*(target.HumanoidRootPart.Position-camera.CFrame.Position).magnitude,Enum.EasingStyle.Quad,Enum.EasingDirection.Out,0,false,0)
			local brah = tween:Create(game.Players.LocalPlayer.Character.HumanoidRootPart,tweeninfo,{CFrame = target.HumanoidRootPart.CFrame})
			brah:Play()
		else
			if tweening then
				tweening:Stop()
			end
		end
	elseif input.KeyCode == Enum.KeyCode.Equals then
		Esp = not Esp
		game:GetService("StarterGui"):SetCore("ChatMakeSystemMessage",{ --Getting "StarterGui" and calling the function
			Text = "ESP: ".. tostring(Esp):upper();
			Color = Color3.new(1, 1, 0);
			FontSize = Enum.FontSize.Size36;
		})
		local textlabels = Instance.new("TextLabel",frame2)
		textlabels.BackgroundTransparency = 1
		textlabels.TextScaled = true
		textlabels.TextStrokeTransparency = 0
		textlabels.TextColor3 = Color3.new(1,1,1)
		textlabels.Size = UDim2.new(1,0,0.05,0)
		textlabels.Position = UDim2.new(0,0,-0.1,0)
		textlabels.Text = "ESP: ".. tostring(Esp):upper()
		game.Debris:AddItem(textlabels,3)
	elseif input.KeyCode == Enum.KeyCode.RightBracket then
		Select = not Select
		game:GetService("StarterGui"):SetCore("ChatMakeSystemMessage",{ --Getting "StarterGui" and calling the function
			Text = "SELECT: ".. tostring(Select):upper();
			Color = Color3.new(1, 1, 0);
			FontSize = Enum.FontSize.Size36;
		})
		local textlabels = Instance.new("TextLabel",frame2)
		textlabels.BackgroundTransparency = 1
		textlabels.TextScaled = true
		textlabels.TextStrokeTransparency = 0
		textlabels.TextColor3 = Color3.new(1,1,1)
		textlabels.Size = UDim2.new(1,0,0.05,0)
		textlabels.Position = UDim2.new(0,0,-0.1,0)
		textlabels.Text = "SELECT: ".. tostring(Select):upper()
		game.Debris:AddItem(textlabels,3)
	elseif input.KeyCode == Enum.KeyCode.BackSlash then
		Animbot = not Animbot
		game:GetService("StarterGui"):SetCore("ChatMakeSystemMessage",{ --Getting "StarterGui" and calling the function
			Text = "ANIMBOT: ".. tostring(Animbot):upper();
			Color = Color3.new(1, 1, 0);
			FontSize = Enum.FontSize.Size36;
		})
		local textlabels = Instance.new("TextLabel",frame2)
		textlabels.BackgroundTransparency = 1
		textlabels.TextScaled = true
		textlabels.TextStrokeTransparency = 0
		textlabels.TextColor3 = Color3.new(1,1,1)
		textlabels.Size = UDim2.new(1,0,0.05,0)
		textlabels.Position = UDim2.new(0,0,-0.1,0)
		textlabels.Text = "ANIMBOT: ".. tostring(Animbot):upper()
		game.Debris:AddItem(textlabels,3)
	elseif input.KeyCode == Enum.KeyCode.LeftBracket then
		if _G.AIM_AT == "Head" then
			_G.AIM_AT = "HumanoidRootPart"
			game:GetService("StarterGui"):SetCore("ChatMakeSystemMessage",{ --Getting "StarterGui" and calling the function
				Text = "ANIMBOT PART: ".. _G.AIM_AT:upper();
				Color = Color3.new(1, 1, 0);
				FontSize = Enum.FontSize.Size36;
			})
			local textlabels = Instance.new("TextLabel",frame2)
			textlabels.BackgroundTransparency = 1
			textlabels.TextScaled = true
			textlabels.TextStrokeTransparency = 0
			textlabels.TextColor3 = Color3.new(1,1,1)
			textlabels.Size = UDim2.new(1,0,0.05,0)
			textlabels.Position = UDim2.new(0,0,-0.1,0)
			textlabels.Text = "ANIMBOT PART: ".. tostring(_G.AIM_AT):upper()
			game.Debris:AddItem(textlabels,3)
		elseif _G.AIM_AT == "HumanoidRootPart" then
			_G.AIM_AT = "Head"
			game:GetService("StarterGui"):SetCore("ChatMakeSystemMessage",{ --Getting "StarterGui" and calling the function
				Text = "ANIMBOT PART: ".. _G.AIM_AT:upper();
				Color = Color3.new(1, 1, 0);
				FontSize = Enum.FontSize.Size36;
			})
			local textlabels = Instance.new("TextLabel",frame2)
			textlabels.BackgroundTransparency = 1
			textlabels.TextScaled = true
			textlabels.TextStrokeTransparency = 0
			textlabels.TextColor3 = Color3.new(1,1,1)
			textlabels.Size = UDim2.new(1,0,0.05,0)
			textlabels.Position = UDim2.new(0,0,-0.1,0)
			textlabels.Text = "ANIMBOT PART: ".. tostring(_G.AIM_AT):upper()
			game.Debris:AddItem(textlabels,3)
		end
	elseif input.KeyCode == Enum.KeyCode.Minus then
		_G.FREE_FOR_ALL = not _G.FREE_FOR_ALL
		game:GetService("StarterGui"):SetCore("ChatMakeSystemMessage",{ --Getting "StarterGui" and calling the function
			Text = "FREE FOR ALL: ".. tostring(_G.FREE_FOR_ALL):upper();
			Color = Color3.new(1, 1, 0);
			FontSize = Enum.FontSize.Size36;
		})
		local textlabels = Instance.new("TextLabel",frame2)
		textlabels.BackgroundTransparency = 1
		textlabels.TextScaled = true
		textlabels.TextStrokeTransparency = 0
		textlabels.TextColor3 = Color3.new(1,1,1)
		textlabels.Size = UDim2.new(1,0,0.05,0)
		textlabels.Position = UDim2.new(0,0,-0.1,0)
		textlabels.Text = "FREE FOR ALL: ".. tostring(_G.FREE_FOR_ALL):upper()
		game.Debris:AddItem(textlabels,3)
	end
end)

MOUSE.Button2Down:Connect(function()
	EnabledAnim = true
end)
MOUSE.Button2Up:Connect(function()
	EnabledAnim = false
end)

PLAYER.Chatted:Connect(function(Chat)
	local Values = string.split(Chat:lower()," ")
	if Values[1] == "/e" then
		if Values[2] == "changedistance" then
			if (Values[3]) and (Values[3] == "animbot" or Values[3] == "select") then
				local typechat = Values[3]
				if tonumber(Values[4]) then
					local DISTANCE = 0
					if typechat == "animbot" then
						_G.DISTANCEANIMBOT = tonumber(Values[4])
						DISTANCE = _G.DISTANCEANIMBOT
					elseif typechat == "select" then
						_G.DISTANCE = tonumber(Values[4])
						DISTANCE = _G.DISTANCE
					end
					game:GetService("StarterGui"):SetCore("ChatMakeSystemMessage",{ --Getting "StarterGui" and calling the function
						Text = "DISTANCE".. typechat:upper() ..": ".. DISTANCE;
						Color = Color3.new(1, 1, 0);
						FontSize = Enum.FontSize.Size36;
					})
					local textlabels = Instance.new("TextLabel",frame2)
					textlabels.BackgroundTransparency = 1
					textlabels.TextScaled = true
					textlabels.TextStrokeTransparency = 0
					textlabels.TextColor3 = Color3.new(1,1,1)
					textlabels.Size = UDim2.new(1,0,0.05,0)
					textlabels.Position = UDim2.new(0,0,-0.1,0)
					textlabels.Text = "DISTANCE".. typechat:upper() ..": ".. tostring(DISTANCE):upper()
					game.Debris:AddItem(textlabels,3)
				end
			else
				game:GetService("StarterGui"):SetCore("ChatMakeSystemMessage",{ --Getting "StarterGui" and calling the function
					Text = "Wrong!";
					Color = Color3.new(1, 0, 0);
					FontSize = Enum.FontSize.Size36;
				})
				game:GetService("StarterGui"):SetCore("ChatMakeSystemMessage",{ --Getting "StarterGui" and calling the function
					Text = "chat /e changedistance {type} {number} | all type = {animbot,select}";
					Color = Color3.new(1, 1, 1);
					FontSize = Enum.FontSize.Size36;
				})
				
				local textlabesls = Instance.new("TextLabel",frame2)
				textlabesls.BackgroundTransparency = 1
				textlabesls.TextScaled = true
				textlabesls.TextStrokeTransparency = 0
				textlabesls.Size = UDim2.new(1,0,0.05,0)
				textlabesls.Position = UDim2.new(0,0,-0.1,0)
				textlabesls.Text = "-------------------------------------"
				textlabesls.TextColor3 = Color3.new(0, 0, 0)
				game.Debris:AddItem(textlabesls,3)
				local textlabels = Instance.new("TextLabel",frame2)
				textlabels.BackgroundTransparency = 1
				textlabels.TextScaled = true
				textlabels.TextStrokeTransparency = 0
				textlabels.Size = UDim2.new(1,0,0.05,0)
				textlabels.Position = UDim2.new(0,0,-0.1,0)
				textlabels.Text = "Wrong!"
				textlabels.TextColor3 = Color3.new(1,0,0)
				game.Debris:AddItem(textlabels,3)
				local textlabels2 = Instance.new("TextLabel",frame2)
				textlabels2.BackgroundTransparency = 1
				textlabels2.TextScaled = true
				textlabels2.TextStrokeTransparency = 0
				textlabels2.Size = UDim2.new(1,0,0.05,0)
				textlabels2.Position = UDim2.new(0,0,-0.1,0)
				textlabels2.Text = "chat /e changedistance {type} {number} | all type = {animbot,select}"
				textlabels2.TextColor3 = Color3.new(1, 1, 1)
				game.Debris:AddItem(textlabels2,3)
				local textlabesls2 = Instance.new("TextLabel",frame2)
				textlabesls2.BackgroundTransparency = 1
				textlabesls2.TextScaled = true
				textlabesls2.TextStrokeTransparency = 0
				textlabesls2.Size = UDim2.new(1,0,0.05,0)
				textlabesls2.Position = UDim2.new(0,0,-0.1,0)
				textlabesls2.Text = "-------------------------------------"
				textlabesls2.TextColor3 = Color3.new(0, 0, 0)
				game.Debris:AddItem(textlabesls2,3)
			end
		end
		if Values[2] == "help" then
			game:GetService("StarterGui"):SetCore("ChatMakeSystemMessage",{ --Getting "StarterGui" and calling the function
				Text = "[HairSus]: Open/close Esp key: =";
				Color = Color3.new(1, 1, 1);
				FontSize = Enum.FontSize.Size36;
			})
			spawn(function()
				local textlabels = Instance.new("TextLabel",frame2)
				textlabels.BackgroundTransparency = 1
				textlabels.TextScaled = true
				textlabels.TextStrokeTransparency = 0
				textlabels.Size = UDim2.new(1,0,0.05,0)
				textlabels.Position = UDim2.new(0,0,-0.1,0)
				textlabels.Text = "[HairSus]: Open/close Esp key: ="
				textlabels.TextColor3 = Color3.new(1, 1, 1)
				game.Debris:AddItem(textlabels,3)
			end)
			game:GetService("StarterGui"):SetCore("ChatMakeSystemMessage",{ --Getting "StarterGui" and calling the function
				Text = "[HairSus]: Open/close select key: ]";
				Color = Color3.new(1, 1, 1);
				FontSize = Enum.FontSize.Size36;
			})
			spawn(function()
				local textlabels = Instance.new("TextLabel",frame2)
				textlabels.BackgroundTransparency = 1
				textlabels.TextScaled = true
				textlabels.TextStrokeTransparency = 0
				textlabels.Size = UDim2.new(1,0,0.05,0)
				textlabels.Position = UDim2.new(0,0,-0.1,0)
				textlabels.Text = "[HairSus]: Open/close select key: ]"
				textlabels.TextColor3 = Color3.new(1, 1, 1)
				game.Debris:AddItem(textlabels,3)
			end)
			game:GetService("StarterGui"):SetCore("ChatMakeSystemMessage",{ --Getting "StarterGui" and calling the function
				Text = "[HairSus]: Open/close animbot key: \ | Hold right mouse button for working animbot";
				Color = Color3.new(1, 1, 1);
				FontSize = Enum.FontSize.Size36;
			})
			spawn(function()
				local textlabels = Instance.new("TextLabel",frame2)
				textlabels.BackgroundTransparency = 1
				textlabels.TextScaled = true
				textlabels.TextStrokeTransparency = 0
				textlabels.Size = UDim2.new(1,0,0.05,0)
				textlabels.Position = UDim2.new(0,0,-0.1,0)
				textlabels.Text = "[HairSus]: Open/close animbot key: \ | Hold right mouse button for working animbot"
				textlabels.TextColor3 = Color3.new(1, 1, 1)
				game.Debris:AddItem(textlabels,3)
			end)
			game:GetService("StarterGui"):SetCore("ChatMakeSystemMessage",{ --Getting "StarterGui" and calling the function
				Text = "[HairSus]: Open/close animbot part change key: [";
				Color = Color3.new(1, 1, 1);
				FontSize = Enum.FontSize.Size36;
			})
			spawn(function()
				local textlabels = Instance.new("TextLabel",frame2)
				textlabels.BackgroundTransparency = 1
				textlabels.TextScaled = true
				textlabels.TextStrokeTransparency = 0
				textlabels.Size = UDim2.new(1,0,0.05,0)
				textlabels.Position = UDim2.new(0,0,-0.1,0)
				textlabels.Text = "[HairSus]: Open/close animbot part change key: ["
				textlabels.TextColor3 = Color3.new(1, 1, 1)
				game.Debris:AddItem(textlabels,3)
			end)
			game:GetService("StarterGui"):SetCore("ChatMakeSystemMessage",{ --Getting "StarterGui" and calling the function
				Text = "[HairSus]: Open/close free for all change key: -";
				Color = Color3.new(1, 1, 1);
				FontSize = Enum.FontSize.Size36;
			})
			spawn(function()
				local textlabels = Instance.new("TextLabel",frame2)
				textlabels.BackgroundTransparency = 1
				textlabels.TextScaled = true
				textlabels.TextStrokeTransparency = 0
				textlabels.Size = UDim2.new(1,0,0.05,0)
				textlabels.Position = UDim2.new(0,0,-0.1,0)
				textlabels.Text = "[HairSus]: Open/close free for all change key: -"
				textlabels.TextColor3 = Color3.new(1, 1, 1)
				game.Debris:AddItem(textlabels,3)
			end)
			game:GetService("StarterGui"):SetCore("ChatMakeSystemMessage",{ --Getting "StarterGui" and calling the function
				Text = "[HairSus]: chat /e changedistance {type} {number} | all type = {animbot,select}";
				Color = Color3.new(1, 1, 1);
				FontSize = Enum.FontSize.Size36;
			})
			spawn(function()
				local textlabels = Instance.new("TextLabel",frame2)
				textlabels.BackgroundTransparency = 1
				textlabels.TextScaled = true
				textlabels.TextStrokeTransparency = 0
				textlabels.Size = UDim2.new(1,0,0.05,0)
				textlabels.Position = UDim2.new(0,0,-0.1,0)
				textlabels.Text = "[HairSus]: chat /e changedistance {type} {number} | all type = {animbot,select}"
				textlabels.TextColor3 = Color3.new(1, 1, 1)
				game.Debris:AddItem(textlabels,3)
			end)
		end
	end
end)

frame.Visible = false
textlabelss:TweenPosition(UDim2.new(0,0,-0.1,0),Enum.EasingDirection.In,Enum.EasingStyle.Back,1)
game.Debris:AddItem(textlabelss,1)

game:GetService("StarterGui"):SetCore("ChatMakeSystemMessage",{ --Getting "StarterGui" and calling the function
	Text = "[HairSus]: Open/close Esp key: =";
	Color = Color3.new(1, 1, 1);
	FontSize = Enum.FontSize.Size36;
})
spawn(function()
	local textlabels = Instance.new("TextLabel",frame2)
	textlabels.BackgroundTransparency = 1
	textlabels.TextScaled = true
	textlabels.TextStrokeTransparency = 0
	textlabels.Size = UDim2.new(1,0,0.05,0)
	textlabels.Position = UDim2.new(0,0,-0.1,0)
	textlabels.Text = "[HairSus]: Open/close Esp key: ="
	textlabels.TextColor3 = Color3.new(1, 1, 1)
	game.Debris:AddItem(textlabels,3)
end)
game:GetService("StarterGui"):SetCore("ChatMakeSystemMessage",{ --Getting "StarterGui" and calling the function
	Text = "[HairSus]: Open/close select key: ]";
	Color = Color3.new(1, 1, 1);
	FontSize = Enum.FontSize.Size36;
})
spawn(function()
	local textlabels = Instance.new("TextLabel",frame2)
	textlabels.BackgroundTransparency = 1
	textlabels.TextScaled = true
	textlabels.TextStrokeTransparency = 0
	textlabels.Size = UDim2.new(1,0,0.05,0)
	textlabels.Position = UDim2.new(0,0,-0.1,0)
	textlabels.Text = "[HairSus]: Open/close select key: ]"
	textlabels.TextColor3 = Color3.new(1, 1, 1)
	game.Debris:AddItem(textlabels,3)
end)
game:GetService("StarterGui"):SetCore("ChatMakeSystemMessage",{ --Getting "StarterGui" and calling the function
	Text = "[HairSus]: Open/close animbot key: \ | Hold right mouse button for working animbot";
	Color = Color3.new(1, 1, 1);
	FontSize = Enum.FontSize.Size36;
})
spawn(function()
	local textlabels = Instance.new("TextLabel",frame2)
	textlabels.BackgroundTransparency = 1
	textlabels.TextScaled = true
	textlabels.TextStrokeTransparency = 0
	textlabels.Size = UDim2.new(1,0,0.05,0)
	textlabels.Position = UDim2.new(0,0,-0.1,0)
	textlabels.Text = "[HairSus]: Open/close animbot key: \ | Hold right mouse button for working animbot"
	textlabels.TextColor3 = Color3.new(1, 1, 1)
	game.Debris:AddItem(textlabels,3)
end)
game:GetService("StarterGui"):SetCore("ChatMakeSystemMessage",{ --Getting "StarterGui" and calling the function
	Text = "[HairSus]: Open/close animbot part change key: [";
	Color = Color3.new(1, 1, 1);
	FontSize = Enum.FontSize.Size36;
})
spawn(function()
	local textlabels = Instance.new("TextLabel",frame2)
	textlabels.BackgroundTransparency = 1
	textlabels.TextScaled = true
	textlabels.TextStrokeTransparency = 0
	textlabels.Size = UDim2.new(1,0,0.05,0)
	textlabels.Position = UDim2.new(0,0,-0.1,0)
	textlabels.Text = "[HairSus]: Open/close animbot part change key: ["
	textlabels.TextColor3 = Color3.new(1, 1, 1)
	game.Debris:AddItem(textlabels,3)
end)
game:GetService("StarterGui"):SetCore("ChatMakeSystemMessage",{ --Getting "StarterGui" and calling the function
	Text = "[HairSus]: Open/close free for all change key: -";
	Color = Color3.new(1, 1, 1);
	FontSize = Enum.FontSize.Size36;
})
spawn(function()
	local textlabels = Instance.new("TextLabel",frame2)
	textlabels.BackgroundTransparency = 1
	textlabels.TextScaled = true
	textlabels.TextStrokeTransparency = 0
	textlabels.Size = UDim2.new(1,0,0.05,0)
	textlabels.Position = UDim2.new(0,0,-0.1,0)
	textlabels.Text = "[HairSus]: Open/close free for all change key: -"
	textlabels.TextColor3 = Color3.new(1, 1, 1)
	game.Debris:AddItem(textlabels,3)
end)
game:GetService("StarterGui"):SetCore("ChatMakeSystemMessage",{ --Getting "StarterGui" and calling the function
	Text = "[HairSus]: chat /e changedistance {type} {number} | all type = {animbot,select}";
	Color = Color3.new(1, 1, 1);
	FontSize = Enum.FontSize.Size36;
})
spawn(function()
	local textlabels = Instance.new("TextLabel",frame2)
	textlabels.BackgroundTransparency = 1
	textlabels.TextScaled = true
	textlabels.TextStrokeTransparency = 0
	textlabels.Size = UDim2.new(1,0,0.05,0)
	textlabels.Position = UDim2.new(0,0,-0.1,0)
	textlabels.Text = "[HairSus]: chat /e changedistance {type} {number} | all type = {animbot,select}"
	textlabels.TextColor3 = Color3.new(1, 1, 1)
	game.Debris:AddItem(textlabels,3)
end)
game:GetService("StarterGui"):SetCore("ChatMakeSystemMessage",{ --Getting "StarterGui" and calling the function
	Text = "[HairSus]: chat /e help";
	Color = Color3.new(1, 1, 1);
	FontSize = Enum.FontSize.Size36;
})
spawn(function()
	local textlabels = Instance.new("TextLabel",frame2)
	textlabels.BackgroundTransparency = 1
	textlabels.TextScaled = true
	textlabels.TextStrokeTransparency = 0
	textlabels.Size = UDim2.new(1,0,0.05,0)
	textlabels.Position = UDim2.new(0,0,-0.1,0)
	textlabels.Text = "[HairSus]: chat /e help"
	textlabels.TextColor3 = Color3.new(1, 1, 1)
	game.Debris:AddItem(textlabels,3)
end)

game:GetService('RunService').RenderStepped:connect(function()
	if Select then
		local TARGET = GetNearestPlayerToMouse(_G.DISTANCE)
		if (TARGET ~= false) then
			target = TARGET.Character
			frame.Visible = true
			textlabelName.Text = TARGET.Character.Name
		else
			target = nil
			frame.Visible = false
		end
	else
		target = nil
		frame.Visible = false
	end
	if Animbot then
		local TARGET = GetNearestPlayerToMouse(_G.DISTANCEANIMBOT)
		if (TARGET ~= false) then
			local AIM = TARGET.Character:FindFirstChild(_G.AIM_AT)
			if AIM and EnabledAnim then
				CC.CoordinateFrame = CFrame.new(CC.CoordinateFrame.p, AIM.CFrame.p)
			end
		end
	end
end)
--[[
⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄
⠄⠄⠄⠄⠄⠄⠄⣀⣀⣐⡀⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄
⠄⠄⢠⠄⣠⣶⣿⣿⣿⠿⠿⣛⣂⣀⣀⡒⠶⣶⣤⣤⣬⣀⡀⠄⢀⠄⠄⠄⠄⠄⠄⠄
⠄⠄⢀⣾⣿⣿⣿⡟⢡⢾⣿⣿⣿⣿⣿⣿⣶⣌⠻⣿⣿⣿⣿⣷⣦⣄⡀⠄⠄⠄⠄⠄
⠄⠄⣈⣉⡛⣿⣿⣿⡌⢇⢻⣿⣿⣿⣿⣿⠿⠛⣡⣿⣿⣿⣿⣿⣿⣿⣿⣦⣄⠄⠄⠄
⠄⠺⠟⣉⣴⡿⠛⣩⣾⣎⠳⠿⠛⣋⣩⣴⣾⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣆⠄⠄
⠄⠄⠄⠘⢋⣴⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡆⠄
⠄⠄⢀⢀⣾⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡇⠄
⠄⠄⠄⣾⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠃⣀
⠄⠄⠄⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡿⠃⠘⠛
⠄⠄⠄⢻⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠟⠋⣀⣀⣠⣤
⠄⠄⣀⣀⡙⠻⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠿⢛⣩⠤⠾⠄⠛⠋⠉⢉
⠄⠺⠿⠛⠛⠃⠄⠉⠙⠛⠛⠻⠿⠿⠿⠟⠛⠛⠛⠉⠁⠄⠄⣀⣀⣠⣤⣠⣴⣶⣼⣿
]]
