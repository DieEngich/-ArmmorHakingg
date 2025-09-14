local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local UICorner = Instance.new("UICorner")
local HeadTransparency = Instance.new("Frame")
local slideFrame = Instance.new("Frame")
local UICorner_2 = Instance.new("UICorner")
local amountValue = Instance.new("TextLabel")
local UICorner_3 = Instance.new("UICorner")
local UICorner_4 = Instance.new("UICorner")
local TextLabel = Instance.new("TextLabel")
local HeadTransparency_2 = Instance.new("Frame")
local slideFrame_2 = Instance.new("Frame")
local UICorner_5 = Instance.new("UICorner")
local amountValue_2 = Instance.new("TextLabel")
local UICorner_6 = Instance.new("UICorner")
local UICorner_7 = Instance.new("UICorner")
local TextLabel_2 = Instance.new("TextLabel")
local HeadTransparency_3 = Instance.new("Frame")
local slideFrame_3 = Instance.new("Frame")
local UICorner_8 = Instance.new("UICorner")
local amountValue_3 = Instance.new("TextLabel")
local UICorner_9 = Instance.new("UICorner")
local UICorner_10 = Instance.new("UICorner")
local TextLabel_3 = Instance.new("TextLabel")
local HeadTransparency_4 = Instance.new("Frame")
local slideFrame_4 = Instance.new("Frame")
local UICorner_11 = Instance.new("UICorner")
local amountValue_4 = Instance.new("TextLabel")
local UICorner_12 = Instance.new("UICorner")
local UICorner_13 = Instance.new("UICorner")
local TextLabel_4 = Instance.new("TextLabel")
local TextLabel_5 = Instance.new("TextLabel")
local TextLabel_6 = Instance.new("TextLabel")
local TextButton = Instance.new("TextButton")
local UICorner_14 = Instance.new("UICorner")

--Properties:

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.fromRGB(48, 48, 48)
Frame.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame.BorderSizePixel = 0
Frame.Position = UDim2.new(0.379415333, 0, 0.337182462, 0)
Frame.Size = UDim2.new(0, 395, 0, 282)
Frame.Visible = false

UICorner.Parent = Frame

HeadTransparency.Name = "HeadTransparency"
HeadTransparency.Parent = Frame
HeadTransparency.AnchorPoint = Vector2.new(0.5, 0.5)
HeadTransparency.BackgroundColor3 = Color3.fromRGB(35, 35, 35)
HeadTransparency.BorderColor3 = Color3.fromRGB(255, 255, 255)
HeadTransparency.BorderSizePixel = 2
HeadTransparency.Position = UDim2.new(0.306531698, 0, 0.114981115, 0)
HeadTransparency.Size = UDim2.new(0.508335114, 0, 0.0666555315, 0)

slideFrame.Name = "slideFrame"
slideFrame.Parent = HeadTransparency
slideFrame.BackgroundColor3 = Color3.fromRGB(136, 0, 255)
slideFrame.BackgroundTransparency = 0.250
slideFrame.BorderColor3 = Color3.fromRGB(27, 42, 53)
slideFrame.BorderSizePixel = 0
slideFrame.Size = UDim2.new(0, 0, 1, 0)

UICorner_2.CornerRadius = UDim.new(1, 0)
UICorner_2.Parent = slideFrame

amountValue.Name = "amountValue"
amountValue.Parent = HeadTransparency
amountValue.AnchorPoint = Vector2.new(0.5, 0.5)
amountValue.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
amountValue.BackgroundTransparency = 1.000
amountValue.BorderColor3 = Color3.fromRGB(27, 42, 53)
amountValue.BorderSizePixel = 0
amountValue.Position = UDim2.new(0.5, 0, 0.49404946, 0)
amountValue.Size = UDim2.new(1, 0, 0.850000024, 0)
amountValue.ZIndex = 2
amountValue.Font = Enum.Font.SourceSansSemibold
amountValue.Text = "0"
amountValue.TextColor3 = Color3.fromRGB(255, 255, 255)
amountValue.TextScaled = true
amountValue.TextSize = 14.000
amountValue.TextWrapped = true

UICorner_3.CornerRadius = UDim.new(1, 0)
UICorner_3.Parent = amountValue

UICorner_4.CornerRadius = UDim.new(1, 0)
UICorner_4.Parent = HeadTransparency

TextLabel.Parent = HeadTransparency
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.BorderSizePixel = 0
TextLabel.Position = UDim2.new(-0.0415557139, 0, -0.959587991, 0)
TextLabel.Size = UDim2.new(0, 200, 0, 20)
TextLabel.Font = Enum.Font.FredokaOne
TextLabel.Text = "Speed Hack"
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.TextSize = 11.000

