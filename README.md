**Optional**
**This will set up your game**

local frame = script.Parent
frame.Anchorpoint = Vector2.new(0.5,0.5)
frame.Position = Udim2.new(0.5,0,0.5,0)
script.Parent.Parent.MouseButton1Down:Connect(function()
frame.Visible = true
print("Frame Is Visible")
end)

script.Parent.Parent.Close.MouseButton1Down:Connect(function()
frame.Visible = false
print("Frame Isn't Visible")
end)
