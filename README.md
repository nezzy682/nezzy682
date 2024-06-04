-- Gui to Lua
-- Version: 3.2

-- Instances:

local EmoteWheelUI = Instance.new("ScreenGui")
local EmoteBG = Instance.new("ImageLabel")
local WaveButton = Instance.new("ImageButton")
local WaveName = Instance.new("TextLabel")
local WaveDescription = Instance.new("TextLabel")
local LaughButton = Instance.new("ImageButton")
local LaughName = Instance.new("TextLabel")
local LaughDescription = Instance.new("TextLabel")
local ClapButton = Instance.new("ImageButton")
local ClapName = Instance.new("TextLabel")
local ClapDescription = Instance.new("TextLabel")
local ThreatButton = Instance.new("ImageButton")
local ThreatName = Instance.new("TextLabel")
local ThreatDescription = Instance.new("TextLabel")
local TextLabel = Instance.new("TextLabel")
local TextLabel_2 = Instance.new("TextLabel")
local EMOTES = Instance.new("TextButton")
local TextLabel_3 = Instance.new("TextLabel")
local IYIELD = Instance.new("TextButton")

--Properties:

EmoteWheelUI.Name = "EmoteWheelUI"
EmoteWheelUI.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
EmoteWheelUI.Enabled = false
EmoteWheelUI.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

EmoteBG.Name = "EmoteBG"
EmoteBG.Parent = EmoteWheelUI
EmoteBG.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
EmoteBG.BackgroundTransparency = 1.000
EmoteBG.Position = UDim2.new(0.261584669, 0, 0.166306496, 0)
EmoteBG.Size = UDim2.new(0.475901484, 0, 0.665595293, 0)
EmoteBG.Image = "rbxassetid://17731767043"
EmoteBG.ImageTransparency = 0.500

WaveButton.Name = "WaveButton"
WaveButton.Parent = EmoteBG
WaveButton.AnchorPoint = Vector2.new(0.5, 0.5)
WaveButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
WaveButton.BackgroundTransparency = 1.000
WaveButton.Position = UDim2.new(0.163429826, 0, 0.116736397, 0)
WaveButton.Size = UDim2.new(0.109999999, 0, 0.0970000029, 0)
WaveButton.Visible = false
WaveButton.Image = "http://www.roblox.com/asset/?id=10004979656"
WaveButton.ImageTransparency = 0.500

WaveName.Name = "WaveName"
WaveName.Parent = WaveButton
WaveName.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
WaveName.BackgroundTransparency = 1.000
WaveName.Position = UDim2.new(0.111500934, 0, 0.997192144, 0)
WaveName.Size = UDim2.new(0.816666663, 0, 0.166666672, 0)
WaveName.Font = Enum.Font.JosefinSans
WaveName.Text = "Wave"
WaveName.TextColor3 = Color3.fromRGB(255, 255, 255)
WaveName.TextScaled = true
WaveName.TextSize = 14.000
WaveName.TextTransparency = 0.500
WaveName.TextWrapped = true

WaveDescription.Name = "WaveDescription"
WaveDescription.Parent = WaveButton
WaveDescription.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
WaveDescription.BackgroundTransparency = 1.000
WaveDescription.Position = UDim2.new(0.0916666687, 0, 1.16385877, 0)
WaveDescription.Size = UDim2.new(0.816666663, 0, 0.166666672, 0)
WaveDescription.Font = Enum.Font.JosefinSans
WaveDescription.Text = "Greet other players."
WaveDescription.TextColor3 = Color3.fromRGB(255, 255, 255)
WaveDescription.TextScaled = true
WaveDescription.TextSize = 14.000
WaveDescription.TextTransparency = 0.500
WaveDescription.TextWrapped = true

LaughButton.Name = "LaughButton"
LaughButton.Parent = EmoteBG
LaughButton.AnchorPoint = Vector2.new(0.5, 0.5)
LaughButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
LaughButton.BackgroundTransparency = 1.000
LaughButton.Position = UDim2.new(0.346260786, 0, 0.117777579, 0)
LaughButton.Size = UDim2.new(0.109999999, 0, 0.0970000029, 0)
LaughButton.Visible = false
LaughButton.Image = "http://www.roblox.com/asset/?id=10005511606"
LaughButton.ImageTransparency = 0.500

