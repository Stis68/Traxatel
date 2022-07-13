local ScreenGui = Instance.new("ScreenGui")
local menu = Instance.new("Frame")
local tag = Instance.new("TextLabel")
local two = Instance.new("TextButton")
local one = Instance.new("TextButton")
local ben = Instance.new("TextLabel")
local fivefive = Instance.new("TextButton")
local fourfour = Instance.new("TextButton")
local thrthr = Instance.new("TextButton")
local twotwo = Instance.new("TextButton")
local oneone = Instance.new("TextButton")
local ffiveee = Instance.new("TextButton")
local fffourr = Instance.new("TextButton")
local thrrree = Instance.new("TextButton")
local twwo = Instance.new("TextButton")
local onne = Instance.new("TextButton")
local who = Instance.new("TextLabel")
local no = Instance.new("TextLabel")
local five = Instance.new("TextButton")
local four = Instance.new("TextButton")
local three = Instance.new("TextButton")
local exit = Instance.new("TextButton")
local six = Instance.new("TextButton")
local seven = Instance.new("TextButton")
local eight = Instance.new("TextButton")
local nine = Instance.new("TextButton")
local ten = Instance.new("TextButton")
local eleven = Instance.new("TextButton")
local sixsix = Instance.new("TextButton")
local sevsev = Instance.new("TextButton")
local eigeig = Instance.new("TextButton")
local nini = Instance.new("TextButton")
local tenten = Instance.new("TextButton")
local elevelev = Instance.new("TextButton")
local sssiiixx = Instance.new("TextButton")
local ssevven = Instance.new("TextButton")
local eiiight = Instance.new("TextButton")
local nnnine = Instance.new("TextButton")
local ttten = Instance.new("TextButton")
local ellleven = Instance.new("TextButton")
local knopka = Instance.new("Frame")
local close = Instance.new("TextButton")
local childnon = Instance.new("TextBox")
local childdop = Instance.new("ScreenGui")

--Properties:

ScreenGui.Parent = game.CoreGui

menu.Name = "menu"
menu.Parent = ScreenGui
menu.BackgroundColor3 = Color3.fromRGB(0, 145, 48)
menu.BorderColor3 = Color3.fromRGB(21, 158, 0)
menu.Position = UDim2.new(0.288643479, 0, 0.105511814, 0)
menu.Size = UDim2.new(0, 604, 0, 501)
menu.Visible = false
menu.Active = true
menu.Draggable = true

tag.Name = "tag"
tag.Parent = menu
tag.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
tag.Size = UDim2.new(0, 604, 0, 24)
tag.Font = Enum.Font.Kalam
tag.Text = "MEGATPAXATELb 9000 V666"
tag.TextColor3 = Color3.fromRGB(255, 0, 4)
tag.TextSize = 36.000

two.Name = "two"
two.Parent = menu
two.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
two.Position = UDim2.new(0.0231788084, 0, 0.195171028, 0)
two.Size = UDim2.new(0, 149, 0, 19)
two.Font = Enum.Font.SourceSans
two.TextColor3 = Color3.fromRGB(0, 0, 0)
two.TextSize = 14.000
two.Text = "XYETA CHTOBI TP(tool)"
two.MouseButton1Down:connect(function()
mouse=game.Players.LocalPlayer:GetMouse()
	tool = Instance.new("Tool")
	tool.RequiresHandle=false;
	tool.Name="TbI lox"
	tool.Activated:connect(function()local z=mouse.Hit+Vector3.new(0,2.5,0)
		z=CFrame.new(z.X,z.Y,z.Z)
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame=z 
	end)
	tool.Parent=game.Players.LocalPlayer.Backpack 
end)


