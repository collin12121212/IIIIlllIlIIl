-- Gui to Lua
-- Version: 3.2

-- Instances:

local DeluxHub = Instance.new("ScreenGui")
local Main = Instance.new("ImageLabel")
local TabFrame = Instance.new("Frame")
local TabSelector = Instance.new("Frame")
local Local = Instance.new("TextButton")
local RemoteSpy = Instance.new("TextButton")
local Info = Instance.new("TextButton")
local Games = Instance.new("Frame")
local Game = Instance.new("TextButton")
local Server = Instance.new("TextButton")
local Seperator = Instance.new("Frame")
local TabHolder = Instance.new("ImageLabel")
local Server_2 = Instance.new("Frame")
local ControlPanel = Instance.new("Frame")
local Info_2 = Instance.new("TextButton")
local ComingSoon = Instance.new("TextButton")
local ComingSoon_2 = Instance.new("TextButton")
local ComingSoon_3 = Instance.new("TextButton")
local ComingSoon_4 = Instance.new("TextButton")
local Players = Instance.new("TextButton")
local Seperator_2 = Instance.new("Frame")
local Tabs = Instance.new("ImageLabel")
local Info_3 = Instance.new("Frame")
local JID = Instance.new("TextLabel")
local ServerTime = Instance.new("TextLabel")
local GameName = Instance.new("TextLabel")
local PlaceId = Instance.new("TextLabel")
local Players_2 = Instance.new("TextLabel")
local Players_3 = Instance.new("Frame")
local PlayerTab = Instance.new("ScrollingFrame")
local Ori = Instance.new("Frame")
local Naem = Instance.new("TextLabel")
local PFP = Instance.new("ImageLabel")
local TP = Instance.new("TextButton")
local Games_2 = Instance.new("Frame")
local Arsenal = Instance.new("Frame")
local ESP = Instance.new("ImageLabel")
local IEX = Instance.new("TextButton")
local Label = Instance.new("TextLabel")
local Aimbot = Instance.new("ImageLabel")
local IEX_2 = Instance.new("TextButton")
local Label_2 = Instance.new("TextLabel")
local Label_3 = Instance.new("TextLabel")
local Anchor = Instance.new("ImageLabel")
local IEX_3 = Instance.new("TextButton")
local Label_4 = Instance.new("TextLabel")
local TPALL = Instance.new("ImageLabel")
local IEX_4 = Instance.new("TextButton")
local Label_5 = Instance.new("TextLabel")
local Label_6 = Instance.new("TextLabel")
local Noclip = Instance.new("ImageLabel")
local IEX_5 = Instance.new("TextButton")
local Label_7 = Instance.new("TextLabel")
local MM2 = Instance.new("Frame")
local TextLabel = Instance.new("TextLabel")
local FleeTheFacility = Instance.new("Frame")
local TextLabel_2 = Instance.new("TextLabel")
local Unknown = Instance.new("Frame")
local TextLabel_3 = Instance.new("TextLabel")
local Info_4 = Instance.new("Frame")
local ControlPanel_2 = Instance.new("Frame")
local Credits = Instance.new("TextButton")
local ChangeLogs = Instance.new("TextButton")
local Seperator_3 = Instance.new("Frame")
local Settings = Instance.new("TextButton")
local Tabs_2 = Instance.new("ImageLabel")
local Credits_2 = Instance.new("Frame")
local Credit = Instance.new("TextLabel")
local CheckBox = Instance.new("ImageLabel")
local IEX_6 = Instance.new("TextButton")
local o = Instance.new("TextLabel")
local Discord = Instance.new("TextButton")
local Clipped = Instance.new("TextLabel")
local Changelogs = Instance.new("Frame")
local Version = Instance.new("TextLabel")
local ChangeLogs_2 = Instance.new("TextLabel")
local ChangeLogs_3 = Instance.new("TextLabel")
local ChangeLogs_4 = Instance.new("TextLabel")
local ChangeLogs_5 = Instance.new("TextLabel")
local Seperator_4 = Instance.new("Frame")
local ChangeLogs_6 = Instance.new("TextLabel")
local Settings_2 = Instance.new("Frame")
local HubColors = Instance.new("TextButton")
local TextButton = Instance.new("TextButton")
local Colors = Instance.new("ScrollingFrame")
local TextButton_2 = Instance.new("TextButton")
local TextButton_3 = Instance.new("TextButton")
local TextButton_4 = Instance.new("TextButton")
local TextButton_5 = Instance.new("TextButton")
local TextButton_6 = Instance.new("TextButton")
local TextButton_7 = Instance.new("TextButton")
local TextButton_8 = Instance.new("TextButton")
local TextButton_9 = Instance.new("TextButton")
local TextButton_10 = Instance.new("TextButton")
local edit = Instance.new("TextButton")
local Remotespy = Instance.new("Frame")
local Logging = Instance.new("ScrollingFrame")
local Original = Instance.new("TextLabel")
local ControlPanel_3 = Instance.new("Frame")
local ClearLogs = Instance.new("TextButton")
local Seperator_5 = Instance.new("Frame")
local Local_2 = Instance.new("Frame")
local ControlPanel_4 = Instance.new("Frame")
local Movement = Instance.new("TextButton")
local HatExploits = Instance.new("TextButton")
local FEBypass = Instance.new("TextButton")
local AimEsp = Instance.new("TextButton")
local Seperator_6 = Instance.new("Frame")
local Tabs_3 = Instance.new("ImageLabel")
local Hats = Instance.new("Frame")
local Amount = Instance.new("ImageLabel")
local AmountBTN = Instance.new("TextBox")
local Aura = Instance.new("ImageLabel")
local AuraBTN = Instance.new("TextButton")
local Drop = Instance.new("ImageLabel")
local DropBTN = Instance.new("TextButton")
local Kill = Instance.new("ImageLabel")
local KillBTN = Instance.new("TextButton")
local F = Instance.new("TextLabel")
local CheckBox_2 = Instance.new("ImageLabel")
local IEX_7 = Instance.new("TextButton")
local Movement_2 = Instance.new("Frame")
local ClickTp = Instance.new("ImageLabel")
local IEX_8 = Instance.new("TextButton")
local Label_8 = Instance.new("TextLabel")
local Gravity = Instance.new("ImageLabel")
local Button = Instance.new("ImageLabel")
local TextButton_11 = Instance.new("TextButton")
local Label_9 = Instance.new("TextLabel")
local InfJump = Instance.new("ImageLabel")
local IEX_9 = Instance.new("TextButton")
local Label_10 = Instance.new("TextLabel")
local JumpPower = Instance.new("ImageLabel")
local Button_2 = Instance.new("ImageLabel")
local TextButton_12 = Instance.new("TextButton")
local Label_11 = Instance.new("TextLabel")
local Noclip_2 = Instance.new("ImageLabel")
local IEX_10 = Instance.new("TextButton")
local Label_12 = Instance.new("TextLabel")
local WalkSpeed = Instance.new("ImageLabel")
local Button_3 = Instance.new("ImageLabel")
local TextButton_13 = Instance.new("TextButton")
local Label_13 = Instance.new("TextLabel")
local Anchor_2 = Instance.new("ImageLabel")
local IEX_11 = Instance.new("TextButton")
local Label_14 = Instance.new("TextLabel")
local TPALL_2 = Instance.new("ImageLabel")
local IEX_12 = Instance.new("TextButton")
local Label_15 = Instance.new("TextLabel")
local SpeedBypass = Instance.new("ImageLabel")
local IEX_13 = Instance.new("TextButton")
local LName = Instance.new("TextLabel")
local UP = Instance.new("TextLabel")
local DOWN = Instance.new("TextLabel")
local Value = Instance.new("TextLabel")
local Bypass = Instance.new("Frame")
local Bypass_2 = Instance.new("ImageLabel")
local FEBypass_2 = Instance.new("TextButton")
local Req = Instance.new("TextLabel")
local TextLabel_4 = Instance.new("TextLabel")
local AimEsp_2 = Instance.new("Frame")
local Aimbot_2 = Instance.new("TextButton")
local chams = Instance.new("TextButton")
local TextLabel_5 = Instance.new("TextLabel")
local TextLabel_6 = Instance.new("TextLabel")
local xray = Instance.new("TextButton")
local Top = Instance.new("ImageLabel")
local Minimize = Instance.new("TextButton")
local Delux = Instance.new("TextLabel")
local Hub = Instance.new("TextLabel")
local Loader = Instance.new("ImageLabel")
local Logo = Instance.new("ImageLabel")

--Properties:

DeluxHub.Name = "DeluxHub"
DeluxHub.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
DeluxHub.ResetOnSpawn = false

Main.Name = "Main"
Main.Parent = DeluxHub
Main.AnchorPoint = Vector2.new(0.5, 0.5)
Main.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Main.BackgroundTransparency = 1.000
Main.Position = UDim2.new(0.233719245, 0, 0.407223791, 0)
Main.Size = UDim2.new(0, 490, 0, 217)
Main.Image = "rbxassetid://3570695787"
Main.ImageColor3 = Color3.fromRGB(40, 40, 40)
Main.ScaleType = Enum.ScaleType.Slice
Main.SliceCenter = Rect.new(100, 100, 100, 100)
Main.SliceScale = 0.120

TabFrame.Name = "TabFrame"
TabFrame.Parent = Main
TabFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TabFrame.BackgroundTransparency = 1.000
TabFrame.BorderSizePixel = 0
TabFrame.Position = UDim2.new(0, 0, 0.103860192, 0)
TabFrame.Size = UDim2.new(0, 490, 0, 195)

TabSelector.Name = "TabSelector"
TabSelector.Parent = TabFrame
TabSelector.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
TabSelector.BorderSizePixel = 0
TabSelector.Position = UDim2.new(0, 0, 0.00730113499, 0)
TabSelector.Size = UDim2.new(0, 489, 0, 20)

Local.Name = "Local"
Local.Parent = TabSelector
Local.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Local.BackgroundTransparency = 1.000
Local.BorderSizePixel = 0
Local.Size = UDim2.new(0, 77, 0, 20)
Local.Font = Enum.Font.SourceSans
Local.Text = "Local"
Local.TextColor3 = Color3.fromRGB(255, 255, 255)
Local.TextSize = 25.000

RemoteSpy.Name = "RemoteSpy"
RemoteSpy.Parent = TabSelector
RemoteSpy.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
RemoteSpy.BackgroundTransparency = 1.000
RemoteSpy.BorderSizePixel = 0
RemoteSpy.Position = UDim2.new(0.157464206, 0, 0, 0)
RemoteSpy.Size = UDim2.new(0, 105, 0, 20)
RemoteSpy.Font = Enum.Font.SourceSans
RemoteSpy.Text = "Remotespy"
RemoteSpy.TextColor3 = Color3.fromRGB(255, 255, 255)
RemoteSpy.TextSize = 25.000

Info.Name = "Info"
Info.Parent = TabSelector
Info.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Info.BackgroundTransparency = 1.000
Info.BorderSizePixel = 0
Info.Position = UDim2.new(0.840238929, 0, 0.00193023682, 0)
Info.Size = UDim2.new(0, 78, 0, 19)
Info.Font = Enum.Font.SourceSans
Info.Text = "Extra"
Info.TextColor3 = Color3.fromRGB(255, 255, 255)
Info.TextSize = 25.000

Games.Name = "Games"
Games.Parent = TabSelector
Games.BackgroundColor3 = Color3.fromRGB(43, 43, 43)
Games.BorderSizePixel = 0
Games.Size = UDim2.new(0, 488, 0, 19)
Games.ZIndex = 0

Game.Name = "Game"
Game.Parent = Games
Game.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Game.BackgroundTransparency = 1.000
Game.BorderSizePixel = 0
Game.Position = UDim2.new(0.527925849, 0, 0, 0)
Game.Size = UDim2.new(0, 153, 0, 20)
Game.Font = Enum.Font.SourceSans
Game.Text = "Game Name"
Game.TextColor3 = Color3.fromRGB(255, 255, 255)
Game.TextSize = 25.000
Game.TextWrapped = true
Game.TextXAlignment = Enum.TextXAlignment.Left

Server.Name = "Server"
Server.Parent = TabSelector
Server.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Server.BackgroundTransparency = 1.000
Server.BorderSizePixel = 0
Server.Position = UDim2.new(0.372188121, 0, 0, 0)
Server.Size = UDim2.new(0, 69, 0, 20)
Server.Font = Enum.Font.SourceSans
Server.Text = "Server"
Server.TextColor3 = Color3.fromRGB(255, 255, 255)
Server.TextSize = 25.000
Server.TextWrapped = true

Seperator.Name = "Seperator"
Seperator.Parent = TabFrame
Seperator.BackgroundColor3 = Color3.fromRGB(28, 28, 28)
Seperator.BorderSizePixel = 0
Seperator.Position = UDim2.new(0, 0, -0.00275730225, 0)
Seperator.Size = UDim2.new(0, 490, 0, 2)

TabHolder.Name = "TabHolder"
TabHolder.Parent = TabFrame
TabHolder.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
TabHolder.BackgroundTransparency = 1.000
TabHolder.Position = UDim2.new(0, 0, 0.109865159, 0)
TabHolder.Size = UDim2.new(0, 490, 0, 173)
TabHolder.Image = "rbxassetid://3570695787"
TabHolder.ImageColor3 = Color3.fromRGB(35, 35, 35)
TabHolder.ScaleType = Enum.ScaleType.Slice
TabHolder.SliceCenter = Rect.new(100, 100, 100, 100)
TabHolder.SliceScale = 0.120

Server_2.Name = "Server"
Server_2.Parent = TabHolder
Server_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Server_2.BackgroundTransparency = 1.000
Server_2.BorderSizePixel = 0
Server_2.Size = UDim2.new(0, 490, 0, 173)
Server_2.Visible = false

ControlPanel.Name = "ControlPanel"
ControlPanel.Parent = Server_2
ControlPanel.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
ControlPanel.BackgroundTransparency = 1.000
ControlPanel.BorderSizePixel = 0
ControlPanel.Size = UDim2.new(0, 100, 0, 173)

Info_2.Name = "Info"
Info_2.Parent = ControlPanel
Info_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Info_2.BackgroundTransparency = 1.000
Info_2.BorderSizePixel = 0
Info_2.Size = UDim2.new(0, 100, 0, 28)
Info_2.Font = Enum.Font.SourceSans
Info_2.Text = "Info"
Info_2.TextColor3 = Color3.fromRGB(255, 255, 255)
Info_2.TextSize = 25.000

ComingSoon.Name = "Coming Soon"
ComingSoon.Parent = ControlPanel
ComingSoon.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ComingSoon.BackgroundTransparency = 1.000
ComingSoon.BorderSizePixel = 0
ComingSoon.Position = UDim2.new(0, 0, 0.333333284, 0)
ComingSoon.Size = UDim2.new(0, 100, 0, 28)
ComingSoon.Visible = false
ComingSoon.Font = Enum.Font.SourceSans
ComingSoon.TextColor3 = Color3.fromRGB(255, 255, 255)
ComingSoon.TextSize = 25.000

ComingSoon_2.Name = "Coming Soon"
ComingSoon_2.Parent = ControlPanel
ComingSoon_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ComingSoon_2.BackgroundTransparency = 1.000
ComingSoon_2.BorderSizePixel = 0
ComingSoon_2.Position = UDim2.new(0, 0, 0.5, 0)
ComingSoon_2.Size = UDim2.new(0, 100, 0, 28)
ComingSoon_2.Visible = false
ComingSoon_2.Font = Enum.Font.SourceSans
ComingSoon_2.TextColor3 = Color3.fromRGB(255, 255, 255)
ComingSoon_2.TextSize = 25.000

ComingSoon_3.Name = "Coming Soon"
ComingSoon_3.Parent = ControlPanel
ComingSoon_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ComingSoon_3.BackgroundTransparency = 1.000
ComingSoon_3.BorderSizePixel = 0
ComingSoon_3.Position = UDim2.new(0, 0, 0.666666746, 0)
ComingSoon_3.Size = UDim2.new(0, 100, 0, 28)
ComingSoon_3.Visible = false
ComingSoon_3.Font = Enum.Font.SourceSans
ComingSoon_3.TextColor3 = Color3.fromRGB(255, 255, 255)
ComingSoon_3.TextSize = 25.000

ComingSoon_4.Name = "Coming Soon"
ComingSoon_4.Parent = ControlPanel
ComingSoon_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ComingSoon_4.BackgroundTransparency = 1.000
ComingSoon_4.BorderSizePixel = 0
ComingSoon_4.Position = UDim2.new(0, 0, 0.833333254, 0)
ComingSoon_4.Size = UDim2.new(0, 100, 0, 28)
ComingSoon_4.Visible = false
ComingSoon_4.Font = Enum.Font.SourceSans
ComingSoon_4.TextColor3 = Color3.fromRGB(255, 255, 255)
ComingSoon_4.TextSize = 25.000

Players.Name = "Players"
Players.Parent = ControlPanel
Players.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Players.BackgroundTransparency = 1.000
Players.BorderSizePixel = 0
Players.Position = UDim2.new(0, 0, 0.166666731, 0)
Players.Size = UDim2.new(0, 100, 0, 28)
Players.Font = Enum.Font.SourceSans
Players.Text = "Players"
Players.TextColor3 = Color3.fromRGB(255, 255, 255)
Players.TextSize = 25.000
Players.TextWrapped = true

Seperator_2.Name = "Seperator"
Seperator_2.Parent = Server_2
Seperator_2.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
Seperator_2.BorderColor3 = Color3.fromRGB(28, 28, 28)
Seperator_2.BorderSizePixel = 0
Seperator_2.Position = UDim2.new(0.20408164, 0, 0, 0)
Seperator_2.Size = UDim2.new(0, 2, 0, 172)

Tabs.Name = "Tabs"
Tabs.Parent = Server_2
Tabs.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Tabs.BackgroundTransparency = 1.000
Tabs.Position = UDim2.new(0.208163261, 0, 0, 0)
Tabs.Size = UDim2.new(0, 388, 0, 172)
Tabs.Image = "rbxassetid://3570695787"
Tabs.ImageColor3 = Color3.fromRGB(40, 40, 40)
Tabs.ScaleType = Enum.ScaleType.Slice
Tabs.SliceCenter = Rect.new(100, 100, 100, 100)
Tabs.SliceScale = 0.120

Info_3.Name = "Info"
Info_3.Parent = Tabs
Info_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Info_3.BackgroundTransparency = 1.000
Info_3.BorderSizePixel = 0
Info_3.Position = UDim2.new(0, 0, 0.00581395347, 0)
Info_3.Size = UDim2.new(0, 388, 0, 172)
Info_3.Visible = false

JID.Name = "JID"
JID.Parent = Info_3
JID.Active = true
JID.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
JID.BackgroundTransparency = 1.000
JID.BorderSizePixel = 0
JID.Position = UDim2.new(-0.00577318668, 0, 0.022326, 0)
JID.Selectable = true
JID.Size = UDim2.new(0, 388, 0, 28)
JID.Font = Enum.Font.SourceSans
JID.Text = "JobId"
JID.TextColor3 = Color3.fromRGB(255, 255, 255)
JID.TextSize = 25.000

ServerTime.Name = "ServerTime"
ServerTime.Parent = Info_3
ServerTime.Active = true
ServerTime.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ServerTime.BackgroundTransparency = 1.000
ServerTime.BorderSizePixel = 0
ServerTime.Position = UDim2.new(-0.00577318668, 0, 0.1841757, 0)
ServerTime.Selectable = true
ServerTime.Size = UDim2.new(0, 388, 0, 28)
ServerTime.Font = Enum.Font.SourceSans
ServerTime.Text = "ServerTime"
ServerTime.TextColor3 = Color3.fromRGB(255, 255, 255)
ServerTime.TextSize = 25.000

GameName.Name = "GameName"
GameName.Parent = Info_3
GameName.Active = true
GameName.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
GameName.BackgroundTransparency = 1.000
GameName.BorderSizePixel = 0
GameName.Position = UDim2.new(-0.00577318668, 0, 0.357586145, 0)
GameName.Selectable = true
GameName.Size = UDim2.new(0, 388, 0, 28)
GameName.Font = Enum.Font.SourceSans
GameName.Text = "GameName"
GameName.TextColor3 = Color3.fromRGB(255, 255, 255)
GameName.TextSize = 25.000

PlaceId.Name = "PlaceId"
PlaceId.Parent = Info_3
PlaceId.Active = true
PlaceId.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
PlaceId.BackgroundTransparency = 1.000
PlaceId.BorderSizePixel = 0
PlaceId.Position = UDim2.new(-0.00577318668, 0, 0.519435823, 0)
PlaceId.Selectable = true
PlaceId.Size = UDim2.new(0, 388, 0, 28)
PlaceId.Font = Enum.Font.SourceSans
PlaceId.Text = "PlaceId"
PlaceId.TextColor3 = Color3.fromRGB(255, 255, 255)
PlaceId.TextSize = 25.000

Players_2.Name = "Players"
Players_2.Parent = Info_3
Players_2.Active = true
Players_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Players_2.BackgroundTransparency = 1.000
Players_2.BorderSizePixel = 0
Players_2.Position = UDim2.new(0, 0, 0.678361773, 0)
Players_2.Selectable = true
Players_2.Size = UDim2.new(0, 387, 0, 28)
Players_2.Font = Enum.Font.SourceSans
Players_2.Text = "Players"
Players_2.TextColor3 = Color3.fromRGB(255, 255, 255)
Players_2.TextSize = 25.000

Players_3.Name = "Players"
Players_3.Parent = Tabs
Players_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Players_3.BackgroundTransparency = 1.000
Players_3.BorderColor3 = Color3.fromRGB(27, 42, 53)
Players_3.BorderSizePixel = 0
Players_3.ClipsDescendants = true
Players_3.Position = UDim2.new(0, 0, 0.00581395347, 0)
Players_3.Size = UDim2.new(0, 388, 0, 172)
Players_3.Visible = false

PlayerTab.Name = "PlayerTab"
PlayerTab.Parent = Players_3
PlayerTab.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
PlayerTab.BackgroundTransparency = 1.000
PlayerTab.BorderSizePixel = 0
PlayerTab.Position = UDim2.new(0, 0, 0.00581395347, 0)
PlayerTab.Selectable = false
PlayerTab.Size = UDim2.new(0, 388, 0, 172)
PlayerTab.CanvasSize = UDim2.new(0, 0, 200, 0)
PlayerTab.ScrollBarThickness = 7

Ori.Name = "Ori"
Ori.Parent = PlayerTab
Ori.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Ori.BackgroundTransparency = 1.000
Ori.Size = UDim2.new(0, 387, 0, 45)

