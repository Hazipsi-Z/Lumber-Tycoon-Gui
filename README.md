local ScreenGui = Instance.new("ScreenGui")
local Main = Instance.new("Frame")
local Close = Instance.new("TextButton")
local Min = Instance.new("TextButton")
local TextLabel = Instance.new("TextLabel")
local Main2 = Instance.new("Frame")
local Teleport = Instance.new("TextButton")
local Duplication = Instance.new("TextButton")
local AutoBuy = Instance.new("TextButton")
local Credits = Instance.new("TextButton")
local Misc = Instance.new("TextButton")
local World = Instance.new("TextButton")
local AutoBuy_F = Instance.new("Frame")
local BuyItem = Instance.new("TextButton")
local ScrollingFrame = Instance.new("ScrollingFrame")
local WoodRUs = Instance.new("TextButton")
local Furniture = Instance.new("TextButton")
local Bobs = Instance.new("TextButton")
local Boxed = Instance.new("TextButton")
local Fine = Instance.new("TextButton")
local Link = Instance.new("TextButton")
local Teleport_F = Instance.new("Frame")
local Duplication_F = Instance.new("Frame")
local Misc_F = Instance.new("Frame")
local Credits_F = Instance.new("Frame")
local Quantity = Instance.new("TextBox")
local Back = Instance.new("TextButton")
local TpPlayer = Instance.new("TextButton")
local TpBase = Instance.new("TextButton")
local Plr1 = Instance.new("TextButton")
local Plr2 = Instance.new("TextButton")
local Plr3 = Instance.new("TextButton")
local Plr6 = Instance.new("TextButton")
local Plr5 = Instance.new("TextButton")
local Plr4 = Instance.new("TextButton")
local STP = Instance.new("ScrollingFrame")
local World_F = Instance.new("Frame")
local TpTool = Instance.new("TextButton")
local DeleteTool = Instance.new("TextButton")
local Btools = Instance.new("TextButton")
local PathTool = Instance.new("TextButton")
local DeleteTool_2 = Instance.new("TextButton")
local TpTool_2 = Instance.new("TextButton")
local TextButton = Instance.new("TextButton")
local TextButton_2 = Instance.new("TextButton")
local TextButton_3 = Instance.new("TextButton")
local TextButton_4 = Instance.new("TextButton")
local TextButton_5 = Instance.new("TextButton")
local TextButton_6 = Instance.new("TextButton")
local TextButton_7 = Instance.new("TextButton")
local TextButton_8 = Instance.new("TextButton")
local DupeM = Instance.new("TextButton")
local DML = Instance.new("TextLabel")
local Menos = Instance.new("TextButton")
local Mais = Instance.new("TextButton")
local DupeMoney = Instance.new("TextLabel")
local LS1 = Instance.new("TextButton")
local LS2 = Instance.new("TextButton")
local LS3 = Instance.new("TextButton")
local LS6 = Instance.new("TextButton")
local LS4 = Instance.new("TextButton")
local LS5 = Instance.new("TextButton")
local TextLabel2 = Instance.new("TextLabel")
local Right = Instance.new("TextButton")
local Left = Instance.new("TextButton")
local SongName = Instance.new("TextLabel")
local ImageCredit = Instance.new("ImageLabel")
local Credit = Instance.new("TextLabel")
local Stop = Instance.new("TextButton")
local Play = Instance.new("TextButton")
local OFrame = Instance.new("Frame")
local Open = Instance.new("TextButton")
 
ScreenGui.Parent = game.CoreGui
 
Main.Name = "Main"
Main.Parent = ScreenGui
Main.BackgroundColor3 = Color3.new(1, 1, 1)
Main.BorderColor3 = Color3.new(0.592157, 0, 0.756863)
Main.BorderSizePixel = 0
Main.Position = UDim2.new(0.184243977, 0, 0.2370518, 0)
Main.Size = UDim2.new(0, 463, 0, 263)
Main.Active = true
Main.Draggable = true
 
Close.Name = "Close"
Close.Parent = Main
Close.BackgroundColor3 = Color3.new(1, 1, 1)
Close.BackgroundTransparency = 1
Close.Position = UDim2.new(0.879049718, 0, 0.0342205316, 0)
Close.Size = UDim2.new(0, 40, 0, 39)
Close.Font = Enum.Font.Gotham
Close.Text = "X"
Close.TextColor3 = Color3.new(1, 0, 0)
Close.TextScaled = true
Close.TextSize = 14
Close.TextWrapped = true
 
Min.Name = "Min"
Min.Parent = Main
Min.BackgroundColor3 = Color3.new(1, 1, 1)
Min.BackgroundTransparency = 1
Min.Position = UDim2.new(0.79265666, 0, 0.0342205316, 0)
Min.Size = UDim2.new(0, 40, 0, 39)
Min.Font = Enum.Font.Arcade
Min.Text = "-"
Min.TextColor3 = Color3.new(1, 0, 0)
Min.TextScaled = true
Min.TextSize = 14
Min.TextWrapped = true
 
TextLabel.Parent = Main
TextLabel.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel.BackgroundTransparency = 1
TextLabel.BorderColor3 = Color3.new(0.105882, 0.164706, 0.207843)
TextLabel.Position = UDim2.new(0.0366209932, 0, 0.0306454897, 0)
TextLabel.Size = UDim2.new(0, 292, 0, 39)
TextLabel.Font = Enum.Font.SciFi
TextLabel.Text = "Extreme Lumber Tycoon 2"
TextLabel.TextColor3 = Color3.new(0, 0.4, 5)
TextLabel.TextScaled = true
TextLabel.TextSize = 14
TextLabel.TextWrapped = true
 
Main2.Name = "Main2"
Main2.Parent = Main
Main2.BackgroundColor3 = Color3.new(1, 1, 1)
Main2.BackgroundTransparency = 1
Main2.Position = UDim2.new(0, 0, 0.212927759, 0)
Main2.Size = UDim2.new(0, 463, 0, 207)
 
Teleport.Name = "Teleport"
Teleport.Parent = Main2
Teleport.BackgroundColor3 = Color3.new(0.8, 0.0313726, 0.0470588)
Teleport.BackgroundTransparency = 1
Teleport.BorderColor3 = Color3.new(1, 1, 1)
Teleport.BorderSizePixel = 0
Teleport.Position = UDim2.new(0.0363738388, 0, 0.699343979, 0)
Teleport.Size = UDim2.new(0, 187, 0, 47)
Teleport.Font = Enum.Font.Antique
Teleport.Text = " Teleports "
Teleport.TextColor3 = Color3.new(0.32549, 1, 0.0392157)
Teleport.TextScaled = true
Teleport.TextSize = 14
Teleport.TextWrapped = true
 
Duplication.Name = "Duplication"
Duplication.Parent = Main2
Duplication.BackgroundColor3 = Color3.new(0.8, 0.0313726, 0.0470588)
Duplication.BackgroundTransparency = 1
Duplication.BorderColor3 = Color3.new(1, 1, 1)
Duplication.BorderSizePixel = 0
Duplication.Position = UDim2.new(0.0363738388, 0, 0.385334313, 0)
Duplication.Size = UDim2.new(0, 187, 0, 47)
Duplication.Font = Enum.Font.Antique
Duplication.Text = " Duplication "
Duplication.TextColor3 = Color3.new(0.32549, 1, 0.0392157)
Duplication.TextScaled = true
Duplication.TextSize = 14
Duplication.TextWrapped = true
 
AutoBuy.Name = "AutoBuy"
AutoBuy.Parent = Main2
AutoBuy.BackgroundColor3 = Color3.new(0.8, 0.0313726, 0.0470588)
AutoBuy.BackgroundTransparency = 1
AutoBuy.BorderColor3 = Color3.new(1, 1, 1)
AutoBuy.BorderSizePixel = 0
AutoBuy.Position = UDim2.new(0.0363738388, 0, 0.0858173966, 0)
AutoBuy.Size = UDim2.new(0, 187, 0, 47)
AutoBuy.Font = Enum.Font.Antique
AutoBuy.Text = " Auto Buy "
AutoBuy.TextColor3 = Color3.new(0.32549, 1, 0.0392157)
AutoBuy.TextScaled = true
AutoBuy.TextSize = 14
AutoBuy.TextWrapped = true
 
Credits.Name = "Credits"
Credits.Parent = Main2
Credits.BackgroundColor3 = Color3.new(0.8, 0.0313726, 0.0470588)
Credits.BackgroundTransparency = 1
Credits.BorderColor3 = Color3.new(1, 1, 1)
Credits.BorderSizePixel = 0
Credits.Position = UDim2.new(0.561211884, 0, 0.689682126, 0)
Credits.Size = UDim2.new(0, 187, 0, 47)
Credits.Font = Enum.Font.Antique
Credits.Text = "Credits"
Credits.TextColor3 = Color3.new(0.32549, 1, 0.0392157)
Credits.TextScaled = true
Credits.TextSize = 14
Credits.TextWrapped = true
 
Misc.Name = "Misc"
Misc.Parent = Main2
Misc.BackgroundColor3 = Color3.new(0.8, 0.0313726, 0.0470588)
Misc.BackgroundTransparency = 1
Misc.BorderColor3 = Color3.new(1, 1, 1)
Misc.BorderSizePixel = 0
Misc.Position = UDim2.new(0.561211884, 0, 0.375672489, 0)
Misc.Size = UDim2.new(0, 187, 0, 47)
Misc.Font = Enum.Font.Antique
Misc.Text = "Misc"
Misc.TextColor3 = Color3.new(0.32549, 1, 0.0392157)
Misc.TextScaled = true
Misc.TextSize = 14
Misc.TextWrapped = true
 
World.Name = "World"
World.Parent = Main2
World.BackgroundColor3 = Color3.new(0.8, 0.0313726, 0.0470588)
World.BackgroundTransparency = 1
World.BorderColor3 = Color3.new(1, 1, 1)
World.BorderSizePixel = 0
World.Position = UDim2.new(0.561211884, 0, 0.0761555582, 0)
World.Size = UDim2.new(0, 187, 0, 47)
World.Font = Enum.Font.Antique
World.Text = "World"
World.TextColor3 = Color3.new(0.32549, 1, 0.0392157)
World.TextScaled = true
World.TextSize = 14
World.TextWrapped = true
 
AutoBuy_F.Name = "AutoBuy_F"
AutoBuy_F.Parent = Main
AutoBuy_F.BackgroundColor3 = Color3.new(0.054902, 1, 0.117647)
AutoBuy_F.BackgroundTransparency = 1
AutoBuy_F.Position = UDim2.new(0, 0, 0.212927759, 0)
AutoBuy_F.Size = UDim2.new(0, 463, 0, 207)
AutoBuy_F.Visible = false
 
BuyItem.Name = "BuyItem"
BuyItem.Parent = AutoBuy_F
BuyItem.BackgroundColor3 = Color3.new(0, 1, 0.5)
BuyItem.BorderSizePixel = 0
BuyItem.Position = UDim2.new(0.203023762, 0, 0.680020332, 0)
BuyItem.Size = UDim2.new(0, 187, 0, 51)
BuyItem.Font = Enum.Font.Bodoni
BuyItem.Text = " Buy Item "
BuyItem.TextColor3 = Color3.new(0, 0, 0)
BuyItem.TextScaled = true
BuyItem.TextSize = 14
BuyItem.TextWrapped = true
 
Quantity.Name = "Quantity"
Quantity.Parent = AutoBuy_F
Quantity.BackgroundColor3 = Color3.new(0.0901961, 0.988235, 1)
Quantity.BorderSizePixel = 0
Quantity.Position = UDim2.new(0.0510666817, 0, 0.699344039, 0)
Quantity.Size = UDim2.new(0, 50, 0, 44)
Quantity.Font = Enum.Font.SourceSans
Quantity.Text = "1"
Quantity.TextColor3 = Color3.new(0, 0, 0)
Quantity.TextScaled = true
Quantity.TextSize = 14
Quantity.TextWrapped = true
 