HeadTransparency_2.Name = "HeadTransparency"
HeadTransparency_2.Parent = Frame
HeadTransparency_2.AnchorPoint = Vector2.new(0.5, 0.5)
HeadTransparency_2.BackgroundColor3 = Color3.fromRGB(35, 35, 35)
HeadTransparency_2.BorderColor3 = Color3.fromRGB(255, 255, 255)
HeadTransparency_2.BorderSizePixel = 2
HeadTransparency_2.Position = UDim2.new(0.306531698, 0, 0.249732897, 0)
HeadTransparency_2.Size = UDim2.new(0.508335114, 0, 0.0666555315, 0)

slideFrame_2.Name = "slideFrame"
slideFrame_2.Parent = HeadTransparency_2
slideFrame_2.BackgroundColor3 = Color3.fromRGB(136, 0, 255)
slideFrame_2.BackgroundTransparency = 0.250
slideFrame_2.BorderColor3 = Color3.fromRGB(27, 42, 53)
slideFrame_2.BorderSizePixel = 0
slideFrame_2.Size = UDim2.new(0, 0, 1, 0)

UICorner_5.CornerRadius = UDim.new(1, 0)
UICorner_5.Parent = slideFrame_2

amountValue_2.Name = "amountValue"
amountValue_2.Parent = HeadTransparency_2
amountValue_2.AnchorPoint = Vector2.new(0.5, 0.5)
amountValue_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
amountValue_2.BackgroundTransparency = 1.000
amountValue_2.BorderColor3 = Color3.fromRGB(27, 42, 53)
amountValue_2.BorderSizePixel = 0
amountValue_2.Position = UDim2.new(0.5, 0, 0.49404946, 0)
amountValue_2.Size = UDim2.new(1, 0, 0.850000024, 0)
amountValue_2.ZIndex = 2
amountValue_2.Font = Enum.Font.SourceSansSemibold
amountValue_2.Text = "0"
amountValue_2.TextColor3 = Color3.fromRGB(255, 255, 255)
amountValue_2.TextScaled = true
amountValue_2.TextSize = 14.000
amountValue_2.TextWrapped = true

UICorner_6.CornerRadius = UDim.new(1, 0)
UICorner_6.Parent = amountValue_2

UICorner_7.CornerRadius = UDim.new(1, 0)
UICorner_7.Parent = HeadTransparency_2

TextLabel_2.Parent = HeadTransparency_2
TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.BackgroundTransparency = 1.000
TextLabel_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_2.BorderSizePixel = 0
TextLabel_2.Position = UDim2.new(-0.0415557139, 0, -0.959587991, 0)
TextLabel_2.Size = UDim2.new(0, 200, 0, 20)
TextLabel_2.Font = Enum.Font.FredokaOne
TextLabel_2.Text = "Jump Hack"
TextLabel_2.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.TextSize = 11.000

HeadTransparency_3.Name = "HeadTransparency"
HeadTransparency_3.Parent = Frame
HeadTransparency_3.AnchorPoint = Vector2.new(0.5, 0.5)
HeadTransparency_3.BackgroundColor3 = Color3.fromRGB(35, 35, 35)
HeadTransparency_3.BorderColor3 = Color3.fromRGB(255, 255, 255)
HeadTransparency_3.BorderSizePixel = 2
HeadTransparency_3.Position = UDim2.new(0.306531698, 0, 0.398669064, 0)
HeadTransparency_3.Size = UDim2.new(0.508335114, 0, 0.0666555315, 0)

slideFrame_3.Name = "slideFrame"
slideFrame_3.Parent = HeadTransparency_3
slideFrame_3.BackgroundColor3 = Color3.fromRGB(136, 0, 255)
slideFrame_3.BackgroundTransparency = 0.250
slideFrame_3.BorderColor3 = Color3.fromRGB(27, 42, 53)
slideFrame_3.BorderSizePixel = 0
slideFrame_3.Size = UDim2.new(0, 0, 1, 0)

UICorner_8.CornerRadius = UDim.new(1, 0)
UICorner_8.Parent = slideFrame_3

amountValue_3.Name = "amountValue"
amountValue_3.Parent = HeadTransparency_3
amountValue_3.AnchorPoint = Vector2.new(0.5, 0.5)
amountValue_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
amountValue_3.BackgroundTransparency = 1.000
amountValue_3.BorderColor3 = Color3.fromRGB(27, 42, 53)
amountValue_3.BorderSizePixel = 0
amountValue_3.Position = UDim2.new(0.5, 0, 0.49404946, 0)
amountValue_3.Size = UDim2.new(1, 0, 0.850000024, 0)
amountValue_3.ZIndex = 2
amountValue_3.Font = Enum.Font.SourceSansSemibold
amountValue_3.Text = "0"
amountValue_3.TextColor3 = Color3.fromRGB(255, 255, 255)
amountValue_3.TextScaled = true
amountValue_3.TextSize = 14.000
amountValue_3.TextWrapped = true