Naem.Name = "Naem"
Naem.Parent = Ori
Naem.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Naem.BackgroundTransparency = 1.000
Naem.BorderSizePixel = 0
Naem.Size = UDim2.new(0, 149, 0, 45)
Naem.Font = Enum.Font.SourceSans
Naem.Text = "Name"
Naem.TextColor3 = Color3.fromRGB(255, 255, 255)
Naem.TextScaled = true
Naem.TextSize = 25.000
Naem.TextWrapped = true

PFP.Name = "PFP"
PFP.Parent = Ori
PFP.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
PFP.BackgroundTransparency = 1.000
PFP.BorderSizePixel = 0
PFP.Position = UDim2.new(0.385012925, 0, 0, 0)
PFP.Size = UDim2.new(0, 45, 0, 45)
PFP.Image = "rbxasset://textures/ui/GuiImagePlaceholder.png"

TP.Name = "TP"
TP.Parent = Ori
TP.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TP.BackgroundTransparency = 1.000
TP.BorderSizePixel = 0
TP.Position = UDim2.new(0.50129199, 0, 0, 0)
TP.Size = UDim2.new(0, 184, 0, 45)
TP.Font = Enum.Font.SourceSans
TP.Text = "Teleport To"
TP.TextColor3 = Color3.fromRGB(255, 255, 255)
TP.TextSize = 25.000

Games_2.Name = "Games"
Games_2.Parent = TabHolder
Games_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Games_2.BackgroundTransparency = 1.000
Games_2.BorderSizePixel = 0
Games_2.Size = UDim2.new(0, 488, 0, 173)

Arsenal.Name = "Arsenal"
Arsenal.Parent = Games_2
Arsenal.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Arsenal.BackgroundTransparency = 1.000
Arsenal.BorderSizePixel = 0
Arsenal.Size = UDim2.new(0, 489, 0, 173)
Arsenal.Visible = false

ESP.Name = "ESP"
ESP.Parent = Arsenal
ESP.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
ESP.BackgroundTransparency = 1.000
ESP.Position = UDim2.new(0.0221580565, 0, 0.0982123315, 0)
ESP.Size = UDim2.new(0, 54, 0, 19)
ESP.Image = "rbxassetid://3570695787"
ESP.ImageColor3 = Color3.fromRGB(50, 50, 50)
ESP.ScaleType = Enum.ScaleType.Slice
ESP.SliceCenter = Rect.new(100, 100, 100, 100)
ESP.SliceScale = 0.120

IEX.Name = "IEX"
IEX.Parent = ESP
IEX.BackgroundColor3 = Color3.fromRGB(35, 35, 35)
IEX.BorderSizePixel = 0
IEX.Position = UDim2.new(0.476999998, 0, -0.119999997, 0)
IEX.Size = UDim2.new(0, 29, 0, 23)
IEX.Font = Enum.Font.SourceSans
IEX.Text = "OFF"
IEX.TextColor3 = Color3.fromRGB(255, 0, 0)
IEX.TextSize = 14.000

Label.Name = "Label"
Label.Parent = ESP
Label.Active = true
Label.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Label.BackgroundTransparency = 1.000
Label.BorderSizePixel = 0
Label.Position = UDim2.new(1.0984329, 0, 0, 0)
Label.Selectable = true
Label.Size = UDim2.new(0, 39, 0, 20)
Label.Font = Enum.Font.SourceSans
Label.Text = "ESP"
Label.TextColor3 = Color3.fromRGB(255, 255, 255)
Label.TextSize = 25.000
Label.TextWrapped = true

Aimbot.Name = "Aimbot"
Aimbot.Parent = Arsenal
Aimbot.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Aimbot.BackgroundTransparency = 1.000
Aimbot.Position = UDim2.new(0.0221580565, 0, 0.277403086, 0)
Aimbot.Size = UDim2.new(0, 54, 0, 19)
Aimbot.Image = "rbxassetid://3570695787"
Aimbot.ImageColor3 = Color3.fromRGB(50, 50, 50)
Aimbot.ScaleType = Enum.ScaleType.Slice
Aimbot.SliceCenter = Rect.new(100, 100, 100, 100)
Aimbot.SliceScale = 0.120

IEX_2.Name = "IEX"
IEX_2.Parent = Aimbot
IEX_2.BackgroundColor3 = Color3.fromRGB(35, 35, 35)
IEX_2.BorderSizePixel = 0
IEX_2.Position = UDim2.new(0.476999998, 0, -0.119999997, 0)
IEX_2.Size = UDim2.new(0, 29, 0, 23)
IEX_2.Font = Enum.Font.SourceSans
IEX_2.Text = "OFF"
IEX_2.TextColor3 = Color3.fromRGB(255, 0, 0)
IEX_2.TextSize = 14.000

Label_2.Name = "Label"
Label_2.Parent = Aimbot
Label_2.Active = true
Label_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Label_2.BackgroundTransparency = 1.000
Label_2.BorderSizePixel = 0
Label_2.Position = UDim2.new(1.06139588, 0, 0, 0)
Label_2.Selectable = true
Label_2.Size = UDim2.new(0, 74, 0, 20)
Label_2.Font = Enum.Font.SourceSans
Label_2.Text = "Aimbot"
Label_2.TextColor3 = Color3.fromRGB(255, 255, 255)
Label_2.TextSize = 25.000
Label_2.TextWrapped = true

Label_3.Name = "Label"
Label_3.Parent = Aimbot
Label_3.Active = true
Label_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Label_3.BackgroundTransparency = 1.000
Label_3.BorderSizePixel = 0
Label_3.Position = UDim2.new(0.950284719, 0, 1.05263162, 0)
Label_3.Selectable = true
Label_3.Size = UDim2.new(0, 85, 0, 20)
Label_3.Font = Enum.Font.SourceSans
Label_3.Text = "Hold 'e' to aim"
Label_3.TextColor3 = Color3.fromRGB(255, 255, 255)
Label_3.TextSize = 15.000
Label_3.TextWrapped = true

Anchor.Name = "Anchor"
Anchor.Parent = Arsenal
Anchor.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Anchor.BackgroundTransparency = 1.000
Anchor.Position = UDim2.new(0.328906506, 0, 0.103992641, 0)
Anchor.Size = UDim2.new(0, 54, 0, 19)
Anchor.Image = "rbxassetid://3570695787"
Anchor.ImageColor3 = Color3.fromRGB(50, 50, 50)
Anchor.ScaleType = Enum.ScaleType.Slice
Anchor.SliceCenter = Rect.new(100, 100, 100, 100)
Anchor.SliceScale = 0.120

IEX_3.Name = "IEX"
IEX_3.Parent = Anchor
IEX_3.BackgroundColor3 = Color3.fromRGB(35, 35, 35)
IEX_3.BorderSizePixel = 0
IEX_3.Position = UDim2.new(0.476999998, 0, -0.119999997, 0)
IEX_3.Size = UDim2.new(0, 29, 0, 23)
IEX_3.Font = Enum.Font.SourceSans
IEX_3.Text = "OFF"
IEX_3.TextColor3 = Color3.fromRGB(255, 0, 0)
IEX_3.TextSize = 14.000

Label_4.Name = "Label"
Label_4.Parent = Anchor
Label_4.Active = true
Label_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Label_4.BackgroundTransparency = 1.000
Label_4.BorderSizePixel = 0
Label_4.Position = UDim2.new(1.0058403, 0, -0.0526315793, 0)
Label_4.Selectable = true
Label_4.Size = UDim2.new(0, 74, 0, 20)
Label_4.Font = Enum.Font.SourceSans
Label_4.Text = "Anchor"
Label_4.TextColor3 = Color3.fromRGB(255, 255, 255)
Label_4.TextSize = 25.000
Label_4.TextWrapped = true

TPALL.Name = "TPALL"
TPALL.Parent = Arsenal
TPALL.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TPALL.BackgroundTransparency = 1.000
TPALL.Position = UDim2.new(0.328906506, 0, 0.283183396, 0)
TPALL.Size = UDim2.new(0, 54, 0, 19)
TPALL.Image = "rbxassetid://3570695787"
TPALL.ImageColor3 = Color3.fromRGB(50, 50, 50)
TPALL.ScaleType = Enum.ScaleType.Slice
TPALL.SliceCenter = Rect.new(100, 100, 100, 100)
TPALL.SliceScale = 0.120

IEX_4.Name = "IEX"
IEX_4.Parent = TPALL
IEX_4.BackgroundColor3 = Color3.fromRGB(35, 35, 35)
IEX_4.BorderSizePixel = 0
IEX_4.Position = UDim2.new(0.476999998, 0, -0.119999997, 0)
IEX_4.Size = UDim2.new(0, 29, 0, 23)
IEX_4.Font = Enum.Font.SourceSans
IEX_4.Text = "OFF"
IEX_4.TextColor3 = Color3.fromRGB(255, 0, 0)
IEX_4.TextSize = 14.000

Label_5.Name = "Label"
Label_5.Parent = TPALL
Label_5.Active = true
Label_5.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Label_5.BackgroundTransparency = 1.000
Label_5.BorderSizePixel = 0
Label_5.Position = UDim2.new(1.0058403, 0, -0.0526315793, 0)
Label_5.Selectable = true
Label_5.Size = UDim2.new(0, 105, 0, 20)
Label_5.Font = Enum.Font.SourceSans
Label_5.Text = "Teleport All"
Label_5.TextColor3 = Color3.fromRGB(255, 255, 255)
Label_5.TextSize = 25.000
Label_5.TextWrapped = true

Label_6.Name = "Label"
Label_6.Parent = Arsenal
Label_6.Active = true
Label_6.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Label_6.BackgroundTransparency = 1.000
Label_6.BorderSizePixel = 0
Label_6.Position = UDim2.new(0.0398099609, 0, 0.606936395, 0)
Label_6.Selectable = true
Label_6.Size = UDim2.new(0, 458, 0, 55)
Label_6.Font = Enum.Font.SourceSans
Label_6.Text = "PS: it doesnt acually work yet i still have to script it im just testing if gamecheck works properly"
Label_6.TextColor3 = Color3.fromRGB(255, 255, 255)
Label_6.TextSize = 25.000
Label_6.TextWrapped = true

Noclip.Name = "Noclip"
Noclip.Parent = Arsenal
Noclip.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Noclip.BackgroundTransparency = 1.000
Noclip.Position = UDim2.new(0.676554799, 0, 0.0808712542, 0)
Noclip.Size = UDim2.new(0, 54, 0, 19)
Noclip.Image = "rbxassetid://3570695787"
Noclip.ImageColor3 = Color3.fromRGB(50, 50, 50)
Noclip.ScaleType = Enum.ScaleType.Slice
Noclip.SliceCenter = Rect.new(100, 100, 100, 100)
Noclip.SliceScale = 0.120

IEX_5.Name = "IEX"
IEX_5.Parent = Noclip
IEX_5.BackgroundColor3 = Color3.fromRGB(35, 35, 35)
IEX_5.BorderSizePixel = 0
IEX_5.Position = UDim2.new(0.476999998, 0, -0.119999997, 0)
IEX_5.Size = UDim2.new(0, 29, 0, 23)
IEX_5.Font = Enum.Font.SourceSans
IEX_5.Text = "OFF"
IEX_5.TextColor3 = Color3.fromRGB(255, 0, 0)
IEX_5.TextSize = 14.000

Label_7.Name = "Label"
Label_7.Parent = Noclip
Label_7.Active = true
Label_7.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Label_7.BackgroundTransparency = 1.000
Label_7.BorderSizePixel = 0
Label_7.Position = UDim2.new(1.00583959, 0, 0, 0)
Label_7.Selectable = true
Label_7.Size = UDim2.new(0, 67, 0, 20)
Label_7.Font = Enum.Font.SourceSans
Label_7.Text = "NoClip"
Label_7.TextColor3 = Color3.fromRGB(255, 255, 255)
Label_7.TextSize = 25.000
Label_7.TextWrapped = true

MM2.Name = "MM2"
MM2.Parent = Games_2
MM2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
MM2.BackgroundTransparency = 1.000
MM2.BorderSizePixel = 0
MM2.Size = UDim2.new(0, 489, 0, 173)
MM2.Visible = false

TextLabel.Parent = MM2
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.BorderSizePixel = 0
TextLabel.Position = UDim2.new(0.114519425, 0, 0.300578028, 0)
TextLabel.Size = UDim2.new(0, 400, 0, 50)
TextLabel.Font = Enum.Font.SourceSans
TextLabel.Text = "i didnt add anything yet im just testing if game stuffs work also this game is very laggy"
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.TextScaled = true
TextLabel.TextSize = 25.000
TextLabel.TextWrapped = true

FleeTheFacility.Name = "FleeTheFacility"
FleeTheFacility.Parent = Games_2
FleeTheFacility.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
FleeTheFacility.BackgroundTransparency = 1.000
FleeTheFacility.BorderSizePixel = 0
FleeTheFacility.Size = UDim2.new(0, 489, 0, 173)
FleeTheFacility.Visible = false

TextLabel_2.Parent = FleeTheFacility
TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.BackgroundTransparency = 1.000
TextLabel_2.BorderSizePixel = 0
TextLabel_2.Position = UDim2.new(0.114519425, 0, 0.300578028, 0)
TextLabel_2.Size = UDim2.new(0, 400, 0, 50)
TextLabel_2.Font = Enum.Font.SourceSans
TextLabel_2.Text = "i didnt add anything yet im just testing if game stuffs work"
TextLabel_2.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.TextScaled = true
TextLabel_2.TextSize = 25.000
TextLabel_2.TextWrapped = true

Unknown.Name = "Unknown"
Unknown.Parent = Games_2
Unknown.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Unknown.BackgroundTransparency = 1.000
Unknown.BorderSizePixel = 0
Unknown.Size = UDim2.new(0, 489, 0, 173)
Unknown.Visible = false

TextLabel_3.Parent = Unknown
TextLabel_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_3.BackgroundTransparency = 1.000
TextLabel_3.BorderSizePixel = 0
TextLabel_3.Position = UDim2.new(0.114519425, 0, 0.300578028, 0)
TextLabel_3.Size = UDim2.new(0, 400, 0, 50)
TextLabel_3.Font = Enum.Font.SourceSans
TextLabel_3.Text = "?????????????"
TextLabel_3.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_3.TextScaled = true
TextLabel_3.TextSize = 25.000
TextLabel_3.TextWrapped = true

Info_4.Name = "Info"
Info_4.Parent = TabHolder
Info_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Info_4.BackgroundTransparency = 1.000
Info_4.BorderSizePixel = 0
Info_4.Position = UDim2.new(-0.00204081624, 0, 0, 0)
Info_4.Size = UDim2.new(0, 491, 0, 173)

ControlPanel_2.Name = "ControlPanel"
ControlPanel_2.Parent = Info_4
ControlPanel_2.BackgroundColor3 = Color3.fromRGB(42, 42, 42)
ControlPanel_2.BackgroundTransparency = 1.000
ControlPanel_2.BorderSizePixel = 0
ControlPanel_2.Position = UDim2.new(0.00203659688, 0, 0, 0)
ControlPanel_2.Size = UDim2.new(0, 113, 0, 173)

Credits.Name = "Credits"
Credits.Parent = ControlPanel_2
Credits.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Credits.BackgroundTransparency = 1.000
Credits.BorderSizePixel = 0
Credits.Position = UDim2.new(-6.75167655e-08, 0, 0, 0)
Credits.Size = UDim2.new(0, 113, 0, 35)
Credits.Font = Enum.Font.SourceSans
Credits.Text = "Credits"
Credits.TextColor3 = Color3.fromRGB(255, 255, 255)
Credits.TextSize = 25.000

ChangeLogs.Name = "ChangeLogs"
ChangeLogs.Parent = ControlPanel_2
ChangeLogs.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ChangeLogs.BackgroundTransparency = 1.000
ChangeLogs.BorderSizePixel = 0
ChangeLogs.Position = UDim2.new(-1.35033531e-07, 0, 0.196531788, 0)
ChangeLogs.Size = UDim2.new(0, 113, 0, 35)
ChangeLogs.Font = Enum.Font.SourceSans
ChangeLogs.Text = "Changelogs"
ChangeLogs.TextColor3 = Color3.fromRGB(255, 255, 255)
ChangeLogs.TextSize = 25.000

Seperator_3.Name = "Seperator"
Seperator_3.Parent = ControlPanel_2
Seperator_3.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
Seperator_3.BorderColor3 = Color3.fromRGB(28, 28, 28)
Seperator_3.BorderSizePixel = 0
Seperator_3.Position = UDim2.new(1.01317549, 0, 0, 0)
Seperator_3.Size = UDim2.new(0, 2, 0, 172)

Settings.Name = "Settings"
Settings.Parent = ControlPanel_2
Settings.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Settings.BackgroundTransparency = 1.000
Settings.BorderSizePixel = 0
Settings.Position = UDim2.new(-6.75167655e-08, 0, 0.393063575, 0)
Settings.Size = UDim2.new(0, 113, 0, 35)
Settings.Font = Enum.Font.SourceSans
Settings.Text = "Settings"
Settings.TextColor3 = Color3.fromRGB(255, 255, 255)
Settings.TextSize = 25.000

Tabs_2.Name = "Tabs"
Tabs_2.Parent = Info_4
Tabs_2.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
Tabs_2.BackgroundTransparency = 1.000
Tabs_2.Position = UDim2.new(0.236252546, 0, 0.00578034669, 0)
Tabs_2.Size = UDim2.new(0, 375, 0, 171)
Tabs_2.Image = "rbxassetid://3570695787"
Tabs_2.ImageColor3 = Color3.fromRGB(40, 40, 40)
Tabs_2.ScaleType = Enum.ScaleType.Slice
Tabs_2.SliceCenter = Rect.new(100, 100, 100, 100)
Tabs_2.SliceScale = 0.120

Credits_2.Name = "Credits"
Credits_2.Parent = Tabs_2
Credits_2.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
Credits_2.BackgroundTransparency = 1.000
Credits_2.BorderSizePixel = 0
Credits_2.Position = UDim2.new(-0.00204085279, 0, 0, 0)
Credits_2.Size = UDim2.new(0, 375, 0, 173)
Credits_2.Visible = false

Credit.Name = "Credit"
Credit.Parent = Credits_2
Credit.Active = true
Credit.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Credit.BackgroundTransparency = 1.000
Credit.BorderSizePixel = 0
Credit.Position = UDim2.new(0.0576679185, 0, 0.092485562, 0)
Credit.Selectable = true
Credit.Size = UDim2.new(0, 335, 0, 107)
Credit.Font = Enum.Font.SourceSans
Credit.Text = "Yes#3963 and Some Person#7173 made the entire hub"
Credit.TextColor3 = Color3.fromRGB(255, 255, 255)
Credit.TextScaled = true
Credit.TextSize = 50.000
Credit.TextWrapped = true

CheckBox.Name = "CheckBox"
CheckBox.Parent = Credits_2
CheckBox.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
CheckBox.BackgroundTransparency = 1.000
CheckBox.Position = UDim2.new(0.0553542897, 0, 0.786073625, 0)
CheckBox.Size = UDim2.new(0, 54, 0, 19)
CheckBox.Image = "rbxassetid://3570695787"
CheckBox.ImageColor3 = Color3.fromRGB(50, 50, 50)
CheckBox.ScaleType = Enum.ScaleType.Slice
CheckBox.SliceCenter = Rect.new(100, 100, 100, 100)
CheckBox.SliceScale = 0.120

IEX_6.Name = "IEX"
IEX_6.Parent = CheckBox
IEX_6.BackgroundColor3 = Color3.fromRGB(35, 35, 35)
IEX_6.BorderSizePixel = 0
IEX_6.Position = UDim2.new(0.476999998, 0, -0.119999997, 0)
IEX_6.Size = UDim2.new(0, 29, 0, 23)
IEX_6.Font = Enum.Font.SourceSans
IEX_6.Text = "OFF"
IEX_6.TextColor3 = Color3.fromRGB(255, 0, 0)
IEX_6.TextSize = 14.000

o.Name = ":o"
o.Parent = CheckBox
o.Active = true
o.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
o.BackgroundTransparency = 1.000
o.BorderSizePixel = 0
o.Position = UDim2.new(-2.02345872, 0, -1.4250071, 0)
o.Selectable = true
o.Size = UDim2.new(0, 173, 0, 20)
o.Font = Enum.Font.SourceSans
o.Text = "This does nothing"
o.TextColor3 = Color3.fromRGB(255, 255, 255)
o.TextSize = 25.000
o.TextWrapped = true

Discord.Name = "Discord"
Discord.Parent = Credits_2
Discord.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Discord.BackgroundTransparency = 1.000
Discord.BorderSizePixel = 0
Discord.Position = UDim2.new(0.789529443, 0, 0.78612715, 0)
Discord.Size = UDim2.new(0, 66, 0, 20)
Discord.Font = Enum.Font.SourceSans
Discord.Text = "Discord"
Discord.TextColor3 = Color3.fromRGB(255, 255, 255)
Discord.TextSize = 25.000
Discord.TextWrapped = true

Clipped.Name = "Clipped"
Clipped.Parent = Discord
Clipped.Active = true
Clipped.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Clipped.BackgroundTransparency = 1.000
Clipped.BorderSizePixel = 0
Clipped.Position = UDim2.new(-2.66487288, 0, 0.0504866354, 0)
Clipped.Selectable = true
Clipped.Size = UDim2.new(0, 175, 0, 19)
Clipped.Font = Enum.Font.SourceSans
Clipped.Text = "Copied to clipboard!"
Clipped.TextColor3 = Color3.fromRGB(255, 255, 255)
Clipped.TextSize = 20.000
Clipped.TextWrapped = true

Changelogs.Name = "Changelogs"
Changelogs.Parent = Tabs_2
Changelogs.BackgroundColor3 = Color3.fromRGB(43, 43, 43)
Changelogs.BackgroundTransparency = 1.000
Changelogs.BorderSizePixel = 0
Changelogs.Position = UDim2.new(-0.00204085279, 0, 0, 0)
Changelogs.Size = UDim2.new(0, 375, 0, 173)
Changelogs.Visible = false

Version.Name = "Version"
Version.Parent = Changelogs
Version.Active = true
Version.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Version.BackgroundTransparency = 1.000
Version.BorderSizePixel = 0
Version.Position = UDim2.new(0.00610992312, 0, 0.0289017335, 0)
Version.Selectable = true
Version.Size = UDim2.new(0, 371, 0, 25)
Version.Font = Enum.Font.SourceSans
Version.Text = "Changelogs v0.5"
Version.TextColor3 = Color3.fromRGB(255, 255, 255)
Version.TextSize = 25.000

