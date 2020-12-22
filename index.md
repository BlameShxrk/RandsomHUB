-- Gui to Lua
-- Version: 3.2

-- Instances:

local RandsomWarev21 = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local BackRound = Instance.new("ImageLabel")
local UICorner = Instance.new("UICorner")
local TextName = Instance.new("TextLabel")
local UICorner_2 = Instance.new("UICorner")
local UICorner_3 = Instance.new("UICorner")
local CarCrushers = Instance.new("TextButton")
local UICorner_4 = Instance.new("UICorner")
local VehicleSimulator = Instance.new("TextButton")
local UICorner_5 = Instance.new("UICorner")
local COMINGSOON = Instance.new("TextButton")
local UICorner_6 = Instance.new("UICorner")
local PrisonLife = Instance.new("TextButton")
local UICorner_7 = Instance.new("UICorner")
local InfYeild = Instance.new("TextButton")
local UICorner_8 = Instance.new("UICorner")
local OWLHUB = Instance.new("TextButton")
local UICorner_9 = Instance.new("UICorner")
local LOGO = Instance.new("ImageLabel")
local UICorner_10 = Instance.new("UICorner")

--Properties:

RandsomWarev21.Name = "Randsom Ware v2.1"
RandsomWarev21.Parent = game.CoreGui
Frame.Parent = RandsomWarev21
Frame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Frame.BackgroundTransparency = 1.000
Frame.Position = UDim2.new(0.280866414, 0, 0.0872235149, 0)
Frame.Size = UDim2.new(0, 618, 0, 492)
Frame.Draggable = true
Frame.Active = true
BackRound.Name = "BackRound"
BackRound.Parent = Frame
BackRound.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
BackRound.Position = UDim2.new(-0.000898046419, 0, -0.00155236467, 0)
BackRound.Size = UDim2.new(0, 624, 0, 492)
BackRound.Image = "rbxassetid://6122390117"
BackRound.Draggable = true

UICorner.CornerRadius = UDim.new(0.200000003, 0)
UICorner.Parent = BackRound

TextName.Name = "Text Name"
TextName.Parent = Frame
TextName.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextName.BackgroundTransparency = 1.000
TextName.Position = UDim2.new(0.198275864, 0, 0, 0)
TextName.Size = UDim2.new(0, 363, 0, 57)
TextName.Font = Enum.Font.PermanentMarker
TextName.Text = "Randsom Ware v2.1"
TextName.TextColor3 = Color3.fromRGB(0, 0, 0)
TextName.TextScaled = true
TextName.TextSize = 14.000
TextName.TextWrapped = true

UICorner_2.CornerRadius = UDim.new(0.300000012, 0)
UICorner_2.Parent = TextName

UICorner_3.CornerRadius = UDim.new(0.200000003, 0)
UICorner_3.Parent = Frame

CarCrushers.Name = "Car Crushers"
CarCrushers.Parent = Frame
CarCrushers.BackgroundColor3 = Color3.fromRGB(255, 82, 85)
CarCrushers.BorderColor3 = Color3.fromRGB(255, 82, 85)
CarCrushers.Position = UDim2.new(0.0485436879, 0, 0.82520324, 0)
CarCrushers.Size = UDim2.new(0, 176, 0, 43)
CarCrushers.Font = Enum.Font.SciFi
CarCrushers.Text = "Car Crushers"
CarCrushers.TextColor3 = Color3.fromRGB(0, 0, 0)
CarCrushers.TextSize = 14.000

UICorner_4.CornerRadius = UDim.new(0.5, 0)
UICorner_4.Parent = CarCrushers

VehicleSimulator.Name = "Vehicle Simulator"
VehicleSimulator.Parent = Frame
VehicleSimulator.BackgroundColor3 = Color3.fromRGB(255, 82, 85)
VehicleSimulator.Position = UDim2.new(0.645631075, 0, 0.82520324, 0)
VehicleSimulator.Size = UDim2.new(0, 176, 0, 43)
VehicleSimulator.Font = Enum.Font.SciFi
VehicleSimulator.Text = "Vechile simulator"
VehicleSimulator.TextColor3 = Color3.fromRGB(0, 0, 0)
VehicleSimulator.TextSize = 14.000

