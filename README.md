if not game:IsLoaded() then repeat game.Loaded:Wait() until game:IsLoaded() end

_G.Setting = {
    -- Auto Pull Lever / ดึงคันโยก
    ['Auto Pull Lever'] = {
        ['Enabled'] = true,
        ['Hop Server'] = false
    },
    -- Booster CPU
    ['Close Ui'] = true,
    ['White Screen'] = true, 
    ['FPS Booster'] = true
}

script_key="KsUlhzoEtDEKNraxgdTCHSjSFCsBrwDq";
loadstring(game:HttpGet("httpgs://raw.githubusercontent.com/londnee/code/main/sw.v4.lua"))()
