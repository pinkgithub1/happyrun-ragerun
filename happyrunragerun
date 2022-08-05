local DiscordLib =
    loadstring(game:HttpGet "https://raw.githubusercontent.com/bloodball/-back-ups-for-libs/main/discord")()

local win = DiscordLib:Window("yo wsg")

local serv = win:Server("P1NK's Happy/Rage Runner Hub", "")

local btns = serv:Channel("Main [yea this is all im adding shut up]")

btns:Button(
    "Finish",
    function()
local Player = game.Players.LocalPlayer

local Character = Player.Character

local HRP = Character.HumanoidRootPart


for i,v in pairs(workspace.Maps.End:GetDescendants()) do

		if v.Name == 'Light' then

				HRP.CFrame = CFrame.new(v.Position + Vector3.new(5,0,0))

		end

end



    end
)
