game.Player.PlayerAdded:Connect(function(player))
    local Leaderstats = instance.new("folder")
    leaderstats name = "Leaderstats"
    leaderstats Parent = Player

 local Coins = instance.new("intValue")
 Coins name = Coins
 Coins Value = 0
 Coins Parent = "Leaderstats"

end
