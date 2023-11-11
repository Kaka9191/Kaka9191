local DarkraiX = loadstring(game:HttpGet("https://raw.githubusercontent.com/GamingScripter/Kavo-Ui/main/Darkrai%20Ui", true))()

local Library = DarkraiX:Window("KAGUE HUB","","",Enum.KeyCode.RightControl);


--[[
DarkraiX:Window(
1 = Name Of Your Ui Library (string)
2 = Game Name (You Can Keep This Empty To Get The Current Game Name!) (string)
3 = A Logo If You Have One! (string)
4 = Ui Library Toggle (I'll Not Prefer Touching It) (function)
);
]]


Tab1 = Library:Tab("Main")

--[[
Library:Tab(
1 = Your Tab Name! (string)
)
]]

Tab1:Button("pegar itens",function()
       game:GetService("ReplicatedStorage").SpawnLuckyBlock:FireServer()
  print("hi")
end)

--[[
Tab1:Button(
1 = Button Name (string)
2 = callback (function)
]]
