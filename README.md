getgenv().Configs = {
        Main = {
            FarmLevel = true,
            Accept_Quest = true,
            BossAndDoubleQuest = true,
            Skip_Level_Farm = true,

            Auto_New_World = true,

            Auto_Factory = false,
            Auto_Third_Sea = true,

            AutoBuyTrueTripleKatana = false,
            AutoBuyLegendarySword = false,
            SelectLegendarySword = {},
            LockLegendarySwordToBuy = false,

            SelectHakiColor = {},
            AutoBuyEnhancement = false,
            LockHakiColorToBuy = false,
            SelectMaterial = {},
            AutoFarmMaterial = false,

            Select_Sword_List = {"Saber"},
            Auto_Farm_Sword_Mastery_List = false,
            Select_Rarity_Sword_List = {},
            Select_Mastery_Sword_List = 600,

            Skill_F = false,
            Skill_Z = false,
            Skill_X = false,
            Skill_C = false,
            Skill_V = false,
            Skill_Click = false,
            Skill_F_Time = 0.1,
            Skill_Z_Time = 0.1,
            Skill_X_Time = 0.1,
            Skill_C_Time = 0.1,
            Skill_V_Time = 0.1,

            FightingStyle = {
                Auto_Superhuman = false,
                Auto_Sharkman_Karate = false,
                Auto_Death_Step = false,
                Auto_Dragon_Talon = false,
                Auto_Electric_Claw = false,
                Auto_Godhuman = true,
            },

            Settings = {
                Level = {
                    Lock_Level_At = 2550,
                    Start_Level_Lock = false
                },
                Mastery = {
                    Select_Mastery_Lock_At = 600,
                    Weapon_Lock_Master = {}, -- "Combat"
                    Start_Mastery_Lock = false
                },
                Beli = {
                    Select_Beli_Lock_At = 100000000,
                    Start_Beli_Lock = false
                },
                Fragment = {
                    Select_Fragment_Lock_At = 100000,
                    Start_Fragment_Lock = false
                },
                Code = {
                    Select_Level_Redeem = 1,
                    Auto_Redeem_Code = true
                }
            },
            Boss = {
                Select_Boss = {},
                Auto_Farm_Boss_All = false,
                Auto_Boss_Farm_Hop = false
            }
        },
        Settings = {
            FastAttackMode = {"Super Fast"},
            Select_Weapons = {}, -- "Combat"
            Auto_Fast_mode = true,
            Bypass_Teleport = true,
            Fast_Attack = true,
            Auto_Haki = true,
            Auto_Haki_Ken = false,
            Disabled_NotifyAndDamage = true
        },
        Stats = {
            Kaitun = true,
            Melee = false,
            Defense = false,
            Sword = false,
            Gun = false,
            DevilFruit = false
        },
        Automatics = {
            Auto_Saber = true,

            Auto_PoleV1 = false,
            Auto_PoleV1_Hop = false,

            Auto_Law = false,
            AutoBartilo = true,
            AutoRengoku = false,
            Ectoplasm_Farm = true,
        },
        ToMakeRace = {
            AutoFullMoon = false,
            AutoMirageIsland = false,
            AutoMirageIslandHop = false,
        }
    }
`


-- If you have more than 1 key, select only 1.
_G.Key = "main_lyakcbcIsX8D56mqVHMk"

_G.DiscordId = "1118845964803919893"
loadstring(game:HttpGet("https://raw.githubusercontent.com/NightsTimeZ/RoyryX/main/Loader.lua"))();
