local UIS = game:GetService("UserInputService")

local doors = workspace:WaitForChild("Doors")

UIS.InputBegan:Connect(function(I)
	if I.KeyCode == Enum.KeyCode.X then
		doors:Destroy()
	end
end)