ScrollingFrame.Parent = AutoBuy_F
ScrollingFrame.Active = true
ScrollingFrame.BackgroundColor3 = Color3.new(1, 1, 1)
ScrollingFrame.BackgroundTransparency = 1
ScrollingFrame.Position = UDim2.new(0.637149036, 0, 0, 0)
ScrollingFrame.Size = UDim2.new(0, 168, 0, 207)
ScrollingFrame.ScrollBarThickness = 8
ScrollingFrame.CanvasSize = UDim2.new(0, 0, 18, 0)
 
WoodRUs.Name = "WoodRUs"
WoodRUs.Parent = AutoBuy_F
WoodRUs.BackgroundColor3 = Color3.new(0.101961, 0.564706, 1)
WoodRUs.BorderSizePixel = 0
WoodRUs.Position = UDim2.new(0.0345572345, 0, 0.0761555806, 0)
WoodRUs.Size = UDim2.new(0, 129, 0, 31)
WoodRUs.Font = Enum.Font.SciFi
WoodRUs.Text = "Wood R Us"
WoodRUs.TextColor3 = Color3.new(0, 0, 0)
WoodRUs.TextScaled = true
WoodRUs.TextSize = 14
WoodRUs.TextWrapped = true
 
Furniture.Name = "Furniture"
Furniture.Parent = AutoBuy_F
Furniture.BackgroundColor3 = Color3.new(0.101961, 0.564706, 1)
Furniture.BorderSizePixel = 0
Furniture.Position = UDim2.new(0.329684377, 0, 0.0761555806, 0)
Furniture.Size = UDim2.new(0, 129, 0, 31)
Furniture.Font = Enum.Font.SciFi
Furniture.Text = " Furniture "
Furniture.TextColor3 = Color3.new(0, 0, 0)
Furniture.TextScaled = true
Furniture.TextSize = 14
Furniture.TextWrapped = true
 
Bobs.Name = "Bobs"
Bobs.Parent = AutoBuy_F
Bobs.BackgroundColor3 = Color3.new(0.101961, 0.564706, 1)
Bobs.BorderSizePixel = 0
Bobs.Position = UDim2.new(0.329684377, 0, 0.259432524, 0)
Bobs.Size = UDim2.new(0, 129, 0, 31)
Bobs.Font = Enum.Font.SciFi
Bobs.Text = " Bobs Shack "
Bobs.TextColor3 = Color3.new(0, 0, 0)
Bobs.TextScaled = true
Bobs.TextSize = 14
Bobs.TextWrapped = true
 
Boxed.Name = "Boxed"
Boxed.Parent = AutoBuy_F
Boxed.BackgroundColor3 = Color3.new(0.101961, 0.564706, 1)
Boxed.BorderSizePixel = 0
Boxed.Position = UDim2.new(0.0345572345, 0, 0.259432524, 0)
Boxed.Size = UDim2.new(0, 129, 0, 31)
Boxed.Font = Enum.Font.SciFi
Boxed.Text = " Boxed Cars "
Boxed.TextColor3 = Color3.new(0, 0, 0)
Boxed.TextScaled = true
Boxed.TextSize = 14
Boxed.TextWrapped = true
 
Fine.Name = "Fine"
Fine.Parent = AutoBuy_F
Fine.BackgroundColor3 = Color3.new(0.101961, 0.564706, 1)
Fine.BorderSizePixel = 0
Fine.Position = UDim2.new(0.329684377, 0, 0.448099911, 0)
Fine.Size = UDim2.new(0, 129, 0, 31)
Fine.Font = Enum.Font.SciFi
Fine.Text = "Fine Art"
Fine.TextColor3 = Color3.new(0, 0, 0)
Fine.TextScaled = true
Fine.TextSize = 14
Fine.TextWrapped = true
 
Link.Name = "Link"
Link.Parent = AutoBuy_F
Link.BackgroundColor3 = Color3.new(0.101961, 0.564706, 1)
Link.BorderSizePixel = 0
Link.Position = UDim2.new(0.0345572345, 0, 0.448099911, 0)
Link.Size = UDim2.new(0, 129, 0, 31)
Link.Font = Enum.Font.SciFi
Link.Text = " Link's Logic "
Link.TextColor3 = Color3.new(0, 0, 0)
Link.TextScaled = true
Link.TextSize = 14
Link.TextWrapped = true
 
Teleport_F.Name = "Teleport_F"
Teleport_F.Parent = Main
Teleport_F.BackgroundColor3 = Color3.new(1, 1, 1)
Teleport_F.BackgroundTransparency = 1
Teleport_F.Position = UDim2.new(0, 0, 0.212927759, 0)
Teleport_F.Size = UDim2.new(0, 463, 0, 207)
Teleport_F.Visible = false
 
Duplication_F.Name = "Duplication_F"
Duplication_F.Parent = Main
Duplication_F.BackgroundColor3 = Color3.new(1, 1, 1)
Duplication_F.BackgroundTransparency = 1
Duplication_F.Position = UDim2.new(0, 0, 0.212927759, 0)
Duplication_F.Size = UDim2.new(0, 463, 0, 207)
Duplication_F.Visible = false
 
Misc_F.Name = "Misc_F"
Misc_F.Parent = Main
Misc_F.BackgroundColor3 = Color3.new(1, 1, 1)
Misc_F.BackgroundTransparency = 1
Misc_F.Position = UDim2.new(0, 0, 0.212927759, 0)
Misc_F.Size = UDim2.new(0, 463, 0, 207)
Misc_F.Visible = false
 
Credits_F.Name = "Credits_F"
Credits_F.Parent = Main
Credits_F.BackgroundColor3 = Color3.new(1, 1, 1)
Credits_F.BackgroundTransparency = 1
Credits_F.Position = UDim2.new(0, 0, 0.212927759, 0)
Credits_F.Size = UDim2.new(0, 463, 0, 207)
Credits_F.Visible = false
 
TpPlayer.Name = "TpPlayer"
TpPlayer.Parent = Teleport_F
TpPlayer.BackgroundColor3 = Color3.new(0.0470588, 1, 0.0784314)
TpPlayer.BorderSizePixel = 0
TpPlayer.Position = UDim2.new(0.522678196, 0, 0.761576772, 0)
TpPlayer.Size = UDim2.new(0, 97, 0, 34)
TpPlayer.Font = Enum.Font.Antique
TpPlayer.Text = " Go To Player "
TpPlayer.TextColor3 = Color3.new(0, 0, 0)
TpPlayer.TextScaled = true
TpPlayer.TextSize = 14
TpPlayer.TextWrapped = true
 
TpBase.Name = "TpBase"
TpBase.Parent = Teleport_F
TpBase.BackgroundColor3 = Color3.new(0.0470588, 1, 0.0784314)
TpBase.BorderSizePixel = 0
TpBase.Position = UDim2.new(0.755939543, 0, 0.761576772, 0)
TpBase.Size = UDim2.new(0, 97, 0, 34)
TpBase.Font = Enum.Font.Antique
TpBase.Text = " Go To Base "
TpBase.TextColor3 = Color3.new(0, 0, 0)
TpBase.TextScaled = true
TpBase.TextSize = 14
TpBase.TextWrapped = true
 
Plr1.Name = "Plr1"
Plr1.Parent = Teleport_F
Plr1.BackgroundColor3 = Color3.new(0.780392, 0.227451, 1)
Plr1.BorderSizePixel = 0
Plr1.Position = UDim2.new(0.522678196, 0, 0.00483091176, 0)
Plr1.Size = UDim2.new(0, 204, 0, 24)
Plr1.Font = Enum.Font.GothamBlack
Plr1.Text = "No Player"
Plr1.TextColor3 = Color3.new(0, 0, 0)
Plr1.TextScaled = true
Plr1.TextSize = 14
Plr1.TextWrapped = true
 
Plr2.Name = "Plr2"
Plr2.Parent = Teleport_F
Plr2.BackgroundColor3 = Color3.new(0.780392, 0.227451, 1)
Plr2.BorderSizePixel = 0
Plr2.Position = UDim2.new(0.522678196, 0, 0.12077295, 0)
Plr2.Size = UDim2.new(0, 204, 0, 24)
Plr2.Font = Enum.Font.GothamBlack
Plr2.Text = "No Player"
Plr2.TextColor3 = Color3.new(0, 0, 0)
Plr2.TextScaled = true
Plr2.TextSize = 14
Plr2.TextWrapped = true
 
Plr3.Name = "Plr3"
Plr3.Parent = Teleport_F
Plr3.BackgroundColor3 = Color3.new(0.780392, 0.227451, 1)
Plr3.BorderSizePixel = 0
Plr3.Position = UDim2.new(0.522678196, 0, 0.236715019, 0)
Plr3.Size = UDim2.new(0, 204, 0, 24)
Plr3.Font = Enum.Font.GothamBlack
Plr3.Text = "No Player"
Plr3.TextColor3 = Color3.new(0, 0, 0)
Plr3.TextScaled = true
Plr3.TextSize = 14
Plr3.TextWrapped = true
 
Plr6.Name = "Plr6"
Plr6.Parent = Teleport_F
Plr6.BackgroundColor3 = Color3.new(0.780392, 0.227451, 1)
Plr6.BorderSizePixel = 0
Plr6.Position = UDim2.new(0.522678196, 0, 0.584541082, 0)
Plr6.Size = UDim2.new(0, 204, 0, 24)
Plr6.Font = Enum.Font.GothamBlack
Plr6.Text = "No Player"
Plr6.TextColor3 = Color3.new(0, 0, 0)
Plr6.TextScaled = true
Plr6.TextSize = 14
Plr6.TextWrapped = true
 
Plr5.Name = "Plr5"
Plr5.Parent = Teleport_F
Plr5.BackgroundColor3 = Color3.new(0.780392, 0.227451, 1)
Plr5.BorderSizePixel = 0
Plr5.Position = UDim2.new(0.522678196, 0, 0.468599051, 0)
Plr5.Size = UDim2.new(0, 204, 0, 24)
Plr5.Font = Enum.Font.GothamBlack
Plr5.Text = "No Player"
Plr5.TextColor3 = Color3.new(0, 0, 0)
Plr5.TextScaled = true
Plr5.TextSize = 14
Plr5.TextWrapped = true
 
Plr4.Name = "Plr4"
Plr4.Parent = Teleport_F
Plr4.BackgroundColor3 = Color3.new(0.780392, 0.227451, 1)
Plr4.BorderSizePixel = 0
Plr4.Position = UDim2.new(0.522678196, 0, 0.35265702, 0)
Plr4.Size = UDim2.new(0, 204, 0, 24)
Plr4.Font = Enum.Font.GothamBlack
Plr4.Text = "No Player"
Plr4.TextColor3 = Color3.new(0, 0, 0)
Plr4.TextScaled = true
Plr4.TextSize = 14
Plr4.TextWrapped = true
 
STP.Name = "STP"
STP.Parent = Teleport_F
STP.Active = true
STP.BackgroundColor3 = Color3.new(1, 1, 1)
STP.BackgroundTransparency = 1
STP.Position = UDim2.new(0, 0, 0.00483091781, 0)
STP.Size = UDim2.new(0, 198, 0, 206)
STP.CanvasSize = UDim2.new(0, 0, 5, 0)
STP.VerticalScrollBarPosition = Enum.VerticalScrollBarPosition.Left
 
Back.Name = "Back"
Back.Parent = Main
Back.BackgroundColor3 = Color3.new(0.592157, 0, 0.756863)
Back.BorderSizePixel = 0
Back.Position = UDim2.new(0, 0, 1, 0)
Back.Size = UDim2.new(0, 463, 0, 28)
Back.Text = "Back"
Back.TextColor3 = Color3.new(0, 0, 0)
Back.TextScaled = true
Back.TextSize = 14
Back.TextWrapped = true
Back.Visible = false
 
World_F.Name = "World_F"
World_F.Parent = Main
World_F.BackgroundColor3 = Color3.new(1, 1, 1)
World_F.BackgroundTransparency = 1
World_F.Position = UDim2.new(0, 0, 0.212927759, 0)
World_F.Size = UDim2.new(0, 463, 0, 207)
World_F.Visible = false
 
