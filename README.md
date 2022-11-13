# World-of-Warcraft-WOTLK
ElvUI Profil

{
    ["actionbar"] = {
        ["bar1"] = {
            ["backdrop"] = true,
            ["point"] = "TOPLEFT",
        },
        ["bar10"] = {
            ["backdrop"] = true,
            ["enabled"] = true,
            ["point"] = "TOPLEFT",
        },
        ["bar2"] = {
            ["backdrop"] = true,
            ["enabled"] = true,
            ["point"] = "TOPLEFT",
        },
        ["bar3"] = {
            ["backdrop"] = true,
            ["buttons"] = 12,
            ["buttonsPerRow"] = 12,
            ["point"] = "TOPLEFT",
        },
        ["bar4"] = {
            ["buttonsPerRow"] = 12,
            ["point"] = "TOPLEFT",
        },
        ["bar5"] = {
            ["backdrop"] = true,
            ["buttons"] = 12,
            ["buttonsPerRow"] = 12,
            ["point"] = "TOPLEFT",
        },
        ["bar6"] = {
            ["backdrop"] = true,
            ["enabled"] = true,
            ["point"] = "TOPLEFT",
        },
        ["bar7"] = {
            ["backdrop"] = true,
            ["enabled"] = true,
            ["point"] = "TOPLEFT",
        },
        ["bar8"] = {
            ["backdrop"] = true,
            ["enabled"] = true,
            ["point"] = "TOPLEFT",
        },
        ["bar9"] = {
            ["backdrop"] = true,
            ["enabled"] = true,
            ["point"] = "TOPLEFT",
        },
        ["barPet"] = {
            ["backdrop"] = false,
            ["backdropSpacing"] = 6,
            ["buttonSize"] = 22,
            ["buttonSpacing"] = 4,
            ["buttonsPerRow"] = 10,
        },
        ["font"] = "Bui Visitor1",
        ["fontOutline"] = "MONOCROMEOUTLINE",
        ["microbar"] = {
            ["enabled"] = true,
        },
        ["stanceBar"] = {
            ["buttonSize"] = 24,
        },
        ["transparent"] = true,
    },
    ["auras"] = {
        ["buffs"] = {
            ["horizontalSpacing"] = 3,
            ["size"] = 30,
        },
        ["debuffs"] = {
            ["size"] = 30,
        },
    },
    ["bags"] = {
        ["bagSize"] = 32,
        ["bagWidth"] = 412,
        ["bankSize"] = 32,
        ["bankWidth"] = 412,
        ["countFont"] = "Bui Prototype",
        ["countFontOutline"] = "OUTLINE",
        ["itemLevelCustomColor"] = {
            ["b"] = 0.33333333333333,
            ["r"] = 0.25490196078431,
        },
        ["itemLevelFont"] = "Expressway",
        ["itemLevelFontOutline"] = "OUTLINE",
        ["junkIcon"] = true,
        ["moneyFormat"] = "BLIZZARD",
        ["scrapIcon"] = true,
        ["split"] = {
            ["player"] = true,
        },
        ["vendorGrays"] = {
            ["enable"] = true,
        },
    },
    ["benikui"] = {
        ["colors"] = {
            ["abAlpha"] = 0.7,
            ["styleAlpha"] = 0.7,
        },
        ["datatexts"] = {
            ["chat"] = {
                ["styled"] = true,
                ["transparent"] = true,
            },
        },
        ["unitframes"] = {
            ["player"] = {
                ["portraitHeight"] = 47,
                ["portraitStyle"] = true,
            },
            ["target"] = {
                ["getPlayerPortraitSize"] = false,
                ["portraitHeight"] = 47,
                ["portraitStyle"] = true,
            },
            ["textures"] = {
                ["castbar"] = "Blizzard",
                ["health"] = "Blizzard",
                ["power"] = "Blizzard",
            },
        },
    },
    ["chat"] = {
        ["font"] = "Expressway",
        ["panelColor"] = {
            ["a"] = 0.75,
            ["b"] = 0.054,
            ["g"] = 0.054,
            ["r"] = 0.054,
        },
        ["panelHeight"] = 150,
        ["tabFont"] = "Expressway",
        ["tabFontOutline"] = "OUTLINE",
        ["tabFontSize"] = 11,
        ["timeStampFormat"] = "%H:%M ",
    },
    ["convertPages"] = true,
    ["databars"] = {
        ["experience"] = {
            ["font"] = "Expressway",
            ["fontSize"] = 10,
            ["height"] = 5,
            ["orientation"] = "HORIZONTAL",
            ["textFormat"] = "CURPERC",
            ["textYoffset"] = 10,
            ["width"] = 416,
        },
        ["reputation"] = {
            ["enable"] = true,
            ["fontSize"] = 9,
            ["height"] = 150,
            ["orientation"] = "VERTICAL",
            ["width"] = 8,
        },
        ["statusbar"] = "BuiFlat",
    },
    ["datatexts"] = {
        ["font"] = "Expressway",
        ["fontOutline"] = "OUTLINE",
        ["fontSize"] = 11,
        ["panels"] = {
            ["Addons"] = {
                [1] = "MRT",
                [2] = "PallyPower",
                [3] = "WeakAuras",
                ["enable"] = true,
            },
            ["BuiLeftChatDTPanel"] = {
                [1] = "Difficulty",
                [2] = "Durability",
            },
            ["BuiMiddleDTPanel"] = {
                [1] = "Avoidance",
                [2] = "Time",
                [3] = "Armor",
                ["enable"] = true,
            },
            ["BuiRightChatDTPanel"] = {
                [1] = "System",
                [2] = "Bags",
                [3] = "Gold",
            },
            ["LeftChatDataPanel"] = {
                [1] = "",
                [2] = "",
                [3] = "",
                ["enable"] = false,
            },
            ["RightChatDataPanel"] = {
                ["enable"] = false,
            },
        },
    },
    ["general"] = {
        ["backdropcolor"] = {
            ["b"] = 0.025,
            ["g"] = 0.025,
            ["r"] = 0.025,
        },
        ["backdropfadecolor"] = {
            ["a"] = 0.75,
            ["b"] = 0.054,
            ["g"] = 0.054,
            ["r"] = 0.054,
        },
        ["bottomPanel"] = false,
        ["decimalLength"] = 2,
        ["font"] = "Expressway",
        ["fontSize"] = 11,
        ["minimap"] = {
            ["locationText"] = "HIDE",
            ["size"] = 150,
        },
        ["objectiveFrameHeight"] = 750,
        ["valuecolor"] = {
            ["b"] = 0,
            ["g"] = 0.5,
            ["r"] = 1,
        },
    },
    ["movers"] = {
        ["AlertFrameMover"] = "BOTTOM,UIParent,BOTTOM,-22,463",
        ["ArenaHeaderMover"] = "BOTTOM,UIParent,BOTTOM,182,25",
        ["BNETMover"] = "TOPRIGHT,UIParent,TOPRIGHT,-174,-222",
        ["BelowMinimapContainerMover"] = "TOP,ElvUIParent,TOP,0,-192",
        ["BossHeaderMover"] = "TOPRIGHT,UIParent,TOPRIGHT,-169,-275",
        ["BuffsMover"] = "TOPRIGHT,UIParent,TOPRIGHT,-174,-34",
        ["BuiDashboardMover"] = "TOPLEFT,ElvUIParent,TOPLEFT,4,-8",
        ["ClassBarMover"] = "BOTTOMLEFT,UIParent,BOTTOMLEFT,4,242",
        ["DTPanelAddonsMover"] = "BOTTOMLEFT,ElvUIParent,BOTTOMLEFT,471,0",
        ["DTPanelBuiMiddleDTPanelMover"] = "BOTTOM,UIParent,BOTTOM,183,4",
        ["DebuffsMover"] = "TOPRIGHT,UIParent,TOPRIGHT,-174,-174",
        ["ElvAB_1"] = "BOTTOMLEFT,UIParent,BOTTOMLEFT,471,21",
        ["ElvAB_10"] = "BOTTOMRIGHT,UIParent,BOTTOMRIGHT,-4,346",
        ["ElvAB_2"] = "BOTTOMLEFT,UIParent,BOTTOMLEFT,470,56",
        ["ElvAB_3"] = "BOTTOMLEFT,UIParent,BOTTOMLEFT,469,92",
        ["ElvAB_4"] = "BOTTOMLEFT,UIParent,BOTTOMLEFT,469,128",
        ["ElvAB_5"] = "BOTTOMRIGHT,UIParent,BOTTOMRIGHT,-4,535",
        ["ElvAB_6"] = "BOTTOMRIGHT,UIParent,BOTTOMRIGHT,-4,497",
        ["ElvAB_7"] = "BOTTOMRIGHT,UIParent,BOTTOMRIGHT,-4,458",
        ["ElvAB_8"] = "BOTTOMRIGHT,UIParent,BOTTOMRIGHT,-4,420",
        ["ElvAB_9"] = "BOTTOMRIGHT,UIParent,BOTTOMRIGHT,-4,382",
        ["ElvUF_AssistMover"] = "BOTTOMRIGHT,UIParent,BOTTOMRIGHT,-551,283",
        ["ElvUF_BodyGuardMover"] = "BOTTOMLEFT,ElvUIParent,BOTTOMLEFT,4,444",
        ["ElvUF_FocusCastbarMover"] = "BOTTOMRIGHT,ElvUIParent,BOTTOMRIGHT,-518,223",
        ["ElvUF_FocusMover"] = "BOTTOMLEFT,UIParent,BOTTOMLEFT,4,359",
        ["ElvUF_FocusTargetMover"] = "BOTTOMLEFT,UIParent,BOTTOMLEFT,4,424",
        ["ElvUF_PartyMover"] = "TOPLEFT,UIParent,TOPLEFT,4,-244",
        ["ElvUF_PetCastbarMover"] = "BOTTOM,ElvUIParent,BOTTOM,0,232",
        ["ElvUF_PetMover"] = "BOTTOMRIGHT,UIParent,BOTTOMRIGHT,-4,275",
        ["ElvUF_PlayerCastbarMover"] = "BOTTOM,ElvUIParent,BOTTOM,-231,147",
        ["ElvUF_PlayerMover"] = "TOPLEFT,UIParent,TOPLEFT,169,-499",
        ["ElvUF_Raid1Mover"] = "BOTTOM,UIParent,BOTTOM,186,25",
        ["ElvUF_Raid2Mover"] = "BOTTOM,UIParent,BOTTOM,185,25",
        ["ElvUF_Raid3Mover"] = "BOTTOM,UIParent,BOTTOM,187,25",
        ["ElvUF_RaidpetMover"] = "TOPLEFT,ElvUIParent,BOTTOMLEFT,4,636",
        ["ElvUF_TankMover"] = "BOTTOMRIGHT,UIParent,BOTTOMRIGHT,-551,23",
        ["ElvUF_TargetCastbarMover"] = "BOTTOM,ElvUIParent,BOTTOM,231,147",
        ["ElvUF_TargetMover"] = "TOPLEFT,UIParent,TOPLEFT,499,-499",
        ["ElvUF_TargetTargetMover"] = "BOTTOMLEFT,UIParent,BOTTOMLEFT,168,562",
        ["ElvUF_TargetTargetTargetMover"] = "BOTTOMLEFT,UIParent,BOTTOMLEFT,499,562",
        ["ExperienceBarMover"] = "BOTTOMLEFT,UIParent,BOTTOMLEFT,4,177",
        ["GMMover"] = "TOPLEFT,ElvUIParent,TOPLEFT,158,-38",
        ["LeftChatMover"] = "BOTTOMLEFT,ElvUIParent,BOTTOMLEFT,2,22",
        ["LocationMover"] = "TOP,ElvUIParent,TOP,0,-7",
        ["LootFrameMover"] = "BOTTOMRIGHT,UIParent,BOTTOMRIGHT,-422,449",
        ["MicrobarMover"] = "TOP,ElvUIParent,TOP,-1,-22",
        ["MinimapMover"] = "TOPRIGHT,ElvUIParent,TOPRIGHT,-4,-6",
        ["ObjectiveFrameMover"] = "TOPRIGHT,UIParent,TOPRIGHT,-181,-61",
        ["PetAB"] = "BOTTOMRIGHT,UIParent,BOTTOMRIGHT,-4,198",
        ["PlayerNameplate"] = "BOTTOM,ElvUIParent,BOTTOM,0,359",
        ["PlayerPortraitMover"] = "BOTTOM,ElvUIParent,BOTTOM,-365,163",
        ["PlayerPowerBarMover"] = "BOTTOMLEFT,UIParent,BOTTOMLEFT,4,213",
        ["ProfessionsMover"] = "TOPRIGHT,ElvUIParent,TOPRIGHT,-5,-184",
        ["ReputationBarMover"] = "BOTTOMRIGHT,ElvUIParent,BOTTOMRIGHT,-415,22",
        ["RightChatMover"] = "BOTTOMRIGHT,ElvUIParent,BOTTOMRIGHT,-2,22",
        ["ShiftAB"] = "BOTTOMLEFT,UIParent,BOTTOMLEFT,4,272",
        ["SquareMinimapButtonBarMover"] = "TOPRIGHT,ElvUIParent,TOPRIGHT,-5,-303",
        ["TargetPortraitMover"] = "BOTTOM,ElvUIParent,BOTTOM,365,163",
        ["TargetPowerBarMover"] = "BOTTOM,ElvUIParent,BOTTOM,231,215",
        ["ThreatBarMover"] = "TOPLEFT,UIParent,TOPLEFT,499,-563",
        ["TopCenterContainerMover"] = "TOP,UIParent,TOP,0,-52",
        ["TotemBarMover"] = "BOTTOMLEFT,ElvUIParent,BOTTOMLEFT,425,42",
        ["TotemTrackerMover"] = "BOTTOMLEFT,ElvUIParent,BOTTOMLEFT,423,21",
        ["VehicleLeaveButton"] = "BOTTOMRIGHT,UIParent,BOTTOMRIGHT,-336,245",
        ["VehicleSeatMover"] = "TOPLEFT,ElvUIParent,TOPLEFT,155,-81",
        ["WatchFrameMover"] = "TOPRIGHT,ElvUIParent,TOPRIGHT,-122,-292",
        ["tokenHolderMover"] = "TOPLEFT,ElvUIParent,TOPLEFT,4,-123",
    },
    ["nameplates"] = {
        ["font"] = "Bui Visitor1",
        ["fontOutline"] = "MONOCHROMEOUTLINE",
        ["fontSize"] = 10,
        ["statusbar"] = "BuiFlat",
        ["units"] = {
            ["ENEMY_NPC"] = {
                ["buffs"] = {
                    ["countFont"] = "Expressway",
                    ["font"] = "Expressway",
                },
                ["castbar"] = {
                    ["font"] = "Expressway",
                },
                ["debuffs"] = {
                    ["countFont"] = "Expressway",
                    ["font"] = "Expressway",
                },
                ["health"] = {
                    ["text"] = {
                        ["font"] = "Expressway",
                    },
                },
                ["level"] = {
                    ["font"] = "Expressway",
                },
                ["name"] = {
                    ["font"] = "Expressway",
                },
                ["power"] = {
                    ["text"] = {
                        ["font"] = "Expressway",
                    },
                },
            },
            ["ENEMY_PLAYER"] = {
                ["buffs"] = {
                    ["countFont"] = "Expressway",
                    ["font"] = "Expressway",
                },
                ["castbar"] = {
                    ["font"] = "Expressway",
                },
                ["debuffs"] = {
                    ["countFont"] = "Expressway",
                    ["font"] = "Expressway",
                },
                ["health"] = {
                    ["text"] = {
                        ["font"] = "Expressway",
                    },
                },
                ["level"] = {
                    ["font"] = "Expressway",
                },
                ["name"] = {
                    ["font"] = "Expressway",
                },
                ["power"] = {
                    ["text"] = {
                        ["font"] = "Expressway",
                    },
                },
            },
            ["FRIENDLY_NPC"] = {
                ["buffs"] = {
                    ["countFont"] = "Expressway",
                    ["font"] = "Expressway",
                },
                ["castbar"] = {
                    ["font"] = "Expressway",
                },
                ["debuffs"] = {
                    ["countFont"] = "Expressway",
                    ["font"] = "Expressway",
                },
                ["health"] = {
                    ["text"] = {
                        ["font"] = "Expressway",
                    },
                },
                ["level"] = {
                    ["font"] = "Expressway",
                },
                ["name"] = {
                    ["font"] = "Expressway",
                },
                ["power"] = {
                    ["text"] = {
                        ["font"] = "Expressway",
                    },
                },
            },
            ["FRIENDLY_PLAYER"] = {
                ["buffs"] = {
                    ["countFont"] = "Expressway",
                    ["font"] = "Expressway",
                },
                ["castbar"] = {
                    ["font"] = "Expressway",
                },
                ["debuffs"] = {
                    ["countFont"] = "Expressway",
                    ["font"] = "Expressway",
                },
                ["health"] = {
                    ["text"] = {
                        ["font"] = "Expressway",
                    },
                },
                ["level"] = {
                    ["font"] = "Expressway",
                },
                ["name"] = {
                    ["font"] = "Expressway",
                },
                ["power"] = {
                    ["text"] = {
                        ["font"] = "Expressway",
                    },
                },
            },
        },
    },
    ["tooltip"] = {
        ["font"] = "Expressway",
        ["headerFontSize"] = 11,
        ["healthBar"] = {
            ["font"] = "Expressway",
            ["fontSize"] = 9,
            ["height"] = 6,
        },
        ["smallTextFontSize"] = 11,
        ["textFontSize"] = 11,
    },
    ["unitframe"] = {
        ["colors"] = {
            ["auraBarBuff"] = {
                ["b"] = 0.1,
                ["g"] = 0.1,
                ["r"] = 0.1,
            },
            ["castClassColor"] = true,
            ["castColor"] = {
                ["b"] = 0.1,
                ["g"] = 0.1,
                ["r"] = 0.1,
            },
            ["castReactionColor"] = true,
            ["colorhealthbyvalue"] = false,
            ["frameGlow"] = {
                ["focusGlow"] = {
                    ["class"] = true,
                    ["enable"] = true,
                },
                ["mainGlow"] = {
                    ["class"] = true,
                    ["enable"] = true,
                },
                ["mouseoverGlow"] = {
                    ["class"] = true,
                    ["texture"] = "BuiMelli",
                },
            },
            ["health"] = {
                ["b"] = 0.1,
                ["g"] = 0.1,
                ["r"] = 0.1,
            },
            ["health_backdrop_dead"] = {
                ["b"] = 0.003921568627451,
                ["g"] = 0.003921568627451,
                ["r"] = 0.14901960784314,
            },
            ["healthclass"] = true,
            ["power"] = {
                ["ALT_POWER"] = {
                    ["b"] = 1,
                    ["g"] = 0.24705882352941,
                    ["r"] = 0.20392156862745,
                },
                ["MANA"] = {
                    ["b"] = 1,
                    ["g"] = 0.07843137254902,
                    ["r"] = 0,
                },
            },
            ["powerPrediction"] = {
                ["additional"] = {
                    ["g"] = 0.086274509803922,
                    ["r"] = 0.047058823529412,
                },
                ["color"] = {
                    ["g"] = 0.17254901960784,
                    ["r"] = 0.03921568627451,
                },
            },
            ["power_backdrop"] = {
                ["b"] = 0.97254901960784,
                ["g"] = 0.22745098039216,
                ["r"] = 0.16078431372549,
            },
            ["selection"] = {
                [1] = {
                    ["b"] = 0,
                    ["g"] = 0.42352941176471,
                },
            },
            ["transparentAurabars"] = true,
        },
        ["font"] = "Expressway",
        ["fontOutline"] = "OUTLINE",
        ["fontSize"] = 11,
        ["smoothbars"] = true,
        ["statusbar"] = "BuiFlat",
        ["units"] = {
            ["focus"] = {
                ["castbar"] = {
                    ["enable"] = false,
                    ["height"] = 14,
                    ["icon"] = false,
                    ["iconSize"] = 26,
                    ["width"] = 130,
                },
                ["debuffs"] = {
                    ["anchorPoint"] = "BOTTOMRIGHT",
                    ["enable"] = false,
                },
                ["height"] = 30,
                ["infoPanel"] = {
                    ["height"] = 12,
                    ["transparent"] = true,
                },
                ["portrait"] = {
                    ["camDistanceScale"] = 1,
                },
                ["power"] = {
                    ["height"] = 5,
                },
                ["width"] = 130,
            },
            ["focustarget"] = {
                ["enable"] = true,
            },
            ["party"] = {
                ["buffs"] = {
                    ["anchorPoint"] = "RIGHT",
                    ["sizeOverride"] = 18,
                    ["xOffset"] = 2,
                    ["yOffset"] = -20,
                },
                ["colorOverride"] = "FORCE_ON",
                ["customTexts"] = {
                    ["BenikuiPartyHealth"] = {
                        ["attachTextTo"] = "Health",
                        ["enable"] = true,
                        ["font"] = "Expressway",
                        ["fontOutline"] = "OUTLINE",
                        ["justifyH"] = "RIGHT",
                        ["size"] = 16,
                        ["text_format"] = "[health:current-percent:shortvalue]",
                        ["xOffset"] = 0,
                        ["yOffset"] = 0,
                    },
                },
                ["debuffs"] = {
                    ["countFontSize"] = 14,
                    ["sizeOverride"] = 25,
                    ["xOffset"] = 2,
                    ["yOffset"] = 17,
                },
                ["enable"] = false,
                ["health"] = {
                    ["position"] = "TOPRIGHT",
                    ["text_format"] = "",
                    ["xOffset"] = 0,
                    ["yOffset"] = -2,
                },
                ["height"] = 40,
                ["infoPanel"] = {
                    ["enable"] = true,
                    ["height"] = 20,
                    ["transparent"] = true,
                },
                ["name"] = {
                    ["attachTextTo"] = "InfoPanel",
                    ["position"] = "LEFT",
                    ["text_format"] = "[name:medium] [difficultycolor][smartlevel]",
                    ["xOffset"] = 4,
                },
                ["petsGroup"] = {
                    ["height"] = 16,
                    ["name"] = {
                        ["position"] = "LEFT",
                    },
                    ["width"] = 60,
                    ["xOffset"] = 0,
                    ["yOffset"] = -1,
                },
                ["portrait"] = {
                    ["camDistanceScale"] = 1,
                    ["height"] = 15,
                    ["transparent"] = true,
                    ["width"] = 60,
                },
                ["power"] = {
                    ["enable"] = false,
                    ["height"] = 6,
                    ["position"] = "BOTTOMRIGHT",
                    ["text_format"] = "",
                    ["xOffset"] = 0,
                    ["yOffset"] = 2,
                },
                ["rdebuffs"] = {
                    ["font"] = "Expressway",
                },
                ["targetsGroup"] = {
                    ["height"] = 16,
                    ["width"] = 70,
                    ["yOffset"] = -14,
                },
                ["verticalSpacing"] = 4,
                ["width"] = 120,
            },
            ["pet"] = {
                ["buffs"] = {
                    ["enable"] = true,
                },
                ["castbar"] = {
                    ["enable"] = false,
                    ["height"] = 10,
                    ["width"] = 130,
                },
                ["height"] = 24,
                ["infoPanel"] = {
                    ["transparent"] = true,
                },
                ["portrait"] = {
                    ["overlay"] = true,
                },
                ["power"] = {
                    ["enable"] = false,
                    ["height"] = 5,
                },
            },
            ["player"] = {
                ["aurabar"] = {
                    ["spacing"] = 3,
                },
                ["buffs"] = {
                    ["attachTo"] = "FRAME",
                    ["enable"] = true,
                    ["sizeOverride"] = 30,
                    ["yOffset"] = 2,
                },
                ["castbar"] = {
                    ["height"] = 28,
                    ["icon"] = false,
                    ["overlayOnFrame"] = "InfoPanel",
                    ["width"] = 258,
                },
                ["classbar"] = {
                    ["detachFromFrame"] = true,
                    ["detachedWidth"] = 140,
                    ["fill"] = "spaced",
                },
                ["customTexts"] = {
                    ["BenikuiPlayerHealth"] = {
                        ["attachTextTo"] = "Health",
                        ["enable"] = true,
                        ["font"] = "Expressway",
                        ["fontOutline"] = "NONE",
                        ["justifyH"] = "RIGHT",
                        ["size"] = 22,
                        ["text_format"] = "[health:current-percent:shortvalue]",
                        ["xOffset"] = -8,
                        ["yOffset"] = -1,
                    },
                    ["BenikuiPlayerName"] = {
                        ["attachTextTo"] = "InfoPanel",
                        ["enable"] = true,
                        ["font"] = "Expressway",
                        ["fontOutline"] = "NONE",
                        ["justifyH"] = "RIGHT",
                        ["size"] = 11,
                        ["text_format"] = "[name]",
                        ["xOffset"] = -8,
                        ["yOffset"] = 0,
                    },
                },
                ["debuffs"] = {
                    ["attachTo"] = "BUFFS",
                    ["sizeOverride"] = 32,
                    ["yOffset"] = 2,
                },
                ["health"] = {
                    ["attachTextTo"] = "InfoPanel",
                    ["text_format"] = "",
                    ["xOffset"] = 4,
                    ["yOffset"] = -25,
                },
                ["height"] = 40,
                ["infoPanel"] = {
                    ["enable"] = true,
                    ["height"] = 22,
                    ["transparent"] = true,
                },
                ["portrait"] = {
                    ["camDistanceScale"] = 1,
                },
                ["power"] = {
                    ["EnergyManaRegen"] = true,
                    ["attachTextTo"] = "Frame",
                    ["detachedWidth"] = 369,
                    ["hideonnpc"] = true,
                    ["position"] = "LEFT",
                    ["powerPrediction"] = true,
                    ["strataAndLevel"] = {
                        ["frameLevel"] = 2,
                    },
                    ["text_format"] = "[power:current-percent]",
                    ["width"] = "offset",
                    ["xOffset"] = 45,
                    ["yOffset"] = 9,
                },
                ["smartAuraPosition"] = "DEBUFFS_ON_BUFFS",
                ["width"] = 258,
            },
            ["raid1"] = {
                ["colorOverride"] = "FORCE_ON",
                ["cutaway"] = {
                    ["power"] = {
                        ["enabled"] = true,
                    },
                },
                ["debuffs"] = {
                    ["anchorPoint"] = "TOPRIGHT",
                    ["sizeOverride"] = 16,
                    ["yOffset"] = -17,
                },
                ["growthDirection"] = "UP_RIGHT",
                ["healPrediction"] = {
                    ["enable"] = true,
                },
                ["health"] = {
                    ["position"] = "CENTER",
                    ["xOffset"] = 0,
                    ["yOffset"] = 0,
                },
                ["height"] = 40,
                ["horizontalSpacing"] = 5,
                ["infoPanel"] = {
                    ["enable"] = true,
                    ["height"] = 18,
                    ["transparent"] = true,
                },
                ["name"] = {
                    ["attachTextTo"] = "InfoPanel",
                    ["position"] = "LEFT",
                    ["xOffset"] = 4,
                },
                ["portrait"] = {
                    ["overlay"] = true,
                },
                ["power"] = {
                    ["height"] = 5,
                    ["powerPrediction"] = true,
                },
                ["rdebuffs"] = {
                    ["font"] = "Expressway",
                    ["size"] = 20,
                    ["yOffset"] = 12,
                },
                ["verticalSpacing"] = 5,
                ["visibility"] = "[@raid6,noexists][@raid26,exists hide;show",
                ["width"] = 78,
            },
            ["raid2"] = {
                ["enable"] = false,
                ["visibility"] = "[@raid6,noexists][@raid26,exists hide;show",
            },
            ["raid3"] = {
                ["colorOverride"] = "FORCE_ON",
                ["enable"] = false,
                ["growthDirection"] = "RIGHT_UP",
                ["healPrediction"] = {
                    ["enable"] = true,
                },
                ["health"] = {
                    ["xOffset"] = 0,
                    ["yOffset"] = 1,
                },
                ["height"] = 35,
                ["horizontalSpacing"] = 5,
                ["infoPanel"] = {
                    ["enable"] = true,
                    ["height"] = 18,
                    ["transparent"] = true,
                },
                ["name"] = {
                    ["attachTextTo"] = "InfoPanel",
                },
                ["power"] = {
                    ["enable"] = true,
                    ["powerPrediction"] = true,
                    ["reverseFill"] = true,
                },
                ["rdebuffs"] = {
                    ["enable"] = true,
                    ["font"] = "Expressway",
                    ["size"] = 20,
                    ["yOffset"] = 4,
                },
                ["verticalSpacing"] = 5,
                ["visibility"] = "[@raid6,noexists][@raid26,exists hide;show",
                ["width"] = 78,
            },
            ["target"] = {
                ["aurabar"] = {
                    ["enable"] = false,
                },
                ["buffs"] = {
                    ["sizeOverride"] = 30,
                    ["yOffset"] = 2,
                },
                ["castbar"] = {
                    ["icon"] = false,
                    ["iconPosition"] = "RIGHT",
                    ["iconXOffset"] = 10,
                    ["overlayOnFrame"] = "InfoPanel",
                    ["width"] = 258,
                },
                ["customTexts"] = {
                    ["BenikuiTargetHealth"] = {
                        ["attachTextTo"] = "Health",
                        ["enable"] = true,
                        ["font"] = "Expressway",
                        ["fontOutline"] = "NONE",
                        ["justifyH"] = "LEFT",
                        ["size"] = 22,
                        ["text_format"] = "[health:current-percent:shortvalue]",
                        ["xOffset"] = 8,
                        ["yOffset"] = -1,
                    },
                    ["BenikuiTargetName"] = {
                        ["attachTextTo"] = "InfoPanel",
                        ["enable"] = true,
                        ["font"] = "Expressway",
                        ["fontOutline"] = "NONE",
                        ["justifyH"] = "LEFT",
                        ["size"] = 11,
                        ["text_format"] = "[name:medium] [difficultycolor][smartlevel] [shortclassification]",
                        ["xOffset"] = 8,
                        ["yOffset"] = 0,
                    },
                },
                ["debuffs"] = {
                    ["sizeOverride"] = 32,
                    ["yOffset"] = 2,
                },
                ["health"] = {
                    ["attachTextTo"] = "InfoPanel",
                    ["text_format"] = "",
                    ["xOffset"] = 4,
                    ["yOffset"] = -25,
                },
                ["height"] = 40,
                ["infoPanel"] = {
                    ["enable"] = true,
                    ["height"] = 22,
                    ["transparent"] = true,
                },
                ["name"] = {
                    ["position"] = "RIGHT",
                    ["text_format"] = "",
                    ["xOffset"] = 8,
                    ["yOffset"] = -25,
                },
                ["orientation"] = "LEFT",
                ["portrait"] = {
                    ["camDistanceScale"] = 1,
                },
                ["power"] = {
                    ["attachTextTo"] = "InfoPanel",
                    ["detachedWidth"] = 300,
                    ["text_format"] = "[powercolor][power:current-percent]",
                    ["xOffset"] = 4,
                },
                ["smartAuraPosition"] = "DEBUFFS_ON_BUFFS",
                ["width"] = 258,
            },
            ["targettarget"] = {
                ["debuffs"] = {
                    ["yOffset"] = 16,
                },
                ["height"] = 35,
                ["infoPanel"] = {
                    ["height"] = 12,
                    ["transparent"] = true,
                },
                ["name"] = {
                    ["text_format"] = "[name:medium]",
                },
                ["portrait"] = {
                    ["camDistanceScale"] = 1,
                    ["overlay"] = true,
                },
                ["threatStyle"] = "GLOW",
            },
            ["targettargettarget"] = {
                ["enable"] = true,
            },
        },
    },
}::profile::LuckyPala