UICorner_9.CornerRadius = UDim.new(1, 0)
UICorner_9.Parent = amountValue_3

UICorner_10.CornerRadius = UDim.new(1, 0)
UICorner_10.Parent = HeadTransparency_3

TextLabel_3.Parent = HeadTransparency_3
TextLabel_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_3.BackgroundTransparency = 1.000
TextLabel_3.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_3.BorderSizePixel = 0
TextLabel_3.Position = UDim2.new(-0.0415557139, 0, -0.959587991, 0)
TextLabel_3.Size = UDim2.new(0, 200, 0, 20)
TextLabel_3.Font = Enum.Font.FredokaOne
TextLabel_3.Text = "Time Set"
TextLabel_3.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_3.TextSize = 11.000

HeadTransparency_4.Name = "HeadTransparency"
HeadTransparency_4.Parent = Frame
HeadTransparency_4.AnchorPoint = Vector2.new(0.5, 0.5)
HeadTransparency_4.BackgroundColor3 = Color3.fromRGB(35, 35, 35)
HeadTransparency_4.BorderColor3 = Color3.fromRGB(255, 255, 255)
HeadTransparency_4.BorderSizePixel = 2
HeadTransparency_4.Position = UDim2.new(0.306531698, 0, 0.547605276, 0)
HeadTransparency_4.Size = UDim2.new(0.508335114, 0, 0.0666555315, 0)

slideFrame_4.Name = "slideFrame"
slideFrame_4.Parent = HeadTransparency_4
slideFrame_4.BackgroundColor3 = Color3.fromRGB(136, 0, 255)
slideFrame_4.BackgroundTransparency = 0.250
slideFrame_4.BorderColor3 = Color3.fromRGB(27, 42, 53)
slideFrame_4.BorderSizePixel = 0
slideFrame_4.Size = UDim2.new(0, 0, 1, 0)

UICorner_11.CornerRadius = UDim.new(1, 0)
UICorner_11.Parent = slideFrame_4

amountValue_4.Name = "amountValue"
amountValue_4.Parent = HeadTransparency_4
amountValue_4.AnchorPoint = Vector2.new(0.5, 0.5)
amountValue_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
amountValue_4.BackgroundTransparency = 1.000
amountValue_4.BorderColor3 = Color3.fromRGB(27, 42, 53)
amountValue_4.BorderSizePixel = 0
amountValue_4.Position = UDim2.new(0.5, 0, 0.49404946, 0)
amountValue_4.Size = UDim2.new(1, 0, 0.850000024, 0)
amountValue_4.ZIndex = 2
amountValue_4.Font = Enum.Font.SourceSansSemibold
amountValue_4.Text = "0"
amountValue_4.TextColor3 = Color3.fromRGB(255, 255, 255)
amountValue_4.TextScaled = true
amountValue_4.TextSize = 14.000
amountValue_4.TextWrapped = true

UICorner_12.CornerRadius = UDim.new(1, 0)
UICorner_12.Parent = amountValue_4

UICorner_13.CornerRadius = UDim.new(1, 0)
UICorner_13.Parent = HeadTransparency_4

TextLabel_4.Parent = HeadTransparency_4
TextLabel_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_4.BackgroundTransparency = 1.000
TextLabel_4.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_4.BorderSizePixel = 0
TextLabel_4.Position = UDim2.new(-0.0415557139, 0, -0.959587991, 0)
TextLabel_4.Size = UDim2.new(0, 200, 0, 20)
TextLabel_4.Font = Enum.Font.FredokaOne
TextLabel_4.Text = "Gamma Set"
TextLabel_4.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_4.TextSize = 11.000

TextLabel_5.Parent = Frame
TextLabel_5.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_5.BackgroundTransparency = 1.000
TextLabel_5.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_5.BorderSizePixel = 0
TextLabel_5.Position = UDim2.new(0.600000024, 0, 0, 0)
TextLabel_5.Size = UDim2.new(0, 158, 0, 40)
TextLabel_5.Font = Enum.Font.FredokaOne
TextLabel_5.Text = "Multi Tool "
TextLabel_5.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_5.TextSize = 14.000

