local BlackPopUpShit = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")

BlackPopUpShit.Name = "BlackPopUpShit"
BlackPopUpShit.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
BlackPopUpShit.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Frame.Parent = BlackPopUpShit
Frame.AnchorPoint = Vector2.new(0.5, 0.5)
Frame.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Frame.BorderSizePixel = 0
Frame.Position = UDim2.new(0.5, 0, 0.5, 0)
Frame.Size = UDim2.new(1, 0, 1, 0)
Frame.Visible = false

task.wait(5) -- for how many second you gotta wait before the screen pop ups

Frame.Visible = true
