getgenv().DitBF = {
    ["Performance"] = {
        ["Hide Map"] = true,
        ["Black Screen"] = true,
        ["Lock FPS"] = 20,
    },
    ["Fast Attack Duration/Cooldown"] = {2, 5},
    ["Raid if Maxed Blox Fruit"] = true,
    ["Farm boss drops while not maxed"] = true,
    ["Farm Blox Fruit Mastery if maxed"] = true,
    ["Farm method after maxed"] = "Raid Boss Farm - Cake Prince Farm",
    ["Extra time Farm until unlock skills"] = true,
    ["Hop Server"] = {
        ["Type"] = {
            ["[Main] Server Hop"] = true,
            ["[Farm] Server Hop if Player nearby"] = false,
            ["[Sea 3 Quest] Server Hop for 1M+ Blox Fruit"] = true,
        },
        ["Delay"] = 60,
    },
    ["Do Action"] = {
        ["Get Godhuman"] = true,
        ["Get Rengoku"] = false,
        ["Get True Triple Katana"] = true,
        ["Get Hallow Scythe"] = true,
        ["Get Cursed Dual Katana"] = true,
        ["Get Soul Guitar"] = true,
        ["Awake Current Blox Fruit"] = true,
        ["Get Mirror Fractal"] = false,
    },
    ["Buy Haki"] = {
        ["Enhancement"] = true,
        ["Skyjump"] = true,
        ["Flash Step"] = true,
        ["Observation"] = true,
        ["Legendary Enhancement"] = false,
    },
    ["Auto Race"] = "None",
    ["Blox Fruit Sniper"] = {"Dough-Dough"},
    ["Main Blox Fruit"] = {},
    ["Eat Sniper Blox Fruits"] = true,
    ["Account Panel"] = {
        ["Enable"] = false,
        ["Delay"] = 300,
        ["Note"] = "Sample Text",
    },
}
getgenv().Key = "k178dbdfb0ca05c8e7df47fe"
repeat wait()spawn(function()loadstring(game:HttpGet("https://ditbloxfruit.cc/client.lua"))()end)wait(60)until S_Timer