one.Name = "one"
one.Parent = menu
one.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
one.Position = UDim2.new(0.0231788047, 0, 0.130784705, 0)
one.Size = UDim2.new(0, 149, 0, 19)
one.Font = Enum.Font.SourceSans
one.TextColor3 = Color3.fromRGB(0, 0, 0)
one.TextSize = 14.000
one.Text = "Tp k rebenky(T)"
one.MouseButton1Down:connect(function()
	childdop.Parent=game.CoreGui;
	childnon.Parent=childdop;
	childnon.BackgroundColor3=Color3.new(0.333333,0.333333,0.333333)
	childnon.Position=UDim2.new(0,0,1,-25)
	childnon.Size=UDim2.new(0,150,0,25)
	childnon.Font=Enum.Font.SourceSans;
	childnon.Text="ben no"
	childnon.TextColor3=Color3.new(1,1,1)
	childnon.TextScaled=true;
	childnon.TextSize=14;
	childnon.TextWrapped=true;
	game:GetService("UserInputService").InputBegan:connect(function(q)if q.KeyCode==Enum.KeyCode.T then local r=childnon.Text;
			local s=game.Players.LocalPlayer.Character;
			local t=game.Workspace:FindFirstChild(r)s.HumanoidRootPart.CFrame=t.HumanoidRootPart.CFrame*CFrame.new(0,2,0)end 
	end)
end)


ben.Name = "ben"
ben.Parent = menu
ben.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ben.Position = UDim2.new(0.350993395, 0, 0.0638722554, 0)
ben.Size = UDim2.new(0, 163, 0, 24)
ben.Font = Enum.Font.SourceSans
ben.Text = "xz"
ben.TextColor3 = Color3.fromRGB(0, 0, 0)
ben.TextSize = 14.000

fivefive.Name = "fivefive"
fivefive.Parent = menu
fivefive.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
fivefive.Position = UDim2.new(0.362582803, 0, 0.384305835, 0)
fivefive.Size = UDim2.new(0, 149, 0, 19)
fivefive.Font = Enum.Font.SourceSans
fivefive.TextColor3 = Color3.fromRGB(0, 0, 0)
fivefive.TextSize = 14.000
fivefive.Text = "Fullbright"
fivefive.MouseButton1Down:connect(function()
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
end)

fourfour.Name = "fourfour"
fourfour.Parent = menu
fourfour.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
fourfour.Position = UDim2.new(0.362582773, 0, 0.321931601, 0)
fourfour.Size = UDim2.new(0, 149, 0, 19)
fourfour.Font = Enum.Font.SourceSans
fourfour.TextColor3 = Color3.fromRGB(0, 0, 0)
fourfour.TextSize = 14.000
fourfour.Text = "Fonar ebat"
fourfour.MouseButton1Down:connect(function()
         loadstring(game:HttpGetAsync("https://pastebin.com/raw/9BBKhHn4"))()
end)


thrthr.Name = "thrthr"
thrthr.Parent = menu
thrthr.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
thrthr.Position = UDim2.new(0.362582803, 0, 0.257545263, 0)
thrthr.Size = UDim2.new(0, 149, 0, 19)
thrthr.Font = Enum.Font.SourceSans
thrthr.TextColor3 = Color3.fromRGB(0, 0, 0)
thrthr.TextSize = 14.000
thrthr.Text = "Leon mode (E)"
thrthr.MouseButton1Down:connect(function()
	loadstring(game:HttpGetAsync("https://raw.githubusercontent.com/Stis68/Invisise/main/Invise.md"))()
end)



twotwo.Name = "twotwo"
twotwo.Parent = menu
twotwo.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
twotwo.Position = UDim2.new(0.362582803, 0, 0.195171028, 0)
twotwo.Size = UDim2.new(0, 149, 0, 19)
twotwo.Font = Enum.Font.SourceSans
twotwo.TextColor3 = Color3.fromRGB(0, 0, 0)
twotwo.TextSize = 14.000
twotwo.Text = "Otkidivalshik (Z/X)"
twotwo.MouseButton1Down:connect(function()
	loadstring(game:HttpGetAsync("https://raw.githubusercontent.com/PhoenixAceVFX/Roblox-Scripts/master/FE%20INVISIBLE%20AND%20FLING.lua"))()
end)