LaughName.Name = "LaughName"
LaughName.Parent = LaughButton
LaughName.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
LaughName.BackgroundTransparency = 1.000
LaughName.Position = UDim2.new(0.111500934, 0, 0.997192144, 0)
LaughName.Size = UDim2.new(0.816666663, 0, 0.166666672, 0)
LaughName.Font = Enum.Font.JosefinSans
LaughName.Text = "Laugh"
LaughName.TextColor3 = Color3.fromRGB(255, 255, 255)
LaughName.TextScaled = true
LaughName.TextSize = 14.000
LaughName.TextTransparency = 0.500
LaughName.TextWrapped = true

LaughDescription.Name = "LaughDescription"
LaughDescription.Parent = LaughButton
LaughDescription.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
LaughDescription.BackgroundTransparency = 1.000
LaughDescription.Position = UDim2.new(0.0916666687, 0, 1.16385877, 0)
LaughDescription.Size = UDim2.new(0.816666663, 0, 0.166666672, 0)
LaughDescription.Font = Enum.Font.JosefinSans
LaughDescription.Text = "Laugh at your enemies."
LaughDescription.TextColor3 = Color3.fromRGB(255, 255, 255)
LaughDescription.TextScaled = true
LaughDescription.TextSize = 14.000
LaughDescription.TextTransparency = 0.500
LaughDescription.TextWrapped = true

ClapButton.Name = "ClapButton"
ClapButton.Parent = EmoteBG
ClapButton.AnchorPoint = Vector2.new(0.5, 0.5)
ClapButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ClapButton.BackgroundTransparency = 1.000
ClapButton.Position = UDim2.new(0.065338403, 0, 0.13195543, 0)
ClapButton.Size = UDim2.new(0.110450827, 0, 0.0974868834, 0)
ClapButton.Visible = false
ClapButton.Image = "http://www.roblox.com/asset/?id=10005559805"
ClapButton.ImageTransparency = 0.500

ClapName.Name = "ClapName"
ClapName.Parent = ClapButton
ClapName.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ClapName.BackgroundTransparency = 1.000
ClapName.Position = UDim2.new(0.111500934, 0, 0.997192144, 0)
ClapName.Size = UDim2.new(0.816666663, 0, 0.166666672, 0)
ClapName.Font = Enum.Font.JosefinSans
ClapName.Text = "Clap"
ClapName.TextColor3 = Color3.fromRGB(255, 255, 255)
ClapName.TextScaled = true
ClapName.TextSize = 14.000
ClapName.TextTransparency = 0.500
ClapName.TextWrapped = true

ClapDescription.Name = "ClapDescription"
ClapDescription.Parent = ClapButton
ClapDescription.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ClapDescription.BackgroundTransparency = 1.000
ClapDescription.Position = UDim2.new(0.0916666687, 0, 1.16385877, 0)
ClapDescription.Size = UDim2.new(0.816666663, 0, 0.166666672, 0)
ClapDescription.Font = Enum.Font.JosefinSans
ClapDescription.Text = "Clap for your friends. Or enemies."
ClapDescription.TextColor3 = Color3.fromRGB(255, 255, 255)
ClapDescription.TextScaled = true
ClapDescription.TextSize = 14.000
ClapDescription.TextTransparency = 0.500
ClapDescription.TextWrapped = true

ThreatButton.Name = "ThreatButton"
ThreatButton.Parent = EmoteBG
ThreatButton.AnchorPoint = Vector2.new(0.5, 0.5)
ThreatButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ThreatButton.BackgroundTransparency = 1.000
ThreatButton.Position = UDim2.new(0.262441516, 0, 0.116908722, 0)
ThreatButton.Size = UDim2.new(0.109999999, 0, 0.0970000029, 0)
ThreatButton.Visible = false
ThreatButton.Image = "http://www.roblox.com/asset/?id=10005631373"
ThreatButton.ImageTransparency = 0.500

ThreatName.Name = "ThreatName"
ThreatName.Parent = ThreatButton
ThreatName.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ThreatName.BackgroundTransparency = 1.000
ThreatName.Position = UDim2.new(0.111500934, 0, 0.997192144, 0)
ThreatName.Size = UDim2.new(0.816666663, 0, 0.166666672, 0)
ThreatName.Font = Enum.Font.JosefinSans
ThreatName.Text = "Threat"
ThreatName.TextColor3 = Color3.fromRGB(255, 255, 255)
ThreatName.TextScaled = true
ThreatName.TextSize = 14.000
ThreatName.TextTransparency = 0.500
ThreatName.TextWrapped = true