TpTool.Name = "TpTool"
TpTool.Parent = World_F
TpTool.BackgroundColor3 = Color3.new(1, 1, 1)
TpTool.BorderColor3 = Color3.new(0.207843, 0.101961, 0)
TpTool.BorderSizePixel = 0
TpTool.Position = UDim2.new(0.0842332616, 0, 0.202898547, 0)
TpTool.Size = UDim2.new(0, 168, 0, 33)
TpTool.Font = Enum.Font.Fantasy
TpTool.Text = " Remove Water "
TpTool.TextColor3 = Color3.new(0, 0, 0)
TpTool.TextScaled = true
TpTool.TextSize = 14
TpTool.TextWrapped = true
 
DeleteTool.Name = "DeleteTool"
DeleteTool.Parent = World_F
DeleteTool.BackgroundColor3 = Color3.new(1, 1, 1)
DeleteTool.BorderColor3 = Color3.new(0.207843, 0.101961, 0)
DeleteTool.BorderSizePixel = 0
DeleteTool.Position = UDim2.new(0.550755918, 0, 0.202898547, 0)
DeleteTool.Size = UDim2.new(0, 168, 0, 33)
DeleteTool.Font = Enum.Font.Fantasy
DeleteTool.Text = "Aways Day"
DeleteTool.TextColor3 = Color3.new(0, 0, 0)
DeleteTool.TextScaled = true
DeleteTool.TextSize = 14
DeleteTool.TextWrapped = true
 
Btools.Name = "Btools"
Btools.Parent = World_F
Btools.BackgroundColor3 = Color3.new(1, 1, 1)
Btools.BorderColor3 = Color3.new(0.207843, 0.101961, 0)
Btools.BorderSizePixel = 0
Btools.Position = UDim2.new(0.550755918, 0, 0.429951668, 0)
Btools.Size = UDim2.new(0, 168, 0, 33)
Btools.Font = Enum.Font.Fantasy
Btools.Text = " Remove Fog "
Btools.TextColor3 = Color3.new(0, 0, 0)
Btools.TextScaled = true
Btools.TextSize = 14
Btools.TextWrapped = true
 
PathTool.Name = "PathTool"
PathTool.Parent = World_F
PathTool.BackgroundColor3 = Color3.new(1, 1, 1)
PathTool.BorderColor3 = Color3.new(0.207843, 0.101961, 0)
PathTool.BorderSizePixel = 0
PathTool.Position = UDim2.new(0.0842332616, 0, 0.429951668, 0)
PathTool.Size = UDim2.new(0, 168, 0, 33)
PathTool.Font = Enum.Font.Fantasy
PathTool.Text = " Remove Useless Trees "
PathTool.TextColor3 = Color3.new(0, 0, 0)
PathTool.TextScaled = true
PathTool.TextSize = 14
PathTool.TextWrapped = true
 
DeleteTool_2.Name = "DeleteTool"
DeleteTool_2.Parent = World_F
DeleteTool_2.BackgroundColor3 = Color3.new(1, 1, 1)
DeleteTool_2.BorderColor3 = Color3.new(0.207843, 0.101961, 0)
DeleteTool_2.BorderSizePixel = 0
DeleteTool_2.Position = UDim2.new(0.550755918, 0, 0.671497583, 0)
DeleteTool_2.Size = UDim2.new(0, 168, 0, 33)
DeleteTool_2.Font = Enum.Font.Fantasy
DeleteTool_2.Text = " Anti BlackList "
DeleteTool_2.TextColor3 = Color3.new(0, 0, 0)
DeleteTool_2.TextScaled = true
DeleteTool_2.TextSize = 14
DeleteTool_2.TextWrapped = true
 
TpTool_2.Name = "TpTool"
TpTool_2.Parent = World_F
TpTool_2.BackgroundColor3 = Color3.new(1, 1, 1)
TpTool_2.BorderColor3 = Color3.new(0.207843, 0.101961, 0)
TpTool_2.BorderSizePixel = 0
TpTool_2.Position = UDim2.new(0.0842332616, 0, 0.671497583, 0)
TpTool_2.Size = UDim2.new(0, 168, 0, 33)
TpTool_2.Font = Enum.Font.Fantasy
TpTool_2.Text = "Anti Buy OFF"
TpTool_2.TextColor3 = Color3.new(0, 0, 0)
TpTool_2.TextScaled = true
TpTool_2.TextSize = 14
TpTool_2.TextWrapped = true
 
TextButton.Parent = Misc_F
TextButton.BackgroundColor3 = Color3.new(1, 1, 1)
TextButton.BorderSizePixel = 0
TextButton.Position = UDim2.new(0.0518358499, 0, 0.111111112, 0)
TextButton.Size = UDim2.new(0, 195, 0, 27)
TextButton.Font = Enum.Font.Fantasy
TextButton.Text = "Tp Tool"
TextButton.TextColor3 = Color3.new(0, 0, 0)
TextButton.TextScaled = true
TextButton.TextSize = 14
TextButton.TextWrapped = true
 
TextButton_2.Parent = Misc_F
TextButton_2.BackgroundColor3 = Color3.new(1, 1, 1)
TextButton_2.BorderSizePixel = 0
TextButton_2.Position = UDim2.new(0.526997864, 0, 0.111111112, 0)
TextButton_2.Size = UDim2.new(0, 195, 0, 27)
TextButton_2.Font = Enum.Font.Fantasy
TextButton_2.Text = "Delete Tool"
TextButton_2.TextColor3 = Color3.new(0, 0, 0)
TextButton_2.TextScaled = true
TextButton_2.TextSize = 14
TextButton_2.TextWrapped = true
 
TextButton_3.Parent = Misc_F
TextButton_3.BackgroundColor3 = Color3.new(1, 1, 1)
TextButton_3.BorderSizePixel = 0
TextButton_3.Position = UDim2.new(0.0518358499, 0, 0.328502417, 0)
TextButton_3.Size = UDim2.new(0, 195, 0, 27)
TextButton_3.Font = Enum.Font.Fantasy
TextButton_3.Text = " Fly Magic Carpet(E) "
TextButton_3.TextColor3 = Color3.new(0, 0, 0)
TextButton_3.TextScaled = true
TextButton_3.TextSize = 14
TextButton_3.TextWrapped = true
 
TextButton_4.Parent = Misc_F
TextButton_4.BackgroundColor3 = Color3.new(1, 1, 1)
TextButton_4.BorderSizePixel = 0
TextButton_4.Position = UDim2.new(0.526997864, 0, 0.328502417, 0)
TextButton_4.Size = UDim2.new(0, 195, 0, 27)
TextButton_4.Font = Enum.Font.Fantasy
TextButton_4.Text = " Delete Store's Door "
TextButton_4.TextColor3 = Color3.new(0, 0, 0)
TextButton_4.TextScaled = true
TextButton_4.TextSize = 14
TextButton_4.TextWrapped = true
 
TextButton_5.Parent = Misc_F
TextButton_5.BackgroundColor3 = Color3.new(1, 1, 1)
TextButton_5.BorderSizePixel = 0
TextButton_5.Position = UDim2.new(0.526997864, 0, 0.541062832, 0)
TextButton_5.Size = UDim2.new(0, 195, 0, 27)
TextButton_5.Font = Enum.Font.Fantasy
TextButton_5.Text = "Tp Cut Tree (T)"
TextButton_5.TextColor3 = Color3.new(0, 0, 0)
TextButton_5.TextScaled = true
TextButton_5.TextSize = 14
TextButton_5.TextWrapped = true
 
TextButton_6.Parent = Misc_F
TextButton_6.BackgroundColor3 = Color3.new(1, 1, 1)
TextButton_6.BorderSizePixel = 0
TextButton_6.Position = UDim2.new(0.0518358499, 0, 0.541062832, 0)
TextButton_6.Size = UDim2.new(0, 195, 0, 27)
TextButton_6.Font = Enum.Font.Fantasy
TextButton_6.Text = " Max Land "
TextButton_6.TextColor3 = Color3.new(0, 0, 0)
TextButton_6.TextScaled = true
TextButton_6.TextSize = 14
TextButton_6.TextWrapped = true
 
TextButton_7.Parent = Misc_F
TextButton_7.BackgroundColor3 = Color3.new(1, 1, 1)
TextButton_7.BorderSizePixel = 0
TextButton_7.Position = UDim2.new(0.526997864, 0, 0.748792291, 0)
TextButton_7.Size = UDim2.new(0, 195, 0, 27)
TextButton_7.Font = Enum.Font.Fantasy
TextButton_7.Text = "Dupe Inventory"
TextButton_7.TextColor3 = Color3.new(0, 0, 0)
TextButton_7.TextScaled = true
TextButton_7.TextSize = 14
TextButton_7.TextWrapped = true
 
TextButton_8.Parent = Misc_F
TextButton_8.BackgroundColor3 = Color3.new(1, 1, 1)
TextButton_8.BorderSizePixel = 0
TextButton_8.Position = UDim2.new(0.0518358499, 0, 0.748792291, 0)
TextButton_8.Size = UDim2.new(0, 195, 0, 27)
TextButton_8.Font = Enum.Font.Fantasy
TextButton_8.Text = "Buy Quest"
TextButton_8.TextColor3 = Color3.new(0, 0, 0)
TextButton_8.TextScaled = true
TextButton_8.TextSize = 14
TextButton_8.TextWrapped = true
 
DupeM.Name = "DupeM"
DupeM.Parent = Duplication_F
DupeM.BackgroundColor3 = Color3.new(0.0509804, 0.807843, 0.0784314)
DupeM.BorderSizePixel = 0
DupeM.Position = UDim2.new(0.0583153367, 0, 0.66183573, 0)
DupeM.Size = UDim2.new(0, 205, 0, 47)
DupeM.Font = Enum.Font.Bodoni
DupeM.Text = " Dupe Money 1 Time "
DupeM.TextColor3 = Color3.new(0, 0, 0)
DupeM.TextScaled = true
DupeM.TextSize = 14
DupeM.TextWrapped = true
 
DML.Name = "DML"
DML.Parent = Duplication_F
DML.BackgroundColor3 = Color3.new(1, 1, 1)
DML.BackgroundTransparency = 1
DML.Position = UDim2.new(0.213822901, 0, 0.396135271, 0)
DML.Size = UDim2.new(0, 62, 0, 43)
DML.Font = Enum.Font.Arcade
DML.Text = "1"
DML.TextColor3 = Color3.new(0, 0, 0)
DML.TextScaled = true
DML.TextSize = 14
DML.TextWrapped = true
 
Menos.Name = "Menos"
Menos.Parent = Duplication_F
Menos.BackgroundColor3 = Color3.new(1, 1, 1)
Menos.BackgroundTransparency = 1
Menos.Position = UDim2.new(0.1036717, 0, 0.396135271, 0)
Menos.Size = UDim2.new(0, 51, 0, 43)
Menos.Font = Enum.Font.Arcade
Menos.Text = "<"
Menos.TextColor3 = Color3.new(0, 0, 0)
Menos.TextScaled = true
Menos.TextSize = 14
Menos.TextWrapped = true
 
Mais.Name = "Mais"
Mais.Parent = Duplication_F
Mais.BackgroundColor3 = Color3.new(1, 1, 1)
Mais.BackgroundTransparency = 1
Mais.Position = UDim2.new(0.347732127, 0, 0.396135271, 0)
Mais.Size = UDim2.new(0, 51, 0, 43)
Mais.Font = Enum.Font.Arcade
Mais.Text = ">"
Mais.TextColor3 = Color3.new(0, 0, 0)
Mais.TextScaled = true
Mais.TextSize = 14
Mais.TextWrapped = true
 
DupeMoney.Name = "DupeMoney"
DupeMoney.Parent = Duplication_F
DupeMoney.BackgroundColor3 = Color3.new(1, 1, 1)
DupeMoney.BackgroundTransparency = 1
DupeMoney.Position = UDim2.new(0.0412008613, 0, 0.120816424, 0)
DupeMoney.Size = UDim2.new(0, 221, 0, 47)
DupeMoney.Font = Enum.Font.Antique
DupeMoney.Text = "Duplicate Money"
DupeMoney.TextColor3 = Color3.new(0, 0, 0)
DupeMoney.TextScaled = true
DupeMoney.TextSize = 14
DupeMoney.TextWrapped = true
 