ChangeLogs_2.Name = "ChangeLogs"
ChangeLogs_2.Parent = Changelogs
ChangeLogs_2.Active = true
ChangeLogs_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ChangeLogs_2.BackgroundTransparency = 1.000
ChangeLogs_2.BorderSizePixel = 0
ChangeLogs_2.Position = UDim2.new(0.00814658403, 0, 0.202312142, 0)
ChangeLogs_2.Selectable = true
ChangeLogs_2.Size = UDim2.new(0, 371, 0, 26)
ChangeLogs_2.Font = Enum.Font.SourceSans
ChangeLogs_2.Text = "[+] Added Players subtab"
ChangeLogs_2.TextColor3 = Color3.fromRGB(255, 255, 255)
ChangeLogs_2.TextSize = 25.000
ChangeLogs_2.TextWrapped = true

ChangeLogs_3.Name = "ChangeLogs"
ChangeLogs_3.Parent = Changelogs
ChangeLogs_3.Active = true
ChangeLogs_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ChangeLogs_3.BackgroundTransparency = 1.000
ChangeLogs_3.BorderSizePixel = 0
ChangeLogs_3.Position = UDim2.new(0.00814658403, 0, 0.364161849, 0)
ChangeLogs_3.Selectable = true
ChangeLogs_3.Size = UDim2.new(0, 371, 0, 26)
ChangeLogs_3.Font = Enum.Font.SourceSans
ChangeLogs_3.Text = "[+] UI is now easier to navigate"
ChangeLogs_3.TextColor3 = Color3.fromRGB(255, 255, 255)
ChangeLogs_3.TextSize = 25.000
ChangeLogs_3.TextWrapped = true

ChangeLogs_4.Name = "ChangeLogs"
ChangeLogs_4.Parent = Changelogs
ChangeLogs_4.Active = true
ChangeLogs_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ChangeLogs_4.BackgroundTransparency = 1.000
ChangeLogs_4.BorderSizePixel = 0
ChangeLogs_4.Position = UDim2.new(0.00814658403, 0, 0.514450848, 0)
ChangeLogs_4.Selectable = true
ChangeLogs_4.Size = UDim2.new(0, 371, 0, 26)
ChangeLogs_4.Font = Enum.Font.SourceSans
ChangeLogs_4.Text = "[-] Game registration underway"
ChangeLogs_4.TextColor3 = Color3.fromRGB(255, 255, 255)
ChangeLogs_4.TextSize = 25.000
ChangeLogs_4.TextWrapped = true

ChangeLogs_5.Name = "ChangeLogs"
ChangeLogs_5.Parent = Changelogs
ChangeLogs_5.Active = true
ChangeLogs_5.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ChangeLogs_5.BackgroundTransparency = 1.000
ChangeLogs_5.BorderSizePixel = 0
ChangeLogs_5.Position = UDim2.new(0.00610992312, 0, 0.664739847, 0)
ChangeLogs_5.Selectable = true
ChangeLogs_5.Size = UDim2.new(0, 371, 0, 26)
ChangeLogs_5.Font = Enum.Font.SourceSans
ChangeLogs_5.Text = "[+] Spiced up UI"
ChangeLogs_5.TextColor3 = Color3.fromRGB(255, 255, 255)
ChangeLogs_5.TextSize = 25.000
ChangeLogs_5.TextWrapped = true

Seperator_4.Name = "Seperator"
Seperator_4.Parent = Changelogs
Seperator_4.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
Seperator_4.BorderColor3 = Color3.fromRGB(28, 28, 28)
Seperator_4.BorderSizePixel = 0
Seperator_4.Position = UDim2.new(0.0024523437, 0, 0.173410401, 0)
Seperator_4.Size = UDim2.new(0, 373, 0, 5)

ChangeLogs_6.Name = "ChangeLogs"
ChangeLogs_6.Parent = Changelogs
ChangeLogs_6.Active = true
ChangeLogs_6.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ChangeLogs_6.BackgroundTransparency = 1.000
ChangeLogs_6.BorderSizePixel = 0
ChangeLogs_6.Position = UDim2.new(0.00877659023, 0, 0.843930602, 0)
ChangeLogs_6.Selectable = true
ChangeLogs_6.Size = UDim2.new(0, 371, 0, 26)
ChangeLogs_6.Font = Enum.Font.SourceSans
ChangeLogs_6.Text = "[+++] Added more animations"
ChangeLogs_6.TextColor3 = Color3.fromRGB(255, 255, 255)
ChangeLogs_6.TextSize = 25.000
ChangeLogs_6.TextWrapped = true

Settings_2.Name = "Settings"
Settings_2.Parent = Tabs_2
Settings_2.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
Settings_2.BackgroundTransparency = 1.000
Settings_2.BorderSizePixel = 0
Settings_2.Position = UDim2.new(-0.00204085279, 0, 0, 0)
Settings_2.Size = UDim2.new(0, 375, 0, 173)
Settings_2.Visible = false

HubColors.Name = "HubColors"
HubColors.Parent = Settings_2
HubColors.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
HubColors.BackgroundTransparency = 1.000
HubColors.Position = UDim2.new(0.0060109864, 0, 0.0982658938, 0)
HubColors.Size = UDim2.new(0, 133, 0, 26)
HubColors.Font = Enum.Font.SourceSans
HubColors.Text = "Hub Colors"
HubColors.TextColor3 = Color3.fromRGB(255, 255, 255)
HubColors.TextSize = 25.000

TextButton.Parent = Settings_2
TextButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton.BackgroundTransparency = 1.000
TextButton.Position = UDim2.new(0.522666633, 0, 0.0982658938, 0)
TextButton.Size = UDim2.new(0, 133, 0, 26)
TextButton.Font = Enum.Font.SourceSans
TextButton.Text = "Text Color"
TextButton.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton.TextSize = 25.000

Colors.Name = "Colors"
Colors.Parent = Settings_2
Colors.Active = true
Colors.BackgroundColor3 = Color3.fromRGB(35, 35, 35)
Colors.BackgroundTransparency = 1.000
Colors.BorderSizePixel = 0
Colors.Position = UDim2.new(0.0060109864, 0, 0.248554915, 0)
Colors.Size = UDim2.new(0, 372, 0, 128)

TextButton_2.Parent = Colors
TextButton_2.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextButton_2.BorderColor3 = Color3.fromRGB(255, 255, 255)
TextButton_2.Position = UDim2.new(0.567204297, 0, 0.0491329469, 0)
TextButton_2.Size = UDim2.new(0, 30, 0, 30)
TextButton_2.Font = Enum.Font.SourceSans
TextButton_2.Text = ""
TextButton_2.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_2.TextSize = 14.000

TextButton_3.Parent = Colors
TextButton_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_3.BorderColor3 = Color3.fromRGB(255, 255, 255)
TextButton_3.Position = UDim2.new(0.567204297, 0, 0.164739877, 0)
TextButton_3.Size = UDim2.new(0, 30, 0, 30)
TextButton_3.Font = Enum.Font.SourceSans
TextButton_3.Text = ""
TextButton_3.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_3.TextSize = 14.000

TextButton_4.Parent = Colors
TextButton_4.BackgroundColor3 = Color3.fromRGB(85, 0, 127)
TextButton_4.BorderColor3 = Color3.fromRGB(255, 255, 255)
TextButton_4.Position = UDim2.new(0.438172042, 0, 0.164739877, 0)
TextButton_4.Size = UDim2.new(0, 30, 0, 30)
TextButton_4.Font = Enum.Font.SourceSans
TextButton_4.Text = ""
TextButton_4.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_4.TextSize = 14.000

TextButton_5.Parent = Colors
TextButton_5.BackgroundColor3 = Color3.fromRGB(170, 0, 255)
TextButton_5.BorderColor3 = Color3.fromRGB(255, 255, 255)
TextButton_5.Position = UDim2.new(0.438172042, 0, 0.0491329469, 0)
TextButton_5.Size = UDim2.new(0, 30, 0, 30)
TextButton_5.Font = Enum.Font.SourceSans
TextButton_5.Text = ""
TextButton_5.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_5.TextSize = 14.000

TextButton_6.Parent = Colors
TextButton_6.BackgroundColor3 = Color3.fromRGB(170, 255, 0)
TextButton_6.BorderColor3 = Color3.fromRGB(255, 255, 255)
TextButton_6.Position = UDim2.new(0.174731195, 0, 0.164739877, 0)
TextButton_6.Size = UDim2.new(0, 30, 0, 30)
TextButton_6.Font = Enum.Font.SourceSans
TextButton_6.Text = ""
TextButton_6.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_6.TextSize = 14.000

TextButton_7.Parent = Colors
TextButton_7.BackgroundColor3 = Color3.fromRGB(255, 85, 0)
TextButton_7.BorderColor3 = Color3.fromRGB(255, 255, 255)
TextButton_7.Position = UDim2.new(0.0403225832, 0, 0.164739877, 0)
TextButton_7.Size = UDim2.new(0, 30, 0, 30)
TextButton_7.Font = Enum.Font.SourceSans
TextButton_7.Text = ""
TextButton_7.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_7.TextSize = 14.000

TextButton_8.Parent = Colors
TextButton_8.BackgroundColor3 = Color3.fromRGB(85, 0, 255)
TextButton_8.BorderColor3 = Color3.fromRGB(255, 255, 255)
TextButton_8.Position = UDim2.new(0.303763449, 0, 0.164739877, 0)
TextButton_8.Size = UDim2.new(0, 30, 0, 30)
TextButton_8.Font = Enum.Font.SourceSans
TextButton_8.Text = ""
TextButton_8.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_8.TextSize = 14.000

TextButton_9.Parent = Colors
TextButton_9.BackgroundColor3 = Color3.fromRGB(0, 125, 225)
TextButton_9.BorderColor3 = Color3.fromRGB(255, 255, 255)
TextButton_9.Position = UDim2.new(0.303763449, 0, 0.0491329469, 0)
TextButton_9.Size = UDim2.new(0, 30, 0, 30)
TextButton_9.Font = Enum.Font.SourceSans
TextButton_9.Text = ""
TextButton_9.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_9.TextSize = 14.000

TextButton_10.Parent = Colors
TextButton_10.BackgroundColor3 = Color3.fromRGB(85, 255, 0)
TextButton_10.BorderColor3 = Color3.fromRGB(255, 255, 255)
TextButton_10.Position = UDim2.new(0.174731195, 0, 0.0491329469, 0)
TextButton_10.Size = UDim2.new(0, 30, 0, 30)
TextButton_10.Font = Enum.Font.SourceSans
TextButton_10.Text = ""
TextButton_10.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_10.TextSize = 14.000

edit.Name = "edit"
edit.Parent = Colors
edit.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
edit.BorderColor3 = Color3.fromRGB(255, 255, 255)
edit.Position = UDim2.new(0.0403225832, 0, 0.0462427735, 0)
edit.Size = UDim2.new(0, 30, 0, 30)
edit.Font = Enum.Font.SourceSans
edit.Text = ""
edit.TextColor3 = Color3.fromRGB(0, 0, 0)
edit.TextSize = 14.000

Remotespy.Name = "Remotespy"
Remotespy.Parent = TabHolder
Remotespy.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Remotespy.BackgroundTransparency = 1.000
Remotespy.BorderSizePixel = 0
Remotespy.Position = UDim2.new(-0.00204081624, 0, 0, 0)
Remotespy.Size = UDim2.new(0, 491, 0, 173)
Remotespy.Visible = false

Logging.Name = "Logging"
Logging.Parent = Remotespy
Logging.Active = true
Logging.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Logging.BackgroundTransparency = 1.000
Logging.BorderColor3 = Color3.fromRGB(28, 28, 28)
Logging.BorderSizePixel = 2
Logging.Position = UDim2.new(0.197150141, 0, 0, 0)
Logging.Size = UDim2.new(0, 393, 0, 173)
Logging.CanvasSize = UDim2.new(0, 0, 50, 0)

Original.Name = "Original"
Original.Parent = Logging
Original.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Original.BackgroundTransparency = 1.000
Original.BorderSizePixel = 0
Original.Size = UDim2.new(0, 378, 0, 115)
Original.Visible = false
Original.Font = Enum.Font.SourceSans
Original.TextColor3 = Color3.fromRGB(255, 255, 255)
Original.TextScaled = true
Original.TextSize = 25.000
Original.TextWrapped = true
Original.TextXAlignment = Enum.TextXAlignment.Left

ControlPanel_3.Name = "ControlPanel"
ControlPanel_3.Parent = Remotespy
ControlPanel_3.BackgroundColor3 = Color3.fromRGB(35, 35, 35)
ControlPanel_3.BackgroundTransparency = 1.000
ControlPanel_3.BorderColor3 = Color3.fromRGB(40, 40, 40)
ControlPanel_3.BorderSizePixel = 0
ControlPanel_3.Position = UDim2.new(0.00203665998, 0, 0, 0)
ControlPanel_3.Size = UDim2.new(0, 93, 0, 173)

ClearLogs.Name = "ClearLogs"
ClearLogs.Parent = ControlPanel_3
ClearLogs.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ClearLogs.BackgroundTransparency = 1.000
ClearLogs.BorderSizePixel = 0
ClearLogs.Size = UDim2.new(0, 93, 0, 32)
ClearLogs.Font = Enum.Font.SourceSans
ClearLogs.Text = "Clear Logs"
ClearLogs.TextColor3 = Color3.fromRGB(255, 255, 255)
ClearLogs.TextSize = 20.000

Seperator_5.Name = "Seperator"
Seperator_5.Parent = ControlPanel_3
Seperator_5.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
Seperator_5.BorderSizePixel = 0
Seperator_5.Position = UDim2.new(1.00860989, 0, 1.76402182e-07, 0)
Seperator_5.Size = UDim2.new(0, 2, 0, 172)

Local_2.Name = "Local"
Local_2.Parent = TabHolder
Local_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Local_2.BackgroundTransparency = 1.000
Local_2.BorderSizePixel = 0
Local_2.Position = UDim2.new(-0.00204081624, 0, 0, 0)
Local_2.Size = UDim2.new(0, 491, 0, 173)
Local_2.Visible = false

ControlPanel_4.Name = "ControlPanel"
ControlPanel_4.Parent = Local_2
ControlPanel_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ControlPanel_4.BackgroundTransparency = 1.000
ControlPanel_4.BorderSizePixel = 0
ControlPanel_4.Size = UDim2.new(0, 100, 0, 173)

Movement.Name = "Movement"
Movement.Parent = ControlPanel_4
Movement.Active = false
Movement.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Movement.BackgroundTransparency = 1.000
Movement.BorderSizePixel = 0
Movement.Position = UDim2.new(0.0122199245, 0, 8.82010909e-08, 0)
Movement.Selectable = false
Movement.Size = UDim2.new(0, 103, 0, 30)
Movement.Font = Enum.Font.SourceSans
Movement.Text = "Movement"
Movement.TextColor3 = Color3.fromRGB(255, 255, 255)
Movement.TextSize = 25.000

HatExploits.Name = "HatExploits"
HatExploits.Parent = ControlPanel_4
HatExploits.Active = false
HatExploits.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
HatExploits.BackgroundTransparency = 1.000
HatExploits.BorderSizePixel = 0
HatExploits.Position = UDim2.new(0.0122199245, 0, 0.196531966, 0)
HatExploits.Selectable = false
HatExploits.Size = UDim2.new(0, 100, 0, 30)
HatExploits.Font = Enum.Font.SourceSans
HatExploits.Text = "Hat Exploits"
HatExploits.TextColor3 = Color3.fromRGB(255, 255, 255)
HatExploits.TextSize = 24.000

FEBypass.Name = "FEBypass"
FEBypass.Parent = ControlPanel_4
FEBypass.Active = false
FEBypass.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
FEBypass.BackgroundTransparency = 1.000
FEBypass.BorderSizePixel = 0
FEBypass.Position = UDim2.new(0.00221992494, 0, 0.404624462, 0)
FEBypass.Selectable = false
FEBypass.Size = UDim2.new(0, 104, 0, 30)
FEBypass.Font = Enum.Font.SourceSans
FEBypass.Text = "FE Bypasses"
FEBypass.TextColor3 = Color3.fromRGB(255, 255, 255)
FEBypass.TextSize = 24.000

AimEsp.Name = "Aim/Esp"
AimEsp.Parent = ControlPanel_4
AimEsp.Active = false
AimEsp.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
AimEsp.BackgroundTransparency = 1.000
AimEsp.BorderSizePixel = 0
AimEsp.Position = UDim2.new(0.0022199247, 0, 0.618497193, 0)
AimEsp.Selectable = false
AimEsp.Size = UDim2.new(0, 103, 0, 30)
AimEsp.Font = Enum.Font.SourceSans
AimEsp.Text = "Aim/Esp"
AimEsp.TextColor3 = Color3.fromRGB(255, 255, 255)
AimEsp.TextSize = 25.000

Seperator_6.Name = "Seperator"
Seperator_6.Parent = Local_2
Seperator_6.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
Seperator_6.BorderColor3 = Color3.fromRGB(28, 28, 28)
Seperator_6.BorderSizePixel = 0
Seperator_6.Position = UDim2.new(0.212264732, 0, 0, 0)
Seperator_6.Size = UDim2.new(0, 2, 0, 172)

Tabs_3.Name = "Tabs"
Tabs_3.Parent = Local_2
Tabs_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Tabs_3.BackgroundTransparency = 1.000
Tabs_3.Position = UDim2.new(0.216338053, 0, 0, 0)
Tabs_3.Size = UDim2.new(0, 384, 0, 173)
Tabs_3.Image = "rbxassetid://3570695787"
Tabs_3.ImageColor3 = Color3.fromRGB(40, 40, 40)
Tabs_3.ScaleType = Enum.ScaleType.Slice
Tabs_3.SliceCenter = Rect.new(100, 100, 100, 100)
Tabs_3.SliceScale = 0.120

Hats.Name = "Hats"
Hats.Parent = Tabs_3
Hats.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Hats.BackgroundTransparency = 1.000
Hats.Position = UDim2.new(0.0020366509, 0, 0, 0)
Hats.Size = UDim2.new(0, 383, 0, 173)
Hats.Visible = false

Amount.Name = "Amount"
Amount.Parent = Hats
Amount.Active = true
Amount.AnchorPoint = Vector2.new(0.5, 0.5)
Amount.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Amount.BackgroundTransparency = 1.000
Amount.Position = UDim2.new(0.14419058, 0, 0.29992342, 0)
Amount.Selectable = true
Amount.Size = UDim2.new(0.207253724, 0, 0.117797919, 0)
Amount.Image = "rbxassetid://3570695787"
Amount.ImageColor3 = Color3.fromRGB(35, 35, 35)
Amount.ScaleType = Enum.ScaleType.Slice
Amount.SliceCenter = Rect.new(100, 100, 100, 100)
Amount.SliceScale = 0.250

AmountBTN.Name = "AmountBTN"
AmountBTN.Parent = Amount
AmountBTN.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
AmountBTN.BackgroundTransparency = 1.000
AmountBTN.Position = UDim2.new(0, 0, 0.0776542723, 0)
AmountBTN.Size = UDim2.new(0, 79, 0, 19)
AmountBTN.Font = Enum.Font.SourceSans
AmountBTN.PlaceholderColor3 = Color3.fromRGB(178, 178, 178)
AmountBTN.PlaceholderText = "DropCount"
AmountBTN.Text = ""
AmountBTN.TextColor3 = Color3.fromRGB(0, 0, 0)
AmountBTN.TextSize = 20.000

Aura.Name = "Aura"
Aura.Parent = Hats
Aura.Active = true
Aura.AnchorPoint = Vector2.new(0.5, 0.5)
Aura.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Aura.BackgroundTransparency = 1.000
Aura.Position = UDim2.new(0.378488421, 0, 0.459725261, 0)
Aura.Selectable = true
Aura.Size = UDim2.new(0.220694676, 0, 0.112268627, 0)
Aura.Image = "rbxassetid://3570695787"
Aura.ImageColor3 = Color3.fromRGB(35, 35, 35)
Aura.ScaleType = Enum.ScaleType.Slice
Aura.SliceCenter = Rect.new(100, 100, 100, 100)
Aura.SliceScale = 0.250

AuraBTN.Name = "AuraBTN"
AuraBTN.Parent = Aura
AuraBTN.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
AuraBTN.BackgroundTransparency = 1.000
AuraBTN.Size = UDim2.new(0, 84, 0, 20)
AuraBTN.Font = Enum.Font.SourceSans
AuraBTN.Text = "Hat Aura"
AuraBTN.TextColor3 = Color3.fromRGB(255, 255, 255)
AuraBTN.TextSize = 20.000

Drop.Name = "Drop"
Drop.Parent = Hats
Drop.Active = true
Drop.AnchorPoint = Vector2.new(0.5, 0.5)
Drop.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Drop.BackgroundTransparency = 1.000
Drop.Position = UDim2.new(0.37965554, 0, 0.307387322, 0)
Drop.Selectable = true
Drop.Size = UDim2.new(0.218360513, 0, 0.114430711, 0)
Drop.Image = "rbxassetid://3570695787"
Drop.ImageColor3 = Color3.fromRGB(35, 35, 35)
Drop.ScaleType = Enum.ScaleType.Slice
Drop.SliceCenter = Rect.new(100, 100, 100, 100)
Drop.SliceScale = 0.250

DropBTN.Name = "DropBTN"
DropBTN.Parent = Drop
DropBTN.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
DropBTN.BackgroundTransparency = 1.000
DropBTN.Size = UDim2.new(0, 84, 0, 19)
DropBTN.Font = Enum.Font.SourceSans
DropBTN.Text = "Drop Hats"
DropBTN.TextColor3 = Color3.fromRGB(255, 255, 255)
DropBTN.TextSize = 20.000

Kill.Name = "Kill"
Kill.Parent = Hats
Kill.Active = true
Kill.AnchorPoint = Vector2.new(0.5, 0.5)
Kill.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Kill.BackgroundTransparency = 1.000
Kill.Position = UDim2.new(0.144190535, 0, 0.460544646, 0)
Kill.Selectable = true
Kill.Size = UDim2.new(0.20725368, 0, 0.110630497, 0)
Kill.Image = "rbxassetid://3570695787"
Kill.ImageColor3 = Color3.fromRGB(35, 35, 35)
Kill.ScaleType = Enum.ScaleType.Slice
Kill.SliceCenter = Rect.new(100, 100, 100, 100)
Kill.SliceScale = 0.250

KillBTN.Name = "KillBTN"
KillBTN.Parent = Kill
KillBTN.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
KillBTN.BackgroundTransparency = 1.000
KillBTN.Size = UDim2.new(0, 80, 0, 19)
KillBTN.Font = Enum.Font.SourceSans
KillBTN.Text = "Kill"
KillBTN.TextColor3 = Color3.fromRGB(255, 255, 255)
KillBTN.TextSize = 20.000

F.Name = "F"
F.Parent = Hats
F.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
F.BackgroundTransparency = 1.000
F.BorderSizePixel = 0
F.Position = UDim2.new(0.181555927, 0, 0.089310661, 0)
F.Size = UDim2.new(0, 132, 0, 10)
F.Font = Enum.Font.SourceSans
F.Text = "Hold 'F' to move hats"
F.TextColor3 = Color3.fromRGB(255, 255, 255)
F.TextSize = 15.000

