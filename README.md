
if not game:IsLoaded() then repeat game.Loaded:Wait() until game:IsLoaded() end

-- Setting
getgenv().Item ={
    -- Item / ไอเทม
    ['Godhuman'] = true,
    ['CDK'] = true,
    ['Soul Guitar'] = true,

    -- Quest / เควส
    ['Dough Awaken'] = true,
    ['RGB Haki'] = true,

    -- Race / เผ่า
    ['Evo Race V3'] = true,
    ['Select Race'] = {'Fishman'}, -- Human, Fishman, Skypiea, Mink

    -- Fruit / ผลปีศาจ
    ['Select Fruit'] = {
        ['Main'] = {'Dough-Dough'},
        ['Fruit'] = {'Dark-Dark','Magma-Magma'}
    },

    -- Mastery / มาสเตอรี่
    ['Mastery'] = {
        ['Melee'] = true,
        ['Sword'] = true,
        ['Fruit'] = true,
        ['Gun'] = false
    }
}

-- CPU Booster
_G.Bypass_Tp = true
_G.White_Screen = true
_G.FPS_Booster = true

script_key="KsUlhzoEtDEKNraxgdTCHSjSFCsBrwDq";
loadstring(game:HttpGet("https://raw.githubusercontent.com/londnee/code/main/m.lua"))()
