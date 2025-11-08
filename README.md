# Commands
This is a script is where you say something In chat then something happens(executor way/lua)

```lua

local plr = game.Players.LocalPlayer
plr.Chatted:Connect(function(msg)

if msg == "hi" then --- replace to what u want to say
print("test") --- replace with anything you want to happen
end
end)