CheckBox_2.Name = "CheckBox"
CheckBox_2.Parent = Hats
CheckBox_2.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
CheckBox_2.BackgroundTransparency = 1.000
CheckBox_2.Position = UDim2.new(0.0565811507, 0, 0.0635302365, 0)
CheckBox_2.Size = UDim2.new(0, 54, 0, 19)
CheckBox_2.Image = "rbxassetid://3570695787"
CheckBox_2.ImageColor3 = Color3.fromRGB(50, 50, 50)
CheckBox_2.ScaleType = Enum.ScaleType.Slice
CheckBox_2.SliceCenter = Rect.new(100, 100, 100, 100)
CheckBox_2.SliceScale = 0.120

IEX_7.Name = "IEX"
IEX_7.Parent = CheckBox_2
IEX_7.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
IEX_7.BorderSizePixel = 0
IEX_7.Position = UDim2.new(0.476999998, 0, -0.119999997, 0)
IEX_7.Size = UDim2.new(0, 29, 0, 23)
IEX_7.Font = Enum.Font.SourceSans
IEX_7.Text = "OFF"
IEX_7.TextColor3 = Color3.fromRGB(255, 0, 0)
IEX_7.TextSize = 14.000

Movement_2.Name = "Movement"
Movement_2.Parent = Tabs_3
Movement_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Movement_2.BackgroundTransparency = 1.000
Movement_2.Size = UDim2.new(0, 384, 0, 173)
Movement_2.Visible = false

ClickTp.Name = "ClickTp"
ClickTp.Parent = Movement_2
ClickTp.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
ClickTp.BackgroundTransparency = 1.000
ClickTp.Position = UDim2.new(0.320049345, 0, 0.861218095, 0)
ClickTp.Size = UDim2.new(0, 54, 0, 19)
ClickTp.Image = "rbxassetid://3570695787"
ClickTp.ImageColor3 = Color3.fromRGB(50, 50, 50)
ClickTp.ScaleType = Enum.ScaleType.Slice
ClickTp.SliceCenter = Rect.new(100, 100, 100, 100)
ClickTp.SliceScale = 0.120

IEX_8.Name = "IEX"
IEX_8.Parent = ClickTp
IEX_8.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
IEX_8.BorderSizePixel = 0
IEX_8.Position = UDim2.new(0.476999998, 0, -0.119999997, 0)
IEX_8.Size = UDim2.new(0, 29, 0, 23)
IEX_8.Font = Enum.Font.SourceSans
IEX_8.Text = "OFF"
IEX_8.TextColor3 = Color3.fromRGB(255, 0, 0)
IEX_8.TextSize = 14.000

Label_8.Name = "Label"
Label_8.Parent = ClickTp
Label_8.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Label_8.BackgroundTransparency = 1.000
Label_8.BorderSizePixel = 0
Label_8.Position = UDim2.new(-2.28982353, 0, -0.0482274108, 0)
Label_8.Size = UDim2.new(0, 114, 0, 19)
Label_8.Font = Enum.Font.SourceSans
Label_8.Text = "'e' TP"
Label_8.TextColor3 = Color3.fromRGB(255, 255, 255)
Label_8.TextSize = 25.000

Gravity.Name = "Gravity"
Gravity.Parent = Movement_2
Gravity.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Gravity.BackgroundTransparency = 1.000
Gravity.Position = UDim2.new(0.328498572, 0, 0.389888763, -10)
Gravity.Size = UDim2.new(0.247255534, 0, -0.00824223738, 20)
Gravity.Image = "rbxassetid://3570695787"
Gravity.ImageColor3 = Color3.fromRGB(53, 53, 53)
Gravity.ImageTransparency = 0.400
Gravity.ScaleType = Enum.ScaleType.Slice
Gravity.SliceCenter = Rect.new(100, 100, 100, 100)
Gravity.SliceScale = 0.120

Button.Name = "Button"
Button.Parent = Gravity
Button.Active = true
Button.AnchorPoint = Vector2.new(0.5, 0.5)
Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Button.BackgroundTransparency = 1.000
Button.Position = UDim2.new(0.077937007, 0, 0.473401606, 0)
Button.Selectable = true
Button.Size = UDim2.new(0, 20, 0, 18)
Button.Image = "rbxassetid://3570695787"
Button.ImageColor3 = Color3.fromRGB(47, 255, 7)
Button.ScaleType = Enum.ScaleType.Slice
Button.SliceCenter = Rect.new(100, 100, 100, 100)
Button.SliceScale = 0.120

TextButton_11.Parent = Button
TextButton_11.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_11.BackgroundTransparency = 1.000
TextButton_11.Size = UDim2.new(1.0627321, 0, 1, 0)
TextButton_11.Font = Enum.Font.Cartoon
TextButton_11.Text = ""
TextButton_11.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_11.TextScaled = true
TextButton_11.TextSize = 14.000
TextButton_11.TextWrapped = true

Label_9.Name = "Label"
Label_9.Parent = Gravity
Label_9.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Label_9.BackgroundTransparency = 1.000
Label_9.BorderSizePixel = 0
Label_9.Position = UDim2.new(-1.29109025, 0, 0, 0)
Label_9.Size = UDim2.new(0, 114, 0, 18)
Label_9.Font = Enum.Font.SourceSans
Label_9.Text = "Gravity"
Label_9.TextColor3 = Color3.fromRGB(255, 255, 255)
Label_9.TextSize = 25.000

InfJump.Name = "InfJump"
InfJump.Parent = Movement_2
InfJump.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
InfJump.BackgroundTransparency = 1.000
InfJump.Position = UDim2.new(0.320049345, 0, 0.514397264, 0)
InfJump.Size = UDim2.new(0, 54, 0, 19)
InfJump.Image = "rbxassetid://3570695787"
InfJump.ImageColor3 = Color3.fromRGB(50, 50, 50)
InfJump.ScaleType = Enum.ScaleType.Slice
InfJump.SliceCenter = Rect.new(100, 100, 100, 100)
InfJump.SliceScale = 0.120

IEX_9.Name = "IEX"
IEX_9.Parent = InfJump
IEX_9.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
IEX_9.BorderSizePixel = 0
IEX_9.Position = UDim2.new(0.476999998, 0, -0.119999997, 0)
IEX_9.Size = UDim2.new(0, 29, 0, 23)
IEX_9.Font = Enum.Font.SourceSans
IEX_9.Text = "OFF"
IEX_9.TextColor3 = Color3.fromRGB(255, 0, 0)
IEX_9.TextSize = 14.000

Label_10.Name = "Label"
Label_10.Parent = InfJump
Label_10.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Label_10.BackgroundTransparency = 1.000
Label_10.BorderSizePixel = 0
Label_10.Position = UDim2.new(-2.28982353, 0, -0.0482274108, 0)
Label_10.Size = UDim2.new(0, 114, 0, 19)
Label_10.Font = Enum.Font.SourceSans
Label_10.Text = "InfJump"
Label_10.TextColor3 = Color3.fromRGB(255, 255, 255)
Label_10.TextSize = 25.000

JumpPower.Name = "JumpPower"
JumpPower.Parent = Movement_2
JumpPower.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
JumpPower.BackgroundTransparency = 1.000
JumpPower.Position = UDim2.new(0.330535173, 0, 0.256940693, -10)
JumpPower.Size = UDim2.new(0.247255534, 0, -0.00824223738, 20)
JumpPower.Image = "rbxassetid://3570695787"
JumpPower.ImageColor3 = Color3.fromRGB(53, 53, 53)
JumpPower.ImageTransparency = 0.400
JumpPower.ScaleType = Enum.ScaleType.Slice
JumpPower.SliceCenter = Rect.new(100, 100, 100, 100)
JumpPower.SliceScale = 0.120

Button_2.Name = "Button"
Button_2.Parent = JumpPower
Button_2.Active = true
Button_2.AnchorPoint = Vector2.new(0.5, 0.5)
Button_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Button_2.BackgroundTransparency = 1.000
Button_2.Position = UDim2.new(0.077937007, 0, 0.473401606, 0)
Button_2.Selectable = true
Button_2.Size = UDim2.new(0, 20, 0, 18)
Button_2.Image = "rbxassetid://3570695787"
Button_2.ImageColor3 = Color3.fromRGB(47, 255, 7)
Button_2.ScaleType = Enum.ScaleType.Slice
Button_2.SliceCenter = Rect.new(100, 100, 100, 100)
Button_2.SliceScale = 0.120

TextButton_12.Parent = Button_2
TextButton_12.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_12.BackgroundTransparency = 1.000
TextButton_12.Size = UDim2.new(1.0627321, 0, 1, 0)
TextButton_12.Font = Enum.Font.Cartoon
TextButton_12.Text = ""
TextButton_12.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_12.TextScaled = true
TextButton_12.TextSize = 14.000
TextButton_12.TextWrapped = true

Label_11.Name = "Label"
Label_11.Parent = JumpPower
Label_11.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Label_11.BackgroundTransparency = 1.000
Label_11.BorderSizePixel = 0
Label_11.Position = UDim2.new(-1.36349642, 0, 0, 0)
Label_11.Size = UDim2.new(0, 114, 0, 18)
Label_11.Font = Enum.Font.SourceSans
Label_11.Text = "JumpPower"
Label_11.TextColor3 = Color3.fromRGB(255, 255, 255)
Label_11.TextSize = 25.000

Noclip_2.Name = "Noclip"
Noclip_2.Parent = Movement_2
Noclip_2.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Noclip_2.BackgroundTransparency = 1.000
Noclip_2.Position = UDim2.new(0.320049345, 0, 0.687807679, 0)
Noclip_2.Size = UDim2.new(0, 54, 0, 19)
Noclip_2.Image = "rbxassetid://3570695787"
Noclip_2.ImageColor3 = Color3.fromRGB(50, 50, 50)
Noclip_2.ScaleType = Enum.ScaleType.Slice
Noclip_2.SliceCenter = Rect.new(100, 100, 100, 100)
Noclip_2.SliceScale = 0.120

IEX_10.Name = "IEX"
IEX_10.Parent = Noclip_2
IEX_10.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
IEX_10.BorderSizePixel = 0
IEX_10.Position = UDim2.new(0.476999998, 0, -0.119999997, 0)
IEX_10.Size = UDim2.new(0, 29, 0, 23)
IEX_10.Font = Enum.Font.SourceSans
IEX_10.Text = "OFF"
IEX_10.TextColor3 = Color3.fromRGB(255, 0, 0)
IEX_10.TextSize = 14.000

Label_12.Name = "Label"
Label_12.Parent = Noclip_2
Label_12.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Label_12.BackgroundTransparency = 1.000
Label_12.BorderSizePixel = 0
Label_12.Position = UDim2.new(-2.28982353, 0, -0.0482274108, 0)
Label_12.Size = UDim2.new(0, 114, 0, 19)
Label_12.Font = Enum.Font.SourceSans
Label_12.Text = "Noclip"
Label_12.TextColor3 = Color3.fromRGB(255, 255, 255)
Label_12.TextSize = 25.000

WalkSpeed.Name = "WalkSpeed"
WalkSpeed.Parent = Movement_2
WalkSpeed.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
WalkSpeed.BackgroundTransparency = 1.000
WalkSpeed.Position = UDim2.new(0.330535173, 0, 0.123992749, -10)
WalkSpeed.Size = UDim2.new(0.247255534, 0, -0.00824223738, 20)
WalkSpeed.Image = "rbxassetid://3570695787"
WalkSpeed.ImageColor3 = Color3.fromRGB(53, 53, 53)
WalkSpeed.ImageTransparency = 0.400
WalkSpeed.ScaleType = Enum.ScaleType.Slice
WalkSpeed.SliceCenter = Rect.new(100, 100, 100, 100)
WalkSpeed.SliceScale = 0.120

Button_3.Name = "Button"
Button_3.Parent = WalkSpeed
Button_3.Active = true
Button_3.AnchorPoint = Vector2.new(0.5, 0.5)
Button_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Button_3.BackgroundTransparency = 1.000
Button_3.Position = UDim2.new(0.077937007, 0, 0.473401606, 0)
Button_3.Selectable = true
Button_3.Size = UDim2.new(0, 20, 0, 18)
Button_3.Image = "rbxassetid://3570695787"
Button_3.ImageColor3 = Color3.fromRGB(47, 255, 7)
Button_3.ScaleType = Enum.ScaleType.Slice
Button_3.SliceCenter = Rect.new(100, 100, 100, 100)
Button_3.SliceScale = 0.120

TextButton_13.Parent = Button_3
TextButton_13.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_13.BackgroundTransparency = 1.000
TextButton_13.Size = UDim2.new(1.0627321, 0, 1, 0)
TextButton_13.Font = Enum.Font.Cartoon
TextButton_13.Text = ""
TextButton_13.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_13.TextScaled = true
TextButton_13.TextSize = 14.000
TextButton_13.TextWrapped = true

Label_13.Name = "Label"
Label_13.Parent = WalkSpeed
Label_13.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Label_13.BackgroundTransparency = 1.000
Label_13.BorderSizePixel = 0
Label_13.Position = UDim2.new(-1.29109025, 0, 0.0123508424, 0)
Label_13.Size = UDim2.new(0, 114, 0, 17)
Label_13.Font = Enum.Font.SourceSans
Label_13.Text = "WalkSpeed"
Label_13.TextColor3 = Color3.fromRGB(255, 255, 255)
Label_13.TextSize = 25.000

Anchor_2.Name = "Anchor"
Anchor_2.Parent = Movement_2
Anchor_2.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Anchor_2.BackgroundTransparency = 1.000
Anchor_2.Position = UDim2.new(0.812282503, 0, 0.520177662, 0)
Anchor_2.Size = UDim2.new(0, 54, 0, 19)
Anchor_2.Image = "rbxassetid://3570695787"
Anchor_2.ImageColor3 = Color3.fromRGB(50, 50, 50)
Anchor_2.ScaleType = Enum.ScaleType.Slice
Anchor_2.SliceCenter = Rect.new(100, 100, 100, 100)
Anchor_2.SliceScale = 0.120

IEX_11.Name = "IEX"
IEX_11.Parent = Anchor_2
IEX_11.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
IEX_11.BorderSizePixel = 0
IEX_11.Position = UDim2.new(0.476999998, 0, -0.119999997, 0)
IEX_11.Size = UDim2.new(0, 29, 0, 23)
IEX_11.Font = Enum.Font.SourceSans
IEX_11.Text = "OFF"
IEX_11.TextColor3 = Color3.fromRGB(255, 0, 0)
IEX_11.TextSize = 14.000

Label_14.Name = "Label"
Label_14.Parent = Anchor_2
Label_14.Active = true
Label_14.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Label_14.BackgroundTransparency = 1.000
Label_14.BorderSizePixel = 0
Label_14.Position = UDim2.new(-1.60527098, 0, 0, 0)
Label_14.Selectable = true
Label_14.Size = UDim2.new(0, 74, 0, 20)
Label_14.Font = Enum.Font.SourceSans
Label_14.Text = "Anchor"
Label_14.TextColor3 = Color3.fromRGB(255, 255, 255)
Label_14.TextSize = 25.000
Label_14.TextWrapped = true

TPALL_2.Name = "TPALL"
TPALL_2.Parent = Movement_2
TPALL_2.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TPALL_2.BackgroundTransparency = 1.000
TPALL_2.Position = UDim2.new(0.812282443, 0, 0.68202728, 0)
TPALL_2.Size = UDim2.new(0, 54, 0, 19)
TPALL_2.Image = "rbxassetid://3570695787"
TPALL_2.ImageColor3 = Color3.fromRGB(50, 50, 50)
TPALL_2.ScaleType = Enum.ScaleType.Slice
TPALL_2.SliceCenter = Rect.new(100, 100, 100, 100)
TPALL_2.SliceScale = 0.120

IEX_12.Name = "IEX"
IEX_12.Parent = TPALL_2
IEX_12.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
IEX_12.BorderSizePixel = 0
IEX_12.Position = UDim2.new(0.476999998, 0, -0.119999997, 0)
IEX_12.Size = UDim2.new(0, 29, 0, 23)
IEX_12.Font = Enum.Font.SourceSans
IEX_12.Text = "OFF"
IEX_12.TextColor3 = Color3.fromRGB(255, 0, 0)
IEX_12.TextSize = 14.000

Label_15.Name = "Label"
Label_15.Parent = TPALL_2
Label_15.Active = true
Label_15.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Label_15.BackgroundTransparency = 1.000
Label_15.BorderSizePixel = 0
Label_15.Position = UDim2.new(-2.17934513, 0, -0.119999938, 0)
Label_15.Selectable = true
Label_15.Size = UDim2.new(0, 105, 0, 21)
Label_15.Font = Enum.Font.SourceSans
Label_15.Text = "Teleport All"
Label_15.TextColor3 = Color3.fromRGB(255, 255, 255)
Label_15.TextSize = 25.000
Label_15.TextWrapped = true

SpeedBypass.Name = "SpeedBypass"
SpeedBypass.Parent = Movement_2
SpeedBypass.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
SpeedBypass.BackgroundTransparency = 1.000
SpeedBypass.Position = UDim2.new(0.615351498, 0, 0.0635301769, 0)
SpeedBypass.Size = UDim2.new(0, 54, 0, 19)
SpeedBypass.Image = "rbxassetid://3570695787"
SpeedBypass.ImageColor3 = Color3.fromRGB(50, 50, 50)
SpeedBypass.ScaleType = Enum.ScaleType.Slice
SpeedBypass.SliceCenter = Rect.new(100, 100, 100, 100)
SpeedBypass.SliceScale = 0.120

IEX_13.Name = "IEX"
IEX_13.Parent = SpeedBypass
IEX_13.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
IEX_13.BorderSizePixel = 0
IEX_13.Position = UDim2.new(0.476999998, 0, -0.119999997, 0)
IEX_13.Size = UDim2.new(0, 29, 0, 23)
IEX_13.Font = Enum.Font.SourceSans
IEX_13.Text = "OFF"
IEX_13.TextColor3 = Color3.fromRGB(255, 0, 0)
IEX_13.TextSize = 14.000

LName.Name = "LName"
LName.Parent = SpeedBypass
LName.Active = true
LName.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
LName.BackgroundTransparency = 1.000
LName.BorderSizePixel = 0
LName.Position = UDim2.new(1.19102538, 0, 0.0362854004, 0)
LName.Selectable = true
LName.Size = UDim2.new(0, 79, 0, 19)
LName.Font = Enum.Font.SourceSans
LName.Text = "Bypass"
LName.TextColor3 = Color3.fromRGB(255, 255, 255)
LName.TextSize = 25.000
LName.TextWrapped = true

UP.Name = "UP"
UP.Parent = SpeedBypass
UP.Active = true
UP.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
UP.BackgroundTransparency = 1.000
UP.BorderSizePixel = 0
UP.Position = UDim2.new(0, 0, 1.45733798, 0)
UP.Selectable = true
UP.Size = UDim2.new(0, 142, 0, 14)
UP.Font = Enum.Font.SourceSans
UP.Text = "Press 'U' to go faster"
UP.TextColor3 = Color3.fromRGB(255, 255, 255)
UP.TextScaled = true
UP.TextSize = 25.000
UP.TextWrapped = true

DOWN.Name = "DOWN"
DOWN.Parent = SpeedBypass
DOWN.Active = true
DOWN.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
DOWN.BackgroundTransparency = 1.000
DOWN.BorderSizePixel = 0
DOWN.Position = UDim2.new(0, 0, 2.19418001, 0)
DOWN.Selectable = true
DOWN.Size = UDim2.new(0, 142, 0, 14)
DOWN.Font = Enum.Font.SourceSans
DOWN.Text = "Press 'J' to slow down"
DOWN.TextColor3 = Color3.fromRGB(255, 255, 255)
DOWN.TextScaled = true
DOWN.TextSize = 25.000
DOWN.TextWrapped = true

Value.Name = "Value"
Value.Parent = SpeedBypass
Value.Active = true
Value.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Value.BackgroundTransparency = 1.000
Value.BorderSizePixel = 0
Value.Position = UDim2.new(0, 0, 2.93102217, 0)
Value.Selectable = true
Value.Size = UDim2.new(0, 142, 0, 14)
Value.Font = Enum.Font.SourceSans
Value.Text = "Current value :"
Value.TextColor3 = Color3.fromRGB(255, 255, 255)
Value.TextScaled = true
Value.TextSize = 25.000
Value.TextWrapped = true

Bypass.Name = "Bypass"
Bypass.Parent = Tabs_3
Bypass.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Bypass.BackgroundTransparency = 1.000
Bypass.BorderSizePixel = 0
Bypass.Size = UDim2.new(0, 384, 0, 172)
Bypass.Visible = false

Bypass_2.Name = "Bypass"
Bypass_2.Parent = Bypass
Bypass_2.AnchorPoint = Vector2.new(0.5, 0.5)
Bypass_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Bypass_2.BackgroundTransparency = 1.000
Bypass_2.Position = UDim2.new(0.185908914, 0, 0.168604657, 0)
Bypass_2.Size = UDim2.new(0.304109424, 0, 0.174418598, 0)
Bypass_2.Image = "rbxassetid://3570695787"
Bypass_2.ImageColor3 = Color3.fromRGB(35, 35, 35)
Bypass_2.ScaleType = Enum.ScaleType.Slice
Bypass_2.SliceCenter = Rect.new(100, 100, 100, 100)
Bypass_2.SliceScale = 0.250

FEBypass_2.Name = "FEBypass"
FEBypass_2.Parent = Bypass_2
FEBypass_2.Active = false
FEBypass_2.BackgroundColor3 = Color3.fromRGB(35, 35, 35)
FEBypass_2.BackgroundTransparency = 1.000
FEBypass_2.BorderSizePixel = 0
FEBypass_2.Selectable = false
FEBypass_2.Size = UDim2.new(0, 116, 0, 30)
FEBypass_2.Font = Enum.Font.SourceSans
FEBypass_2.Text = "Neptunian V"
FEBypass_2.TextColor3 = Color3.fromRGB(255, 255, 255)
FEBypass_2.TextSize = 24.000

Req.Name = "Req"
Req.Parent = Bypass_2
Req.BackgroundColor3 = Color3.fromRGB(35, 35, 35)
Req.BackgroundTransparency = 1.000
Req.BorderSizePixel = 0
Req.Position = UDim2.new(-1.30664915e-07, 0, 0.866666734, 0)
Req.Size = UDim2.new(0, 157, 0, 76)
Req.Font = Enum.Font.SourceSans
Req.Text = "Requires Corrupt-Demonic-Greatsword and *one* hat of choice, character *has* to be r6"
Req.TextColor3 = Color3.fromRGB(255, 255, 255)
Req.TextScaled = true
Req.TextSize = 24.000
Req.TextWrapped = true