oneone.Name = "oneone"
oneone.Parent = menu
oneone.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
oneone.Position = UDim2.new(0.362582803, 0, 0.130784705, 0)
oneone.Size = UDim2.new(0, 149, 0, 19)
oneone.Font = Enum.Font.SourceSans
oneone.TextColor3 = Color3.fromRGB(0, 0, 0)
oneone.TextSize = 14.000
oneone.Text = "Aimbot"
oneone.MouseButton1Down:connect(function()
	loadstring(game:GetObjects('rbxassetid://340856112')[1].Source)()

	wait()

	_G.FREE_FOR_ALL = true

	_G.BIND = 50 -- LEFT CTRL
	_G.ESP_BIND = 52 -- LEFT ALT
end)

ffiveee.Name = "ffiveee"
ffiveee.Parent = menu
ffiveee.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ffiveee.Position = UDim2.new(0.730132461, 0, 0.384305835, 0)
ffiveee.Size = UDim2.new(0, 149, 0, 19)
ffiveee.Font = Enum.Font.SourceSans
ffiveee.Text = "MEGA-ELDAK (+1000)"
ffiveee.TextColor3 = Color3.fromRGB(0, 0, 0)
ffiveee.TextSize = 14.000
ffiveee.MouseButton1Down:connect(function()
	local made = false
	local defSpeed = 16
	game:getService("RunService"):BindToRenderStep("SpeedHack",0,
	function()
		if not game.Players.LocalPlayer.Character or not game.Players.LocalPlayer.Character:findFirstChildOfClass("Humanoid") then
			return
		end
		if not made then defSpeed = game.Players.LocalPlayer.Character:findFirstChildOfClass("Humanoid").WalkSpeed;made=true end
		if game:getService("UserInputService"):IsKeyDown(Enum.KeyCode.W) then
			game.Players.LocalPlayer.Character:findFirstChildOfClass("Humanoid").WalkSpeed = 1000
		else
			game.Players.LocalPlayer.Character:findFirstChildOfClass("Humanoid").WalkSpeed = defSpeed
		end
	end
	)
end)

fffourr.Name = "fffourr"
fffourr.Parent = menu
fffourr.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
fffourr.Position = UDim2.new(0.730132461, 0, 0.321931601, 0)
fffourr.Size = UDim2.new(0, 149, 0, 19)
fffourr.Font = Enum.Font.SourceSans
fffourr.Text = "XYI T-REXA (+450)"
fffourr.TextColor3 = Color3.fromRGB(0, 0, 0)
fffourr.TextSize = 14.000
fffourr.MouseButton1Down:connect(function()
local made = false
local defSpeed = 16
game:getService("RunService"):BindToRenderStep("SpeedHack",0,
function()
	if not game.Players.LocalPlayer.Character or not game.Players.LocalPlayer.Character:findFirstChildOfClass("Humanoid") then
		return
	end
	if not made then defSpeed = game.Players.LocalPlayer.Character:findFirstChildOfClass("Humanoid").WalkSpeed;made=true end
	if game:getService("UserInputService"):IsKeyDown(Enum.KeyCode.W) then
		game.Players.LocalPlayer.Character:findFirstChildOfClass("Humanoid").WalkSpeed = 450
	else
		game.Players.LocalPlayer.Character:findFirstChildOfClass("Humanoid").WalkSpeed = defSpeed
		end
	end
	)
end)