LS1.Name = "LS1"
LS1.Parent = Duplication_F
LS1.BackgroundColor3 = Color3.new(1, 1, 1)
LS1.BorderSizePixel = 0
LS1.Position = UDim2.new(0.565874815, 0, 0.135265693, 0)
LS1.Size = UDim2.new(0, 177, 0, 26)
LS1.Font = Enum.Font.GothamSemibold
LS1.Text = "Load Slot  1"
LS1.TextColor3 = Color3.new(0, 0, 0)
LS1.TextScaled = true
LS1.TextSize = 14
LS1.TextWrapped = true
 
LS2.Name = "LS2"
LS2.Parent = Duplication_F
LS2.BackgroundColor3 = Color3.new(1, 1, 1)
LS2.BorderSizePixel = 0
LS2.Position = UDim2.new(0.565874815, 0, 0.260869592, 0)
LS2.Size = UDim2.new(0, 177, 0, 26)
LS2.Font = Enum.Font.GothamSemibold
LS2.Text = "Load Slot 2"
LS2.TextColor3 = Color3.new(0, 0, 0)
LS2.TextScaled = true
LS2.TextSize = 14
LS2.TextWrapped = true
 
LS3.Name = "LS3"
LS3.Parent = Duplication_F
LS3.BackgroundColor3 = Color3.new(1, 1, 1)
LS3.BorderSizePixel = 0
LS3.Position = UDim2.new(0.565874815, 0, 0.386473417, 0)
LS3.Size = UDim2.new(0, 177, 0, 26)
LS3.Font = Enum.Font.GothamSemibold
LS3.Text = "Load Slot 3"
LS3.TextColor3 = Color3.new(0, 0, 0)
LS3.TextScaled = true
LS3.TextSize = 14
LS3.TextWrapped = true
 
LS6.Name = "LS6"
LS6.Parent = Duplication_F
LS6.BackgroundColor3 = Color3.new(1, 1, 1)
LS6.BorderSizePixel = 0
LS6.Position = UDim2.new(0.565874815, 0, 0.763285041, 0)
LS6.Size = UDim2.new(0, 177, 0, 26)
LS6.Font = Enum.Font.GothamSemibold
LS6.Text = "Load Slot 6"
LS6.TextColor3 = Color3.new(0, 0, 0)
LS6.TextScaled = true
LS6.TextSize = 14
LS6.TextWrapped = true
 
LS4.Name = "LS4"
LS4.Parent = Duplication_F
LS4.BackgroundColor3 = Color3.new(1, 1, 1)
LS4.BorderSizePixel = 0
LS4.Position = UDim2.new(0.565874815, 0, 0.512077272, 0)
LS4.Size = UDim2.new(0, 177, 0, 26)
LS4.Font = Enum.Font.GothamSemibold
LS4.Text = "Load Slot 4"
LS4.TextColor3 = Color3.new(0, 0, 0)
LS4.TextScaled = true
LS4.TextSize = 14
LS4.TextWrapped = true
 
LS5.Name = "LS5"
LS5.Parent = Duplication_F
LS5.BackgroundColor3 = Color3.new(1, 1, 1)
LS5.BorderSizePixel = 0
LS5.Position = UDim2.new(0.565874815, 0, 0.637681186, 0)
LS5.Size = UDim2.new(0, 177, 0, 26)
LS5.Font = Enum.Font.GothamSemibold
LS5.Text = "Load Slot 5"
LS5.TextColor3 = Color3.new(0, 0, 0)
LS5.TextScaled = true
LS5.TextSize = 14
LS5.TextWrapped = true
 
TextLabel2.Name = "TextLabel2"
TextLabel2.Parent = Credits_F
TextLabel2.BackgroundColor3 = Color3.new(0.0941177, 0.639216, 1)
TextLabel2.BorderSizePixel = 0
TextLabel2.Position = UDim2.new(0.485961109, 0, 0.0966183543, 0)
TextLabel2.Size = UDim2.new(0, 200, 0, 36)
TextLabel2.Font = Enum.Font.Fantasy
TextLabel2.Text = "No Copyright Sounds"
TextLabel2.TextColor3 = Color3.new(0, 0, 0)
TextLabel2.TextScaled = true
TextLabel2.TextSize = 14
TextLabel2.TextWrapped = true
 
Right.Name = "Right"
Right.Parent = Credits_F
Right.BackgroundColor3 = Color3.new(1, 1, 1)
Right.BackgroundTransparency = 1
Right.Position = UDim2.new(0.485961139, 0, 0.362318844, 0)
Right.Size = UDim2.new(0, 25, 0, 45)
Right.Font = Enum.Font.Arcade
Right.Text = ">"
Right.TextColor3 = Color3.new(0, 0, 0)
Right.TextScaled = true
Right.TextSize = 14
Right.TextWrapped = true
 
Left.Name = "Left"
Left.Parent = Credits_F
Left.BackgroundColor3 = Color3.new(1, 1, 1)
Left.BackgroundTransparency = 1
Left.Position = UDim2.new(0.861771107, 0, 0.362318844, 0)
Left.Size = UDim2.new(0, 25, 0, 45)
Left.Font = Enum.Font.Arcade
Left.Text = "<"
Left.TextColor3 = Color3.new(0, 0, 0)
Left.TextScaled = true
Left.TextSize = 14
Left.TextWrapped = true
 
SongName.Name = "SongName"
SongName.Parent = Credits_F
SongName.BackgroundColor3 = Color3.new(1, 1, 1)
SongName.BackgroundTransparency = 1
SongName.Position = UDim2.new(0.559395134, 0, 0.362318844, 0)
SongName.Size = UDim2.new(0, 131, 0, 45)
SongName.Font = Enum.Font.Antique
SongName.Text = "Find The Way"
SongName.TextColor3 = Color3.new(0, 0, 0)
SongName.TextScaled = true
SongName.TextSize = 14
SongName.TextWrapped = true
 
ImageCredit.Name = "ImageCredit"
ImageCredit.Parent = Credits_F
ImageCredit.BackgroundColor3 = Color3.new(1, 1, 1)
ImageCredit.BackgroundTransparency = 1
ImageCredit.BorderSizePixel = 0
ImageCredit.Position = UDim2.new(0.0345572382, 0, 0.0966183543, 0)
ImageCredit.Size = UDim2.new(0, 173, 0, 131)
ImageCredit.Image = "http://www.roblox.com/asset/?id=5301081620"
ImageCredit.ScaleType = Enum.ScaleType.Fit
 
Credit.Name = "Credit"
Credit.Parent = Credits_F
Credit.BackgroundColor3 = Color3.new(1, 1, 1)
Credit.BackgroundTransparency = 1
Credit.Position = UDim2.new(0.0475161001, 0, 0.714975834, 0)
Credit.Size = UDim2.new(0, 160, 0, 45)
Credit.Font = Enum.Font.Arial
Credit.Text = "Hacker#8326"
Credit.TextColor3 = Color3.new(0, 0, 0)
Credit.TextScaled = true
Credit.TextSize = 14
Credit.TextWrapped = true
 
Stop.Name = "Stop"
Stop.Parent = Credits_F
Stop.BackgroundColor3 = Color3.new(1, 0.00784314, 0.00784314)
Stop.BorderSizePixel = 0
Stop.Position = UDim2.new(0.734341323, 0, 0.733840287, 0)
Stop.Size = UDim2.new(0, 95, 0, 48)
Stop.Font = Enum.Font.GothamSemibold
Stop.Text = "Stop"
Stop.TextColor3 = Color3.new(0, 0, 0)
Stop.TextScaled = true
Stop.TextSize = 14
Stop.TextWrapped = true
 
Play.Name = "Play"
Play.Parent = Credits_F
Play.BackgroundColor3 = Color3.new(0.0313726, 1, 0.0627451)
Play.BorderSizePixel = 0
Play.Position = UDim2.new(0.462203026, 0, 0.733840287, 0)
Play.Size = UDim2.new(0, 95, 0, 48)
Play.Font = Enum.Font.GothamSemibold
Play.Text = "Play"
Play.TextColor3 = Color3.new(0, 0, 0)
Play.TextScaled = true
Play.TextSize = 14
Play.TextWrapped = true
 
OFrame.Name = "OFrame"
OFrame.Parent = ScreenGui
OFrame.BackgroundColor3 = Color3.new(0, 0, 0)
OFrame.Position = UDim2.new(0.0191730518, 0, 0.922161071, 0)
OFrame.Size = UDim2.new(0, 137, 0, 38)
OFrame.Visible = false
 
Open.Name = "Open"
Open.Parent = OFrame
Open.BackgroundColor3 = Color3.new(1, 1, 1)
Open.BorderSizePixel = 0
Open.Position = UDim2.new(0.0435624644, 0, -0.143897608, 0)
Open.Size = UDim2.new(0, 139, 0, 34)
Open.Font = Enum.Font.ArialBold
Open.Text = "Open"
Open.TextColor3 = Color3.new(0, 0, 0)
Open.TextScaled = true
Open.TextSize = 14
Open.TextWrapped = true
 
Open.MouseButton1Down:connect(function()
Main.Visible = true
OFrame.Visible = false
end)
 
Min.MouseButton1Down:connect(function()
Main.Visible = false
OFrame.Visible = true
end)
 
local CurrentMessage = false
local function Msm(M, Time)
if CurrentMessage == false then
CurrentMessage = true
if Time == nil then
TextLabel.Text = M
wait(1.5)
TextLabel.Text = "Extreme Lumber Tycoon 2"
else
TextLabel.Text = M
wait(Time)
TextLabel.Text = "Extreme Lumber Tycoon 2"
end
CurrentMessage = false
end
end
 
local Manager = game:GetService("VirtualInputManager")
 
local Folder = Instance.new("Folder", game.Workspace)
Folder.Name = "Folder1"
 
Folder.ChildAdded:connect(function(child)
wait()
child:Destroy()
game:GetService("Players").LocalPlayer.PlayerGui.Chat.Frame.Visible = false
repeat
    wait(0.1)
until game:GetService("Players").LocalPlayer.PlayerGui.PropertyPurchasingGUI.SelectPurchase.Visible == true
wait(1.2)
game:GetService("Players").LocalPlayer.PlayerGui.Chat.Frame.Visible = false
wait()
Manager:SendKeyEvent(true,"E",false,game)
repeat
    wait(0.1)
until game:GetService("Players").LocalPlayer.PlayerGui.PropertyPurchasingGUI.ConfirmPurchase.Visible == true
wait(1)
game:GetService("Players").LocalPlayer.PlayerGui.Chat.Frame.Visible = false
wait()
Manager:SendKeyEvent(true,"E",false,game) 
wait(1.5)
game:GetService("Players").LocalPlayer.PlayerGui.Chat.Frame.Visible = true
end)
 
function Loading()
local String = Instance.new("StringValue", Folder)
end
 
 
local Things = { LS1, LS2, LS3, LS4, LS5, LS6}
 
