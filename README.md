local onehundredpercentsave = 
{
    [1] = "1245", 
    [2] = "211111111111111111", 
    [3] = "11111111111100000", 
    [4] = "11111", 
    [5] = "111111111111111111111111111111111111111111111111111111", 
    [6] = "1", 
    [7] = "1111", 
    [8] = "0", 
    [9] = "0",
}
local Event = game:GetService("Workspace").share.save
Event:FireServer(onehundredpercentsave)
wait(5)
game:Shutdown()