thrrree.Name = "thrrree"
thrrree.Parent = menu
thrrree.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
thrrree.Position = UDim2.new(0.730132461, 0, 0.257545263, 0)
thrrree.Size = UDim2.new(0, 149, 0, 19)
thrrree.Font = Enum.Font.SourceSans
thrrree.Text = "Xyi flesha (+150)"
thrrree.TextColor3 = Color3.fromRGB(0, 0, 0)
thrrree.TextSize = 14.000
thrrree.MouseButton1Down:connect(function()
	local made = false
	local defSpeed = 16
	game:getService("RunService"):BindToRenderStep("SpeedHack",0,
	function()
		if not game.Players.LocalPlayer.Character or not game.Players.LocalPlayer.Character:findFirstChildOfClass("Humanoid") then
			return
		end
		if not made then defSpeed = game.Players.LocalPlayer.Character:findFirstChildOfClass("Humanoid").WalkSpeed;made=true end
		if game:getService("UserInputService"):IsKeyDown(Enum.KeyCode.W) then
			game.Players.LocalPlayer.Character:findFirstChildOfClass("Humanoid").WalkSpeed = 150
		else
			game.Players.LocalPlayer.Character:findFirstChildOfClass("Humanoid").WalkSpeed = defSpeed
		end
	end
	)
end)

twwo.Name = "twwo"
twwo.Parent = menu
twwo.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
twwo.Position = UDim2.new(0.730132461, 0, 0.195171028, 0)
twwo.Size = UDim2.new(0, 149, 0, 19)
twwo.Font = Enum.Font.SourceSans
twwo.Text = "Bolshoi xyi (+75)"
twwo.TextColor3 = Color3.fromRGB(0, 0, 0)
twwo.TextSize = 14.000
twwo.MouseButton1Down:connect(function()
	local made = false
	local defSpeed = 16
	game:getService("RunService"):BindToRenderStep("SpeedHack",0,
	function()
		if not game.Players.LocalPlayer.Character or not game.Players.LocalPlayer.Character:findFirstChildOfClass("Humanoid") then
			return
		end
		if not made then defSpeed = game.Players.LocalPlayer.Character:findFirstChildOfClass("Humanoid").WalkSpeed;made=true end
		if game:getService("UserInputService"):IsKeyDown(Enum.KeyCode.W) then
			game.Players.LocalPlayer.Character:findFirstChildOfClass("Humanoid").WalkSpeed = 75
		else
			game.Players.LocalPlayer.Character:findFirstChildOfClass("Humanoid").WalkSpeed = defSpeed
		end
	end
	)
end)

onne.Name = "onne"
onne.Parent = menu
onne.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
onne.Position = UDim2.new(0.730132461, 0, 0.130784705, 0)
onne.Size = UDim2.new(0, 149, 0, 19)
onne.Font = Enum.Font.SourceSans
onne.Text = "Norm xyi (16)"
onne.TextColor3 = Color3.fromRGB(0, 0, 0)
onne.TextSize = 14.000
onne.MouseButton1Down:connect(function()
	local made = false
	local defSpeed = 16
	game:getService("RunService"):BindToRenderStep("SpeedHack",0,
	function()
		if not game.Players.LocalPlayer.Character or not game.Players.LocalPlayer.Character:findFirstChildOfClass("Humanoid") then
			return
		end
		if not made then defSpeed = game.Players.LocalPlayer.Character:findFirstChildOfClass("Humanoid").WalkSpeed;made=true end
		if game:getService("UserInputService"):IsKeyDown(Enum.KeyCode.W) then
			game.Players.LocalPlayer.Character:findFirstChildOfClass("Humanoid").WalkSpeed = 16
		else
			game.Players.LocalPlayer.Character:findFirstChildOfClass("Humanoid").WalkSpeed = defSpeed
		end
	end
	)
end)

who.Name = "who"
who.Parent = menu
who.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
who.Position = UDim2.new(0.0115894042, 0, 0.0638722554, 0)
who.Size = UDim2.new(0, 163, 0, 24)
who.Font = Enum.Font.SourceSans
who.Text = "choto"
who.TextColor3 = Color3.fromRGB(0, 0, 0)
who.TextSize = 14.000

no.Name = "no"
no.Parent = menu
no.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
no.Position = UDim2.new(0.718543053, 0, 0.0638722554, 0)
no.Size = UDim2.new(0, 163, 0, 24)
no.Font = Enum.Font.SourceSans
no.Text = "chtoto"
no.TextColor3 = Color3.fromRGB(0, 0, 0)
no.TextSize = 14.000

