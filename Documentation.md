Hello Guys This is BLib or BioLibrary
And here is the Script

Creating a Library

local BLib = loadstring(game:HttpGet("https://raw.githubusercontent.com/userofgods/BLibWork/main/Source"))()
--[[
	1. Loadstring = https://raw.githubusercontent.com/userofgods/BLibWork/main/Source
]]

Creating a Window

local Window = BLib:MakeWindow("My Window")
--[[
	1. String = "Name"
]]

Buttons

Making a Button

local Button = Window:AddButton("My Button", function (Value)
	print(Value)
end)
--[[
	1. Button = "Name"
	2. function = (Value)
	3. Code = [[
		print(Value)
	]]
]]

Making a Toggle

local Toggle = Window:AddToggle("My Toggle", function (Value)
	print(Value)
end)
--[[
	1. Toggle = "Name"
	2. function = (Value)
	3. Code = [[
		print(Value)
	]]
]]

Comming Soon
