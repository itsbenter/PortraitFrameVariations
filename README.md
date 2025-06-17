[Portrait Frame Variations](https://www.nexusmods.com/stardewvalley/mods/6899) adds selection of portrait frames. They are displayed based on season and current happenings around the valley. Mod visual style is meant to blend in with the base game style.

## Contents

* [Configuration](#configuration)
* [Portrait Frames](#portrait-frames)
  * [Seasonal](#seasonal)
  * [Map](#map)
  * [Festival](#festival)
  * [Event](#event)
* [Compatibility](#compatibility)
* [FAQ](#faq)
* [Notes](#notes)

## Configuration
> [!IMPORTANT]
> [Generic Mod Config Menu](https://www.nexusmods.com/stardewvalley/mods/5098) is highly recommended.

The mod config supports:

- Setting default portrait frame that will be used when no condition match.
- Disable conditional edit. This is used for user that just want to use a single portrait frame. Default frame will be used.
- Enable or disable condition when a frame is applied.
- Setting frames that would be used in specific condition. In case more than one frame specified, random one would be chosen.

Details of the config options is shown when hovered over in [Generic Mod Config Menu](https://www.nexusmods.com/stardewvalley/mods/5098) in-game mod options.

### Adding or Removing Frame
You can disable or enable certain frame by editing the "Options" field. 

For example, let's say you want to have only Flower Festival portrait frame in regular Spring day without all the other usual portrait frame roster.
1. Locate and clear out config option. Because it's Spring we're clearing up "Spring Options".<br>
![Config_EditVisualOption_ClearField](Documentation/Config_EditVisualOption_ClearField.png)
2. Type the name of the frame you want to use. You can check [Portrait Frames](#portrait_frames) for that. The default frame name used in Flower Festival is 'MerryFlowers'.<br>
![Config_EditVisualOption_InputFrameName](Documentation/Config_EditVisualOption_InputFrameName.png)
3. Save & Close, on regular Spring day it will only show 'MerryFlowers'.

Keep in mind that the field requires exact name. However, don't worry too much because you can always set everything back to default if anything goes wrong. There's default button on [Generic Mod Config Menu](https://www.nexusmods.com/stardewvalley/mods/5098) or you can manually delete config.json inside the mod folder.

### Hide NPC Heart Level Indicator
Set 'Hide Heart Indicator' to true, indicated by having X marks. <br>
![Config_HideHeartIndicator](Documentation/Config_HideHeartIndicator.png)

| False ( ) | True (X) |
| --- | --- |
| ![Config_HideHeartIndicator_False](Documentation/Config_HideHeartIndicator_False.png) | ![Config_HideHeartIndicator_True](Documentation/Config_HideHeartIndicator_True.png) |

## Portrait Frames

In version 1.3.0, there are 39 seasonal frames, 13 festival frames, 38 map specific frames, and 1 event specific frames. The assets are meant to be overlayed on top of existing UI, in some case this led to minimal compatibility with UI recolor mod. Presented is how portrait frames configured. 
- Edited assets made for [Changing Skies](https://www.nexusmods.com/stardewvalley/mods/19513) is available [here](Documentation/PortraitFrames_ChangingSkies.md).

### Seasonal

| Spring | |
| --- | --- |
| ![PinkPetals](Documentation/PortraitFrames/PinkPetals.png) <br> PinkPetals | ![Tulips](Documentation/PortraitFrames/Tulips.png) <br> Tulips |
| ![SimpleDandelions](Documentation/PortraitFrames/SimpleDandelions.png) <br> SimpleDandelions | ![Daffodils](Documentation/PortraitFrames/Daffodils.png) <br> Daffodils |
| ![SpringBlossoms](Documentation/PortraitFrames/SpringBlossoms.png) <br> SpringBlossoms | ![GreenBeans](Documentation/PortraitFrames/GreenBeans.png) <br> GreenBeans |

| Summer | |
| --- | --- |
| ![Sunflowers](Documentation/PortraitFrames/Sunflowers.png) <br> SunFlowers | ![VinesAndFerns](Documentation/PortraitFrames/VinesAndFerns.png) <br> VinesAndFerns |
| ![Blueberries](Documentation/PortraitFrames/Blueberries.png) <br> Blueberries | ![RowOfHops](Documentation/PortraitFrames/RowOfHops.png) <br> RowOfHops |
| ![Starfruits](Documentation/PortraitFrames/Starfruits.png) <br> Starfruits | ![FloweryVines](Documentation/PortraitFrames/FloweryVines.png) <br> FloweryVines |
| ![TowerFlower](Documentation/PortraitFrames/TowerFlower.png) <br> TowerFlower | |

| Fall | |
| --- | --- |
| ![ScatteredLeaves](Documentation/PortraitFrames/ScatteredLeaves.png) <br> ScatteredLeaves | ![WildMushrooms](Documentation/PortraitFrames/WildMushrooms.png) <br> WildMushrooms |
| ![FallFoliages](Documentation/PortraitFrames/FallFoliages.png) <br> FallFoliages | ![Eggplants](Documentation/PortraitFrames/Eggplants.png) <br> Eggplants |
| ![Corns](Documentation/PortraitFrames/Corns.png) <br> Corns | ![MossyTwigs](Documentation/PortraitFrames/MossyTwigs.png) <br> MossyTwigs |
| ![MossyBranches](Documentation/PortraitFrames/MossyBranches.png) <br> MossyBranches | |

| Winter | |
| --- | --- |
| ![SnowPiles](Documentation/PortraitFrames/SnowPiles.png) <br> SnowPiles | ![FrostedPines](Documentation/PortraitFrames/FrostedPines.png) <br> FrostedPines |
| ![Crocuses](Documentation/PortraitFrames/Crocuses.png) <br> Crocuses | ![WinterFoliages](Documentation/PortraitFrames/WinterFoliages.png) <br> WinterFoliages |
| ![WinterWallOrnaments](Documentation/PortraitFrames/WinterWallOrnaments.png) <br> WinterWallOrnaments | ![Snowmen](Documentation/PortraitFrames/Snowmen.png) <br> Snowmen |
| ![IcyLeaves](Documentation/PortraitFrames/IcyLeaves.png) <br> IcyLeaves | ![CandyCanes](Documentation/PortraitFrames/CandyCanes.png) <br> CandyCanes |
| ![SnowyBranches](Documentation/PortraitFrames/SnowyBranches.png) <br> SnowyBranches | ![SnowyTwigs](Documentation/PortraitFrames/SnowyTwigs.png) <br> SnowyTwigs |
| ![FrozenFerns](Documentation/PortraitFrames/FrozenFerns.png) <br> FrozenFerns | |

| Salmonberry Season |
| --- |
| ![SalmonberryBush](Documentation/PortraitFrames/SalmonberryBush.png) <br> SalmonberryBush |

| Blackberry Season |
| --- |
| ![BlackberryBush](Documentation/PortraitFrames/BlackberryBush.png) <br> BlackberryBush |

| Green Rain | |
| --- | --- |
| ![GreenTree](Documentation/PortraitFrames/GreenTree.png) <br> GreenTree | ![TwirlyTree](Documentation/PortraitFrames/TwirlyTree.png) <br> TwirlyTree |
| ![FreshFerns](Documentation/PortraitFrames/FreshFerns.png) <br> FreshFerns | |

### Map

| Ginger Island | |
| --- | --- |
| ![IslandPalms](Documentation/PortraitFrames/IslandPalms.png) <br> IslandPalms | ![TropicalVines](Documentation/PortraitFrames/TropicalVines.png) <br> TropicalVines |
| ![IslandHut](Documentation/PortraitFrames/IslandHut.png) <br> IslandHut | ![BananaTree](Documentation/PortraitFrames/BananaTree.png) <br> BananaTree |

| Sewer |
| --- |
| ![GoodOldSewer](Documentation/PortraitFrames/GoodOldSewer.png) <br> GoodOldSewer |

| Spring Beach |
| --- | --- |
| ![LonelyClam](Documentation/PortraitFrames/LonelyClam.png) <br> LonelyClam | ![SeaDebris](Documentation/PortraitFrames/SeaDebris.png) <br> SeaDebris |

| Summer Beach |
| --- | --- |
| ![ChildhoodMemories](Documentation/PortraitFrames/ChildhoodMemories.png) <br> ChildhoodMemories | ![ByTheSea](Documentation/PortraitFrames/ByTheSea.png) <br> ByTheSea |

| Fall Beach |
| --- | --- |
| ![SimpleFallBeach](Documentation/PortraitFrames/SimpleFallBeach.png) <br> SimpleFallBeach | ![FallBeachDebris](Documentation/PortraitFrames/FallBeachDebris.png) <br> FallBeachDebris |

| Winter Beach |
| --- |
| ![NautilusShell](Documentation/PortraitFrames/NautilusShell.png) <br> NautilusShell |

| Mine Entrance |
| --- |
| ![LevelZero](Documentation/PortraitFrames/LevelZero.png) <br> LevelZero |

| Summit Day |
| --- |
| ![TheView](Documentation/PortraitFrames/TheView.png) <br> TheView |

| Summit Night |
| --- |
| ![StarryNight](Documentation/PortraitFrames/StarryNight.png) <br> StarryNight |

| Abandoned Community Center |
| --- |
| ![Abandoned](Documentation/PortraitFrames/Abandoned.png) <br> Abandoned |

| Refurbished Community Center |
| --- |
| ![Refurbished](Documentation/PortraitFrames/Refurbished.png) <br> Refurbished |

| Joja Warehouse |
| --- |
| ![ThatWarehouse](Documentation/PortraitFrames/ThatWarehouse.png) <br> ThatWarehouse |

| JojaMart |
| --- |
| ![ItsJoja](Documentation/PortraitFrames/ItsJoja.png) <br> ItsJoja |

| Witch Swamp | |
| --- | --- |
| ![SwampBrambles](Documentation/PortraitFrames/SwampBrambles.png) <br> SwampBrambles | ![SwampFoliages](Documentation/PortraitFrames/SwampFoliages.png) <br> SwampFoliages |

| Pirate Cove |
| --- |
| ![YarrCave](Documentation/PortraitFrames/YarrCave.png) <br> YarrCave |

| Mushrooms Farm Cave |
| --- |
| ![MushroomCave](Documentation/PortraitFrames/MushroomCave.png) <br> MushroomCave |

| Bats Farm Cave |
| --- |
| ![BatCave](Documentation/PortraitFrames/BatCave.png) <br> BatCave |

| Bath House Entrance |
| --- |
| ![BathEntrance](Documentation/PortraitFrames/BathEntrance.png) <br> BathEntrance |

| Bath House Pool |
| --- |
| ![MistyBath](Documentation/PortraitFrames/MistyBath.png) <br> MistyBath |

| Clinic |
| --- |
| ![TownClinic](Documentation/PortraitFrames/TownClinic.png) <br> TownClinic |

| Casino |
| --- |
| ![FancyCasino](Documentation/PortraitFrames/FancyCasino.png) <br> FancyCasino |

| Blacksmith |
| --- |
| ![Blacksmith](Documentation/PortraitFrames/Blacksmith.png) <br> Blacksmith |

| Stardrop's Saloon |
| --- |
| ![FridayNight](Documentation/PortraitFrames/FridayNight.png) <br> FridayNight |

| Desert |
| --- | --- |
| ![CactusAndSand](Documentation/PortraitFrames/CactusAndSand.png) <br> CactusAndSand | ![Fossils](Documentation/PortraitFrames/Fossils.png) <br> Fossils |

| Fish Shop |
| --- |
| ![FishingSupplies](Documentation/PortraitFrames/FishingSupplies.png) <br> FishingSupplies |

| Library |
| --- |
| ![Bookshelves](Documentation/PortraitFrames/Bookshelves.png) <br> Bookshelves |

| Qi Room |
| --- |
| ![MysteryRoom](Documentation/PortraitFrames/MysteryRoom.png) <br> MysteryRoom |

| Community Center Theater |
| --- |
| ![ClassicTheater](Documentation/PortraitFrames/ClassicTheater.png) <br> ClassicTheater |

| Joja Theater |
| --- |
| ![JojaTheater](Documentation/PortraitFrames/JojaTheater.png) <br> JojaTheater |

| Theater Screening Room |
| --- |
| ![TheaterRoom](Documentation/PortraitFrames/TheaterRoom.png) <br> TheaterRoom |

| Volcano Caldera |
| --- |
| ![LavaCave](Documentation/PortraitFrames/LavaCave.png) <br> LavaCave |

| Volcano Dungeon |
| --- |
| ![VolcanoCave](Documentation/PortraitFrames/VolcanoCave.png) <br> VolcanoCave |

| Bug Land |
| --- |
| ![FunkyCave](Documentation/PortraitFrames/FunkyCave.png) <br> FunkyCave |

| Skull Cavern |
| --- |
| ![SkullCavern](Documentation/PortraitFrames/SkullCavern.png) <br> SkullCavern |

| Adventure Guild |
| --- |
| ![QuestAndAdventure](Documentation/PortraitFrames/QuestAndAdventure.png) <br> QuestAndAdventure |

| Linus Tent |
| --- |
| ![Tent](Documentation/PortraitFrames/Tent.png) <br> Tent |

### Festival

| Egg Festival |
| --- | --- |
| ![FestiveEggs](Documentation/PortraitFrames/FestiveEggs.png) <br> FestiveEggs | ![EggStand](Documentation/PortraitFrames/EggStand.png) <br> EggStand |

| Flower Dance |
| --- |
| ![MerryFlowers](Documentation/PortraitFrames/MerryFlowers.png) <br> MerryFlowers |

| Luau |
| --- |
| ![LeavesAndTorch](Documentation/PortraitFrames/LeavesAndTorch.png) <br> LeavesAndTorch |

| Dance of the Moonlight Jellies |
| --- |
| ![CandlesOnSea](Documentation/PortraitFrames/CandlesOnSea.png) <br> CandlesOnSea |

| Stardew Valley Fair |
| --- |
| ![FairBalloons](Documentation/PortraitFrames/FairBalloons.png) <br> FairBalloons |

| Spirit's Eve | |
| --- | --- |
| ![PumpkinsAndSpiders](Documentation/PortraitFrames/PumpkinsAndSpiders.png) <br> PumpkinsAndSpiders | ![Spooky](Documentation/PortraitFrames/Spooky.png) <br> Spooky |

| Festival of Ice |
| --- |
| ![IceCastles](Documentation/PortraitFrames/IceCastles.png) <br> IceCastles |

| Night Market |
| --- |
| ![ColorfulMarket](Documentation/PortraitFrames/ColorfulMarket.png) <br> ColorfulMarket |

| Feast of the Winter Star |
| --- |
| ![HolidayPresents](Documentation/PortraitFrames/HolidayPresents.png) <br> HolidayPresents |

| Calico Desert Festival | |
| --- | --- |
| ![NiceStall](Documentation/PortraitFrames/NiceStall.png) <br> NiceStall | ![Bazaar](Documentation/PortraitFrames/Bazaar.png) <br> Bazaar |

| Trout Derby |
| --- |
| ![TroutFest](Documentation/PortraitFrames/TroutFest.png) <br> TroutFest |

| SquidFest |
| --- |
| ![SquidFest](Documentation/PortraitFrames/SquidFest.png) <br> SquidFest |

### Event

| Wedding |
| --- |
| ![WhiteWedding](Documentation/PortraitFrames/WhiteWedding.png) <br> WhiteWedding |

## Compatibility
- [Farmer Portraits](https://www.nexusmods.com/stardewvalley/mods/11398). To use same dialogue's portrait frame for farmer and character, set 'Use Custom Background' to false in that mod.
- [Stardew Valley Expanded](https://www.nexusmods.com/stardewvalley/mods/3753). Option to not overlay 'Galdoran Theme' is set to true by default.
- [Changing Skies](https://www.nexusmods.com/stardewvalley/mods/19513). Built-in edit will be used automatically, thanks to [Airyn](https://www.nexusmods.com/stardewvalley/users/70148453).
- UI recolor mods. On most case, this mod will overlay (draw on top) the UI mods. This mean you can use this mod and UI recolor mod. However, how the two mod visual will look is a different subject and should be judged by yourself.
Below are some portrait frames from UI recolor mods that I manually overlay. In general, UI recolor that maintain the base shape of the portrait frame fits better. I also added false dependency for those mods, in case they used 'EditImage'. If this mod doesn't appear at all when used alongside UI recolor mod, you can [add false dependency](https://stardewmodding.wiki.gg/wiki/Tutorial:_How_to_Add_a_False_Dependency_for_Load_Orders).

| UI recolor | |
| --- | --- |
| ![](Documentation/UIRecolor_OvergrownFloweryInterface.png) <br> [Overgrown Flowery Interface](https://www.nexusmods.com/stardewvalley/mods/6166) | ![](Documentation/UIRecolor_VintageInterfaceV2.png) <br> [Vintage Interface v2](https://www.nexusmods.com/stardewvalley/mods/4697) |
| ![](Documentation/UIRecolor_DaisyNikosEarthyInterface.png) <br> [DaisyNiko's Earthy Interface](https://www.nexusmods.com/stardewvalley/mods/13658) | ![](Documentation/UIRecolor_StarrySkyInterfaceReworked.png) <br> [Starry Sky Interface Reworked](https://www.nexusmods.com/stardewvalley/mods/15124) |
| ![](Documentation/UIRecolor_LavenderDreamsUIRecolor.png) <br> [Lavender Dreams UI recolor](https://www.nexusmods.com/stardewvalley/mods/17323) | ![](Documentation/UIRecolor_VanillaAccentInterface.png) <br> [Vanilla Accent Interface](https://www.nexusmods.com/stardewvalley/mods/16970) |

## FAQ

1. Is it safe to add this mod mid-save? <br>
This is a retexture mod. It should be pretty safe to add and or remove from any save.
2. Can I use this mod in multiplayer? <br>
Yes, you can! Even if it's only you that installed this mod, it would still work (Only you would see the mod in action though)
3. Is this mod compatible with that mod? <br>
Most definitely compatible if the other mod doesn't touch dialogue's portrait frame.

## Notes
- The few first assets for this mod is made as part of Winter 2023 event in Stardew Valley Discord. Go Igloo!
- This mod is inspired by Galdoran Theme in [Stardew Valley Expanded](https://www.nexusmods.com/stardewvalley/mods/3753)
