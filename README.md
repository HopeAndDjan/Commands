# Commands
This is a script is where you say something In chat then something happens(executor way/lua)

```lua

local plr = game.Players.LocalPlayer
plr.Chatted:Connect(function(msg)

if msg == "hi" then --- replace to what u want to say
print("test") --- replace with anything you want to happen
end
end)

if you want to make another command do not copy and paste and do different things just do

if msg == "sometimes" then
print("good")
end
end)