UICorner_5.CornerRadius = UDim.new(0.5, 0)
UICorner_5.Parent = VehicleSimulator

COMINGSOON.Name = "COMING SOON"
COMINGSOON.Parent = Frame
COMINGSOON.BackgroundColor3 = Color3.fromRGB(255, 82, 85)
COMINGSOON.Position = UDim2.new(0.349514574, 0, 0.82520324, 0)
COMINGSOON.Size = UDim2.new(0, 176, 0, 43)
COMINGSOON.Font = Enum.Font.SciFi
COMINGSOON.Text = "COMING SOON"
COMINGSOON.TextColor3 = Color3.fromRGB(0, 0, 0)
COMINGSOON.TextSize = 14.000

UICorner_6.CornerRadius = UDim.new(0.5, 0)
UICorner_6.Parent = COMINGSOON

PrisonLife.Name = "Prison Life"
PrisonLife.Parent = Frame
PrisonLife.BackgroundColor3 = Color3.fromRGB(255, 82, 85)
PrisonLife.BorderColor3 = Color3.fromRGB(255, 82, 85)
PrisonLife.Position = UDim2.new(0.349514574, 0, 0.691056907, 0)
PrisonLife.Size = UDim2.new(0, 176, 0, 43)
PrisonLife.Font = Enum.Font.SciFi
PrisonLife.Text = "Prison Life"
PrisonLife.TextColor3 = Color3.fromRGB(0, 0, 0)
PrisonLife.TextSize = 14.000
PrisonLife.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/RbxCheats/RbxCheats/master/Scripts/PLG%20v3.1.lua",true))()
end)

UICorner_7.CornerRadius = UDim.new(0.5, 0)
UICorner_7.Parent = PrisonLife

InfYeild.Name = "Inf Yeild"
InfYeild.Parent = Frame
InfYeild.BackgroundColor3 = Color3.fromRGB(255, 82, 85)
InfYeild.BorderColor3 = Color3.fromRGB(255, 82, 85)
InfYeild.Position = UDim2.new(0.645631075, 0, 0.691056907, 0)
InfYeild.Size = UDim2.new(0, 176, 0, 43)
InfYeild.Font = Enum.Font.SciFi
InfYeild.Text = "Inf Yeild"
InfYeild.TextColor3 = Color3.fromRGB(0, 0, 0)
InfYeild.TextSize = 14.000
InfYeild.MouseButton1Down:connect(function()
	loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
end)
UICorner_8.CornerRadius = UDim.new(0.5, 0)
UICorner_8.Parent = InfYeild

OWLHUB.Name = "OWL HUB"
OWLHUB.Parent = Frame
OWLHUB.BackgroundColor3 = Color3.fromRGB(255, 82, 85)
OWLHUB.BorderColor3 = Color3.fromRGB(255, 82, 85)
OWLHUB.Position = UDim2.new(0.0485436916, 0, 0.691056907, 0)
OWLHUB.Size = UDim2.new(0, 176, 0, 43)
OWLHUB.Font = Enum.Font.SciFi
OWLHUB.Text = "OWL HUB"
OWLHUB.TextColor3 = Color3.fromRGB(0, 0, 0)
OWLHUB.TextSize = 14.000
OWLHUB.TextWrapped = true
OWLHUB.MouseButton1Down:connect(function()
	loadstring(game:HttpGet('https://pastebin.com/raw/yTpB26k5'))()
end)
UICorner_9.CornerRadius = UDim.new(0.5, 0)
UICorner_9.Parent = OWLHUB

LOGO.Name = "LOGO"
LOGO.Parent = Frame
LOGO.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
LOGO.Position = UDim2.new(0.796116531, 0, 0.0264227651, 0)
LOGO.Size = UDim2.new(0, 70, 0, 55)
LOGO.Image = "rbxassetid://6122348358"

UICorner_10.CornerRadius = UDim.new(0.5, 0)
UICorner_10.Parent = LOGO