TextLabel_6.Parent = Frame
TextLabel_6.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_6.BackgroundTransparency = 1.000
TextLabel_6.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_6.BorderSizePixel = 0
TextLabel_6.Position = UDim2.new(0.650632918, 0, 0.113475174, 0)
TextLabel_6.Size = UDim2.new(0, 117, 0, 40)
TextLabel_6.Font = Enum.Font.FredokaOne
TextLabel_6.Text = "By @ArmmorHakingg"
TextLabel_6.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_6.TextSize = 14.000

TextButton.Parent = ScreenGui
TextButton.BackgroundColor3 = Color3.fromRGB(54, 54, 54)
TextButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton.BorderSizePixel = 0
TextButton.Position = UDim2.new(0.183120072, 0, 0.426368982, 0)
TextButton.Size = UDim2.new(0, 81, 0, 34)
TextButton.Font = Enum.Font.FredokaOne
TextButton.Text = "Open"
TextButton.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton.TextSize = 14.000

UICorner_14.Parent = TextButton

-- Scripts:

local function VCFPWOV_fake_script() -- HeadTransparency.mainScript 
	local script = Instance.new('LocalScript', HeadTransparency)

	local mouse = game:GetService("Players").LocalPlayer:GetMouse()
	local humanoid = game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid")
	
	local function initiateDrag(frame, callbackFunction)
		local dragging = false
		
		frame.InputBegan:Connect(function(input)
			if input.UserInputType == Enum.UserInputType.MouseButton1 then
				dragging = true
			end
		end)
		
		frame.InputEnded:Connect(function(input)
			if input.UserInputType == Enum.UserInputType.MouseButton1 then
				dragging = false
			end
		end)
		
		frame.InputBegan:Connect(function(input)
			if input.UserInputType == Enum.UserInputType.MouseButton1 then
				local pos = UDim2.new(math.clamp((mouse.X - frame.AbsolutePosition.X) / frame.AbsoluteSize.X, 0, 1), 0, 1, 0)
				frame.slideFrame:TweenSize(pos, Enum.EasingDirection.Out, Enum.EasingStyle.Quad, 0.25, true, callbackFunction(pos.X.Scale))
			end
		end)
		
		game:GetService("UserInputService").InputChanged:Connect(function(input)
			if dragging and input.UserInputType == Enum.UserInputType.MouseMovement then
				local pos = UDim2.new(math.clamp((mouse.X - frame.AbsolutePosition.X) / frame.AbsoluteSize.X, 0, 1), 0, 1, 0)
				frame.slideFrame:TweenSize(pos, Enum.EasingDirection.Out, Enum.EasingStyle.Quad, 0.25, true, callbackFunction(pos.X.Scale))
			end
		end)
	end
	
	initiateDrag(script.Parent, function(value)
		script.Parent.amountValue.Text = tostring(math.floor(value * 1000))
		game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = value * 1000
	end)
end
coroutine.wrap(VCFPWOV_fake_script)()
local function KZQVF_fake_script() -- HeadTransparency_2.mainScript 
	local script = Instance.new('LocalScript', HeadTransparency_2)

	local mouse = game:GetService("Players").LocalPlayer:GetMouse()
	local humanoid = game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid")
	
	local function initiateDrag(frame, callbackFunction)
		local dragging = false
		
		frame.InputBegan:Connect(function(input)
			if input.UserInputType == Enum.UserInputType.MouseButton1 then
				dragging = true
			end
		end)
		
		frame.InputEnded:Connect(function(input)
			if input.UserInputType == Enum.UserInputType.MouseButton1 then
				dragging = false
			end
		end)
		
		frame.InputBegan:Connect(function(input)
			if input.UserInputType == Enum.UserInputType.MouseButton1 then
				local pos = UDim2.new(math.clamp((mouse.X - frame.AbsolutePosition.X) / frame.AbsoluteSize.X, 0, 1), 0, 1, 0)
				frame.slideFrame:TweenSize(pos, Enum.EasingDirection.Out, Enum.EasingStyle.Quad, 0.25, true, callbackFunction(pos.X.Scale))
			end
		end)
		
		game:GetService("UserInputService").InputChanged:Connect(function(input)
			if dragging and input.UserInputType == Enum.UserInputType.MouseMovement then
				local pos = UDim2.new(math.clamp((mouse.X - frame.AbsolutePosition.X) / frame.AbsoluteSize.X, 0, 1), 0, 1, 0)
				frame.slideFrame:TweenSize(pos, Enum.EasingDirection.Out, Enum.EasingStyle.Quad, 0.25, true, callbackFunction(pos.X.Scale))
			end
		end)
	end
	
	initiateDrag(script.Parent, function(value)
		script.Parent.amountValue.Text = tostring(math.floor(value * 1000))
		game.Players.LocalPlayer.Character.Humanoid.JumpHeight = value * 1000
	end)
