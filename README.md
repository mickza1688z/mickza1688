# mickza1688
local p=game.Players.LocalPlayer local r=p.Character:WaitForChild("HumanoidRootPart") local t=game:GetService("TweenService") local pos=Vector3.new(100,10,100) t:Create(r,TweenInfo.new(2),{CFrame=CFrame.new(pos)}):Play()