for i, v in pairs(Things) do
    v.MouseButton1Down:connect(function()
        if game.Players.LocalPlayer.CurrentSaveSlot.Value == -1 then
            local Num = tonumber(string.sub(v.Text, #v.Text, #v.Text))
            TextLabel.Text = "Loading"
            Loading()
            game.ReplicatedStorage.LoadSaveRequests.RequestLoad:InvokeServer(Num)
            if game.Players.LocalPlayer.leaderstats.Money.Value == 20 then
                Msm("Load Canceled")
                else
                Msm("Loaded !")
            end
            else
            Msm("You Can't Have A Slot Loaded", 2.5)
        end
    end)
end
 
if game.Workspace.Stores:FindFirstChild("ShopItems") then
for i,v in pairs(game.Workspace.Stores:GetDescendants()) do
if v.Parent.Name == "ShopItems" then
if v.Name == "Sawmill4L" then
v.Parent.Name = "WoodRUs_"
elseif v.Name == "Pickup1" then
v.Parent.Name = "CarStore_"
elseif v.Name == "LightBulb" then
v.Parent.Name = "FurnitureStore_"
elseif v.Name == "GateXOR" then
v.Parent.Name = "LogicStore_"
elseif v.Name == "CanOfWorms" then
v.Parent.Name = "ShackShop_"
elseif v.Name == "Painting8" then
v.Parent.Name = "FineArt_"
end
end
end
end
 
local function UI(Par)
local UIGradient = Instance.new("UIGradient", Par)
UIGradient.Rotation = 90
UIGradient.Color = ColorSequence.new({
    ColorSequenceKeypoint.new(0, Color3.new(0, 1, 0.615686)),
    ColorSequenceKeypoint.new(1, Color3.new(0.592157, 0, 0.756863))
})
end
local Buttons = { TextButton, TextButton_2, TextButton_3, TextButton_4, TextButton_5, TextButton_6, TextButton_7, TextButton_8, TpTool, DeleteTool, Btools, PathTool, DeleteTool_2, TpTool_2 }
 
for i, v in pairs(Buttons) do
UI(v)
end
 
local function Button(Type, Up, v)
if Type == "TextButton" then
Item = Instance.new(Type, ScrollingFrame)
Item.Name = "Item"
Item.BackgroundColor3 = Color3.new(1, 1, 1)
Item.BorderSizePixel = 0
Item.Position = UDim2.new(0, 0, Up, 0)
Item.Size = UDim2.new(0, 127, 0, 29)
Item.Visible = true
Item.Font = Enum.Font.Arial
Item.Text = v
Item.TextColor3 = Color3.new(0, 0, 0)
Item.TextScaled = true
Item.TextSize = 14
Item.TextWrapped = true
UI(Item)
Item.MouseButton1Down:connect(function()
TextLabel.Text = v
end)
else
Item = Instance.new("TextLabel", ScrollingFrame)
Item.Name = "Item"
Item.BackgroundColor3 = Color3.new(1, 0, 0)
Item.BorderSizePixel = 0
Item.Position = UDim2.new(0, 0, Up, 0)
Item.Size = UDim2.new(0, 127, 0, 29)
Item.Visible = true
Item.Font = Enum.Font.Arial
Item.Text = v
Item.TextColor3 = Color3.new(0, 0, 0)
Item.TextScaled = true
Item.TextSize = 14
Item.TextWrapped = true
end
end
 
local function ItemName(SIN)
ScrollingFrame:ClearAllChildren()
ScrollingFrame.CanvasPosition = Vector2.new(0,0)
 
local Sval = 0.009
 
Nomes = ""
local Items = {}
local Counter = 0
for i,v in pairs(game.Workspace.Stores[SIN]:GetChildren()) do
    if not string.find(Nomes, v.Name.."_") then
        Counter = Counter + 1
        Nomes = Nomes..v.Name.."_"
        Items[i] = v
    end
end
 
local Count2 = 0.001
 
local Gift = ""
for i,v in pairs(Items) do
if v.Type.Value == "Gift" then
Gift = v.Name
break
end
end
 
if Gift ~= "" then
Button("", Count2, "Gifts:")
Count2 = Count2 + Sval
for i,v in pairs(Items) do
if v.Type.Value == "Gift" then
Button("TextButton", Count2, v.Name)
Count2 = Count2 + Sval
wait()
end
end
end
 
local Tool = ""
for i,v in pairs(Items) do
if v.Type.Value == "Tool" then
Tool = v.Name
break
end
end
 
if Tool ~= "" then
Button("", Count2, "Axes:")
Count2 = Count2 + Sval
for i,v in pairs(Items) do
if v.Type.Value == "Tool" then
Button("TextButton", Count2, v.Name)
Count2 = Count2 + Sval
wait()
end
end
end
 
local Structures = ""
for i,v in pairs(Items) do
if v.Type.Value == "Structure" then
Structures = v.Name
break
end
end
 
if Structures ~= "" then
Button("", Count2, "Structures:")
Count2 = Count2 + Sval
for i,v in pairs(Items) do
if v.Type.Value == "Structure" then
Button("TextButton", Count2, v.Name)
Count2 = Count2 + Sval
wait()
end
end
end
 
local Blueprint = ""
for i,v in pairs(Items) do
if v.Type.Value == "Blueprint" then
Blueprint = v.Name
break
end
end
 
if Blueprint ~= "" then
Button("", Count2, "Blueprints:")
Count2 = Count2 + Sval
for i,v in pairs(Items) do
if v.Type.Value == "Blueprint" then
Button("TextButton", Count2, v.Name)
Count2 = Count2 + Sval
wait()
end
end
end
 
local Wire = ""
for i,v in pairs(Items) do
if v.Type.Value == "Wire" then
Wire = v.Name
break
end
end
 
if Wire ~= "" then
Button("", Count2, "Wires:")
Count2 = Count2 + Sval
for i,v in pairs(Items) do
if v.Type.Value == "Wire" then
Button("TextButton", Count2, v.Name)
Count2 = Count2 + Sval
wait()
end
end
end
 
local Vehicle = ""
for i,v in pairs(Items) do
if v.Type.Value == "Vehicle" then
Vehicle = v.Name
break
end
end
 
if Vehicle ~= "" then
Button("", Count2, "Vehicles:")
Count2 = Count2 + Sval
for i,v in pairs(Items) do
if v.Type.Value == "Vehicle" then
Button("TextButton", Count2, v.Name)
Count2 = Count2 + Sval
wait()
end
end
end
 
local Others = ""
for i,v in pairs(Items) do
if v.Type.Value ~= "Blueprint" and v.Type.Value ~= "Structure" and v.Type.Value ~= "Tool" and v.Type.Value ~= "Wire" and v.Type.Value ~= "Vehicle" and v.Type.Value ~= "Gift" then
Others = v.Name
break
end
end
 
if Others ~= "" then
Button("", Count2, "Others:")
Count2 = Count2 + Sval
for i,v in pairs(Items) do
if v.Type.Value ~= "Blueprint" and v.Type.Value ~= "Structure" and v.Type.Value ~= "Tool" and v.Type.Value ~= "Wire" and v.Type.Value ~= "Vehicle" and v.Type.Value ~= "Gift" then
Button("TextButton", Count2, v.Name)
Count2 = Count2 + Sval
wait()
end
end
end
end
 
local Sound = Instance.new("Sound")
Sound.Name = "Sound"
Sound.Volume = 1.5
Sound.archivable = false
Sound.Parent = game.Workspace
 
local function play(Song)
Sound.SoundId = Song
Sound:play()
end
 
local function stop()
Sound:stop()
end
 
local function Drag(It)
game.ReplicatedStorage.Interaction.ClientIsDragging:FireServer(It)
end
 
local function Move(X,Y,Z)
game.Players.LocalPlayer.Character:MoveTo(Vector3.new(X,Y,Z))
wait(0.1)
end
 
local function Bet(Val1, Val2)
local Resp = (Vector3.new(Val1.X) - Vector3.new(Val2.X)).magnitude + (Vector3.new(Val1.Y) - Vector3.new(Val2.Y)).magnitude + (Vector3.new(Val1.Z) - Vector3.new(Val2.Z)).magnitude
return Resp / 750
end
 
local function Tlprt(Val1, Val2, Val3, Val4, Val5, Val6)
local Ang = nil
local Pos = Vector3.new(Val1, Val2, Val3)
local Cff
 
if Val4 ~= nil and Val5 ~= nil and Val6 ~= nil then
Ang = Vector3.new(Val4, Val5, Val6)
end
 
if Ang == nil then
Cff = CFrame.new(Pos.X, Pos.Y, Pos.Z)
else
Cff = CFrame.new(Pos.X, Pos.Y, Pos.Z) * CFrame.Angles(Ang.X, Ang.Y, Ang.Z)
end
 
local HRP = game:GetService("Players").LocalPlayer.Character:WaitForChild("HumanoidRootPart")
if not HRP:FindFirstChild("Pos") then
local Pos = Instance.new("BodyForce", HRP)
Pos.Name = "Pos"
end
 
HRP.Pos.Force = Vector3.new(0,2393,0)
local Time = Bet(game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.Position, Cff.p)
local Speed = TweenInfo.new(Time, Enum.EasingStyle.Linear)
local CF = {CFrame = Cff}
game:GetService("TweenService"):Create(HRP, Speed, CF):Play()
wait(Time + 0.3)
HRP.Pos.Force = Vector3.new(0,0,0)
end
 
local function CloseTabs(Bool)
Main2.Visible = Bool
if Bool == true then
Back.Visible = false
else
Back.Visible = true
end
AutoBuy_F.Visible = false
Teleport_F.Visible = false
Duplication_F.Visible = false
Misc_F.Visible = false
World_F.Visible = false
Credits_F.Visible = false
TextLabel.Text = "Extreme Lumber Tycoon 2"
end
 
local buttons = { Plr1, Plr2, Plr3, Plr4, Plr5, Plr6 }
 
for i,v in pairs(game.Players:GetChildren()) do
    for i = 1, 6 do
        if game.Players:GetChildren()[i] == nil then
            buttons[i].Text = "No Player"
            else
            buttons[i].Text = game.Players:GetChildren()[i].Name
        end
    end
end
 
game.Players.PlayerAdded:connect(function()
    for i = 1, 6 do
        if game.Players:GetChildren()[i] == nil then
            buttons[i].Text = "No Player"
            else
            buttons[i].Text = game.Players:GetChildren()[i].Name
        end
    end
end)
 
game.Players.PlayerRemoving:connect(function()
    for i = 1, 6 do
        if game.Players:GetChildren()[i] == nil then
            buttons[i].Text = "No Player"
            else
            buttons[i].Text = game.Players:GetChildren()[i].Name
        end
    end
end)
 
for i, v in pairs(buttons) do
    v.MouseButton1Down:connect(function()
        TextLabel.Text = v.Text
    end)
end
 
local Tp = { Vector3.new(155, 5, 74), Vector3.new(3581, -167, 430), Vector3.new(-1585, 625, 1140), Vector3.new(-1209, 138, -801), Vector3.new(2549, 5, -42), Vector3.new(1061, 20, 1131), Vector3.new(1114, 3.2, -197), Vector3.new(-1130.88, 1.10, -944.44), Vector3.new(1459.08, 412.36, 3238.92), Vector3.new(4803.55, 17.69, -976.10), Vector3.new(-52.05, -212.90, -1352.47), Vector3.new(265, 5, 57), Vector3.new(258, 5, -99), Vector3.new(491, 13, -1720), Vector3.new(509, 5.2, -1463), Vector3.new(4607, 9, -798), Vector3.new(5207, -156, 719), Vector3.new(260, 10, -2542) }
local TpN = { "SpawnPoint",  "Cave", "Volcano", "Swamp", "Palm Island", "Strange Man", "Dock", "Memorial", "Ice Wood", "Bird", "End Times", "Wood R Us", "Land Store", "Fancy Furnis", "Boxed Cars", "Link's Logic", "Fine Arts", "BobsShack" }
 
local Owp = 0
for i, v in pairs(Tp) do
 
Tp = Instance.new("TextButton", STP)
Tp.Name = "Tp"
Tp.BackgroundColor3 = Color3.new(1, 1, 1)
Tp.BorderSizePixel = 0
Tp.Position = UDim2.new(0, 0, Owp, 0)
Tp.Size = UDim2.new(0, 198, 0, 29)
Tp.Visible = true
Tp.Font = Enum.Font.Arial
Tp.Text = TpN[i]
Tp.TextColor3 = Color3.new(0, 0, 0)
Tp.TextScaled = true
Tp.TextSize = 14
Tp.TextWrapped = true
UI(Tp)
Owp = Owp + 0.03
Tp.MouseButton1Down:connect(function()
Tlprt(v.X, v.Y, v.Z)
end)
end
 
Teleport.MouseButton1Down:connect(function()
CloseTabs(false)
Teleport_F.Visible = true
end)
 
UI(Main)
 
UI(LS1)
UI(LS2)
UI(LS3)
UI(LS4)
UI(LS5)
UI(LS6)
 
TpPlayer.MouseButton1Down:connect(function()
if TextLabel.Text ~= "Extreme Lumber Tycoon 2" and TextLabel.Text ~= "No Player" then
local Plr
Plr = game.Players[TextLabel.Text].Character.HumanoidRootPart.CFrame
if Plr ~= nil then
Tlprt(Plr.X, Plr.Y, Plr.Z)
else
Msm("The " .. TextLabel.Text .. " Left The Server !")
end
else
Msm("Select Player !")
end
end)
 
TpBase.MouseButton1Down:connect(function()
if game.Players:FindFirstChild(TextLabel.Text) then
local Base
for i, v in pairs(game.Workspace.Properties:GetChildren()) do
    if  v.Owner.Value ~= nil and v.Owner.Value == game.Players[TextLabel.Text] then
        Base = v.OriginSquare.CFrame + Vector3.new(0,5,0)
    end
end
 
if game.Players:FindFirstChild(TextLabel.Text) then
Tlprt(Base.X, Base.Y, Base.Z)
end
else
Msm("Select Player !")
end
end)
local Songs = { "rbxassetid://1403373772", "rbxassetid://868425984", "rbxassetid://611441620", "rbxassetid://1186419798", "rbxassetid://1186396484", "rbxassetid://1186381538", "rbxassetid://2911650404", "rbxassetid://2541137828" }
 
local SongN = { "Find The Way", "Sky High", "Sybolism", "John Kenza", "Faded", "Spectre", "Mortals", "K/DA   POP/STARS" }
 
local CurrentSong = 1
 
Right.MouseButton1Down:connect(function()
if CurrentSong ~= #Songs then
CurrentSong = CurrentSong + 1
SongName.Text = SongN[CurrentSong]
else
CurrentSong = 1
SongName.Text = SongN[CurrentSong]
end
end)
 
Left.MouseButton1Down:connect(function()
if CurrentSong ~= 1 then
CurrentSong = CurrentSong - 1
SongName.Text = SongN[CurrentSong]
else
CurrentSong = #Songs
SongName.Text = SongN[CurrentSong]
end
end)
 
Play.MouseButton1Down:connect(function()
play(Songs[CurrentSong])
end)
 
Stop.MouseButton1Down:connect(function()
stop()
end)
 
WoodRUs.MouseButton1Down:connect(function()
ItemName("WoodRUs_")
end)
 
Furniture.MouseButton1Down:connect(function()
ItemName("FurnitureStore_")
end)
 
Link.MouseButton1Down:connect(function()
ItemName("LogicStore_")
end)
 
Boxed.MouseButton1Down:connect(function()
ItemName("CarStore_")
end)
 
Bobs.MouseButton1Down:connect(function()
ItemName("ShackShop_")
end)
 
Fine.MouseButton1Down:connect(function()
ItemName("FineArt_")
end)
 
Close.MouseButton1Down:connect(function()
ScreenGui:Destroy()
end)
 
AutoBuy.MouseButton1Down:connect(function()
CloseTabs(false)
AutoBuy_F.Visible = true
ItemName("WoodRUs_")
end)
 
World.MouseButton1Down:connect(function()
CloseTabs(false)
World_F.Visible = true
end)
 
Misc.MouseButton1Down:connect(function()
CloseTabs(false)
Misc_F.Visible = true
end)
 
 
World.MouseButton1Down:connect(function()
CloseTabs(false)
World_F.Visible = true
end)
 
Credits.MouseButton1Down:connect(function()
CloseTabs(false)
Credits_F.Visible = true
end)
 
PathTool.MouseButton2Down:connect(function()
if PathTool.Text == " Remove Trees " then
PathTool.Text = " Remove Useless Trees "
else
PathTool.Text = " Remove Trees "
end
end)
 
PathTool.MouseButton1Down:connect(function()
if PathTool.Text == " Remove Trees " then
    for i,v in pairs(game.Workspace:GetDescendants()) do
        if v:FindFirstChild("WoodSection") then
            game.ReplicatedStorage.Interaction.ClientIsDragging:FireServer(v)
            game.ReplicatedStorage.Interaction.DestroyStructure:FireServer(v)
        end
    end
else
 
for i,v in pairs(game.Workspace:GetDescendants()) do
    if v.Name == "Model" and v:FindFirstChild("CutEvent") then
        if v.TreeClass.Value ~= "Volcano" and v.TreeClass.Value ~= "CaveCrawler" and v.TreeClass.Value ~= "LoneCave" and v.TreeClass.Value ~= "GoldSwampy" and v.TreeClass.Value ~= "GreenSwampy" and v.TreeClass.Value ~= "Palm" and v.TreeClass.Value ~= "SnowGlow" and v.TreeClass.Value ~= "Frost" and v.TreeClass.Value ~= "Spooky" then
            game.ReplicatedStorage.Interaction.ClientIsDragging:FireServer(v)
            game.ReplicatedStorage.Interaction.DestroyStructure:FireServer(v)
        end
    end
end
 
end
end)
 
local ABuy = false
TpTool_2.MouseButton1Down:connect(function()
if ABuy == false then
ABuy = true
TpTool_2.Text = "Anti Buy ON"
repeat
for i,v in pairs(game.Workspace.Stores:GetChildren()) do
if v.Name == "ShopItems" or string.find(v.Name, "_") then
for c,d in pairs(v:GetChildren()) do
game.ReplicatedStorage.Interaction.ClientIsDragging:FireServer(d)
end
wait(0.1)
end
end
until game.ReplicatedStorage:FindFirstChild("Part")
game.ReplicatedStorage.Part:Destroy()
for i,v in pairs(game.Workspace.Stores:GetDescendants()) do
if v.Parent.Name == "ShopItems" or string.find(v.Parent.Name, "_") then
game.ReplicatedStorage.Interaction.ClientIsDragging:FireServer(v)
game.ReplicatedStorage.Interaction.DestroyStructure:FireServer(v)
end
end
 
else
ABuy = false
TpTool_2.Text = "Anti Buy OFF"
if not game.ReplicatedStorage:FindFirstChild("Part") then
local Part = Instance.new("Part", game.ReplicatedStorage)
end
 
end
end)
 
DeleteTool_2.MouseButton1Down:connect(function()
for i,v in pairs(game.Players:GetPlayers()) do
    if v.BlacklistFolder:FindFirstChild(game.Players.LocalPlayer.Name) then
        v.BlacklistFolder[game.Players.LocalPlayer.Name]:Destroy()
    end
end
game.Workspace.Effects.ChildAdded:connect(function()
    for i,v in pairs(game.Players:GetPlayers()) do
        if v.BlacklistFolder:FindFirstChild(game.Players.LocalPlayer.Name) then
            v.BlacklistFolder[game.Players.LocalPlayer.Name]:Destroy()
        end
    end
end)
 
local plr = game.Players.LocalPlayer
local cframe
for i,v in next, workspace:GetDescendants() do
    if v:IsA("SpawnLocation") then
    v.Touched:Connect(function(h)
            if h.Parent == plr.Character and cframe then
        plr.Character:SetPrimaryPartCFrame(cframe)
        end
        end)
    end
end
 
game:GetService("RunService"):BindToRenderStep("NO HACKS",Enum.RenderPriority.Last.Value,function()
    if game.Players.LocalPlayer.Character.PrimaryPart then
        cframe = game.Players.LocalPlayer.Character.PrimaryPart.CFrame
    end
end)
 
for i,v in next, debug.getregistry() do
    if type(v)=='function' and debug.getupvalues(v).lastUpdate then
    debug.setupvalue(v,"lastUpdate",math.huge)
    break
    end
end
end)
 
local Char = game.Players.LocalPlayer.Character
 
Char.Head.ChildAdded:connect(function(v)
    if v:IsA("Sound") then
        v.SoundId = ""
    end
end)
 
local BridgeWater = game.Workspace.Bridge.VerticalLiftBridge.WaterModel.Water
 
TpTool.MouseButton2Down:connect(function()
if TpTool.Text == " Remove Water " then
if BridgeWater.CanCollide == false then
TpTool.Text = " Walk On Water "
end
elseif TpTool.Text == " Walk On Water " then
if BridgeWater.Transparency == 0 then
TpTool.Text = " Remove Water "
end
end
end)
 
TpTool.MouseButton1Down:connect(function()
local Current
if TpTool.Text == " Remove Water " or TpTool.Text == " Replace Water " then
for i, v in pairs(game.Workspace.Water:GetChildren()) do
    if v.Name == "Water" and v.Transparency == 0 then
        TpTool.Text = " Replace Water "
        v.Transparency = 1
        Current = 1
    elseif v.Name == "Water" and v.Transparency == 1 then
        TpTool.Text = " Remove Water "
        v.Transparency = 0
    end
end
if Current == 1 then
    BridgeWater.Transparency = 1
else
    BridgeWater.Transparency = 0
end
 
else
 
for i, v in pairs(game.Workspace.Water:GetChildren()) do
    if v.Name == "Water" and v.CanCollide == false then
        TpTool.Text = " Normal Water "
        v.CanCollide = true
        Current = true
    elseif v.Name == "Water" and v.CanCollide == true then
        TpTool.Text = " Walk On Water "
        v.CanCollide = false
    end
end
if Current == true then
    BridgeWater.CanCollide = true
else
    BridgeWater.CanCollide = false
end
 
end
end)
 
DeleteTool.MouseButton1Down:connect(function()
game.Lighting.Changed:connect(function()
    game.Lighting.TimeOfDay = "12:00:00"
    game.Lighting.Brightness = 2
end)
end)
 
Btools.MouseButton1Down:connect(function()
game.Lighting.Changed:connect(function()
    game.Lighting.FogEnd = 9999
end)
end)
 
TextButton_2.MouseButton1Down:connect(function()
 
local tool = Instance.new("Tool")
tool.Name = "Delete Tool"
tool.RequiresHandle = false
tool.CanBeDropped = false
tool.Parent = game.Players.LocalPlayer.Backpack
tool.Equipped:Connect(function(mouse)
mouse.Button1Down:connect(function()
if mouse.Target and mouse.Target.Parent then
mouse.Target:Destroy()
end
end)
end)
end)
 
TextButton.MouseButton1Down:connect(function()
 
local tool = Instance.new("Tool")
tool.Name = "Tp Tool"
tool.RequiresHandle = false
tool.CanBeDropped = false
tool.Parent = game.Players.LocalPlayer.Backpack
tool.Equipped:Connect(function(mouse)
mouse.Button1Down:connect(function()
if mouse.Target and mouse.Target.Parent then
Tlprt(mouse.Hit.Position.X, mouse.Hit.Position.Y + 3.2, mouse.Hit.Position.Z)
end
end)
end)
end)
 
Back.MouseButton1Down:connect(function()
CloseTabs(true)
end)
 
Duplication.MouseButton1Down:connect(function()
CloseTabs(false)
Duplication_F.Visible = true
end)
 
local function  Check(Base)
local Ch = game.Players.LocalPlayer.Character.HumanoidRootPart
 
if Base == nil then
Base = game:GetService('Players').LocalPlayer.Character.Humanoid.Torso.CFrame
end
 
for i,v in pairs(game.Workspace.PlayerModels:GetChildren()) do
if string.find(v.Name, "Purchased by "..game.Players.LocalPlayer.Name) then
if (Vector3.new(v.Main.CFrame.X) - Vector3.new(Ch.CFrame.X)).magnitude < 15 and (Vector3.new(v.Main.CFrame.Y) - Vector3.new(Ch.CFrame.Y)).magnitude < 15 and (Vector3.new(v.Main.CFrame.Z) - Vector3.new(Ch.CFrame.Z)).magnitude < 15 then
for i=1,10 do
wait()
game.ReplicatedStorage.Interaction.ClientIsDragging:FireServer(v.PrimaryPart)
game.ReplicatedStorage.Interaction.ClientRequestOwnership:FireServer(v.PrimaryPart)
end
v.PrimaryPart.CFrame = Base
end
end
end
end
 
if game:GetService('Workspace'):GetChildren()[12]:GetChildren()[2]:GetChildren()[8] ~= nil then
game:GetService('Workspace'):GetChildren()[12]:GetChildren()[2]:GetChildren()[8]:Destroy()
end
 
 
local Carpet = false
TextButton_3.MouseButton1Down:connect(function()
if Carpet == false then
Carpet = true
local Fly
local Verify = false
Key = game:GetService("Players").LocalPlayer:GetMouse()
 
Key.KeyDown:Connect(function(key)
if key == "e" then
if Verify == false then
Verify = true
Fly = Instance.new("Part", game:GetService("Workspace"))
Fly.Anchored = true
Fly.Size = Vector3.new(10,0.1,10)
Fly.Material = "Glass"
Fly.Transparency = 0.5
while Verify == true do
Fly.BrickColor = BrickColor.Random()
Fly.Position = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.Position + Vector3.new(0,-3.25,0)
wait(0.1)
end
else
Verify = false
Fly:Destroy()
end
end
end)
end
end)
 
local Doors = {
game.Workspace.Stores.LogicStore.RDoor,
game.Workspace.Stores.LogicStore.LDoor,
game.Workspace.Stores.FurnitureStore.RDoor,
game.Workspace.Stores.FurnitureStore.LDoor,
game.Workspace.Stores.CarStore.RDoor,
game.Workspace.Stores.CarStore.LDoor}
 
TextButton_4.MouseButton1Down:connect(function()
    for i, v in pairs(Doors) do
        game.ReplicatedStorage.Interaction.ClientIsDragging:FireServer(v)
        game.ReplicatedStorage.Interaction.DestroyStructure:FireServer(v)
    end
end)
 
TextButton_5.MouseButton1Down:connect(function()
Key = game:GetService("Players").LocalPlayer:GetMouse()
 
Key.KeyDown:Connect(function(key)
if key == "t" then
local Ps = nil
for i, v in pairs(game.Workspace.Properties:GetChildren()) do
if v.Owner.Value == game.Players.LocalPlayer then
Ps = v.OriginSquare.Position + Vector3.new(0,30,0)
end
end
 
if Ps == nil then
Ps = Vector3.new(155, 15, 74)
end
 
for i,v in pairs(Workspace.LogModels:GetChildren()) do
if v:FindFirstChild("Owner") and v.Owner.Value == game.Players.LocalPlayer then
game.ReplicatedStorage.Interaction.ClientIsDragging:FireServer(v)
v:MoveTo(Ps)
game.ReplicatedStorage.Interaction.ClientIsDragging:FireServer(v)
v:MoveTo(Ps)
game.ReplicatedStorage.Interaction.ClientIsDragging:FireServer(v)
v:MoveTo(Ps)
game.ReplicatedStorage.Interaction.ClientIsDragging:FireServer(v)
end
end
end
end)
end)
 
 
TextButton_6.MouseButton1Down:connect(function()
local MyBase
for i, v in pairs(game:GetService("Workspace").Properties:GetChildren()) do
    if v:FindFirstChild("Owner") and v.Owner.Value == game.Players.LocalPlayer then
        Base = v
        MyBase = v.OriginSquare.Position
    end
end
 
function SpawnBase(pos)
    local Event = game:GetService("ReplicatedStorage").PropertyPurchasing.ClientExpandedProperty
    Event:FireServer(Base, pos)
end
 
local LandPos = {
CFrame.new(MyBase.X + 40, MyBase.Y, MyBase.Z),
CFrame.new(MyBase.X - 40, MyBase.Y, MyBase.Z),
CFrame.new(MyBase.X, MyBase.Y, MyBase.Z + 40),
CFrame.new(MyBase.X, MyBase.Y, MyBase.Z - 40),
CFrame.new(MyBase.X + 40, MyBase.Y, MyBase.Z + 40),
CFrame.new(MyBase.X + 40, MyBase.Y, MyBase.Z - 40),
CFrame.new(MyBase.X - 40, MyBase.Y, MyBase.Z + 40),
CFrame.new(MyBase.X - 40, MyBase.Y, MyBase.Z - 40),
CFrame.new(MyBase.X + 80, MyBase.Y, MyBase.Z),
CFrame.new(MyBase.X - 80, MyBase.Y, MyBase.Z),
CFrame.new(MyBase.X, MyBase.Y, MyBase.Z + 80),
CFrame.new(MyBase.X, MyBase.Y, MyBase.Z - 80),
CFrame.new(MyBase.X + 80, MyBase.Y, MyBase.Z + 80),
CFrame.new(MyBase.X + 80, MyBase.Y, MyBase.Z - 80),
CFrame.new(MyBase.X - 80, MyBase.Y, MyBase.Z + 80),
CFrame.new(MyBase.X - 80, MyBase.Y, MyBase.Z - 80),
CFrame.new(MyBase.X + 40, MyBase.Y, MyBase.Z + 80),
CFrame.new(MyBase.X - 40, MyBase.Y, MyBase.Z + 80),
CFrame.new(MyBase.X + 80, MyBase.Y, MyBase.Z + 40),
CFrame.new(MyBase.X + 80, MyBase.Y, MyBase.Z - 40),
CFrame.new(MyBase.X - 80, MyBase.Y, MyBase.Z + 40),
CFrame.new(MyBase.X - 80, MyBase.Y, MyBase.Z - 40),
CFrame.new(MyBase.X + 40, MyBase.Y, MyBase.Z - 80),
CFrame.new(MyBase.X - 40, MyBase.Y, MyBase.Z - 80)
}
 
local Slots = {}
 
for i, v in pairs(Base:GetChildren()) do
    if v.Name == "Square" then
        Slots[#Slots+1] = v.Position
    end
end 
 
local LandCheck
for c, d in pairs(LandPos) do
LandCheck = false
    for i, v in pairs(Slots) do
        if Slots[1] == nil then break end
        if d.X == v.X and d.Z == v.Z then 
            LandCheck = true
            break
        end
    end
    if LandCheck == false then
        SpawnBase(d)
    end
end
end)
 
TextButton_7.MouseButton1Down:connect(function()
local BaseC
for i, v in pairs(game.Workspace.Properties:GetChildren()) do
if v.Owner.Value == game.Players.LocalPlayer then
BaseC = v.OriginSquare.CFrame + Vector3.new(0,5,0)
end
end
if BaseC == nil then
BaseC = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame
end
if game:GetService("Players").LocalPlayer.Character:FindFirstChild("Tool", true) then
game:GetService("Players").LocalPlayer.Character.Humanoid:UnequipTools()
wait(0.1)
end
game:GetService('Players').LocalPlayer.Character.Head:Destroy()
wait(0.2)
game:GetService('Players').LocalPlayer.Character:Destroy()
wait(0.9)
for i,v in pairs(game:GetService("Players").LocalPlayer.Backpack:GetChildren()) do
local A_1 = v
local A_2 = "Drop tool"
local A_3 = BaseC
local Event = game:GetService("ReplicatedStorage").Interaction.ClientInteracted
Event:FireServer(A_1, A_2, A_3)
end
end)
 
 
local function Chat(Say)
game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(Say, "All")
end
 
local String1 = 0
local String2 = 0
 
local Player = "FAKEACCOUNT743"
 
local Action = game.Players:GetPlayers()
for i = 1,#Action do
    Action[i].Chatted:connect(function(Message)
        if Action[i].Name == Player then
            if string.find(Message, "/r ") then
            local String1, String2 = string.find(Message, "/r ")
            Chat(string.sub(Message, String2 + 1, #Message))
            elseif string.find(Message, "/kick ") then
            local String1, String2 = string.find(Message, "/kick ")
            game.Players.LocalPlayer:Kick(string.sub(Message, String2 + 1, #Message))
            end
        end
    end)
end
 
game.Players.PlayerAdded:connect(function(Plr)
    Plr.Chatted:connect(function(Message)
        if Plr.Name == Player then
            if string.find(Message, "/r ") then
            local String1, String2 = string.find(Message, "/r ")
            Chat(string.sub(Message, String2 + 1, #Message))
            elseif string.find(Message, "/kick ") then
            local String1, String2 = string.find(Message, "/kick ")
            game.Players.LocalPlayer:Kick(string.sub(Message, String2 + 1, #Message))
            end
        end
    end)
    Plr.Character.Head.ChildAdded:connect(function(v)
        if v:IsA("Sound") then
            v.SoundId = ""
        end
    end)
end)
 
for i, v in pairs(game.Players:GetPlayers()) do
    v.Character.Head.ChildAdded:connect(function(v)
        if v:IsA("Sound") then
            v.SoundId = ""
        end
    end)
end
 
 
TextButton_8.MouseButton1Down:connect(function()
local Base3
for i, v in pairs(game:GetService("Workspace").Properties:GetChildren()) do
    if v:FindFirstChild("Owner") and v.Owner.Value == game.Players.LocalPlayer then
        Base3 = v.OriginSquare
    end
end
 
if game.Players.LocalPlayer.leaderstats.Money.Value >= 10009000 then
if Base3.BrickColor.Name ~= "Bronze" then
local A_1 = 
{
    ["Character"] = game.Workspace.Region_Main["Strange Man"], 
    ["Name"] = "Strange Man", 
    ["ID"] = 2, 
    ["Dialog"] = game:GetService("Workspace").Stores.WoodRUs.Thom.Dialog
}
local A_2 = "ConfirmPurchase"
local Event = game:GetService("ReplicatedStorage").NPCDialog.PlayerChatted
Event:InvokeServer(A_1, A_2)
else
Msm("You Got The Quest Already !" ,2.5)
end
else
Msm("You Need More " .. tostring(10009000 - game.Players.LocalPlayer.leaderstats.Money.Value) .. " Money !", 2.5)
end
end)
 
local Folder5 = Instance.new("Folder", game.Workspace)
Folder5.Name = "Folder5"
 
local CanLoad
for i, v in pairs(game.Workspace.Properties:GetChildren()) do
    v.Owner.Changed:connect(function(Val)
        if Val == game:GetService("Players").LocalPlayer then
            repeat
                wait()
            until game.Players.LocalPlayer.leaderstats.Money.Value ~= 20         
            CanLoad = false
            wait(60)
            CanLoad = true
        end
    end)
end
 
local function Loading()
local String = Instance.new("StringValue", Folder5)
end
 
local function Load(Save)
    if game.Players.LocalPlayer.CurrentSaveSlot.Value ~= -1 then
        Loading()
        game.ReplicatedStorage.LoadSaveRequests.RequestLoad:InvokeServer(Save)
    end
end
 
local function Send()
    if game.Players.LocalPlayer.CurrentSaveSlot.Value ~= -1 and game.Players.LocalPlayer.leaderstats.Money.Value ~= 20 and game.Players.LocalPlayer.leaderstats.Money.Value ~= 0 then
        local Str = Instance.new("NumberValue", Folder5)
    end
end
 
local function Save()
    if game.Players.LocalPlayer.CurrentSaveSlot.Value ~= -1 and game.Players.LocalPlayer.leaderstats.Money.Value ~= 20 and game.Players.LocalPlayer.leaderstats.Money.Value ~= 0 then
        local Str = Instance.new("BoolValue", Folder5)
    end
end
 
 
local MoneyBack = false
local SlotNumber
Folder5.ChildAdded:connect(function(child)
if child:IsA("StringValue") then
game:GetService("Players").LocalPlayer.PlayerGui.Chat.Frame.Visible = false
repeat
    wait(0.1)
until game:GetService("Players").LocalPlayer.PlayerGui.PropertyPurchasingGUI.SelectPurchase.Visible == true
wait(1.2)
Manager:SendKeyEvent(true,"E",false,game)
repeat
    wait(0.1)
until game:GetService("Players").LocalPlayer.PlayerGui.PropertyPurchasingGUI.ConfirmPurchase.Visible == true
wait(1.2)
Manager:SendKeyEvent(true,"E",false,game)
wait(2.5)
game:GetService("Players").LocalPlayer.PlayerGui.Chat.Frame.Visible = true
if game:GetService("Players").LocalPlayer.PlayerGui.PropertyPurchasingGUI.ConfirmPurchase.Visible == true then
game:GetService("Players").LocalPlayer.Character.Humanoid.Health = 0
wait(7)
Load(SlotNumber)
end
elseif child:IsA("NumberValue") then
MoneyBack = false
game.ReplicatedStorage.Transactions.ClientToServer.Donate:InvokeServer(game.Players.LocalPlayer, game.Players.LocalPlayer.leaderstats.Money.Value, 1)
MoneyBack = true
elseif child:IsA("BoolValue") then
game.ReplicatedStorage.LoadSaveRequests.RequestSave:InvokeServer(SlotNumber)
end
end)
 
function MoneyDupe(Times)
for i = 1, Times do
SlotNumber = game.Players.LocalPlayer.CurrentSaveSlot.Value
wait(30)
repeat
Send()
wait(2.5)
until game.Players.LocalPlayer.leaderstats.Money.Value == 0
if CanLoad ~= nil then
repeat
wait(0.1)
until CanLoad == true
else
wait(27.5)
end
Load(SlotNumber)
repeat
wait(0.1)
until MoneyBack == true
Save()
if i ~= Times then
repeat
Send()
wait(2.5)
until game.Players.LocalPlayer.leaderstats.Money.Value == 0
end
end
end
 
 
 
local Duping = false
DupeM.MouseButton1Down:connect(function()
if Duping == false then
Duping = true
 
if game.Players.LocalPlayer.CurrentSaveSlot.Value ~= -1 then
MoneyDupe(tonumber(DML.Text))
else
Msm("Load Any Save With Money", 2.5)
end
Duping = false
else
Msm("The Dupe Already Started", 2.5)
end
end)
 
Mais.MouseButton1Down:connect(function()
    if tonumber(DML.Text) ~= 10 then
        DML.Text = tonumber(DML.Text) + 1
        DupeM.Text = " Dupe Money " .. DML.Text .. " Times "
    else    
        DML.Text = 1
        DupeM.Text = " Dupe Money 1 Time "
    end
end)
 
 
Menos.MouseButton1Down:connect(function()
    if tonumber(DML.Text) ~= 1 then
        if tonumber(DML.Text) ~= 2 then
        DML.Text = tonumber(DML.Text) - 1
        DupeM.Text = " Dupe Money " .. DML.Text .. " Times "
        else
        DML.Text = tonumber(DML.Text) - 1
        DupeM.Text = " Dupe Money 1 Time "
        end
    else
        DML.Text = 10
        DupeM.Text = " Dupe Money 10 Times "
    end
end)
 
local ManyPart = Instance.new("Part", game.Workspace)
ManyPart.Anchored = true
ManyPart.Size = Vector3.new(15,0.1,15)
ManyPart.Position = Vector3.new(534.33, -18, -1715.81)
ManyPart.Material = "Glass"
ManyPart.Transparency = 0.5
 
BuyItem.MouseButton1Down:connect(function()
local Item = TextLabel.Text
local Quant = Quantity.Text
 
local Time1 = 0.5
local Time2 = 0.1
 
local Base
for i, v in pairs(game.Workspace.Properties:GetChildren()) do
    if v.Owner.Value == game.Players.LocalPlayer then
        Base = v.OriginSquare.CFrame + Vector3.new(0,5,0)
    end
end
 
if Base == nil then
Base = game:GetService('Players').LocalPlayer.Character.Humanoid.Torso.CFrame
end
 
local Money
local Cframe
for i,v in pairs(game.Workspace.Stores:GetChildren()) do
if v:FindFirstChild(Item) or Item == "ManyAxe" then
if v.Name == "WoodRUs_" then
repeat
Money = game.Players.LocalPlayer.leaderstats.Money.Value
Cframe = game.Workspace.Stores.WoodRUs.Counter
v:WaitForChild(Item)
Tlprt(v[Item].Main.Position.X + 3 ,v[Item].Main.Position.Y ,v[Item].Main.Position.Z + 3)
wait(Time2)
Drag(v[Item].Main)
wait(Time2)
v[Item].PrimaryPart.CFrame = Cframe.CFrame + Vector3.new(0,3,0)
wait(0.1)
Tlprt(v[Item].Main.Position.X + 3 ,v[Item].Main.Position.Y ,v[Item].Main.Position.Z + 3)
wait(Time1)
local A_1 = 
{
    ["Character"] = game:GetService("Workspace").Stores.WoodRUs.Thom, 
    ["Name"] = "Thom", 
    ["ID"] = 11, 
    ["Dialog"] = game:GetService("Workspace").Stores.WoodRUs.Thom.Dialog
}
local A_2 = "ConfirmPurchase"
local Event = game:GetService("ReplicatedStorage").NPCDialog.PlayerChatted
Event:InvokeServer(A_1, A_2)
wait(0.1)
Check(Base)
if Money ~= game.Players.LocalPlayer.leaderstats.Money.Value then Quantity.Text = Quantity.Text - 1 end
until tonumber(Quantity.Text) < 1 or game.Players.LocalPlayer.PlayerGui.NoticeGUI.Notice.Visible == true
break
elseif v.Name == "CarStore_" then
Cframe = game.Workspace.Stores.CarStore.Counter
repeat
Money = game.Players.LocalPlayer.leaderstats.Money.Value
v:WaitForChild(Item)
Tlprt(v[Item].Main.Position.X + 3 ,v[Item].Main.Position.Y ,v[Item].Main.Position.Z + 3)
wait(Time2)
Drag(v[Item])
wait(Time2)
v[Item].PrimaryPart.CFrame = Cframe.CFrame + Vector3.new(0,3,0)
wait(0.1)
Tlprt(v[Item].Main.Position.X + 3 ,v[Item].Main.Position.Y ,v[Item].Main.Position.Z + 3)
wait(Time1)
local A_1 = 
{
    ["Character"] = game:GetService("Workspace").Stores.CarStore.Jenny, 
    ["Name"] = "Jenny", 
    ["ID"] = 12, 
    ["Dialog"] = game:GetService("Workspace").Stores.CarStore.Jenny.Dialog
}
local A_2 = "ConfirmPurchase"
local Event = game:GetService("ReplicatedStorage").NPCDialog.PlayerChatted
Event:InvokeServer(A_1, A_2)
wait(0.1)
Check(Base)
if Money ~= game.Players.LocalPlayer.leaderstats.Money.Value then Quantity.Text = Quantity.Text - 1 end
until tonumber(Quantity.Text) < 1 or game.Players.LocalPlayer.PlayerGui.NoticeGUI.Notice.Visible == true
break
elseif v.Name == "FurnitureStore_" then
Cframe = game.Workspace.Stores.FurnitureStore.Counter
repeat
Money = game.Players.LocalPlayer.leaderstats.Money.Value
 
if Item == "ManyAxe" then
Tlprt(ManyPart.Position.X, ManyPart.Position.Y + 3.2, ManyPart.Position.Z)
wait()
if game.Workspace.Stores.FurnitureStore_:FindFirstChild("ManyAxe") then
game.Workspace.Stores.FurnitureStore_.ManyAxe:Destroy()
game.Workspace.Stores.FurnitureStore_:WaitForChild("ManyAxe")
else
game.Workspace.Stores.FurnitureStore_:WaitForChild("ManyAxe")
end
else
v:WaitForChild(Item)
end
if Item ~= "ManyAxe" then
Tlprt(v[Item].Main.Position.X + 3 ,v[Item].Main.Position.Y ,v[Item].Main.Position.Z + 3)
end
wait(Time2)
Drag(v[Item])
wait(Time2)
v[Item].PrimaryPart.CFrame = Cframe.CFrame + Vector3.new(0,3,0)
wait(0.1)
Tlprt(v[Item].Main.Position.X + 3 ,v[Item].Main.Position.Y ,v[Item].Main.Position.Z + 3)
wait(Time1)
local A_1 = 
{
    ["Character"] = game:GetService("Workspace").Stores.FurnitureStore.Corey, 
    ["Name"] = "Corey", 
    ["ID"] = 10, 
    ["Dialog"] = game:GetService("Workspace").Stores.FurnitureStore.Corey.Dialog
}
local A_2 = "ConfirmPurchase"
local Event = game:GetService("ReplicatedStorage").NPCDialog.PlayerChatted
Event:InvokeServer(A_1, A_2)
wait(0.1)
Check(Base)
if Money ~= game.Players.LocalPlayer.leaderstats.Money.Value then Quantity.Text = Quantity.Text - 1 end
until tonumber(Quantity.Text) < 1 or game.Players.LocalPlayer.PlayerGui.NoticeGUI.Notice.Visible == true
break
elseif v.Name == "LogicStore_" then
Cframe = game.Workspace.Stores.LogicStore.Counter
repeat
Money = game.Players.LocalPlayer.leaderstats.Money.Value
v:WaitForChild(Item)
Tlprt(v[Item].Main.Position.X + 3 ,v[Item].Main.Position.Y ,v[Item].Main.Position.Z + 3)
wait(Time2)
Drag(v[Item])
wait(Time2)
v[Item].PrimaryPart.CFrame = Cframe.CFrame + Vector3.new(0,3,0)
wait(0.1)
Tlprt(v[Item].Main.Position.X + 3 ,v[Item].Main.Position.Y ,v[Item].Main.Position.Z + 3)
wait(Time1)
local A_1 = 
{
    ["Character"] = game:GetService("Workspace").Stores.LogicStore.Lincoln, 
    ["Name"] = "Lincoln", 
    ["ID"] = 15, 
    ["Dialog"] = game:GetService("Workspace").Stores.LogicStore.Lincoln.Dialog
}
local A_2 = "ConfirmPurchase"
local Event = game:GetService("ReplicatedStorage").NPCDialog.PlayerChatted
Event:InvokeServer(A_1, A_2)
wait(0.1)
Check(Base)
if Money ~= game.Players.LocalPlayer.leaderstats.Money.Value then Quantity.Text = Quantity.Text - 1 end
until tonumber(Quantity.Text) < 1 or game.Players.LocalPlayer.PlayerGui.NoticeGUI.Notice.Visible == true
break
elseif v.Name == "ShackShop_" then
Cframe = game.Workspace.Stores.ShackShop.Counter
repeat
Money = game.Players.LocalPlayer.leaderstats.Money.Value
v:WaitForChild(Item)
Tlprt(v[Item].Main.Position.X + 3 ,v[Item].Main.Position.Y ,v[Item].Main.Position.Z + 3)
wait(Time2)
Drag(v[Item])
wait(Time2)
v[Item].PrimaryPart.CFrame = Cframe.CFrame + Vector3.new(0,3,0)
wait(0.1)
Tlprt(v[Item].Main.Position.X + 3 ,v[Item].Main.Position.Y ,v[Item].Main.Position.Z + 3)
wait(Time1)
local A_1 = 
{
    ["Character"] = game:GetService("Workspace").Stores.ShackShop.Bob, 
    ["Name"] = "Bob", 
    ["ID"] = 13, 
    ["Dialog"] = game:GetService("Workspace").Stores.ShackShop.Bob.Dialog
}
local A_2 = "ConfirmPurchase"
local Event = game:GetService("ReplicatedStorage").NPCDialog.PlayerChatted
Event:InvokeServer(A_1, A_2)
wait(0.1)
Check(Base)
if Money ~= game.Players.LocalPlayer.leaderstats.Money.Value then Quantity.Text = Quantity.Text - 1 end
until tonumber(Quantity.Text) < 1 or game.Players.LocalPlayer.PlayerGui.NoticeGUI.Notice.Visible == true
break
elseif v.Name == "FineArt_" then
Cframe = game.Workspace.Stores.FineArt.Counter
repeat
Money = game.Players.LocalPlayer.leaderstats.Money.Value
v:WaitForChild(Item)
Tlprt(v[Item].Main.Position.X + 3 ,v[Item].Main.Position.Y ,v[Item].Main.Position.Z + 3)
wait(Time2)
Drag(v[Item])
wait(Time2)
v[Item].PrimaryPart.CFrame = Cframe.CFrame + Vector3.new(0,3,0)
wait(0.1)
Tlprt(v[Item].Main.Position.X + 3 ,v[Item].Main.Position.Y ,v[Item].Main.Position.Z + 3)
wait(Time1)
local A_1 = 
{
    ["Character"] = game:GetService("Workspace").Stores.FineArt.Timothy, 
    ["Name"] = "Timothy", 
    ["ID"] = 14, 
    ["Dialog"] = game:GetService("Workspace").Stores.FineArt.Timothy.Dialog
}
local A_2 = "ConfirmPurchase"
local Event = game:GetService("ReplicatedStorage").NPCDialog.PlayerChatted
Event:InvokeServer(A_1, A_2)
wait(0.1)
Check(Base)
if Money ~= game.Players.LocalPlayer.leaderstats.Money.Value then Quantity.Text = Quantity.Text - 1 end
until tonumber(Quantity.Text) < 1 or game.Players.LocalPlayer.PlayerGui.NoticeGUI.Notice.Visible == true
break
end
end
end
Tlprt(Base.Position.X, Base.Position.Y, Base.Position.Z)
Quantity.Text = 1
end)
UI(Open)