ThreatDescription.Name = "ThreatDescription"
ThreatDescription.Parent = ThreatButton
ThreatDescription.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ThreatDescription.BackgroundTransparency = 1.000
ThreatDescription.Position = UDim2.new(0.0916666687, 0, 1.16385877, 0)
ThreatDescription.Size = UDim2.new(0.816666663, 0, 0.166666672, 0)
ThreatDescription.Font = Enum.Font.JosefinSans
ThreatDescription.Text = "Threaten your enemies."
ThreatDescription.TextColor3 = Color3.fromRGB(255, 255, 255)
ThreatDescription.TextScaled = true
ThreatDescription.TextSize = 14.000
ThreatDescription.TextTransparency = 0.500
ThreatDescription.TextWrapped = true

TextLabel.Parent = EmoteBG
TextLabel.BackgroundColor3 = Color3.fromRGB(0, 0, 255)
TextLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.BorderSizePixel = 0
TextLabel.Position = UDim2.new(0.173309341, 0, 1.49251473e-08, 0)
TextLabel.Size = UDim2.new(0.585385561, 0, 0.059593156, 0)
TextLabel.Font = Enum.Font.Unknown
TextLabel.Text = "FOA: FAMILY OVER ANYTHING"
TextLabel.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.TextSize = 26.000

TextLabel_2.Parent = EmoteBG
TextLabel_2.BackgroundColor3 = Color3.fromRGB(0, 0, 255)
TextLabel_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_2.BorderSizePixel = 0
TextLabel_2.Position = UDim2.new(0.00109555537, 0, 0.232317805, 0)
TextLabel_2.Size = UDim2.new(0, 116, 0, 46)
TextLabel_2.Font = Enum.Font.Unknown
TextLabel_2.Text = "EMOTES"
TextLabel_2.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_2.TextSize = 17.000

EMOTES.Name = "EMOTES"
EMOTES.Parent = TextLabel_2
EMOTES.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
EMOTES.BackgroundTransparency = 0.800
EMOTES.BorderColor3 = Color3.fromRGB(0, 0, 0)
EMOTES.BorderSizePixel = 0
EMOTES.Position = UDim2.new(-0.00404831441, 0, 1, 0)
EMOTES.Size = UDim2.new(0, 116, 0, 46)
EMOTES.Font = Enum.Font.Unknown
EMOTES.Text = "ACTIVATE"
EMOTES.TextColor3 = Color3.fromRGB(0, 0, 0)
EMOTES.TextSize = 15.000
EMOTES.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://pastebin.com/raw/eCpipCTH"))()
end)

TextLabel_3.Parent = EmoteBG
TextLabel_3.BackgroundColor3 = Color3.fromRGB(0, 0, 255)
TextLabel_3.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_3.BorderSizePixel = 0
TextLabel_3.Position = UDim2.new(0.851682901, 0, 0.23231779, 0)
TextLabel_3.Size = UDim2.new(0, 90, 0, 46)
TextLabel_3.Font = Enum.Font.Unknown
TextLabel_3.Text = "I-YIELD"
TextLabel_3.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_3.TextSize = 19.000

IYIELD.Name = "IYIELD"
IYIELD.Parent = TextLabel_3
IYIELD.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
IYIELD.BackgroundTransparency = 0.800
IYIELD.BorderColor3 = Color3.fromRGB(0, 0, 0)
IYIELD.BorderSizePixel = 0
IYIELD.Position = UDim2.new(-0.00404595258, 0, 1, 0)
IYIELD.Size = UDim2.new(0, 90, 0, 46)
IYIELD.Font = Enum.Font.Unknown
IYIELD.Text = "ACTIVATE"
IYIELD.TextColor3 = Color3.fromRGB(0, 0, 0)
IYIELD.TextSize = 12.000
IYIELD.MouseButton1Down:connect(function()
	loadstring(game:HttpGet(('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'),true))()
end)

-- Scripts:

local function KNAV_fake_script() -- EmoteWheelUI.EmoteUIHandler 
	local script = Instance.new('LocalScript', EmoteWheelUI)

	local gui = script.Parent
	local uis = game:GetService("UserInputService")
	
	uis.InputBegan:Connect(function(input)
		if input.KeyCode == Enum.KeyCode.Z then
			gui.Enabled = not gui.Enabled
		end	
	end)
end
coroutine.wrap(KNAV_fake_script)()
local function DWMWBH_fake_script() -- WaveButton.EmoteButtonScript 
	local script = Instance.new('LocalScript', WaveButton)

	local tweenService = game:GetService("TweenService")
	local tweenInfo = TweenInfo.new(0.3, Enum.EasingStyle.Quad)
	local gui = script.Parent.Parent.Parent
	local wavebutton = script.Parent
	local wavename = script.Parent.WaveName
	local wavedesc = script.Parent.WaveDescription
	local Player = game.Players.LocalPlayer
	local char = Player.Character or Player.CharacterAdded:Wait()
	
	wavebutton.MouseEnter:Connect(function()
		tweenService:Create(wavebutton, tweenInfo, {ImageTransparency = 0}):Play()
		tweenService:Create(wavename, tweenInfo, {TextTransparency = 0}):Play()
		tweenService:Create(wavedesc, tweenInfo, {TextTransparency = 0}):Play()
	end)
	
	wavebutton.MouseLeave:Connect(function()
		tweenService:Create(wavebutton, tweenInfo, {ImageTransparency = 0.5}):Play()
		tweenService:Create(wavename, tweenInfo, {TextTransparency = 0.5}):Play()
		tweenService:Create(wavedesc, tweenInfo, {TextTransparency = 0.5}):Play()
	end)
	
	wavebutton.MouseButton1Click:Connect(function()
		gui.Enabled = false
		local humanoid = char:WaitForChild("Humanoid")
		local animator = humanoid:FindFirstChildOfClass("Animator")
		local anim = Instance.new("Animation")
		anim.AnimationId = "rbxassetid://17731973124" -- YOUR ID HERE
		local track = animator:LoadAnimation(anim)
		track.Looped = false
		track:Play()
		tweenService:Create(wavebutton, tweenInfo, {ImageTransparency = 0.5}):Play()
		tweenService:Create(wavename, tweenInfo, {TextTransparency = 0.5}):Play()
		tweenService:Create(wavedesc, tweenInfo, {TextTransparency = 0.5}):Play()
	end)
end
coroutine.wrap(DWMWBH_fake_script)()
local function JIPCZA_fake_script() -- LaughButton.EmoteButtonScript 
	local script = Instance.new('LocalScript', LaughButton)

	local tweenService = game:GetService("TweenService")
	local tweenInfo = TweenInfo.new(0.3, Enum.EasingStyle.Quad)
	local gui = script.Parent.Parent.Parent
	local wavebutton = script.Parent
	local wavename = script.Parent.LaughName
	local wavedesc = script.Parent.LaughDescription
	local Player = game.Players.LocalPlayer
	local char = Player.Character or Player.CharacterAdded:Wait()
	
	wavebutton.MouseEnter:Connect(function()
		tweenService:Create(wavebutton, tweenInfo, {ImageTransparency = 0}):Play()
		tweenService:Create(wavename, tweenInfo, {TextTransparency = 0}):Play()
		tweenService:Create(wavedesc, tweenInfo, {TextTransparency = 0}):Play()
	end)
	
	wavebutton.MouseLeave:Connect(function()
		tweenService:Create(wavebutton, tweenInfo, {ImageTransparency = 0.5}):Play()
		tweenService:Create(wavename, tweenInfo, {TextTransparency = 0.5}):Play()
		tweenService:Create(wavedesc, tweenInfo, {TextTransparency = 0.5}):Play()
	end)
	
	wavebutton.MouseButton1Click:Connect(function()
		gui.Enabled = false
		local humanoid = char:WaitForChild("Humanoid")
		local animator = humanoid:FindFirstChildOfClass("Animator")
		local anim = Instance.new("Animation")
		anim.AnimationId = "rbxassetid://17731964594" -- YOUR ID HERE
		local track = animator:LoadAnimation(anim)
		track.Looped = false
		track:Play()
		tweenService:Create(wavebutton, tweenInfo, {ImageTransparency = 0.5}):Play()
		tweenService:Create(wavename, tweenInfo, {TextTransparency = 0.5}):Play()
		tweenService:Create(wavedesc, tweenInfo, {TextTransparency = 0.5}):Play()
	end)