five.Name = "five"
five.Parent = menu
five.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
five.Position = UDim2.new(0.0231788103, 0, 0.384305835, 0)
five.Size = UDim2.new(0, 149, 0, 19)
five.Font = Enum.Font.SourceSans
five.TextColor3 = Color3.fromRGB(0, 0, 0)
five.TextSize = 14.000
five.Text = "Sapogi Mario"
five.MouseButton1Down:connect(function()
local v=true;
game:GetService("UserInputService").JumpRequest:connect(function()
if v then game:GetService"Players".LocalPlayer.Character:
FindFirstChildOfClass'Humanoid':
ChangeState("Jumping")end 
end)
local w=CreateButton("Infinite Jump: Off",StuffFrame)
w.Position=UDim2.new(0,10,0,130)
w.Size=UDim2.new(0,150,0,30)
w.MouseButton1Click:connect(function()
local x=w.Text:sub(string.len("Infinite Jump: ")+1)
local y=x=="Off"and"On"or x=="On"and"Off"v=y=="On"
w.Text="Infinite Jump: "..y end)
end)

four.Name = "four"
four.Parent = menu
four.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
four.Position = UDim2.new(0.0231788084, 0, 0.321931601, 0)
four.Size = UDim2.new(0, 149, 0, 19)
four.Font = Enum.Font.SourceSans
four.TextColor3 = Color3.fromRGB(0, 0, 0)
four.TextSize = 14.000
four.Text = "BTOOLS"
four.MouseButton1Down:connect(function()
	local grab = Instance.new("HopperBin", game.Players.LocalPlayer.Backpack)
	grab.BinType = 2
	local clone = Instance.new("HopperBin", game.Players.LocalPlayer.Backpack)
	clone.BinType = 3
	hammer = Instance.new("HopperBin", game.Players.LocalPlayer.Backpack)
	hammer.BinType = 4
end)

three.Name = "three"
three.Parent = menu
three.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
three.Position = UDim2.new(0.0231788084, 0, 0.257545263, 0)
three.Size = UDim2.new(0, 149, 0, 19)
three.Font = Enum.Font.SourceSans
three.TextColor3 = Color3.fromRGB(0, 0, 0)
three.TextSize = 14.000
three.Text = "RAZ'EBOSHIVATEL'(CAPS)"
three.MouseButton1Down:connect(function()
	local A=game:GetService("Players").LocalPlayer;
	local B=A:GetMouse()
	B.Button1Down:connect(function()
		if not game:GetService("UserInputService"):IsKeyDown(Enum.KeyCode.CapsLock)then return end;
		if not B.Target then return end;
		B.Target:Destroy()end)
end)


exit.Name = "exit"
exit.Parent = menu
exit.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
exit.Position = UDim2.new(0.956953645, 0, 0, 0)
exit.Size = UDim2.new(0, 26, 0, 24)
exit.Font = Enum.Font.SourceSans
exit.Text = "X"
exit.TextColor3 = Color3.fromRGB(0, 0, 0)
exit.TextSize = 14.000
exit.MouseButton1Down:connect(function()
	menu.Visible = false
	knopka.Visible = true
end)

six.Name = "six"
six.Parent = menu
six.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
six.Position = UDim2.new(0.0231788084, 0, 0.444667995, 0)
six.Size = UDim2.new(0, 149, 0, 19)
six.Font = Enum.Font.SourceSans
six.TextColor3 = Color3.fromRGB(0, 0, 0)
six.TextSize = 14.000

seven.Name = "seven"
seven.Parent = menu
seven.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
seven.Position = UDim2.new(0.0231788047, 0, 0.503018081, 0)
seven.Size = UDim2.new(0, 149, 0, 19)
seven.Font = Enum.Font.SourceSans
seven.TextColor3 = Color3.fromRGB(0, 0, 0)
seven.TextSize = 14.000