TextLabel_4.Parent = Bypass
TextLabel_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_4.BackgroundTransparency = 1.000
TextLabel_4.Position = UDim2.new(0.75, 0, 0.0232558139, 0)
TextLabel_4.Size = UDim2.new(0, 95, 0, 26)
TextLabel_4.Font = Enum.Font.SourceSans
TextLabel_4.Text = "Disclaimer! Scripts arent mine"
TextLabel_4.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_4.TextScaled = true
TextLabel_4.TextSize = 25.000
TextLabel_4.TextWrapped = true

AimEsp_2.Name = "Aim/Esp"
AimEsp_2.Parent = Tabs_3
AimEsp_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
AimEsp_2.BackgroundTransparency = 1.000
AimEsp_2.BorderSizePixel = 0
AimEsp_2.Position = UDim2.new(-0.00520833349, 0, 8.82010909e-08, 0)
AimEsp_2.Size = UDim2.new(0, 386, 0, 172)

Aimbot_2.Name = "Aimbot"
Aimbot_2.Parent = AimEsp_2
Aimbot_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Aimbot_2.BackgroundTransparency = 1.000
Aimbot_2.BorderSizePixel = 0
Aimbot_2.Position = UDim2.new(0.0336787552, 0, 0.0813953504, 0)
Aimbot_2.Size = UDim2.new(0, 120, 0, 30)
Aimbot_2.Font = Enum.Font.SourceSans
Aimbot_2.Text = "Aimbot"
Aimbot_2.TextColor3 = Color3.fromRGB(255, 255, 255)
Aimbot_2.TextSize = 25.000

chams.Name = "chams"
chams.Parent = AimEsp_2
chams.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
chams.BackgroundTransparency = 1.000
chams.BorderSizePixel = 0
chams.Position = UDim2.new(0.51295346, 0, 0.0813953504, 0)
chams.Size = UDim2.new(0, 127, 0, 30)
chams.Font = Enum.Font.SourceSans
chams.Text = "Chams/ESP"
chams.TextColor3 = Color3.fromRGB(255, 255, 255)
chams.TextSize = 25.000

TextLabel_5.Parent = AimEsp_2
TextLabel_5.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_5.BackgroundTransparency = 1.000
TextLabel_5.Position = UDim2.new(0.0544041432, 0, 0.372093022, 0)
TextLabel_5.Size = UDim2.new(0, 112, 0, 30)
TextLabel_5.Font = Enum.Font.SourceSans
TextLabel_5.Text = "Not working yet..."
TextLabel_5.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_5.TextSize = 16.000

TextLabel_6.Parent = AimEsp_2
TextLabel_6.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_6.BackgroundTransparency = 1.000
TextLabel_6.Position = UDim2.new(0.0544041432, 0, 0.255813956, 0)
TextLabel_6.Size = UDim2.new(0, 112, 0, 20)
TextLabel_6.Font = Enum.Font.SourceSans
TextLabel_6.Text = "^^"
TextLabel_6.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_6.TextSize = 16.000

xray.Name = "x-ray"
xray.Parent = AimEsp_2
xray.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
xray.BackgroundTransparency = 1.000
xray.BorderSizePixel = 0
xray.Position = UDim2.new(0.51295346, 0, 0.654999971, 0)
xray.Size = UDim2.new(0, 127, 0, 30)
xray.Font = Enum.Font.SourceSans
xray.Text = "X-Ray"
xray.TextColor3 = Color3.fromRGB(255, 255, 255)
xray.TextSize = 25.000

Top.Name = "Top"
Top.Parent = Main
Top.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Top.BackgroundTransparency = 1.000
Top.Position = UDim2.new(-6.22107734e-08, 0, 0, 0)
Top.Size = UDim2.new(0, 489, 0, 22)
Top.Image = "rbxassetid://3570695787"
Top.ImageColor3 = Color3.fromRGB(40, 40, 40)
Top.ScaleType = Enum.ScaleType.Slice
Top.SliceCenter = Rect.new(100, 100, 100, 100)
Top.SliceScale = 0.120

Minimize.Name = "Minimize"
Minimize.Parent = Top
Minimize.BackgroundColor3 = Color3.fromRGB(28, 28, 28)
Minimize.BackgroundTransparency = 1.000
Minimize.BorderSizePixel = 0
Minimize.Position = UDim2.new(0.934308589, 0, 0, 0)
Minimize.Size = UDim2.new(0, 32, 0, 22)
Minimize.Font = Enum.Font.SourceSans
Minimize.Text = "-"
Minimize.TextColor3 = Color3.fromRGB(255, 255, 255)
Minimize.TextSize = 25.000

Delux.Name = "Delux"
Delux.Parent = Top
Delux.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Delux.BackgroundTransparency = 1.000
Delux.BorderSizePixel = 0
Delux.Position = UDim2.new(6.24081338e-08, 0, 0, 0)
Delux.Size = UDim2.new(0, 62, 0, 22)
Delux.Font = Enum.Font.SourceSansBold
Delux.Text = "Delux"
Delux.TextColor3 = Color3.fromRGB(0, 125, 255)
Delux.TextSize = 25.000

Hub.Name = "Hub"
Hub.Parent = Top
Hub.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Hub.BackgroundTransparency = 1.000
Hub.BorderSizePixel = 0
Hub.Position = UDim2.new(0.128426895, 0, 0, 0)
Hub.Size = UDim2.new(0, 31, 0, 22)
Hub.Font = Enum.Font.SourceSans
Hub.Text = "Hub"
Hub.TextColor3 = Color3.fromRGB(255, 255, 255)
Hub.TextSize = 25.000

Loader.Name = "Loader"
Loader.Parent = DeluxHub
Loader.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Loader.BackgroundTransparency = 1.000
Loader.Position = UDim2.new(0.463096946, 0, 0.36245507, 0)
Loader.Size = UDim2.new(0.0725036189, 0, 0.146893352, 0)
Loader.Visible = false
Loader.Image = "rbxassetid://3570695787"
Loader.ImageColor3 = Color3.fromRGB(40, 40, 40)
Loader.ScaleType = Enum.ScaleType.Slice
Loader.SliceCenter = Rect.new(100, 100, 100, 100)
Loader.SliceScale = 0.120

Logo.Name = "Logo"
Logo.Parent = Loader
Logo.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Logo.BackgroundTransparency = 1.000
Logo.BorderSizePixel = 0
Logo.Position = UDim2.new(0.0668723136, 0, 0.0599133968, 0)
Logo.Size = UDim2.new(0.857896805, 0, 0.865195215, 0)
Logo.Visible = false
Logo.Image = "rbxassetid://5213385332"

-- Scripts:

local function SAQP_fake_script() -- TabSelector.LocalScript 
	local script = Instance.new('LocalScript', TabSelector)

	local g = script.Parent.Games
	local p = script.Parent
	local LBTN = p.Local
	local CBTN = p.Info
	local RBTN = p.RemoteSpy
	local GBTN = g.Game
	local SBTN = p.Server
	local tab = script.Parent.Parent.TabHolder
	local loc = tab.Local
	local spy = tab.Remotespy
	local cre = tab.Info
	local ser = tab.Server
	local gaem = nil
	for _, v in pairs(tab.Games:GetChildren()) do
		v.Visible = false
	end
	g.Game.Visible = false
	local function check(Id, Name, Object)
		if game.PlaceId == Id then --Check
			GBTN.Text = Name
			gaem = Object
			g.Game.Visible = true
			gaem.Visible = true
		end
	end
	
	check(286090429,'Arsenal', tab.Games.Arsenal)
	check(142823291,'Murder Mistery 2',tab.Games.MM2)
	check(893973440,'Flee the Facility[Beta]', tab.Games.FleeTheFacility)
	
	LBTN.MouseButton1Down:Connect(function()
		for _, v in pairs(tab:GetChildren()) do
			v.Visible = false
		end
		tab:TweenSize(UDim2.new(0, 490,0, 10), 'Out', 'Quad', 0.4)
		wait(0.4)
		tab:TweenSize(UDim2.new(0, 490,0, 173), 'Out', 'Quad', 0.4)
		wait(0.3)
		loc.Visible = true
	end)
	
	CBTN.MouseButton1Down:Connect(function()
		for _, v in pairs(tab:GetChildren()) do
			v.Visible = false
		end
		tab:TweenSize(UDim2.new(0, 490,0, 10), 'Out', 'Quad', 0.4)
		wait(0.4)
		tab:TweenSize(UDim2.new(0, 490,0, 173), 'Out', 'Quad', 0.4)
		wait(0.3)
		cre.Visible = true
	end)
	
	RBTN.MouseButton1Down:Connect(function()
		for _, v in pairs(tab:GetChildren()) do
			v.Visible = false
		end
		tab:TweenSize(UDim2.new(0, 490,0, 10), 'Out', 'Quad', 0.4)
		wait(0.4)
		tab:TweenSize(UDim2.new(0, 490,0, 173), 'Out', 'Quad', 0.4)
		wait(0.3)
		spy.Visible = true
	end)
	
	GBTN.MouseButton1Down:Connect(function()
		for _, v in pairs(tab:GetChildren()) do
			v.Visible = false
		end
		tab:TweenSize(UDim2.new(0, 490,0, 10), 'Out', 'Quad', 0.4)
		wait(0.4)
		tab:TweenSize(UDim2.new(0, 490,0, 173), 'Out', 'Quad', 0.4)
		wait(0.3)
		tab.Games.Visible = true
		gaem.Visible = true
	end)
	
	SBTN.MouseButton1Down:Connect(function()
		for _, v in pairs(tab:GetChildren()) do
			v.Visible = false
		end
		tab:TweenSize(UDim2.new(0, 490,0, 10), 'Out', 'Quad', 0.4)
		wait(0.4)
		tab:TweenSize(UDim2.new(0, 490,0, 173), 'Out', 'Quad', 0.4)
		wait(0.3)
		ser.Visible = true
	end)
end
coroutine.wrap(SAQP_fake_script)()
local function URUEU_fake_script() -- ControlPanel.LocalScript 
	local script = Instance.new('LocalScript', ControlPanel)

	local tab = script.Parent.Parent.Tabs
	local inf = tab.Info
	local plr = tab.Players
	local INF = script.Parent.Info
	local PLR = script.Parent.Players
	
	INF.MouseButton1Down:Connect(function()
	for _, v in pairs(tab:GetChildren()) do
		v.Visible = false
		end
		tab:TweenSize(UDim2.new(0, 0,0, 172), 'Out', 'Quad', 0.4)
		wait(0.4)
		tab:TweenSize(UDim2.new(0, 388,0, 172), 'Out', 'Quad', 0.4)
		wait(0.3)
		inf.Visible = true
	end)
	
	PLR.MouseButton1Down:Connect(function()
	for _, v in pairs(tab:GetChildren()) do
			v.Visible = false
		end
		tab:TweenSize(UDim2.new(0, 0,0, 172), 'Out', 'Quad', 0.4)
		wait(0.4)
		tab:TweenSize(UDim2.new(0, 388,0, 172), 'Out', 'Quad', 0.4)
		wait(0.3)
		plr.Visible = true
	end)
end
coroutine.wrap(URUEU_fake_script)()
local function IZJJF_fake_script() -- JID.LocalScript 
	local script = Instance.new('LocalScript', JID)

	local p = script.Parent
	
	p.Text = game.JobId
end
coroutine.wrap(IZJJF_fake_script)()
local function QJVC_fake_script() -- ServerTime.LocalScript 
	local script = Instance.new('LocalScript', ServerTime)

	local p = script.Parent
	
	while wait() do script.Parent.Text = 'Server Time: ' .. tostring(game:GetService('Workspace').DistributedGameTime) end
end
coroutine.wrap(QJVC_fake_script)()
local function BGMRRMZ_fake_script() -- GameName.LocalScript 
	local script = Instance.new('LocalScript', GameName)

	local p = script.Parent
	local marketplaceService = game:GetService("MarketplaceService")
	local isSuccessful, info = pcall(marketplaceService.GetProductInfo, marketplaceService, game.PlaceId)
	if isSuccessful then
	    p.Text = info.Name
	end
end
coroutine.wrap(BGMRRMZ_fake_script)()
local function BITZEJ_fake_script() -- PlaceId.LocalScript 
	local script = Instance.new('LocalScript', PlaceId)

	local p = script.Parent
	
	while wait() do p.Text = "PlaceId: " .. game.PlaceId end
end
coroutine.wrap(BITZEJ_fake_script)()
local function CIGPZL_fake_script() -- Players_2.LocalScript 
	local script = Instance.new('LocalScript', Players_2)

	local p = script.Parent
	
	
	while wait() do p.Text = "Players: " ..#game.Players:GetPlayers() end
end
coroutine.wrap(CIGPZL_fake_script)()
local function CYQXXT_fake_script() -- Players_3.PlayerHandler 
	local script = Instance.new('LocalScript', Players_3)

	local tab = script.Parent.PlayerTab
	local pos = tab.Ori.Position
	
	for _,v in pairs(tab:GetChildren()) do
		v.Visible = false
	end
	
	local function Add(name)
		local clone = tab.Ori:Clone();
		clone.Name = "KeyFrame"
		clone.Parent = tab;
		local Players = game:GetService("Players");
		local userId = name.UserId;
		local thumbType = Enum.ThumbnailType.HeadShot;
		local thumbSize = Enum.ThumbnailSize.Size420x420;
		local content, isReady = Players:GetUserThumbnailAsync(userId, thumbType, thumbSize);
		local imageLabel = clone.PFP;
		imageLabel.Image = content;
		clone.Naem.Text = name.Name;
		clone.Position = pos;
		pos = pos + UDim2.new(0,0,0,45);
		clone.Visible = true;
			clone.TP.MouseButton1Down:Connect(function()
			local a = clone.Naem.Text
			    for i,v in pairs(game.Players:GetChildren()) do
		        local b = v.Character
		        if a == b.Name then
					game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = b.HumanoidRootPart.CFrame
		        end
		    end
		end)
	end
	
	for _,v in pairs(game.Players:GetChildren()) do
		Add(v)
	end
	
	game.Players.ChildAdded:Connect(function(child)
		Add(child)
	end)
	
	game.Players.ChildRemoved:Connect(function(child)
		for _,v in pairs(tab:GetChildren()) do
			if v.Name == "KeyFrame" then
				v:Destroy()
				pos = UDim2.new(0,0,0,0);
			end
		end
		for _,v in pairs(game.Players:GetChildren()) do
			Add(v)
		end
	end)
end
coroutine.wrap(CYQXXT_fake_script)()
local function EHKIY_fake_script() -- IEX.LocalScript 
	local script = Instance.new('LocalScript', IEX)

	local p = script.Parent
	local on = false
	local plr = game.Players.LocalPlayer
	local mouse = plr:GetMouse()
	
	p.MouseButton1Down:Connect(function()
		if on == true then
			on = false
			p.Text = "OFF"
				p.TextColor3 = Color3.fromRGB(255, 0, 0)
					p:TweenPosition(UDim2.new(0.477, 0,-0.12, 0), 'Out', 'Quad', 0.2)
					wait(0.2001)
		else
			on = true
				p.Text = "ON"
				p:TweenPosition(UDim2.new(-0.005, 0,-0.12, 0), 'Out', 'Quad', 0.2)
			p.TextColor3 = Color3.fromRGB(85, 255, 0)
									ALLYCOLOR = {0,255,255}  	--//Color of the ESP  of people on the same team
									ENEMYCOLOR =  {255,0,0} 	--//Color of the ESP  of people on NOT the same team
									TRANSPARENCY = 0.5			--//Transparency of the ESP
									HEALTHBAR_ACTIVATED = true 	--//Renders the Healthbar
	--
	--
	
	--							!!!Don't Change Anything Below Here Unless You Know What You're Doing!!!
	
	function createFlex()
	-- -----------------------------------------------------------------------------------
	--[VARIABLES] //Changing may result in Errors!
	players = game:GetService("Players") --//Required for PF
	faces = {"Front","Back","Bottom","Left","Right","Top"} --//Every possible Enum face
	currentPlayer = nil --//Used for the Team-Check
	lplayer = players.LocalPlayer --//The LocalPlayer
	-- -----------------------------------------------------------------------------------
	players.PlayerAdded:Connect(function(p)
		currentPlayer = p
			p.CharacterAdded:Connect(function(character) --//For when a new Player joins the game 
				createESP(character)			
			end)		
	end)
	-- -----------------------------------------------------------------------------------
	function checkPart(obj)  if (obj:IsA("Part") or obj:IsA("MeshPart")) and obj.Name~="HumanoidRootPart" then return true end end --//Check if the Part is suitable 
	-- -----------------------------------------------------------------------------------
	function actualESP(obj) 
		
		for i=0,5 do
			surface = Instance.new("SurfaceGui",obj) --//Creates the SurfaceGui
			surface.Face = Enum.NormalId[faces[i+1]] --//Adjusts the Face and chooses from the face table
			surface.AlwaysOnTop = true
	
			frame = Instance.new("Frame",surface)	--//Creates the viewable Frame
			frame.Size = UDim2.new(1,0,1,0)
			frame.BorderSizePixel = 0												
			frame.BackgroundTransparency = TRANSPARENCY
				if currentPlayer.Team == players.LocalPlayer.Team then --//Checks the Players Team
						frame.BackgroundColor3 = Color3.new(ALLYCOLOR[1],ALLYCOLOR[2],ALLYCOLOR[3])	--//If in same Team											
				else
					frame.BackgroundColor3 = Color3.new(ENEMYCOLOR[1],ENEMYCOLOR[2],ENEMYCOLOR[3])	--//If in another Team
				end
																
		end
	end
	-- -----------------------------------------------------------------------------------
	function createHealthbar(hrp) 
		board =Instance.new("BillboardGui",hrp) --//Creates the BillboardGui with HumanoidRootPart as the Parent
		board.Name = "total"
		board.Size = UDim2.new(1,0,1,0)
		board.StudsOffset = Vector3.new(3,1,0)
		board.AlwaysOnTop = true
	
		bar = Instance.new("Frame",board) --//Creates the red background
		bar.BackgroundColor3 = Color3.new(255,0,0)
		bar.BorderSizePixel = 0
		bar.Size = UDim2.new(0.2,0,4,0)
		bar.Name = "total2"
													
		health = Instance.new("Frame",bar) --//Creates the changing green Frame
		health.BackgroundColor3 = Color3.new(0,255,0)
		health.BorderSizePixel = 0
		health.Size = UDim2.new(1,0,hrp.Parent.Humanoid.Health/100,0)
			hrp.Parent.Humanoid.Changed:Connect(function(property) --//Triggers when any Property changed
				hrp.total.total2.Frame.Size = UDim2.new(1,0,hrp.Parent.Humanoid.Health/100,0) --//Adjusts the size of the green Frame								
			end)
	end
	-- -----------------------------------------------------------------------------------
	function createESP(c) --//Checks and calls the proper function
		bugfix = c:WaitForChild("Head") --// *Used so the children of the character arent nil.
		for i,v in pairs(c:GetChildren()) do
			if checkPart(v) then
			actualESP(v)
			end
		end
		if HEALTHBAR_ACTIVATED then --//If the user decided to
			createHealthbar(c:WaitForChild("HumanoidRootPart")) --//Calls the function of the creation
		end
	end
	-- -----------------------------------------------------------------------------------
	for i,people in pairs(players:GetChildren())do
		if people ~= players.LocalPlayer and on == true then
			currentPlayer = people
																	--//Used for Players already in the Game
			createESP(people.Character)
				people.CharacterAdded:Connect(function(character)
					createESP(character)			
				end)
		end
	end
	-- -----------------------------------------------------------------------------------
	end --//End of the entire function
	
	createFlex() --// Does exactly that :)
				wait(0.2001)
		end
	end)
end
coroutine.wrap(EHKIY_fake_script)()
local function IVGZ_fake_script() -- IEX_2.LocalScript 
	local script = Instance.new('LocalScript', IEX_2)

	local p = script.Parent
	local on = false
	
	p.MouseButton1Down:Connect(function()
		if on == true then
			on = false
				p.Text = "OFF"
				p.TextColor3 = Color3.fromRGB(255, 0, 0)
					p:TweenPosition(UDim2.new(0.477, 0,-0.12, 0), 'Out', 'Quad', 0.2)
					wait(0.2001)
		else
			on = true
				p.Text = "ON"
				p:TweenPosition(UDim2.new(-0.005, 0,-0.12, 0), 'Out', 'Quad', 0.2)
			p.TextColor3 = Color3.fromRGB(85, 255, 0)
				wait(0.2001)
		end
	end)
	--/-------------
	--| MADE BY HELLOM8L0L
	--\-------------
end
coroutine.wrap(IVGZ_fake_script)()
local function IMNC_fake_script() -- IEX_3.LocalScript 
	local script = Instance.new('LocalScript', IEX_3)

	local p = script.Parent
	local on = false
	
	p.MouseButton1Down:Connect(function()
		if on == true then
			on = false
			game.Players.LocalPlayer.Character.HumanoidRootPart.Anchored = false
				p.Text = "OFF"
				p.TextColor3 = Color3.fromRGB(255, 0, 0)
					p:TweenPosition(UDim2.new(0.477, 0,-0.12, 0), 'Out', 'Quad', 0.2)
					wait(0.2001)
		else
			on = true
			game.Players.LocalPlayer.Character.HumanoidRootPart.Anchored = true
				p.Text = "ON"
				p:TweenPosition(UDim2.new(-0.005, 0,-0.12, 0), 'Out', 'Quad', 0.2)
			p.TextColor3 = Color3.fromRGB(85, 255, 0)
				wait(0.2001)
		end
	end)
	--/-------------
	--| MADE BY HELLOM8L0L
	--\-------------
	
end
coroutine.wrap(IMNC_fake_script)()
local function TAMMQN_fake_script() -- IEX_4.LocalScript 
	local script = Instance.new('LocalScript', IEX_4)

	local p = script.Parent
	local on = false
	
	p.MouseButton1Down:Connect(function()
		if on == true then
			on = false
				p.Text = "OFF"
				p.TextColor3 = Color3.fromRGB(255, 0, 0)
					p:TweenPosition(UDim2.new(0.477, 0,-0.12, 0), 'Out', 'Quad', 0.2)
					wait(0.2001)
		else
			on = true
			p.Text = "ON"
				p:TweenPosition(UDim2.new(-0.005, 0,-0.12, 0), 'Out', 'Quad', 0.2)
			p.TextColor3 = Color3.fromRGB(85, 255, 0)
					while wait() do
	            for _,v in pairs(game.Players:GetChildren()) do
	                v.Character.HumanoidRootPart.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame.Lookvector * 5
	            end
	            if on == false then break end
	        end
				wait(0.2001)
		end
	end)
	--/-------------
	--| MADE BY HELLOM8L0L
	--\-------------
