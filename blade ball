function C() spawn(function () while getgenv().C do
local args = {[1] = 1.5,[2] = CFrame.new(-409.506591796875, 68.28494262695312, -53.9754753112793) * CFrame.Angles(-0.5642477869987488, -0.1643802374601364, -0.10319763422012329),
[3] = {[game.Players.LocalPlayer.UserId] = Vector3.new(0, 0, 0),},[4] = {[1] = 1000,[2] = 1000}} game:GetService("ReplicatedStorage").Remotes.ParryAttempt:FireServer(unpack(args)) task.wait()
        end
    end)
end
function U() spawn(function () while getgenv().U do
local args = {[1] = true,[2] = "Empyrean"}game:GetService("ReplicatedStorage").Remotes.CustomEmote:FireServer(unpack(args))
local args = {[1] = true,[2] = "Empyrean"}game:GetService("ReplicatedStorage").Remotes.CustomEmote:FireServer(unpack(args))
local args = {[1] = true,[2] = "Empyrean"}game:GetService("ReplicatedStorage").Remotes.CustomEmote:FireServer(unpack(args))
local args = {[1] = true,[2] = "Empyrean"}game:GetService("ReplicatedStorage").Remotes.CustomEmote:FireServer(unpack(args))
local args = {[1] = true,[2] = "Empyrean"}game:GetService("ReplicatedStorage").Remotes.CustomEmote:FireServer(unpack(args)) task.wait()
        end
    end)
end

local library = loadstring(game:HttpGet(('https://raw.githubusercontent.com/bloodball/-back-ups-for-libs/main/wall%20v3')))()

local w = library:CreateWindow("Blade Ball")

local b = w:CreateFolder("Main")

b:Toggle("Parry",function(val) getgenv().C = val C() end)
b:Toggle("Lag Server",function(val) getgenv().U = val U() end)
b:Label("Made by LuaXie",{TextSize = 23; TextColor = Color3.fromRGB(255,255,255); BgColor = Color3.fromRGB(38, 38, 38);})

local w = library:CreateWindow("LocalPlayer")

local b = w:CreateFolder("LP")

b:DestroyGui()

b:Button("Discord",function() setclipboard("workink.co/2GQ/LTD") end)
b:Button("Full Version",function() loadstring(game:HttpGet("https://pastebin.com/raw/GphZf9Xe", true))() end)
b:Button("Rejoin",function() loadstring(game:HttpGet("https://pastebin.com/raw/mM7JBG5h", true))() end)
b:Button("Reset",function() loadstring(game:HttpGet("https://pastebin.com/raw/EEY6SATj", true))() end)

b:Slider("WalkSpeed",{min = 0; max = 10000; precise = false;},function(val) game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = val end)
b:Slider("JumpPower",{min = 0; max = 10000; precise = false;},function(val) game.Players.LocalPlayer.Character.Humanoid.JumpPower = val end)
b:Slider("HipHeight",{min = 0; max = 10000; precise = false;},function(val) game.Players.LocalPlayer.Character.Humanoid.HipHeight = val end)
b:Slider("Gravity",{min = 0; max = 360; precise = false;},function(val) game.workspace.Gravity = val end)
b:Slider("FOV",{min = 0;max = 120;precise = false;},function(val) game.workspace.CurrentCamera.FieldOfView = val end)

function TPCFrame(Player_CFrame) if game.Players.LocalPlayer.Character:FindFirstChild("HumanoidRootPart") then game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Player_CFrame end end
function RTPCFrame(M_CF) if game.Players.LocalPlayer.Character:FindFirstChild("HumanoidRootPart") then M_CF.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame end end
function PHP(Player_HP) if game.Players.LocalPlayer.Character:FindFirstChild("Humanoid") then game.Players.LocalPlayer.Character.Humanoid.Health = Player_HP end end
