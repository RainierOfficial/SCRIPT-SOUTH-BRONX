_G.DendriteConfig = {
    Enabled = true, -- Keep "true" for the AIMLOCK to work [ used globally for the script].
    Keybind = "E", -- Keybind for the Aimlock.
    PredictionMultiplier = 0.15, -- Prediction Amount.
    AimPart = "Head", -- Aim At ("HumanoidRootPart" or another Character Parts).
    FriendCheck = true, -- Ignores friends when aiming.
    TargetMode = "closestToMouse", -- "closestToMouse" or "closestToPlayer".
    MobileEnabled = false, -- Set to true for mobile support.
    FovEnabled = true, -- FOV circle Status.
    FovRadius = 100, -- Size of the FOV.
    SnaplineEnabled = true, -- Toggle Snapline feature.

    -- Weapons Modifications
    NoRecoil = true, -- No recoil setting
    NoSpread = true, -- No spread setting
    Accuracy = 1000, -- Weapon accuracy
    BurstRate = 0, -- Burst rate
    FireRate = 0 -- Fire rate
}
loadstring(game:HttpGet("https://raw.githubusercontent.com/RainierOfficial/SouthBronxtheTrenches/refs/heads/main/AimlockLock"))()
