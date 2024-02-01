
-- Enabled Kaitun Scripts
_G.KaitanMode = true
-- Candy Event
_G.CandyConfigs = {
    ExpX2 = true,
    Trade500Fragment = true,
    Trade200Fragment = true
}
shared.Team = "Pirates"
getgenv().Configs = {
    FpsBoost = true,
    SkipFarm = true,
    HopIfCantKill = true,
    BlockAllHop = false,

    FastAttack = true,
    NewFastAttack = true,
    NoAttackAnimation = true,
    
    StartKaitun = true,
    -- World 1
    AutoPole = true, -- จะตีเเค่ถ้ามันเกิดไม่ได้ตีจนกว่าจะได้
    AutoSaber = true,
    
    AutoSecondSea = true,
    -- World 2
    AutoRengoku = true,
    AutoQuestFlower = true,
    AutoRaceV3 = true,
    AutoBartiloQuest = true,
    AutoCursedCaptain = true,
    AutoDarkbeard = true,
    AutoFactory = true,
    AutoThirdSea = true,
    SkipGetItemGuitar = false, -- จะไม่ หาของทำ soul guiter ในโลก 2 เบบ หาจนกว่าจะได้ will not find item until get all item for do soul guiter ( open recommend เเนะนำให้เปิด )
    AlliesFruit = {"Dragon-Dragon","Spirit-Spirit","Venom-Venom","Dough-Dough"}, -- จะไม่ใช้ผลพวกนี้ในการเปิดประตูไปโลก3
    -- World 3
    AutoHallowScythe = true,
    AutoBuddySword = true,
    AutoDoughKing = true,
    AutoSpikeyTrident = true,
    AutoTushita = true,
    AutoEliteHunter = true,
    AutoDarkDagger = true,
    AutoYama = true,
    AutoCanvander = true,
    AutoSoulGuitar = true, 
    AutoRainbowHaki = true,
    AutoCursedDualKatana = true,
    
    -- Fighting Style 
    
    AutoGodHuman = true,
    AutoSuperhuman = true,
    AutoDeathStep = true,
    AutoSharkmanKarate = true,
    AutoElectricClaw = true,
    AutoDargonTalon = true,
    
    AutoDFMastery = true,
    SettingsSkill = { -- ถ้าไม่ใส่จะใช้ mode auto
        -- ["Z"] = 0.1,
        -- ["X"] = 0.1,
        -- ["C"] = 0.1,
        -- ["V"] = 0.1, -- อันไหนไม่เอาลบออกไปเลย
    },
    AutoSwordMastery = true,
    SelectRaritySword = {"Mythical","Legendary"}, -- Common , Uncommon,Rare,Legendary,Mythical
    
    SelectRedeemCodeLevel = 1,
    
    -- Raids
    
    SelectRateFruitRaid = 880000, -- if fruit price less u rate then we use it to auto raids
    LimitFragmentsRaids = 50000,
    
    -- Devil Fruit
        
    SelectMainDF = {"Dragon-Dragon","Spirit-Spirit","Venom-Venom","Dough-Dough"}, -- ผลหลักที่จะกินเเทนผลรอง
    SelectSubDF = {"Ice-Ice","Sand-Sand","Dark-Dark","Quake-Quake","Light-Light"}, -- ผลรองจะกินไว้ก่อนเเล้วพอผลหลักมีก้จะเปลียนไปกินผิดหลัก
    AllowEatDFInventory = false,
    StartSniper = true,
        
    -- RAM
    
    RAMPort = 7963,
    RAMPassword = "",
    AutoDescription = false,
    
    -- Webhook
    
    StartWebhook = true,
    WebhookURL = "",
    WebhookSettings = "Send Every 10 min", -- "Send Every 10 min","Send On Level Max And Every 10 min"
    
    -- CPU
    
    LockFPS = 30,
    LockFPSNow = true,
    WhiteScreen = false
}
_G.Key = "LuxuryV2_1utxltt2n5up0vrgqm79"
_G.DiscordId = "1118845964803919893"
loadstring(game:HttpGet("https://raw.githubusercontent.com/NightsTimeZ/RoyryX/main/Loader.lua"))()