end
coroutine.wrap(TAMMQN_fake_script)()
local function APJPQK_fake_script() -- IEX_5.LocalScript 
	local script = Instance.new('LocalScript', IEX_5)

	local p = script.Parent
	local on = false
	
	p.MouseButton1Down:Connect(function()
		if on == true then
			on = false
				p.Text = "OFF"
				p.TextColor3 = Color3.fromRGB(255, 0, 0)
					p:TweenPosition(UDim2.new(0.477, 0,-0.12, 0), 'Out', 'Quad', 0.2)
					wait(0.2001)
		else
			on = true
				p.Text = "ON"
				p:TweenPosition(UDim2.new(-0.005, 0,-0.12, 0), 'Out', 'Quad', 0.2)
			p.TextColor3 = Color3.fromRGB(85, 255, 0)
			game:GetService('RunService').Stepped:connect(function()
				if on then
				game.Players.LocalPlayer.Character.Humanoid:ChangeState(11)
				end
				end)
				if on == true then
				game.Players.LocalPlayer.Character.Humanoid:ChangeState(11)
			end
		end
	end)
	--/-------------
	--| MADE BY HELLOM8L0L
	--\-------------
end
coroutine.wrap(APJPQK_fake_script)()
local function ZQNDBK_fake_script() -- ControlPanel_2.LocalScript 
	local script = Instance.new('LocalScript', ControlPanel_2)

	local tab = script.Parent.Parent.Tabs
	local info = tab.Credits
	local log = tab.Changelogs
	local sett = tab.Settings
	local CRE = script.Parent.Credits
	local CHA = script.Parent.ChangeLogs
	local SET = script.Parent.Settings
	
	CRE.MouseButton1Down:Connect(function()
	for _, v in pairs(tab:GetChildren()) do
		v.Visible = false
		end
		tab:TweenSize(UDim2.new(0, 0,0, 171), 'Out', 'Quad', 0.4)
		wait(0.4)
		tab:TweenSize(UDim2.new(0, 375,0, 171), 'Out', 'Quad', 0.4)
		wait(0.3)
		info.Visible = true
	end)
	
	CHA.MouseButton1Down:Connect(function()
	for _, v in pairs(tab:GetChildren()) do
		v.Visible = false
		end
		tab:TweenSize(UDim2.new(0, 0,0, 171), 'Out', 'Quad', 0.4)
		wait(0.4)
		tab:TweenSize(UDim2.new(0, 375,0, 171), 'Out', 'Quad', 0.4)
		wait(0.3)
		log.Visible = true
	end)
	
	SET.MouseButton1Down:Connect(function()
	for _, v in pairs(tab:GetChildren()) do
		v.Visible = false
		end
		tab:TweenSize(UDim2.new(0, 0,0, 171), 'Out', 'Quad', 0.4)
		wait(0.4)
		tab:TweenSize(UDim2.new(0, 375,0, 171), 'Out', 'Quad', 0.4)
		wait(0.3)
		sett.Visible = true
	end)
end
coroutine.wrap(ZQNDBK_fake_script)()
local function WDZMOAZ_fake_script() -- IEX_6.LocalScript 
	local script = Instance.new('LocalScript', IEX_6)

	script.Parent.Parent[":o"].Visible = false
	local p = script.Parent
	local on = false
	
	p.MouseButton1Down:Connect(function()
		if on == true then
			on = false
			script.Parent.Parent[":o"].Visible = true
			wait()
			script.Parent.Parent[":o"].Visible = false
				p.Text = "OFF"
				p.TextColor3 = Color3.fromRGB(255, 0, 0)
					p:TweenPosition(UDim2.new(0.477, 0,-0.12, 0), 'Out', 'Quad', 0.2)
			wait(0.2001)
		else
			script.Parent.Parent[":o"].Visible = true
			wait()
			script.Parent.Parent[":o"].Visible = false
			on = true
				p.Text = "ON"
				p:TweenPosition(UDim2.new(-0.005, 0,-0.12, 0), 'Out', 'Quad', 0.2)
			p.TextColor3 = Color3.fromRGB(85, 255, 0)
				wait(0.2001)
		end
	end)
	--/-------------
	--| MADE BY HELLOM8L0L
	--\-------------
end
coroutine.wrap(WDZMOAZ_fake_script)()
local function UKEFUT_fake_script() -- Discord.Clip 
	local script = Instance.new('LocalScript', Discord)

	script.Parent.Clipped.Visible = false
	
	script.Parent.MouseButton1Down:Connect(function()
		setclipboard("https://discord.gg/5r6qjPR")
		script.Parent.Clipped.Visible = true
		wait(1)
		script.Parent.Clipped.Visible = false
	end)
end
coroutine.wrap(UKEFUT_fake_script)()
local function HRVSGMA_fake_script() -- HubColors.LocalScript 
	local script = Instance.new('LocalScript', HubColors)

	local color = script.Parent.Parent.Colors
	local shown = false
	local function open()
		color.Visible = true
		color:TweenSize(UDim2.new(0, 372,0, 128),'Out', 'Sine', 0.5)
		shown = true
	end
	local function close()
		color:TweenSize(UDim2.new(0, 372,0, 0),'Out', 'Sine', 0.5)
		wait(0.5)
		color.Visible = false
		shown = false
	end
	close()
	
	script.Parent.MouseButton1Down:Connect(function()
		if shown == true then
			close()
		else
			open()
		end
	end)
	
end
coroutine.wrap(HRVSGMA_fake_script)()
local function XPYPAGR_fake_script() -- TextButton_2.LocalScript 
	local script = Instance.new('LocalScript', TextButton_2)

	script.Parent.MouseButton1Up:Connect(function()
	script.Parent.Parent.Parent.Parent.Parent.Parent.Parent.TabSelector.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
	script.Parent.Parent.Parent.Parent.ImageColor3 = Color3.fromRGB(0, 0, 0)
	script.Parent.Parent.Parent.Parent.Parent.Parent.Parent.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
	script.Parent.Parent.Parent.Parent.Parent.ControlPanel.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
	end)
end
coroutine.wrap(XPYPAGR_fake_script)()
local function MWQIEAB_fake_script() -- TextButton_3.LocalScript 
	local script = Instance.new('LocalScript', TextButton_3)

	script.Parent.MouseButton1Up:Connect(function()
	script.Parent.Parent.Parent.Parent.Parent.Parent.Parent.TabSelector.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	script.Parent.Parent.Parent.Parent.ImageColor3 = Color3.fromRGB(255, 255, 255)
	script.Parent.Parent.Parent.Parent.Parent.Parent.Parent.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	script.Parent.Parent.Parent.Parent.Parent.ControlPanel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	
	end)
end
coroutine.wrap(MWQIEAB_fake_script)()
local function BBKVMOY_fake_script() -- TextButton_4.LocalScript 
	local script = Instance.new('LocalScript', TextButton_4)

	script.Parent.MouseButton1Up:Connect(function()
	script.Parent.Parent.Parent.Parent.Parent.Parent.Parent.TabSelector.BackgroundColor3 = Color3.fromRGB(85, 0, 127)
	script.Parent.Parent.Parent.Parent.ImageColor3 = Color3.fromRGB(85, 0, 127)
	script.Parent.Parent.Parent.Parent.Parent.Parent.Parent.BackgroundColor3 = Color3.fromRGB(85, 0, 127)
	script.Parent.Parent.Parent.Parent.Parent.ControlPanel.BackgroundColor3 = Color3.fromRGB(85, 0, 127)
	
	end)
end
coroutine.wrap(BBKVMOY_fake_script)()
local function EZFELY_fake_script() -- TextButton_5.LocalScript 
	local script = Instance.new('LocalScript', TextButton_5)

	script.Parent.MouseButton1Up:Connect(function()
	script.Parent.Parent.Parent.Parent.Parent.Parent.Parent.TabSelector.BackgroundColor3 = Color3.fromRGB(170, 0, 255)
	script.Parent.Parent.Parent.Parent.ImageColor3 = Color3.fromRGB(170, 0, 255)
	script.Parent.Parent.Parent.Parent.Parent.Parent.Parent.BackgroundColor3 = Color3.fromRGB(170, 0, 255)
	script.Parent.Parent.Parent.Parent.Parent.ControlPanel.BackgroundColor3 = Color3.fromRGB(170, 0, 255)
	
	end)
end
coroutine.wrap(EZFELY_fake_script)()
local function KJQTA_fake_script() -- TextButton_6.LocalScript 
	local script = Instance.new('LocalScript', TextButton_6)

	script.Parent.MouseButton1Up:Connect(function()
	script.Parent.Parent.Parent.Parent.Parent.Parent.Parent.TabSelector.BackgroundColor3 = Color3.fromRGB(170, 255, 0)
	script.Parent.Parent.Parent.Parent.ImageColor3 = Color3.fromRGB(170, 255, 0)
	script.Parent.Parent.Parent.Parent.Parent.Parent.Parent.BackgroundColor3 = Color3.fromRGB(170, 255, 0)
	script.Parent.Parent.Parent.Parent.Parent.ControlPanel.BackgroundColor3 = Color3.fromRGB(170, 255, 0)
	
	end)
end
coroutine.wrap(KJQTA_fake_script)()
local function WBXWFI_fake_script() -- TextButton_7.LocalScript 
	local script = Instance.new('LocalScript', TextButton_7)

	script.Parent.MouseButton1Up:Connect(function()
	script.Parent.Parent.Parent.Parent.Parent.Parent.Parent.TabSelector.BackgroundColor3 = Color3.fromRGB(255, 85, 0)
	script.Parent.Parent.Parent.Parent.ImageColor3 = Color3.fromRGB(255, 85, 0)
	script.Parent.Parent.Parent.Parent.Parent.Parent.Parent.BackgroundColor3 = Color3.fromRGB(255, 85, 0)
	script.Parent.Parent.Parent.Parent.Parent.ControlPanel.BackgroundColor3 = Color3.fromRGB(255, 85, 0)
	
	end)
end
coroutine.wrap(WBXWFI_fake_script)()
local function FECB_fake_script() -- TextButton_8.LocalScript 
	local script = Instance.new('LocalScript', TextButton_8)

	script.Parent.MouseButton1Up:Connect(function()
	script.Parent.Parent.Parent.Parent.Parent.Parent.Parent.TabSelector.BackgroundColor3 = Color3.fromRGB(85, 0, 255)
	script.Parent.Parent.Parent.Parent.ImageColor3 = Color3.fromRGB(85, 0, 255)
	script.Parent.Parent.Parent.Parent.Parent.Parent.Parent.BackgroundColor3 = Color3.fromRGB(85, 0, 255)
	script.Parent.Parent.Parent.Parent.Parent.ControlPanel.BackgroundColor3 = Color3.fromRGB(85, 0, 255)
	
	end)
end
coroutine.wrap(FECB_fake_script)()
local function PHDVRK_fake_script() -- TextButton_9.LocalScript 
	local script = Instance.new('LocalScript', TextButton_9)

	script.Parent.MouseButton1Up:Connect(function()
	script.Parent.Parent.Parent.Parent.Parent.Parent.Parent.TabSelector.BackgroundColor3 = Color3.fromRGB(0, 125, 225)
	script.Parent.Parent.Parent.Parent.ImageColor3 = Color3.fromRGB(0, 125, 225)
	script.Parent.Parent.Parent.Parent.Parent.Parent.Parent.BackgroundColor3 = Color3.fromRGB(0, 125, 225)
	script.Parent.Parent.Parent.Parent.Parent.ControlPanel.BackgroundColor3 = Color3.fromRGB(0, 125, 225)
	
	end)
end
coroutine.wrap(PHDVRK_fake_script)()
local function WTCTF_fake_script() -- TextButton_10.LocalScript 
	local script = Instance.new('LocalScript', TextButton_10)

	script.Parent.MouseButton1Up:Connect(function()
	script.Parent.Parent.Parent.Parent.Parent.Parent.Parent.TabSelector.BackgroundColor3 = Color3.fromRGB(85, 255, 0)
	script.Parent.Parent.Parent.Parent.ImageColor3 = Color3.fromRGB(85, 255, 0)
	script.Parent.Parent.Parent.Parent.Parent.Parent.Parent.BackgroundColor3 = Color3.fromRGB(85, 255, 0)
	script.Parent.Parent.Parent.Parent.Parent.ControlPanel.BackgroundColor3 = Color3.fromRGB(85, 255, 0)
	
	end)
end
coroutine.wrap(WTCTF_fake_script)()
local function EYIMWA_fake_script() -- edit.LocalScript 
	local script = Instance.new('LocalScript', edit)

	script.Parent.MouseButton1Up:Connect(function()
	script.Parent.Parent.Parent.Parent.Parent.Parent.Parent.TabSelector.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
	script.Parent.Parent.Parent.Parent.ImageColor3 = Color3.fromRGB(255, 0, 0)
	script.Parent.Parent.Parent.Parent.Parent.Parent.Parent.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
	script.Parent.Parent.Parent.Parent.Parent.ControlPanel.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
	
	end)