eight.Name = "eight"
eight.Parent = menu
eight.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
eight.Position = UDim2.new(0.0231788084, 0, 0.567404389, 0)
eight.Size = UDim2.new(0, 149, 0, 19)
eight.Font = Enum.Font.SourceSans
eight.TextColor3 = Color3.fromRGB(0, 0, 0)
eight.TextSize = 14.000

nine.Name = "nine"
nine.Parent = menu
nine.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
nine.Position = UDim2.new(0.0231788084, 0, 0.629778624, 0)
nine.Size = UDim2.new(0, 149, 0, 19)
nine.Font = Enum.Font.SourceSans
nine.TextColor3 = Color3.fromRGB(0, 0, 0)
nine.TextSize = 14.000

ten.Name = "ten"
ten.Parent = menu
ten.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ten.Position = UDim2.new(0.0231788084, 0, 0.694164991, 0)
ten.Size = UDim2.new(0, 149, 0, 19)
ten.Font = Enum.Font.SourceSans
ten.TextColor3 = Color3.fromRGB(0, 0, 0)
ten.TextSize = 14.000

eleven.Name = "eleven"
eleven.Parent = menu
eleven.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
eleven.Position = UDim2.new(0.0231788103, 0, 0.756539226, 0)
eleven.Size = UDim2.new(0, 149, 0, 19)
eleven.Font = Enum.Font.SourceSans
eleven.TextColor3 = Color3.fromRGB(0, 0, 0)
eleven.TextSize = 14.000

sixsix.Name = "sixsix"
sixsix.Parent = menu
sixsix.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
sixsix.Position = UDim2.new(0.362582803, 0, 0.444667995, 0)
sixsix.Size = UDim2.new(0, 149, 0, 19)
sixsix.Font = Enum.Font.SourceSans
sixsix.TextColor3 = Color3.fromRGB(0, 0, 0)
sixsix.TextSize = 14.000

sevsev.Name = "sevsev"
sevsev.Parent = menu
sevsev.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
sevsev.Position = UDim2.new(0.362582803, 0, 0.503018081, 0)
sevsev.Size = UDim2.new(0, 149, 0, 19)
sevsev.Font = Enum.Font.SourceSans
sevsev.TextColor3 = Color3.fromRGB(0, 0, 0)
sevsev.TextSize = 14.000

eigeig.Name = "eigeig"
eigeig.Parent = menu
eigeig.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
eigeig.Position = UDim2.new(0.362582803, 0, 0.567404389, 0)
eigeig.Size = UDim2.new(0, 149, 0, 19)
eigeig.Font = Enum.Font.SourceSans
eigeig.TextColor3 = Color3.fromRGB(0, 0, 0)
eigeig.TextSize = 14.000

nini.Name = "nini"
nini.Parent = menu
nini.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
nini.Position = UDim2.new(0.362582803, 0, 0.629778624, 0)
nini.Size = UDim2.new(0, 149, 0, 19)
nini.Font = Enum.Font.SourceSans
nini.TextColor3 = Color3.fromRGB(0, 0, 0)
nini.TextSize = 14.000

tenten.Name = "tenten"
tenten.Parent = menu
tenten.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
tenten.Position = UDim2.new(0.362582803, 0, 0.694164991, 0)
tenten.Size = UDim2.new(0, 149, 0, 19)
tenten.Font = Enum.Font.SourceSans
tenten.TextColor3 = Color3.fromRGB(0, 0, 0)
tenten.TextSize = 14.000

elevelev.Name = "elevelev"
elevelev.Parent = menu
elevelev.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
elevelev.Position = UDim2.new(0.362582803, 0, 0.756539226, 0)
elevelev.Size = UDim2.new(0, 149, 0, 19)
elevelev.Font = Enum.Font.SourceSans
elevelev.TextColor3 = Color3.fromRGB(0, 0, 0)
elevelev.TextSize = 14.000

