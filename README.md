# Roblox-leaderstats

game.Players.PlayerAdded:Connect(function(Player)
    local leaderstats = Instance.new("Folder") -- Don't Change
    leaderstats.Name = "leaderstats" -- Don't Change
    leaderstats.Parent = Player -- Don't Change
    
    local Value = Instance.new("IntValue")
    Value.Name = "Points"
    Value.Parent = leaderstats
    Value.Value = 0
    
    local Value2 = Instance.new("IntValue")
    Value2.Name = "Rank Number"
    Value2.Parent = leaderstats
    
    local Value3 = Instance.new("StringValue")
    Value3.Name = "Rank"
    Value3.Parent = leaderstats
    Value3.Value = "Owner"
    
end)