end
coroutine.wrap(EYIMWA_fake_script)()
local function PHPXJH_fake_script() -- Original.LocalScript 
	local script = Instance.new('LocalScript', Original)

	local pos = script.Parent.Position
	
	local function add(text)
		local e = script.Parent:Clone()
		e.LocalScript:Destroy()
		e.Name = "Clone"
		e.Parent = script.Parent.Parent
		e.Visible = true
		e.Position = pos
		e.Text = (text)
		pos = pos + UDim2.new(0,0,0,115)
	end
	_G.scanRemotes = true
	
	_G.ignoreNames = {
		Event = true;
		MessagesChanged = true;
	}
	
	setreadonly(getrawmetatable(game), false)
	local pseudoEnv = {}
	local gameMeta = getrawmetatable(game)
	
	local tabChar = "      "
	
	local function getSmaller(a, b, notLast)
		local aByte = a:byte() or -1
		local bByte = b:byte() or -1
		if aByte == bByte then
			if notLast and #a == 1 and #b == 1 then
				return -1
			elseif #b == 1 then
				return false
			elseif #a == 1 then
				return true
			else
				return getSmaller(a:sub(2), b:sub(2), notLast)
			end
		else
			return aByte < bByte
		end
	end
	
	local function parseData(obj, numTabs, isKey, overflow, noTables, forceDict)
		local objType = typeof(obj)
		local objStr = tostring(obj)
		if objType == "table" then
			if noTables then
				return objStr
			end
			local isCyclic = overflow[obj]
			overflow[obj] = true
			local out = {}
			local nextIndex = 1
			local isDict = false
			local hasTables = false
			local data = {}
	
			for key, val in next, obj do
				if not hasTables and typeof(val) == "table" then
					hasTables = true
				end
	
				if not isDict and key ~= nextIndex then
					isDict = true
				else
					nextIndex = nextIndex + 1
				end
	
				data[#data+1] = {key, val}
			end
	
			if isDict or hasTables or forceDict then
				out[#out+1] = (isCyclic and "Cyclic " or "") .. "{"
				table.sort(data, function(a, b)
					local aType = typeof(a[2])
					local bType = typeof(b[2])
					if bType == "string" and aType ~= "string" then
						return false
					end
					local res = getSmaller(aType, bType, true)
					if res == -1 then
						return getSmaller(tostring(a[1]), tostring(b[1]))
					else
						return res
					end
				end)
				for i = 1, #data do
					local arr = data[i]
					local nowKey = arr[1]
					local nowVal = arr[2]
					local parseKey = parseData(nowKey, numTabs+1, true, overflow, isCyclic)
					local parseVal = parseData(nowVal, numTabs+1, false, overflow, isCyclic)
					if isDict then
						local nowValType = typeof(nowVal)
						local preStr = ""
						local postStr = ""
						if i > 1 and (nowValType == "table" or typeof(data[i-1][2]) ~= nowValType) then
							preStr = "\n"
						end
						if i < #data and nowValType == "table" and typeof(data[i+1][2]) ~= "table" and typeof(data[i+1][2]) == nowValType then
							postStr = "\n"
						end
						out[#out+1] = preStr .. string.rep(tabChar, numTabs+1) .. parseKey .. " = " .. parseVal .. ";" .. postStr
					else
						out[#out+1] = string.rep(tabChar, numTabs+1) .. parseVal .. ";"
					end
				end
				out[#out+1] = string.rep(tabChar, numTabs) .. "}"
			else
				local data2 = {}
				for i = 1, #data do
					local arr = data[i]
					local nowVal = arr[2]
					local parseVal = parseData(nowVal, 0, false, overflow, isCyclic)
					data2[#data2+1] = parseVal
				end
				out[#out+1] = "{" .. table.concat(data2, ", ") .. "}"
			end
	
			return table.concat(out, "\n")
		else
			local returnVal = nil
			if (objType == "string" or objType == "Content") and (not isKey or tonumber(obj:sub(1, 1))) then
				local retVal = '"' .. objStr .. '"'
				if isKey then
					retVal = "[" .. retVal .. "]"
				end
				returnVal = retVal
			elseif objType == "EnumItem" then
				returnVal = "Enum." .. tostring(obj.EnumType) .. "." .. obj.Name
			elseif objType == "Enum" then
				returnVal = "Enum." .. objStr
			elseif objType == "Instance" then
				returnVal = obj.Parent and obj:GetFullName() or obj.ClassName
			elseif objType == "CFrame" then
				returnVal = "CFrame.new(" .. objStr .. ")"
			elseif objType == "Vector3" then
				returnVal = "Vector3.new(" .. objStr .. ")"
			elseif objType == "Vector2" then
				returnVal = "Vector2.new(" .. objStr .. ")"
			elseif objType == "UDim2" then
				returnVal = "UDim2.new(" .. objStr:gsub("[{}]", "") .. ")"
			elseif objType == "BrickColor" then
				returnVal = "BrickColor.new(\"" .. objStr .. "\")"
			elseif objType == "Color3" then
				returnVal = "Color3.new(" .. objStr .. ")"
			elseif objType == "NumberRange" then
				returnVal = "NumberRange.new(" .. objStr:gsub("^%s*(.-)%s*$", "%1"):gsub(" ", ", ") .. ")"
			elseif objType == "PhysicalProperties" then
				returnVal = "PhysicalProperties.new(" .. objStr .. ")"
			else
				returnVal = objStr
			end
			return returnVal
		end
	end
	
	function tableToString(t)
		return parseData(t, 0, false, {}, nil, false)
	end
	
	local detectClasses = {
		BindableEvent = true;
		BindableFunction = true;
		RemoteEvent = true;
		RemoteFunction = true;
	}
	
	local classMethods = {
		BindableEvent = "Fire";
		BindableFunction = "Invoke";
		RemoteEvent = "FireServer";
		RemoteFunction = "InvokeServer";
	}
	
	local realMethods = {}
	
	for name, enabled in next, detectClasses do
		if enabled then
			realMethods[classMethods[name]] = Instance.new(name)[classMethods[name]]
		end
	end
	
	for key, value in next, gameMeta do pseudoEnv[key] = value end
	
	local incId = 0
	
	local function getValues(self, key, ...)
		return {realMethods[key](self, ...)}
	end
	
	gameMeta.__index, gameMeta.__namecall = function(self, key)
		if not realMethods[key] or _G.ignoreNames[self.Name] or not _G.scanRemotes then return pseudoEnv.__index(self, key) end
		return function(_, ...)
			incId = incId + 1
			local nowId = incId
			local strId = "[RemoteSpy_" .. nowId .. "]"
	
			local allPassed = {...}
			local returnValues = {}
	
			local ok, data = pcall(getValues, self, key, ...)
	
			if ok then
				returnValues = data
				add("\n" .. strId .. " ClassName: " .. self.ClassName .. " | Path: " .. self:GetFullName() .. " | Method: " .. key .. "\n" .. strId .. " Packed Arguments: " .. tableToString(allPassed) .. "\n" .. strId .. " Packed Returned: " .. tableToString(returnValues) .. "\n")
			else
				add("\n" .. strId .. " ClassName: " .. self.ClassName .. " | Path: " .. self:GetFullName() .. " | Method: " .. key .. "\n" .. strId .. " Packed Arguments: " .. tableToString(allPassed) .. "\n" .. strId .. " Packed Returned: [ERROR] " .. data .. "\n")
			end
	
			return unpack(returnValues)
		end
	end
end
coroutine.wrap(PHPXJH_fake_script)()
local function SPQOI_fake_script() -- ClearLogs.LocalScript 
	local script = Instance.new('LocalScript', ClearLogs)

	script.Parent.MouseButton1Down:Connect(function()
		script.Parent.Parent.Parent.Logging.Original.Parent = script.Parent
				for _,v in pairs(script.Parent.Parent.Parent.Logging:GetDescendants()) do
					v:Destroy()
				end
			script.Parent.Original.Parent = script.Parent.Parent.Parent.Logging
		script.Parent.Parent.Parent.Logging.Original.Position = UDim2.new(0,0,0,0)
	end)
end
coroutine.wrap(SPQOI_fake_script)()
local function THUNE_fake_script() -- ControlPanel_4.LocalScript 
	local script = Instance.new('LocalScript', ControlPanel_4)

	local tab = script.Parent.Parent.Tabs
	local move = tab.Movement
	local hat = tab.Hats
	local bypass = tab.Bypass
	local aim_esp = tab["Aim/Esp"]
	local MOV = script.Parent.Movement
	local HAT = script.Parent.HatExploits
	local BYP = script.Parent.FEBypass
	local AIM = script.Parent["Aim/Esp"]
	
	MOV.MouseButton1Down:Connect(function()
	for _, v in pairs(tab:GetChildren()) do
		v.Visible = false
		end
		tab:TweenSize(UDim2.new(0, 0,0, 173), 'Out', 'Quad', 0.4)
		wait(0.4)
		tab:TweenSize(UDim2.new(0, 384,0, 173), 'Out', 'Quad', 0.4)
		wait(0.3)
		move.Visible = true
	end)
	
	HAT.MouseButton1Down:Connect(function()
	for _, v in pairs(tab:GetChildren()) do
		v.Visible = false
		end
		tab:TweenSize(UDim2.new(0, 0,0, 173), 'Out', 'Quad', 0.4)
		wait(0.4)
		tab:TweenSize(UDim2.new(0, 384,0, 173), 'Out', 'Quad', 0.4)
		wait(0.3)
		hat.Visible = true
	end)
	
	BYP.MouseButton1Down:Connect(function()
	for _, v in pairs(tab:GetChildren()) do
		v.Visible = false
		end
		tab:TweenSize(UDim2.new(0, 0,0, 173), 'Out', 'Quad', 0.4)
		wait(0.4)
		tab:TweenSize(UDim2.new(0, 384,0, 173), 'Out', 'Quad', 0.4)
		wait(0.3)
		bypass.Visible = true
	end)
	
	AIM.MouseButton1Down:Connect(function()
	for _, v in pairs(tab:GetChildren()) do
		v.Visible = false
		end
		tab:TweenSize(UDim2.new(0, 0,0, 173), 'Out', 'Quad', 0.4)
		wait(0.4)
		tab:TweenSize(UDim2.new(0, 384,0, 173), 'Out', 'Quad', 0.4)
		wait(0.3)
		aim_esp.Visible = true
	end)
end
coroutine.wrap(THUNE_fake_script)()
local function ZNGWIBP_fake_script() -- Hats.Worker 
	local script = Instance.new('LocalScript', Hats)

	-- Scripts:
	
		spawn(function()
			while true do
				game:GetService("RunService").Heartbeat:wait()
				for i, v in pairs(game.Players:GetPlayers()) do
					if v == game.Players.LocalPlayer == false then
						game.Players.LocalPlayer.MaximumSimulationRadius = math.pow(math.huge, math.huge) * math.huge
						game.Players.LocalPlayer.SimulationRadius = math.pow(math.huge, math.huge) * math.huge
						v.MaximumSimulationRadius = 0
						v.SimulationRadius = 0
						game:GetService("RunService").Stepped:wait()
					end
				end
			end
		end)
	--Variables
	
	local UIS = game:GetService("UserInputService")
	local plr = game.Players.LocalPlayer
	local char = plr.Character
	local mouse = plr:GetMouse()
	local val = script.Parent.Amount.AmountBTN
	
	local function OBLITERATE()
		game.Players.LocalPlayer.Character.Humanoid.Health = 0
		wait(game.Players.RespawnTime + 1)
		char.Humanoid.Health = math.huge
	end
	
	local function DropHats(amount)
	local value = "1"
		for i = 1, amount + 1 do
			for i, v in pairs(game.Players.LocalPlayer.Character:GetChildren()) do
				if (v:IsA("Accessory")) then
					v.Parent = workspace
					wait()
				end
			end
			if amount > value then
				wait(0.25)
				OBLITERATE()
			end
			print(i)
		end
	end
	local function AURA()
		local Player = game:GetService("Players").LocalPlayer
		local Players = game:GetService("Players")
		local HatList = {}
		local i = 0
		for _, l in pairs(Player.Character:GetChildren()) do
			if l:IsA("Accessory") then
				if i > 0 then
					l.Parent = workspace
				end
				i = i + 1
			end;
		end
		wait(.1)
	
	
	
		for _, v in pairs(game.Workspace:GetDescendants()) do
			if v.Name == "Handle" and v:IsA("BasePart") and v.Parent:IsA("Accessory") and v:IsDescendantOf(Player.Character) == false and Players:GetPlayerFromCharacter(v.Parent.Parent) == nil then
				table.insert(HatList, v)
			end
		end
	
		for _, hat in pairs(HatList) do
			hat.Parent = workspace
			hat.Position = Player.Character.HumanoidRootPart.Position + Player.Character.HumanoidRootPart.CFrame.lookVector * 5
			local BodyPos = Instance.new("BodyPosition", hat)
			local BodyAng = Instance.new("BodyAngularVelocity", hat)
			BodyAng.AngularVelocity = Vector3.new(0, 9e12, 0)
			BodyAng.P = 9e12
			BodyPos.MaxForce = Vector3.new(9e9, 9e9, 9e9)
			BodyPos.P = 9e8
			spawn(function()
				while wait() do
					if pcall(function()
						hat.CanCollide = false
						BodyPos.Position = Player.Character.HumanoidRootPart.Position + Vector3.new(math.random(-2, 2), math.random(-2, 2), math.random(-2, 2))
					end) then
					else
						BodyPos:Destroy()
						hat.CanCollide = true
					end
				end
			end)
	
		end
	end
	
	--Drop
	
	script.Parent.Drop.DropBTN.MouseButton1Down:Connect(function()
		if val.Text == "" then
			val.Text = "1"
			DropHats(val.Text)
			val.Text = ""
		else
			DropHats(val.Text)
			val.Text = ""
		end
	end)
	
	--Kill
	
	script.Parent.Kill.KillBTN.MouseButton1Down:Connect(function()
		OBLITERATE()
	end)
	
	--Move
	--script made by kuraga#4659
	UIS.InputBegan:Connect(function(input, gameproc)
		while input.KeyCode == Enum.KeyCode.F and wait() and script.Parent.CheckBox.IEX.TextColor3 == Color3.fromRGB(85, 255, 0) do
					if not UIS:IsKeyDown(Enum.KeyCode.F) then
				break;
			end
			for i, v in pairs(game.Workspace:GetChildren()) do
				if (v:IsA("Accessory") and v:IsDescendantOf(game.Players.LocalPlayer.Character)== false) then
					game:GetService("RunService").Stepped:wait()
					v.Handle.Position = mouse.hit.Position
				end
			end
		end
	end)
	
	--Aura
	
	script.Parent.Aura.AuraBTN.MouseButton1Down:Connect(function()
		AURA()
	end)
end
coroutine.wrap(ZNGWIBP_fake_script)()
local function FSSZ_fake_script() -- IEX_7.LocalScript 
	local script = Instance.new('LocalScript', IEX_7)

	local p = script.Parent
	local on = false
	
	p.MouseButton1Down:Connect(function()
		if on == true then
			on = false
				p.Text = "OFF"
				p.TextColor3 = Color3.fromRGB(255, 0, 0)
					p:TweenPosition(UDim2.new(0.477, 0,-0.12, 0), 'Out', 'Quad', 0.2)
					wait(0.2001)
		else
			on = true
				p.Text = "ON"
				p:TweenPosition(UDim2.new(-0.005, 0,-0.12, 0), 'Out', 'Quad', 0.2)
			p.TextColor3 = Color3.fromRGB(85, 255, 0)
				wait(0.2001)
		end
	end)
	--/-------------
	--| MADE BY HELLOM8L0L
	--\-------------
end
coroutine.wrap(FSSZ_fake_script)()
local function SOLO_fake_script() -- IEX_8.Toggle 
	local script = Instance.new('LocalScript', IEX_8)

	local p = script.Parent
	local on = false
	plr = game.Players.LocalPlayer
	hum = plr.Character:WaitForChild("HumanoidRootPart")
	mouse = plr:GetMouse()
	
	p.MouseButton1Down:Connect(function()
		if on == true then
			on = false
				p.Text = "OFF"
				p.TextColor3 = Color3.fromRGB(255, 0, 0)
					p:TweenPosition(UDim2.new(0.477, 0,-0.12, 0), 'Out', 'Quad', 0.2)
					wait(0.2001)
		else
			on = true
				p.Text = "ON"
				p:TweenPosition(UDim2.new(-0.005, 0,-0.12, 0), 'Out', 'Quad', 0.2)
			p.TextColor3 = Color3.fromRGB(85, 255, 0)
			mouse.KeyDown:Connect(function(key)
			    if key == "e" and on == true then
			        if mouse.Target then
			            hum.CFrame = CFrame.new(mouse.Hit.Position)
			        end
			    end
			end)
		end
	end)
	--/-------------
	--| MADE BY HELLOM8L0L
	--\-------------
end
coroutine.wrap(SOLO_fake_script)()
local function SJTP_fake_script() -- Gravity.Handler 
	local script = Instance.new('LocalScript', Gravity)

	local Slider = script.Parent
	local SliderBtn = Slider.Button
	local Player = game:GetService("Players").LocalPlayer
	local UIS = game:GetService("UserInputService")
	local RuS = game:GetService("RunService")
	
	-- Properties
	local held = false
	local step = 0.01
	local percentage = 0
	
	function snap(number, factor)
		if factor == 0 then
			return number
		else
			return math.floor(number/factor+0.5)*factor
		end
	end
	
	UIS.InputEnded:connect(function(input, processed)
		if input.UserInputType == Enum.UserInputType.MouseButton1 then
			held = false
		end
	end)
	
	script.Parent.Button.TextButton.MouseButton1Down:Connect(function()
		held = true
	end)
	
	RuS.RenderStepped:connect(function(delta)
		if held then
			local MousePos = UIS:GetMouseLocation().X
			local BtnPos = SliderBtn.Position
			local SliderSize = Slider.AbsoluteSize.X
			local SliderPos = Slider.AbsolutePosition.X
			local pos = snap((MousePos-SliderPos)/SliderSize,step)
			percentage = math.clamp(pos,0,1)
			SliderBtn.Position = UDim2.new(percentage,0,BtnPos.Y.Scale, BtnPos.Y.Offset)
		end
	end)
end
coroutine.wrap(SJTP_fake_script)()
local function TPMDHY_fake_script() -- TextButton_11.LocalScript 
	local script = Instance.new('LocalScript', TextButton_11)

	local player = game.Players.LocalPlayer
	script.Parent.Parent.Position = UDim2.new(0, 0,0.473, 0)
	
	script.Parent.Parent.Changed:Connect(function()
		
		local axis = script.Parent.Parent.Position.X.Scale
		local color =  Color3.fromRGB(255,255,0):Lerp(Color3.fromRGB(250, 138, 25),axis/1)
		local number = math.floor(axis*100)
		local volume = number
		local hum = player.Character:FindFirstChild("Humanoid")
		if hum then
			game.Workspace.Gravity =  196.2 - (volume + volume)
			if	game.Workspace.Gravity <= 5 then game.Workspace.Gravity = 10 end
		end
	end)
end
coroutine.wrap(TPMDHY_fake_script)()
local function GMNHFVO_fake_script() -- IEX_9.Toggle 
	local script = Instance.new('LocalScript', IEX_9)

	local p = script.Parent
	local on = false
	
	p.MouseButton1Down:Connect(function()
		if on == true then
			on = false
				p.Text = "OFF"
				p.TextColor3 = Color3.fromRGB(255, 0, 0)
					p:TweenPosition(UDim2.new(0.477, 0,-0.12, 0), 'Out', 'Quad', 0.2)
					wait(0.2001)
		else
			on = true
				p.Text = "ON"
				p:TweenPosition(UDim2.new(-0.005, 0,-0.12, 0), 'Out', 'Quad', 0.2)
			p.TextColor3 = Color3.fromRGB(85, 255, 0)
				wait(0.2001)
		end
	end)
	--/-------------
	--| MADE BY HELLOM8L0L
	--\-------------
	
	
	local Player = game:GetService'Players'.LocalPlayer;
	local UIS = game:GetService'UserInputService';
	
	function Action(Object, Function) if Object ~= nil then Function(Object); end end
	_G.JumpHeight = 50;
	
	UIS.InputBegan:connect(function(UserInput)
	 if UserInput.UserInputType == Enum.UserInputType.Keyboard and UserInput.KeyCode == Enum.KeyCode.Space and on == true then
		    Action(Player.Character.Humanoid, function(self)
		        if self:GetState() == Enum.HumanoidStateType.Jumping or self:GetState() == Enum.HumanoidStateType.Freefall then
		                Action(self.Parent.HumanoidRootPart, function(self)
		                    self.Velocity = Vector3.new(0, _G.JumpHeight, 0);
		                end)
		          end
	         end)
		 end
	end)
end
coroutine.wrap(GMNHFVO_fake_script)()
local function WURIGD_fake_script() -- JumpPower.Handler 
	local script = Instance.new('LocalScript', JumpPower)

	local Slider = script.Parent
	local SliderBtn = Slider.Button
	local Player = game:GetService("Players").LocalPlayer
	local UIS = game:GetService("UserInputService")
	local RuS = game:GetService("RunService")
	
	-- Properties
	local held = false
	local step = 0.01
	local percentage = 0
	
	function snap(number, factor)
		if factor == 0 then
			return number
		else
			return math.floor(number/factor+0.5)*factor
		end
	end
	
	UIS.InputEnded:connect(function(input, processed)
		if input.UserInputType == Enum.UserInputType.MouseButton1 then
			held = false
		end
	end)
	
	script.Parent.Button.TextButton.MouseButton1Down:Connect(function()
		held = true
	end)
	
	RuS.RenderStepped:connect(function(delta)
		if held then
			local MousePos = UIS:GetMouseLocation().X
			local BtnPos = SliderBtn.Position
			local SliderSize = Slider.AbsoluteSize.X
			local SliderPos = Slider.AbsolutePosition.X
			local pos = snap((MousePos-SliderPos)/SliderSize,step)
			percentage = math.clamp(pos,0,1)
			SliderBtn.Position = UDim2.new(percentage,0,BtnPos.Y.Scale, BtnPos.Y.Offset)
		end
	end)
end
coroutine.wrap(WURIGD_fake_script)()
local function TUAHHV_fake_script() -- TextButton_12.LocalScript 
	local script = Instance.new('LocalScript', TextButton_12)

	local player = game.Players.LocalPlayer
	script.Parent.Parent.Position = UDim2.new(0, 0,0.473, 0)
	
	script.Parent.Parent.Changed:Connect(function()
		
		local axis = script.Parent.Parent.Position.X.Scale
		local color =  Color3.fromRGB(255,255,0):Lerp(Color3.fromRGB(250, 138, 25),axis/1)
		local number = math.floor(axis*100)
		local volume = number
		local hum = player.Character:FindFirstChild("Humanoid")
		if hum then
			hum.JumpPower =  50 + (volume)
		end
	end)
end
coroutine.wrap(TUAHHV_fake_script)()
local function USZCTQN_fake_script() -- IEX_10.Toggle 
	local script = Instance.new('LocalScript', IEX_10)

	local p = script.Parent
	local on = false
	
	p.MouseButton1Down:Connect(function()
		if on == true then
			on = false
				p.Text = "OFF"
				p.TextColor3 = Color3.fromRGB(255, 0, 0)
					p:TweenPosition(UDim2.new(0.477, 0,-0.12, 0), 'Out', 'Quad', 0.2)
					wait(0.2001)
		else
			on = true
				p.Text = "ON"
				p:TweenPosition(UDim2.new(-0.005, 0,-0.12, 0), 'Out', 'Quad', 0.2)
			p.TextColor3 = Color3.fromRGB(85, 255, 0)
			game:GetService('RunService').Stepped:connect(function()
				if on then
				game.Players.LocalPlayer.Character.Humanoid:ChangeState(11)
				end
				end)
				if on == true then
				game.Players.LocalPlayer.Character.Humanoid:ChangeState(11)
			end
		end
	end)
	--/-------------
	--| MADE BY HELLOM8L0L
	--\-------------
end
coroutine.wrap(USZCTQN_fake_script)()
local function XTEWLG_fake_script() -- WalkSpeed.Handler 
	local script = Instance.new('LocalScript', WalkSpeed)

	local Slider = script.Parent
	local SliderBtn = Slider.Button
	local Player = game:GetService("Players").LocalPlayer
	local UIS = game:GetService("UserInputService")
	local RuS = game:GetService("RunService")
	
	-- Properties
	local held = false
	local step = 0.01
	local percentage = 0
	
	function snap(number, factor)
		if factor == 0 then
			return number
		else
			return math.floor(number/factor+0.5)*factor
		end
	end
	
	UIS.InputEnded:connect(function(input, processed)
		if input.UserInputType == Enum.UserInputType.MouseButton1 then
			held = false
		end
	end)
	
	script.Parent.Button.TextButton.MouseButton1Down:Connect(function()
		held = true
	end)
	
	RuS.RenderStepped:connect(function(delta)
		if held then
			local MousePos = UIS:GetMouseLocation().X
			local BtnPos = SliderBtn.Position
			local SliderSize = Slider.AbsoluteSize.X
			local SliderPos = Slider.AbsolutePosition.X
			local pos = snap((MousePos-SliderPos)/SliderSize,step)
			percentage = math.clamp(pos,0,1)
			SliderBtn.Position = UDim2.new(percentage,0,BtnPos.Y.Scale, BtnPos.Y.Offset)
		end
	end)
end
coroutine.wrap(XTEWLG_fake_script)()
local function UBMKVOO_fake_script() -- TextButton_13.LocalScript 
	local script = Instance.new('LocalScript', TextButton_13)

	local player = game.Players.LocalPlayer
	script.Parent.Parent.Position = UDim2.new(0, 0,0.473, 0)
	
	script.Parent.Parent.Changed:Connect(function()
		
		local axis = script.Parent.Parent.Position.X.Scale
		local color =  Color3.fromRGB(255,255,0):Lerp(Color3.fromRGB(250, 138, 25),axis/1)
		local number = math.floor(axis*100)
		local volume = number
		local hum = player.Character:FindFirstChild("Humanoid")
		if hum then
			hum.WalkSpeed =  16 + (volume)
		end
	end)
end
coroutine.wrap(UBMKVOO_fake_script)()
local function YTRJX_fake_script() -- IEX_11.LocalScript 
	local script = Instance.new('LocalScript', IEX_11)

	local p = script.Parent
	local on = false
	
	p.MouseButton1Down:Connect(function()
		if on == true then
			on = false
			game.Players.LocalPlayer.Character.HumanoidRootPart.Anchored = false
				p.Text = "OFF"
				p.TextColor3 = Color3.fromRGB(255, 0, 0)
					p:TweenPosition(UDim2.new(0.477, 0,-0.12, 0), 'Out', 'Quad', 0.2)
					wait(0.2001)
		else
			on = true
			game.Players.LocalPlayer.Character.HumanoidRootPart.Anchored = true
				p.Text = "ON"
				p:TweenPosition(UDim2.new(-0.005, 0,-0.12, 0), 'Out', 'Quad', 0.2)
			p.TextColor3 = Color3.fromRGB(85, 255, 0)
				wait(0.2001)
		end
	end)
	--/-------------
	--| MADE BY HELLOM8L0L
	--\-------------
	
end
coroutine.wrap(YTRJX_fake_script)()
local function JIJC_fake_script() -- IEX_12.LocalScript 
	local script = Instance.new('LocalScript', IEX_12)

	local p = script.Parent
	local on = false
	
	p.MouseButton1Down:Connect(function()
		if on == true then
			on = false
				p.Text = "OFF"
				p.TextColor3 = Color3.fromRGB(255, 0, 0)
					p:TweenPosition(UDim2.new(0.477, 0,-0.12, 0), 'Out', 'Quad', 0.2)
					wait(0.2001)
		else
			on = true
			p.Text = "ON"
				p:TweenPosition(UDim2.new(-0.005, 0,-0.12, 0), 'Out', 'Quad', 0.2)
			p.TextColor3 = Color3.fromRGB(85, 255, 0)
					while wait() do
	            for _,v in pairs(game.Players:GetChildren()) do
	                v.Character.HumanoidRootPart.Position = CFrame.new(game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame.Lookvector * 5)
	            end
	            if on == false then break end
	        end
				wait(0.2001)
		end
	end)
	--/-------------
	--| MADE BY HELLOM8L0L
	--\-------------
end
coroutine.wrap(JIJC_fake_script)()
local function GNACR_fake_script() -- IEX_13.LocalScript 
	local script = Instance.new('LocalScript', IEX_13)

	local p = script.Parent
	local on = false
	local tab = script.Parent.Parent
	tab.UP.Visible = false
	tab.DOWN.Visible = false
	tab.Value.Visible = false
	
	p.MouseButton1Down:Connect(function()
		if on == true then
			on = false
				p.Text = "OFF"
				p.TextColor3 = Color3.fromRGB(255, 0, 0)
			p:TweenPosition(UDim2.new(0.477, 0,-0.12, 0), 'Out', 'Quad', 0.2)
					local tab = script.Parent.Parent
			tab.UP.Visible = false
			tab.DOWN.Visible = false
			tab.Value.Visible = false
			wait(0.2001)
		else
			on = true
			p.Text = "ON"
				p:TweenPosition(UDim2.new(-0.005, 0,-0.12, 0), 'Out', 'Quad', 0.2)
			p.TextColor3 = Color3.fromRGB(85, 255, 0)
					local tab = script.Parent.Parent
			tab.UP.Visible = true
			tab.DOWN.Visible = true
			tab.Value.Visible = true
			wait(0.2001)
		end
	end)
	--/-------------
	--| MADE BY HELLOM8L0L
	--\-------------
	
	local UIS = game:GetService("UserInputService")
	local speed = false
	local boost = 1
	script.Parent.Parent.Value.Text = "Current Value: " .. boost
	
	UIS.InputBegan:Connect(function(i,p)
		while i.KeyCode == Enum.KeyCode.LeftShift do
			game:GetService("RunService").Stepped:Wait()
			if on == true then
		        game.Players.LocalPlayer.Character:SetPrimaryPartCFrame(game.Players.LocalPlayer.Character:GetPrimaryPartCFrame()*CFrame.new(0, 0, -boost))
		        if not UIS:IsKeyDown(Enum.KeyCode.LeftShift) then
		            break
		        end
			end
	    end
	end)
	
	UIS.InputBegan:Connect(function(i,p)
	    if i.KeyCode == Enum.KeyCode.U and on == true then
	        if boost < 0 then boost = 1 return 
	        else
				            boost = boost + 1
				script.Parent.Parent.Value.Text = "Current Value: " .. boost
	        end
	    end
	end)
	UIS.InputBegan:Connect(function(i,p)
	    if i.KeyCode == Enum.KeyCode.J and on == true then
			        boost = boost - 1
			script.Parent.Parent.Value.Text = "Current Value: " .. boost
	    end
	end)
end
coroutine.wrap(GNACR_fake_script)()
local function TXBZOC_fake_script() -- FEBypass_2.LocalScript 
	local script = Instance.new('LocalScript', FEBypass_2)

	script.Parent.MouseButton1Down:Connect(function()
		loadstring(game:GetObjects("rbxassetid://5204508994")[1].Source)()
	end)
end
coroutine.wrap(TXBZOC_fake_script)()
local function LCZCR_fake_script() -- chams.LocalScript 
	local script = Instance.new('LocalScript', chams)

	script.Parent.MouseButton1Click:Connect(function()
	-- Gui to Lua
	-- Version: 3.2
	
	-- Instances:
	
	local ScreenGui = Instance.new("ScreenGui")
	local Button = Instance.new("TextButton")
	local TextLabel = Instance.new("TextLabel")
	local Close = Instance.new("TextButton")
	local help = Instance.new("TextButton")
	local Frame = Instance.new("Frame")
	local Page = Instance.new("TextLabel")
	local Image = Instance.new("ImageLabel")
	local Message = Instance.new("TextLabel")
	local Message2 = Instance.new("TextLabel")
	local Close2 = Instance.new("TextButton")
	local TextLabel_2 = Instance.new("TextLabel")
	local TextLabel_3 = Instance.new("TextLabel")
	local TextLabel_4 = Instance.new("TextLabel")
	
	--Properties:
	
	ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
	ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling
	
	Button.Name = "Button"
	Button.Parent = ScreenGui
	Button.BackgroundColor3 = Color3.fromRGB(43, 43, 43)
	Button.Position = UDim2.new(0.738909066, 0, 0.383292377, 0)
	Button.Size = UDim2.new(0, 200, 0, 67)
	Button.Font = Enum.Font.GothamBold
	Button.Text = "Press \"Insert\" On Your Keyboard To Activate ESP/Chams"
	Button.TextColor3 = Color3.fromRGB(218, 218, 218)
	Button.TextSize = 12.000
	Button.TextWrapped = true
	
	TextLabel.Parent = ScreenGui
	TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	TextLabel.BackgroundTransparency = 1.000
	TextLabel.Position = UDim2.new(0.74969697, 0, 0.436759859, 0)
	TextLabel.Size = UDim2.new(0, 163, 0, 8)
	TextLabel.Font = Enum.Font.GothamBold
	TextLabel.Text = "And To Update The Players!"
	TextLabel.TextColor3 = Color3.fromRGB(218, 218, 218)
	TextLabel.TextSize = 12.000
	TextLabel.TextWrapped = true
	
	Close.Name = "Close"
	Close.Parent = ScreenGui
	Close.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	Close.BackgroundTransparency = 1.000
	Close.Position = UDim2.new(0.831515133, 0, 0.383292377, 0)
	Close.Size = UDim2.new(0, 28, 0, 20)
	Close.Font = Enum.Font.GothamBold
	Close.Text = "X"
	Close.TextColor3 = Color3.fromRGB(66, 7, 7)
	Close.TextSize = 20.000
	
	help.Name = "help"
	help.Parent = ScreenGui
	help.BackgroundColor3 = Color3.fromRGB(63, 63, 63)
	help.Position = UDim2.new(0.738787889, 0, 0.383292377, 0)
	help.Size = UDim2.new(0, 47, 0, 14)
	help.Font = Enum.Font.GothamBold
	help.Text = "Help!"
	help.TextColor3 = Color3.fromRGB(0, 0, 0)
	help.TextSize = 14.000
	
	Frame.Parent = ScreenGui
	Frame.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
	Frame.Position = UDim2.new(0.192242458, 0, 0.277641267, 0)
	Frame.Size = UDim2.new(0, 497, 0, 364)
	Frame.Visible = false
	
	Page.Name = "Page"
	Page.Parent = Frame
	Page.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
	Page.Size = UDim2.new(0, 503, 0, 33)
	Page.Font = Enum.Font.GothamBold
	Page.Text = "Need Help?"
	Page.TextColor3 = Color3.fromRGB(255, 255, 255)
	Page.TextSize = 20.000
	
	Image.Name = "Image"
	Image.Parent = Frame
	Image.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	Image.Position = UDim2.new(0, 0, 0.0906593427, 0)
	Image.Size = UDim2.new(0, 503, 0, 273)
	Image.Image = "rbxassetid://5205418791"
	
	Message.Name = "Message"
	Message.Parent = Frame
	Message.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
	Message.Position = UDim2.new(0, 0, 0.84065932, 0)
	Message.Size = UDim2.new(0, 503, 0, 58)
	Message.Font = Enum.Font.GothamBold
	Message.Text = "The Insert Button Is The One Circled On The Top!"
	Message.TextColor3 = Color3.fromRGB(255, 255, 255)
	Message.TextSize = 20.000
	
	Message2.Name = "Message 2"
	Message2.Parent = Frame
	Message2.BackgroundColor3 = Color3.fromRGB(43, 43, 43)
	Message2.Position = UDim2.new(1.01207244, 0, 0, 0)
	Message2.Size = UDim2.new(0, 200, 0, 364)
	Message2.Font = Enum.Font.GothamBold
	Message2.Text = "If That Doesn't Work Then Press \"Delete\" The One Circled On The Bottom!! If You Click Insert And The ESP Doesn't Work Then The Game Is Most Likely R6 Therefore Press \"Insert\""
	Message2.TextColor3 = Color3.fromRGB(255, 255, 255)
	Message2.TextScaled = true
	Message2.TextSize = 14.000
	Message2.TextWrapped = true
	
	Close2.Name = "Close2"
	Close2.Parent = Frame
	Close2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	Close2.BackgroundTransparency = 1.000
	Close2.Position = UDim2.new(0.933601618, 0, 0, 0)
	Close2.Size = UDim2.new(0, 39, 0, 33)
	Close2.Font = Enum.Font.GothamBold
	Close2.Text = "X"
	Close2.TextColor3 = Color3.fromRGB(66, 7, 7)
	Close2.TextSize = 40.000
	
	TextLabel_2.Parent = Frame
	TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	TextLabel_2.BackgroundTransparency = 1.000
	TextLabel_2.Position = UDim2.new(0.297786713, 0, 0.810439527, 0)
	TextLabel_2.Size = UDim2.new(0, 200, 0, 44)
	TextLabel_2.Font = Enum.Font.GothamBold
	TextLabel_2.Text = "Press \"Insert\"!!"
	TextLabel_2.TextColor3 = Color3.fromRGB(255, 255, 255)
	TextLabel_2.TextSize = 20.000
	
	TextLabel_3.Parent = ScreenGui
	TextLabel_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	TextLabel_3.BackgroundTransparency = 1.000
	TextLabel_3.Position = UDim2.new(0.738303006, 0, 0.45577395, 0)
	TextLabel_3.Size = UDim2.new(0, 200, 0, 14)
	TextLabel_3.Font = Enum.Font.GothamBold
	TextLabel_3.Text = "May Need To Double Tap..."
	TextLabel_3.TextColor3 = Color3.fromRGB(0, 0, 0)
	TextLabel_3.TextSize = 10.000
	
	TextLabel_4.Parent = ScreenGui
	TextLabel_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	TextLabel_4.BackgroundTransparency = 1.000
	TextLabel_4.Position = UDim2.new(0.781818151, 0, 0.384520859, 0)
	TextLabel_4.Size = UDim2.new(0, 38, 0, 13)
	TextLabel_4.Font = Enum.Font.GothamBold
	TextLabel_4.Text = "Some Guy#7173"
	TextLabel_4.TextColor3 = Color3.fromRGB(0, 0, 0)
	TextLabel_4.TextSize = 10.000
	
	-- Scripts:
	
	local function HTSLU_fake_script() -- Button.Script 
		local script = Instance.new('Script', Button)
	
		UserInputService = game:GetService("UserInputService")
		
		UserInputService.InputBegan:Connect(function(input, gameProcessedEvent)
		if input.KeyCode == Enum.KeyCode.Insert then
		--𝘾𝙧𝙚𝙖𝙩𝙚𝙙 𝙗𝙮: 𝙎𝙤𝙢𝙚 𝙂𝙪𝙮#7173
			
			local y = game.Players:GetChildren()
			for i,x in pairs(y) do
			    local co = x.TeamColor.Color
				game.Players.LocalPlayer.Name = "Me"
				wait()
				game.Players.LocalPlayer.Character.Name = "Me"
				wait()
				
				
				local a = game.Players:GetChildren()
				for i,v in pairs(a) do
				
				
				    local gui = Instance.new("BillboardGui")
				    gui.Parent = v.Character.Head
				    gui.Size = UDim2.new(0,200,7,50)
				    gui.AlwaysOnTop = true
				    gui.ResetOnSpawn = false
				    
				
				
				    local word = Instance.new("TextLabel")
				    word.TextColor3 = Color3.fromRGB(255, 255, 255)
				    word.Font = "GothamBold"
				    word.Text = v.Name
				    word.Parent = gui
				    word.BackgroundColor3 = Color3.fromRGB(86, 86, 86)
				    word.BackgroundTransparency = 1
				    word.TextScaled = true
				    word.TextSize = 30
				    word.Size = UDim2.new(0,200,0,50)
				
				end
				
				for i,v in pairs(game.Players:GetChildren()) do
				    
				    local char = v.Character
				
				if v.Name ~= "Me" then
				
				local a = Instance.new("BoxHandleAdornment")
				a.Color3 = co
				a.Parent = char
				a.Adornee = char.LeftHand
				a.ZIndex = 1
				a.AlwaysOnTop = true
				a.Size = Vector3.new(0.4,0.5,0.6)
				
				
				local b = Instance.new("BoxHandleAdornment")
				b.Color3 = co
				b.Parent = char
				b.Adornee = char.HumanoidRootPart
				b.ZIndex = 1
				b.AlwaysOnTop = true
				b.Size = Vector3.new(1.6,2,0.7)
				b.SizeRelativeOffset = Vector3.new(0,0,-0.7)
				
				
				local c = Instance.new("BoxHandleAdornment")
				c.Color3 = co
				c.Parent = char
				c.Adornee = char.RightHand
				c.ZIndex = 1
				c.AlwaysOnTop = true
				c.Size = Vector3.new(0.4,0.5,0.6)
				
				
				local d = Instance.new("BoxHandleAdornment")
				d.Color3 = co
				d.Parent = char
				d.Adornee = char.RightHand
				d.ZIndex = 1
				d.AlwaysOnTop = true
				d.Size = Vector3.new(0.4,0.5,0.6)
				
				
				local e = Instance.new("BoxHandleAdornment")
				e.Color3 = co
				e.Parent = char
				e.Adornee = char.Head
				e.ZIndex = 1
				e.AlwaysOnTop = true
				e.Size = Vector3.new(1,1.3,1)
				
				
				local f = Instance.new("BoxHandleAdornment")
				f.Color3 = co
				f.Parent = char
				f.Adornee = char.LeftLowerLeg
				f.ZIndex = 1
				f.AlwaysOnTop = true
				f.Size = Vector3.new(0.5,2.3,0.5)
				
				
				local g = Instance.new("BoxHandleAdornment")
				g.Color3 = co
				g.Parent = char
				g.Adornee = char.RightLowerLeg
				g.ZIndex = 1
				g.AlwaysOnTop = true
				g.Size = Vector3.new(0.5,2.3,0.5)
				
				
				local h = Instance.new("BoxHandleAdornment")
				h.Color3 = co
				h.Parent = char
				h.Adornee = char.RightUpperArm
				h.ZIndex = 1
				h.AlwaysOnTop = true
				h.Size = Vector3.new(0.5,1,0.5)
				
				
				local i = Instance.new("BoxHandleAdornment")
				i.Color3 = co
				i.Parent = char
				i.Adornee = char.LeftUpperArm
				i.ZIndex = 1
				i.AlwaysOnTop = true
				i.Size = Vector3.new(0.5,1,0.5)
				
				
				local j = Instance.new("BoxHandleAdornment")
				j.Color3 = co
				j.Parent = char
				j.Adornee = char.LeftLowerArm
				j.ZIndex = 1
				j.AlwaysOnTop = true
				j.Size = Vector3.new(0.5,1,0.5)
				
				
				local k = Instance.new("BoxHandleAdornment")
				k.Color3 = co
				k.Parent = char
				k.Adornee = char.RightLowerArm
				k.ZIndex = 1
				k.AlwaysOnTop = true
				k.Size = Vector3.new(0.5,1,0.5)
				
				wait(0.1)
				end
				end
				end
				
				
			
			end
			end)
		UserInputService = game:GetService("UserInputService")
		UserInputService.InputBegan:Connect(function(input, gameProcessedEvent)
		if input.KeyCode == Enum.KeyCode.Delete then
		local person = game.Players:GetPlayers()
		game.Players.LocalPlayer.Name = "Me"
				game.Players.LocalPlayer.Character.Name = "Me"
				wait()
		
		for i,v in pairs(person) do
		    local char = v.Character
		    local y = game.Players:GetChildren()
			for i,x in pairs(y) do
			    local co = x.TeamColor.Color
		    
		    if char.Name ~= "Me" then
		    local l = Instance.new("BoxHandleAdornment")
				l.Color3 = co
				l.Parent = char
				l.Adornee = char:FindFirstChild("Left Arm")
				l.ZIndex = 1
				l.AlwaysOnTop = true
				l.Size = Vector3.new(1,2,1)
				
				
				
				
				local m = Instance.new("BoxHandleAdornment")
				m.Color3 = co
				m.Parent = char
				m.Adornee = char:FindFirstChild("Right Arm")
				m.ZIndex = 1
				m.AlwaysOnTop = true
				m.Size = Vector3.new(1,2,1)
				
				
				
				
				local m = Instance.new("BoxHandleAdornment")
				m.Color3 = co
				m.Parent = char
				m.Adornee = char:FindFirstChild("Left Leg")
				m.ZIndex = 1
				m.AlwaysOnTop = true
				m.Size = Vector3.new(1,2,1)
				
				
				
				
				local m = Instance.new("BoxHandleAdornment")
				m.Color3 = co
				m.Parent = char
				m.Adornee = char:FindFirstChild("Right Leg")
				m.ZIndex = 1
				m.AlwaysOnTop = true
				m.Size = Vector3.new(1,2,1)
				
				
				
				
				local m = Instance.new("BoxHandleAdornment")
				m.Color3 = co
				m.Parent = char
				m.Adornee = char:FindFirstChild("Torso")
				m.ZIndex = 1
				m.AlwaysOnTop = true
				m.Size = Vector3.new(2,2,1)
				
				
				
				
				local m = Instance.new("BoxHandleAdornment")
				m.Color3 = co
				m.Parent = char
				m.Adornee = char:FindFirstChild("Head")
				m.ZIndex = 1
				m.AlwaysOnTop = true
				m.Size = Vector3.new(1.2,1.2,1.2)
			    end
		    end
		end
		end
		end)
	end
	coroutine.wrap(HTSLU_fake_script)()
	local function QRRWO_fake_script() -- Close.Script 
		local script = Instance.new('Script', Close)
	
		script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.Enabled = false
		end)
	end
	coroutine.wrap(QRRWO_fake_script)()
	local function KPHL_fake_script() -- help.Script 
		local script = Instance.new('Script', help)
	
		script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.Frame.Visible = true
		end)
	end
	coroutine.wrap(KPHL_fake_script)()
	local function RLYAJT_fake_script() -- Close2.Script 
		local script = Instance.new('Script', Close2)
	
		script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.Visible = false
		end)
	end
	coroutine.wrap(RLYAJT_fake_script)()
	end)
end
coroutine.wrap(LCZCR_fake_script)()
local function QTTET_fake_script() -- xray.LocalScript 
	local script = Instance.new('LocalScript', xray)

	script.Parent.MouseButton1Up:Connect(function()
	-- Gui to Lua
	-- Version: 3.2
	
	-- Instances:
	
	local ScreenGui = Instance.new("ScreenGui")
	local Frame = Instance.new("Frame")
	local On = Instance.new("TextButton")
	local name = Instance.new("TextLabel")
	local Off = Instance.new("TextButton")
	local Credit = Instance.new("TextLabel")
	local Close = Instance.new("TextButton")
	local enjoy = Instance.new("TextLabel")
	
	--Properties:
	
	ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
	ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling
	
	Frame.Parent = ScreenGui
	Frame.BackgroundColor3 = Color3.fromRGB(43, 43, 43)
	Frame.Position = UDim2.new(0.709651291, 0, 0.434017539, 0)
	Frame.Size = UDim2.new(0, 215, 0, 59)
	
	On.Name = "On"
	On.Parent = Frame
	On.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	On.BackgroundTransparency = 1.000
	On.BorderColor3 = Color3.fromRGB(43, 43, 43)
	On.Position = UDim2.new(-0.00273607834, 0, 0.542372882, 0)
	On.Size = UDim2.new(0, 80, 0, 27)
	On.Font = Enum.Font.GothamBold
	On.Text = "On"
	On.TextColor3 = Color3.fromRGB(255, 255, 255)
	On.TextSize = 14.000
	
	name.Name = "name"
	name.Parent = Frame
	name.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	name.BackgroundTransparency = 1.000
	name.BorderColor3 = Color3.fromRGB(43, 43, 43)
	name.Position = UDim2.new(-0.00465116277, 0, 0, 0)
	name.Size = UDim2.new(0, 216, 0, 32)
	name.Font = Enum.Font.GothamBold
	name.Text = "X-Ray"
	name.TextColor3 = Color3.fromRGB(250, 250, 250)
	name.TextSize = 14.000
	
	Off.Name = "Off"
	Off.Parent = Frame
	Off.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	Off.BackgroundTransparency = 1.000
	Off.BorderColor3 = Color3.fromRGB(43, 43, 43)
	Off.Position = UDim2.new(0.625171185, 0, 0.542372882, 0)
	Off.Size = UDim2.new(0, 80, 0, 27)
	Off.Font = Enum.Font.GothamBold
	Off.Text = "Off"
	Off.TextColor3 = Color3.fromRGB(255, 255, 255)
	Off.TextSize = 14.000
	
	Credit.Name = "Credit"
	Credit.Parent = Frame
	Credit.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	Credit.BackgroundTransparency = 1.000
	Credit.Position = UDim2.new(-0.00273607834, 0, -0.101694912, 0)
	Credit.Size = UDim2.new(0, 80, 0, 32)
	Credit.Font = Enum.Font.GothamBold
	Credit.Text = "Some Guy#7173"
	Credit.TextColor3 = Color3.fromRGB(255, 255, 255)
	Credit.TextSize = 10.000
	
	Close.Name = "Close"
	Close.Parent = Frame
	Close.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	Close.BackgroundTransparency = 1.000
	Close.Position = UDim2.new(0.81860435, 0, 0, 0)
	Close.Size = UDim2.new(0, 38, 0, 32)
	Close.Font = Enum.Font.GothamBold
	Close.Text = "X"
	Close.TextColor3 = Color3.fromRGB(58, 16, 16)
	Close.TextSize = 30.000
	
	enjoy.Name = "enjoy"
	enjoy.Parent = Frame
	enjoy.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	enjoy.BackgroundTransparency = 1.000
	enjoy.Position = UDim2.new(0.36935693, 0, 0.542372882, 0)
	enjoy.Size = UDim2.new(0, 55, 0, 26)
	enjoy.Font = Enum.Font.GothamBold
	enjoy.Text = "Enjoy!"
	enjoy.TextColor3 = Color3.fromRGB(0, 0, 0)
	enjoy.TextSize = 14.000
	
	-- Scripts:
	
	local function QRMZGFV_fake_script() -- On.Script 
		local script = Instance.new('Script', On)
	
		script.Parent.MouseButton1Up:Connect(function()
		for i, v in ipairs(workspace:GetDescendants()) do
		    if v:IsA("BasePart") then v.Transparency = 0.75
		        
		    end 
		end
		
		end)
	end
	coroutine.wrap(QRMZGFV_fake_script)()
	local function IHDTEFL_fake_script() -- Off.Script 
		local script = Instance.new('Script', Off)
	
		script.Parent.MouseButton1Up:Connect(function()
		for i, v in ipairs(workspace:GetDescendants()) do
		    if v:IsA("BasePart") then v.Transparency = 0
		        
		    end 
		end
		
		end)
	end
	coroutine.wrap(IHDTEFL_fake_script)()
	local function INLF_fake_script() -- Close.Script 
		local script = Instance.new('Script', Close)
	
		script.Parent.MouseButton1Up:Connect(function()
		script.Parent.Parent.Parent:Destroy()
		end)
	end
	coroutine.wrap(INLF_fake_script)()
	
	end)
end
coroutine.wrap(QTTET_fake_script)()
local function RFKLI_fake_script() -- Minimize.LocalScript 
	local script = Instance.new('LocalScript', Minimize)

	--Variables--
	local Main = script.Parent.Parent.Parent
	local p = script.Parent
	local shown = true
	--Code--
	p.MouseButton1Down:Connect(function()
		if shown == false then
			shown = true
			Main:TweenSize(UDim2.new(0, 490,0, 217), 'Out', 'Quad', 0.4)
			wait(0.4)
			for _,v in pairs(script.Parent.Parent.Parent.TabFrame:GetChildren()) do
				v.Visible = true
			end
		else
			for _,v in pairs(script.Parent.Parent.Parent.TabFrame:GetChildren()) do
				v.Visible = false
			end
			Main:TweenSize(UDim2.new(0, 490,0, 22), 'Out', 'Quad', 0.4)
			wait(0.4)
			shown = false
		end
	end)
end
coroutine.wrap(RFKLI_fake_script)()
local function VDJTD_fake_script() -- Top.Draggable 
	local script = Instance.new('LocalScript', Top)

	function dragify(Frame)
	dragToggle = nil
	dragSpeed = .1 -- You can edit this.
	dragInput = nil
	dragStart = nil
	dragPos = nil
	
	function updateInput(input)
	Delta = input.Position - dragStart
	Position = UDim2.new(startPos.X.Scale, startPos.X.Offset + Delta.X, startPos.Y.Scale, startPos.Y.Offset + Delta.Y)
	game:GetService("TweenService"):Create(Frame, TweenInfo.new(.25), {Position = Position}):Play()
	end
	
	Frame.InputBegan:Connect(function(input)
	if (input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch) then
	dragToggle = true
	dragStart = input.Position
	startPos = Frame.Position
	input.Changed:Connect(function()
	if (input.UserInputState == Enum.UserInputState.End) then
	dragToggle = false
	end
	end)
	end
	end)
	
	Frame.InputChanged:Connect(function(input)
	if (input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch) then
	dragInput = input
	end
	end)
	
	game:GetService("UserInputService").InputChanged:Connect(function(input)
	if (input == dragInput and dragToggle) then
	updateInput(input)
	end
	end)
	end
	
	dragify(script.Parent.Parent)
end
coroutine.wrap(VDJTD_fake_script)()
local function IRPFHSD_fake_script() -- Logo.LocalScript 
	local script = Instance.new('LocalScript', Logo)

	local p = script.Parent
	local pp = script.Parent.Parent
	local ppp = script.Parent.Parent.Parent.Main
	p.ImageTransparency = 1
	p.Visible = true
	pp.ImageTransparency = 1
	pp.Visible = true
	ppp.Visible = false
	wait(2)
	for	i = 1,10 do
		pp.ImageTransparency = pp.ImageTransparency - 0.1
		wait()
	end
	wait(0.2)
	for	i = 1,10 do
		p.ImageTransparency = p.ImageTransparency - 0.1
		wait()
	end
	
	wait(0.2)
	
	for	i = 1,10 do
		p.ImageTransparency = p.ImageTransparency + 0.1
		wait()
	end
	wait(0.2)
	for	i = 1,10 do
		pp.ImageTransparency = pp.ImageTransparency + 0.1
		wait()
	end
	wait(0.2)
	ppp.Visible = true
end
coroutine.wrap(IRPFHSD_fake_script)()
local function COZQ_fake_script() -- DeluxHub.Hide/Show 
	local script = Instance.new('LocalScript', DeluxHub)

	UserInputService = game:GetService('UserInputService') local p = script.Parent local bl = true UserInputService.InputBegan:Connect (function(input, gameProcessedEvent) if input.KeyCode == Enum.KeyCode.Insert then if bl == true then p.Enabled = false bl = false else p.Enabled = true bl = true end end end)
end
coroutine.wrap(COZQ_fake_script)()
