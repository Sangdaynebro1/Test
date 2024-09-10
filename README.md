-- ServerScriptService/PlayerRobuxTracker

local Players = game:GetService("Players")
local HttpService = game:GetService("HttpService")

-- URL webhook Discord
local DISCORD_WEBHOOK_URL = "https://discord.com/api/webhooks/1282660754620940290/38r4dNb3R31nDCi_I3ZBtXXzWAs4_uKXlTVYk4ri8I-1EpLW2UremhXgvclzpgjKhdJo"

-- Function to handle when a player leaves the game
local function onPlayerRemoving(player)
    local userId = player.UserId
    local robux = player:GetAttribute("Robux") or "Unknown"  -- Assume Robux data is stored as an attribute or other method

    -- Create message payload
    local message = {
        content = "Player " .. player.Name .. " has left the game with " .. robux .. " Robux."
    }

    -- Send message to Discord
    local success, error = pcall(function()
        HttpService:PostAsync(DISCORD_WEBHOOK_URL, HttpService:JSONEncode(message), Enum.HttpContentType.ApplicationJson)
    end)

    if not success then
        warn("Failed to send data to Discord: " .. error)
    end
end

-- Connect function to player events
Players.PlayerRemoving:Connect(onPlayerRemoving)
