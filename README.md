-- Gui to Lua
-- Version: 3.2

-- Instances:
local success, err = pcall(function()
local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local UICorner = Instance.new("UICorner")
local TextLabel = Instance.new("TextLabel")
local TextLabel_2 = Instance.new("TextLabel")
local TextLabel_3 = Instance.new("TextLabel")
local Clothes = Instance.new("TextButton")
local Walls = Instance.new("TextButton")
local AllSounds = Instance.new("TextButton")
local IY = Instance.new("TextButton")
local TextLabel_4 = Instance.new("TextLabel")
local ScrollingFrame = Instance.new("ScrollingFrame")
local UIListLayout = Instance.new("UIListLayout")
local ScrollingTemp = Instance.new("Folder")
local Frame_2 = Instance.new("Frame")
local TextLabel_5 = Instance.new("TextLabel")
local TextButton = Instance.new("TextButton")
local TextLabel_6 = Instance.new("TextLabel")
local TextLabel_7 = Instance.new("TextLabel")
local TextLabel_8 = Instance.new("TextLabel")

--Properties:

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Frame.BorderColor3 = Color3.fromRGB(202, 202, 202)
Frame.Position = UDim2.new(0.276041657, 0, 0.456021637, 0)
Frame.Size = UDim2.new(0, 479, 0, 291)

UICorner.Parent = Frame

TextLabel.Parent = Frame
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.Position = UDim2.new(0, 0, 0.0343642607, 0)
TextLabel.Size = UDim2.new(0.657620013, 0, 0.305841923, 0)
TextLabel.Font = Enum.Font.LuckiestGuy
TextLabel.Text = "Roblox Squid game GUI!"
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.TextScaled = true
TextLabel.TextSize = 14.000
TextLabel.TextStrokeTransparency = 0.300
TextLabel.TextWrapped = true

TextLabel_2.Parent = Frame
TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.BackgroundTransparency = 1.000
TextLabel_2.Position = UDim2.new(0.655671477, 0, 0.0343642607, 0)
TextLabel_2.Size = UDim2.new(0.158663884, 0, 0.0549828187, 0)
TextLabel_2.Font = Enum.Font.LuckiestGuy
TextLabel_2.Text = "made by:"
TextLabel_2.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.TextScaled = true
TextLabel_2.TextSize = 14.000
TextLabel_2.TextStrokeTransparency = 0.300
TextLabel_2.TextWrapped = true

TextLabel_3.Parent = Frame
TextLabel_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_3.BackgroundTransparency = 1.000
TextLabel_3.Position = UDim2.new(0.655671477, 0, 0.0893470794, 0)
TextLabel_3.Size = UDim2.new(0.28601253, 0, 0.0412371121, 0)
TextLabel_3.Font = Enum.Font.LuckiestGuy
TextLabel_3.Text = "thatchrisie (v3rm)"
TextLabel_3.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_3.TextScaled = true
TextLabel_3.TextSize = 14.000
TextLabel_3.TextStrokeTransparency = 0.300
TextLabel_3.TextWrapped = true

Clothes.Name = "Clothes"
Clothes.Parent = Frame
Clothes.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Clothes.BackgroundTransparency = 0.950
Clothes.Position = UDim2.new(0.0480167009, 0, 0.340206176, 0)
Clothes.Size = UDim2.new(0.33611691, 0, 0.16838488, 0)
Clothes.Font = Enum.Font.Cartoon
Clothes.Text = "Admin Clothes"
Clothes.TextColor3 = Color3.fromRGB(0, 0, 0)
Clothes.TextScaled = true
Clothes.TextSize = 14.000
Clothes.TextWrapped = true

Walls.Name = "Walls"
Walls.Parent = Frame
Walls.BackgroundColor3 = Color3.fromRGB(6, 6, 6)
Walls.BackgroundTransparency = 0.950
Walls.Position = UDim2.new(0.40292275, 0, 0.340206176, 0)
Walls.Size = UDim2.new(0.33611691, 0, 0.16838488, 0)
Walls.Font = Enum.Font.Cartoon
Walls.Text = "Disable Invisible Walls"
Walls.TextColor3 = Color3.fromRGB(165, 165, 165)
Walls.TextScaled = true
Walls.TextSize = 14.000
Walls.TextWrapped = true

AllSounds.Name = "AllSounds"
AllSounds.Parent = Frame
AllSounds.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
AllSounds.BackgroundTransparency = 0.950
AllSounds.Position = UDim2.new(0.0480166972, 0, 0.542955339, 0)
AllSounds.Size = UDim2.new(0.33611691, 0, 0.16838488, 0)
AllSounds.Font = Enum.Font.Cartoon
AllSounds.Text = "Toggle All Sounds - Off"
AllSounds.TextColor3 = Color3.fromRGB(0, 0, 0)
AllSounds.TextScaled = true
AllSounds.TextSize = 14.000
AllSounds.TextWrapped = true

IY.Name = "IY"
IY.Parent = Frame
IY.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
IY.BackgroundTransparency = 0.950
IY.Position = UDim2.new(0.40292275, 0, 0.542955339, 0)
IY.Size = UDim2.new(0.33611691, 0, 0.16838488, 0)
IY.Font = Enum.Font.Cartoon
IY.Text = "Execute IY"
IY.TextColor3 = Color3.fromRGB(0, 0, 0)
IY.TextScaled = true
IY.TextSize = 14.000
IY.TextWrapped = true

TextLabel_4.Parent = Frame
TextLabel_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_4.BackgroundTransparency = 1.000
TextLabel_4.Position = UDim2.new(0.415448844, 0, 0.731958747, 0)
TextLabel_4.Size = UDim2.new(0.31106472, 0, 0.0481099673, 0)
TextLabel_4.Font = Enum.Font.LuckiestGuy
TextLabel_4.Text = "(Try using ;invisfling)"
TextLabel_4.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_4.TextScaled = true
TextLabel_4.TextSize = 14.000
TextLabel_4.TextStrokeTransparency = 0.500
TextLabel_4.TextWrapped = true

ScrollingFrame.Parent = Frame
ScrollingFrame.Active = true
ScrollingFrame.BackgroundColor3 = Color3.fromRGB(249, 249, 249)
ScrollingFrame.BackgroundTransparency = 0.450
ScrollingFrame.BorderColor3 = Color3.fromRGB(241, 241, 241)
ScrollingFrame.Position = UDim2.new(0.0480167009, 0, 0.731958747, 0)
ScrollingFrame.Size = UDim2.new(0.33611691, 0, 0.237113401, 0)
ScrollingFrame.ScrollBarThickness = 8
ScrollingFrame.CanvasSize = UDim2.new(0, 0, 5, 0)

UIListLayout.Parent = ScrollingFrame
UIListLayout.SortOrder = Enum.SortOrder.LayoutOrder
UIListLayout.Padding = UDim.new(0, 5)

ScrollingTemp.Name = "ScrollingTemp"
ScrollingTemp.Parent = Frame

Frame_2.Parent = ScrollingTemp
Frame_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Frame_2.BorderColor3 = Color3.fromRGB(239, 239, 239)
Frame_2.Size = UDim2.new(0.949999988, 0, 0, 30)
Frame_2.Visible = false

TextLabel_5.Parent = Frame_2
TextLabel_5.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_5.BackgroundTransparency = 1.000
TextLabel_5.Size = UDim2.new(0.699999988, 0, 1, 0)
TextLabel_5.Font = Enum.Font.SourceSans
TextLabel_5.Text = "Sound Name"
TextLabel_5.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_5.TextScaled = true
TextLabel_5.TextSize = 14.000
TextLabel_5.TextWrapped = true

TextButton.Parent = Frame_2
TextButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton.BackgroundTransparency = 0.950
TextButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton.BorderSizePixel = 2
TextButton.Position = UDim2.new(0.76066792, 0, -0.0237113237, 0)
TextButton.Size = UDim2.new(0.224999994, 0, 1, 0)
TextButton.Font = Enum.Font.Cartoon
TextButton.Text = "Play"
TextButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton.TextScaled = true
TextButton.TextSize = 14.000
TextButton.TextWrapped = true

TextLabel_6.Parent = Frame
TextLabel_6.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_6.BackgroundTransparency = 1.000
TextLabel_6.Position = UDim2.new(0.384133607, 0, 0.848797202, 0)
TextLabel_6.Size = UDim2.new(0.31106472, 0, 0.0481099673, 0)
TextLabel_6.Font = Enum.Font.LuckiestGuy
TextLabel_6.Text = "< List of all Buttons"
TextLabel_6.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_6.TextScaled = true
TextLabel_6.TextSize = 14.000
TextLabel_6.TextStrokeTransparency = 0.500
TextLabel_6.TextWrapped = true

TextLabel_7.Parent = Frame
TextLabel_7.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_7.BackgroundTransparency = 1.000
TextLabel_7.Position = UDim2.new(0.384133607, 0, 0.89690721, 0)
TextLabel_7.Size = UDim2.new(0.31106472, 0, 0.0378006883, 0)
TextLabel_7.Font = Enum.Font.LuckiestGuy
TextLabel_7.Text = "(Sounds are included)"
TextLabel_7.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_7.TextScaled = true
TextLabel_7.TextSize = 14.000
TextLabel_7.TextStrokeTransparency = 0.500
TextLabel_7.TextWrapped = true

TextLabel_8.Parent = Frame
TextLabel_8.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_8.BackgroundTransparency = 1.000
TextLabel_8.Position = UDim2.new(0.755741119, 0, 0.340206176, 0)
TextLabel_8.Size = UDim2.new(0.185803756, 0, 0.16838491, 0)
TextLabel_8.Font = Enum.Font.LuckiestGuy
TextLabel_8.Text = "< this button is useless now"
TextLabel_8.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_8.TextScaled = true
TextLabel_8.TextSize = 14.000
TextLabel_8.TextStrokeTransparency = 0.500
TextLabel_8.TextWrapped = true






--custom


UICorner.CornerRadius = UDim.new(0, 8)








-- Scripts:

local function ATRPDZ_fake_script() -- Frame.Drag 
	local script = Instance.new('LocalScript', Frame)

	local UserInputService = game:GetService("UserInputService")
	
	local gui = script.Parent
	
	local dragging
	local dragInput
	local dragStart
	local startPos
	
	local function update(input)
		local delta = input.Position - dragStart
		gui.Position = UDim2.new(startPos.X.Scale, startPos.X.Offset + delta.X, startPos.Y.Scale, startPos.Y.Offset + delta.Y)
	end
	
	gui.InputBegan:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch then
			dragging = true
			dragStart = input.Position
			startPos = gui.Position
			
			input.Changed:Connect(function()
				if input.UserInputState == Enum.UserInputState.End then
					dragging = false
				end
			end)
		end
	end)
	
	gui.InputChanged:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
			dragInput = input
		end
	end)
	
	UserInputService.InputChanged:Connect(function(input)
		if input == dragInput and dragging then
			update(input)
		end
	end)