end
coroutine.wrap(JIPCZA_fake_script)()
local function JLJZ_fake_script() -- ClapButton.EmoteButtonScript 
	local script = Instance.new('LocalScript', ClapButton)

	local tweenService = game:GetService("TweenService")
	local tweenInfo = TweenInfo.new(0.3, Enum.EasingStyle.Quad)
	local gui = script.Parent.Parent.Parent
	local wavebutton = script.Parent
	local wavename = script.Parent.ClapName
	local wavedesc = script.Parent.ClapDescription
	local Player = game.Players.LocalPlayer
	local char = Player.Character or Player.CharacterAdded:Wait()
	
	wavebutton.MouseEnter:Connect(function()
		tweenService:Create(wavebutton, tweenInfo, {ImageTransparency = 0}):Play()
		tweenService:Create(wavename, tweenInfo, {TextTransparency = 0}):Play()
		tweenService:Create(wavedesc, tweenInfo, {TextTransparency = 0}):Play()
	end)
	
	wavebutton.MouseLeave:Connect(function()
		tweenService:Create(wavebutton, tweenInfo, {ImageTransparency = 0.5}):Play()
		tweenService:Create(wavename, tweenInfo, {TextTransparency = 0.5}):Play()
		tweenService:Create(wavedesc, tweenInfo, {TextTransparency = 0.5}):Play()
	end)
	
	wavebutton.MouseButton1Click:Connect(function()
		gui.Enabled = false
		local humanoid = char:WaitForChild("Humanoid")
		local animator = humanoid:FindFirstChildOfClass("Animator")
		local anim = Instance.new("Animation")
		anim.AnimationId = "rbxassetid://15609995579" -- YOUR ID HERE
		local track = animator:LoadAnimation(anim)
		track.Looped = false
		track:Play()
		tweenService:Create(wavebutton, tweenInfo, {ImageTransparency = 0.5}):Play()
		tweenService:Create(wavename, tweenInfo, {TextTransparency = 0.5}):Play()
		tweenService:Create(wavedesc, tweenInfo, {TextTransparency = 0.5}):Play()
	end)
end
coroutine.wrap(JLJZ_fake_script)()
local function AVRK_fake_script() -- ThreatButton.EmoteButtonScript 
	local script = Instance.new('LocalScript', ThreatButton)

	local tweenService = game:GetService("TweenService")
	local tweenInfo = TweenInfo.new(0.3, Enum.EasingStyle.Quad)
	local gui = script.Parent.Parent.Parent
	local wavebutton = script.Parent
	local wavename = script.Parent.ThreatName
	local wavedesc = script.Parent.ThreatDescription
	local Player = game.Players.LocalPlayer
	local char = Player.Character or Player.CharacterAdded:Wait()
	
	wavebutton.MouseEnter:Connect(function()
		tweenService:Create(wavebutton, tweenInfo, {ImageTransparency = 0}):Play()
		tweenService:Create(wavename, tweenInfo, {TextTransparency = 0}):Play()
		tweenService:Create(wavedesc, tweenInfo, {TextTransparency = 0}):Play()
	end)
	
	wavebutton.MouseLeave:Connect(function()
		tweenService:Create(wavebutton, tweenInfo, {ImageTransparency = 0.5}):Play()
		tweenService:Create(wavename, tweenInfo, {TextTransparency = 0.5}):Play()
		tweenService:Create(wavedesc, tweenInfo, {TextTransparency = 0.5}):Play()
	end)
	
	wavebutton.MouseButton1Click:Connect(function()
		gui.Enabled = false
		local humanoid = char:WaitForChild("Humanoid")
		local animator = humanoid:FindFirstChildOfClass("Animator")
		local anim = Instance.new("Animation")
		anim.AnimationId = "rbxassetid://17731969215" -- YOUR ID HERE
		local track = animator:LoadAnimation(anim)
		track.Looped = false
		track:Play()
		tweenService:Create(wavebutton, tweenInfo, {ImageTransparency = 0.5}):Play()
		tweenService:Create(wavename, tweenInfo, {TextTransparency = 0.5}):Play()
		tweenService:Create(wavedesc, tweenInfo, {TextTransparency = 0.5}):Play()
	end)
end
coroutine.wrap(AVRK_fake_script)()