sssiiixx.Name = "sssiiixx"
sssiiixx.Parent = menu
sssiiixx.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
sssiiixx.Position = UDim2.new(0.730132461, 0, 0.444667995, 0)
sssiiixx.Size = UDim2.new(0, 149, 0, 19)
sssiiixx.Font = Enum.Font.SourceSans
sssiiixx.TextColor3 = Color3.fromRGB(0, 0, 0)
sssiiixx.TextSize = 14.000
sssiiixx.MouseButton1Down:connect(function()
	local v=true;
	game:GetService("UserInputService").JumpRequest:connect(function()
		if v then game:GetService"Players".LocalPlayer.Character:
			FindFirstChildOfClass'Humanoid':
			ChangeState("Jumping")end 
	end)
	local w=CreateButton("Infinite Jump: Off",StuffFrame)
	w.Position=UDim2.new(0,10,0,130)
	w.Size=UDim2.new(0,150,0,30)
	w.MouseButton1Click:connect(function()
		local x=w.Text:sub(string.len("Infinite Jump: ")+1)
		local y=x=="Off"and"On"or x=="On"and"Off"v=y=="On"
		w.Text="Infinite Jump: "..y end)
end)

ssevven.Name = "ssevven"
ssevven.Parent = menu
ssevven.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ssevven.Position = UDim2.new(0.730132461, 0, 0.503018081, 0)
ssevven.Size = UDim2.new(0, 149, 0, 19)
ssevven.Font = Enum.Font.SourceSans
ssevven.TextColor3 = Color3.fromRGB(0, 0, 0)
ssevven.TextSize = 14.000

eiiight.Name = "eiiight"
eiiight.Parent = menu
eiiight.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
eiiight.Position = UDim2.new(0.730132461, 0, 0.567404389, 0)
eiiight.Size = UDim2.new(0, 149, 0, 19)
eiiight.Font = Enum.Font.SourceSans
eiiight.TextColor3 = Color3.fromRGB(0, 0, 0)
eiiight.TextSize = 14.000

nnnine.Name = "nnnine"
nnnine.Parent = menu
nnnine.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
nnnine.Position = UDim2.new(0.730132461, 0, 0.629778624, 0)
nnnine.Size = UDim2.new(0, 149, 0, 19)
nnnine.Font = Enum.Font.SourceSans
nnnine.TextColor3 = Color3.fromRGB(0, 0, 0)
nnnine.TextSize = 14.000

ttten.Name = "ttten"
ttten.Parent = menu
ttten.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ttten.Position = UDim2.new(0.730132461, 0, 0.694164991, 0)
ttten.Size = UDim2.new(0, 149, 0, 19)
ttten.Font = Enum.Font.SourceSans
ttten.TextColor3 = Color3.fromRGB(0, 0, 0)
ttten.TextSize = 14.000

ellleven.Name = "ellleven"
ellleven.Parent = menu
ellleven.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ellleven.Position = UDim2.new(0.730132461, 0, 0.756539226, 0)
ellleven.Size = UDim2.new(0, 149, 0, 19)
ellleven.Font = Enum.Font.SourceSans
ellleven.TextColor3 = Color3.fromRGB(0, 0, 0)
ellleven.TextSize = 14.000

knopka.Name = "knopka"
knopka.Parent = ScreenGui
knopka.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
knopka.Position = UDim2.new(0.0346462093, 0, 0.732283473, 0)
knopka.Size = UDim2.new(0, 61, 0, 111)

close.Name = "close"
close.Parent = knopka
close.BackgroundColor3 = Color3.fromRGB(2, 168, 0)
close.Position = UDim2.new(0.180327863, 0, 0.297297299, 0)
close.Size = UDim2.new(0, 38, 0, 44)
close.Font = Enum.Font.SourceSansBold
close.Text = "xyi"
close.TextColor3 = Color3.fromRGB(255, 0, 0)
close.TextSize = 14.000
close.MouseButton1Down:connect(function()
	knopka.Visible = false
	menu.Visible = true
end)