end
coroutine.wrap(ATRPDZ_fake_script)()
local function VTBZYO_fake_script() -- Frame.LocalScript 
	local script = Instance.new('LocalScript', Frame)

	getgenv().toggleAll = false
	
	
	
	script.Parent.Clothes.MouseButton1Click:Connect(function()
		for i, v in pairs(workspace:GetDescendants()) do
			if v:IsA("ClickDetector") then
				fireclickdetector(v)
			end
		end
	end)
	
	script.Parent.Walls.MouseButton1Click:Connect(function()
		for i, v in pairs(workspace:GetDescendants()) do
			if v:IsA("ClickDetector") and v.Parent.Color == Color3.fromRGB(196, 40, 28) then
				fireclickdetector(v)
			end
		end
	end)
	
	script.Parent.AllSounds.MouseButton1Click:Connect(function()
		toggleAll = not toggleAll
		
		script.Parent.AllSounds.Text = toggleAll and "Toggle All Sounds - On" or "Toggle All Sounds - Off" 
	end)
	
	script.Parent.Clothes.MouseButton1Click:Connect(function()
		for i, v in pairs(workspace:GetDescendants()) do
			if v:IsA("ClickDetector") then
				fireclickdetector(v)
			end
		end
	end)
	
	script.Parent.IY.MouseButton1Click:Connect(function()
		spawn(function()
			loadstring(game:HttpGet(('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'),true))()
		end)
	end)
	
	
	if not game:IsLoaded() then
		game.Loaded:Wait()
	end
	
	function inAdd(i, v)
		local clone = script.Parent.ScrollingTemp.Frame:Clone()

		clone.Parent = script.Parent.ScrollingFrame

		clone.TextLabel.Text = "Sound" .. i .. ", " .. v.Parent.Name

		clone.TextButton.Text = v.Parent.Name:lower() ~= "head" and v.Parent.Name or "Click"

        clone.Visible = true

		clone.TextButton.MouseButton1Click:Connect(function()
			fireclickdetector(v)
		end) 
	end
	
	spawn(function()
    	for i, v in pairs(workspace:GetDescendants()) do
    		if v:IsA("ClickDetector") and (v.Parent.Name:lower() == "play" or v.Parent.Name:lower() == "stop") then
    			inAdd(i, v)
    		end
    	end
    end)
	
	
	
	while true do
		wait()
	
		if toggleAll then
			for i, v in pairs(workspace:GetDescendants()) do
				if v:IsA("ClickDetector") and (v.Parent.Color ~= Color3.fromRGB(196, 40, 28) or v.Name == "play" or v.Name == "Head") then
					fireclickdetector(v)
				end
			end
		end
	end
end
coroutine.wrap(VTBZYO_fake_script)()
end)

print(success, err)
