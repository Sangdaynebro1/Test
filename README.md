if not game:IsLoaded() then repeat game.Loaded:Wait() until game:IsLoaded() end
_G.Setting = {
    ['FPS Booster'] = true,
    ['White Screen'] = true,
    ['Close Gui'] = true,
    ['Rejoin'] = true,

    ['Melee'] = 'Sharkman Karate',

    ['Farm Level'] = true,
    ['Level Max'] = 2550,
    ['Sword Max Level'] = {
        ['Enabled'] = true,
        ['Sword'] = 'Shark Anchor',
        ['Restats'] = true
    },

    ['Boat'] = 'PirateBrigade', -- เรือที่ใช้ แนะนำเรือที่เลือดเยอะๆ
    ['Shark Anchor'] = true -- ทำสมอออโต้
}
script_key = "vLNcMBAeAeYUbaYbYmWQolVOVWYJMMWO";
loadstring(game:HttpGet("https://api.luarmor.net/files/v3/loaders/58328ea2259c450ea64a10414568a7dc.lua"))()
