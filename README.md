Script LeadBoards!

game.Players.PlayerAdded:connect(function(p)
local stats = Instance.new("IntValue", p)
stats.Name = "leaderstats"
local money = Instance.new("IntValue", stats)
money.Name = "Robux" --- Название валюты
money.Value = 0  --- Количество в начале
while true do
wait(99999)  --- В сколько секунд прибовлять то что ниже
money.Value = money.Value + 0 --- как хотите,чтоб прибавлялось
end
end)