end
coroutine.wrap(KZQVF_fake_script)()
local function GIOHXBX_fake_script() -- HeadTransparency_3.mainScript 
	local script = Instance.new('LocalScript', HeadTransparency_3)

	local mouse = game:GetService("Players").LocalPlayer:GetMouse()
	local humanoid = game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid")
	
	local function initiateDrag(frame, callbackFunction)
		local dragging = false
		
		frame.InputBegan:Connect(function(input)
			if input.UserInputType == Enum.UserInputType.MouseButton1 then
				dragging = true
			end
		end)
		
		frame.InputEnded:Connect(function(input)
			if input.UserInputType == Enum.UserInputType.MouseButton1 then
				dragging = false
			end
		end)
		
		frame.InputBegan:Connect(function(input)
			if input.UserInputType == Enum.UserInputType.MouseButton1 then
				local pos = UDim2.new(math.clamp((mouse.X - frame.AbsolutePosition.X) / frame.AbsoluteSize.X, 0, 1), 0, 1, 0)
				frame.slideFrame:TweenSize(pos, Enum.EasingDirection.Out, Enum.EasingStyle.Quad, 0.25, true, callbackFunction(pos.X.Scale))
			end
		end)
		
		game:GetService("UserInputService").InputChanged:Connect(function(input)
			if dragging and input.UserInputType == Enum.UserInputType.MouseMovement then
				local pos = UDim2.new(math.clamp((mouse.X - frame.AbsolutePosition.X) / frame.AbsoluteSize.X, 0, 1), 0, 1, 0)
				frame.slideFrame:TweenSize(pos, Enum.EasingDirection.Out, Enum.EasingStyle.Quad, 0.25, true, callbackFunction(pos.X.Scale))
			end
		end)
	end
	
	initiateDrag(script.Parent, function(value)
		script.Parent.amountValue.Text = tostring(math.floor(value * 24))
		game.Lighting.ClockTime = value * 24
	end)
end
coroutine.wrap(GIOHXBX_fake_script)()
local function LGUW_fake_script() -- HeadTransparency_4.mainScript 
	local script = Instance.new('LocalScript', HeadTransparency_4)

	local mouse = game:GetService("Players").LocalPlayer:GetMouse()
	local humanoid = game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid")
	
	local function initiateDrag(frame, callbackFunction)
		local dragging = false
		
		frame.InputBegan:Connect(function(input)
			if input.UserInputType == Enum.UserInputType.MouseButton1 then
				dragging = true
			end
		end)
		
		frame.InputEnded:Connect(function(input)
			if input.UserInputType == Enum.UserInputType.MouseButton1 then
				dragging = false
			end
		end)
		
		frame.InputBegan:Connect(function(input)
			if input.UserInputType == Enum.UserInputType.MouseButton1 then
				local pos = UDim2.new(math.clamp((mouse.X - frame.AbsolutePosition.X) / frame.AbsoluteSize.X, 0, 1), 0, 1, 0)
				frame.slideFrame:TweenSize(pos, Enum.EasingDirection.Out, Enum.EasingStyle.Quad, 0.25, true, callbackFunction(pos.X.Scale))
			end
		end)
		
		game:GetService("UserInputService").InputChanged:Connect(function(input)
			if dragging and input.UserInputType == Enum.UserInputType.MouseMovement then
				local pos = UDim2.new(math.clamp((mouse.X - frame.AbsolutePosition.X) / frame.AbsoluteSize.X, 0, 1), 0, 1, 0)
				frame.slideFrame:TweenSize(pos, Enum.EasingDirection.Out, Enum.EasingStyle.Quad, 0.25, true, callbackFunction(pos.X.Scale))
			end
		end)
	end
	
	initiateDrag(script.Parent, function(value)
		script.Parent.amountValue.Text = tostring(math.floor(value * 100))
		game.Lighting.Brightness = value * 100
	end)
end
coroutine.wrap(LGUW_fake_script)()
local function XJQIS_fake_script() -- TextButton.Dragify 
	local script = Instance.new('LocalScript', TextButton)

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
coroutine.wrap(XJQIS_fake_script)()
local function JWZQPH_fake_script() -- TextButton.LocalScript 
	local script = Instance.new('LocalScript', TextButton)

	local frame = script.Parent.Parent.Frame
	
	script.Parent.MouseButton1Up:Connect(function()
		if frame.Visible == false then
			frame.Visible = true
		else
			frame.Visible = false
		end
	end)
end
coroutine.wrap(JWZQPH_fake_script)()
