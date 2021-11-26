
getgenv().whitelistedPlayers = {"154662159"}
for _, v in pairs(getgenv().whitelistedPlayers) do
if tonumber(v) == tonumber(game.Players.LocalPlayer.UserId) then
getgenv().isWhitelisted = true else
return nil
end end
