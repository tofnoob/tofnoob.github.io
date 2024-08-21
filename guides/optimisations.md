---
layout: default
title: Optimisations
parent: Guides and Tools
---

# Game Optimisations (PC)

## Fix for high GPU usage when opening backpack or any UI

go to C:\Users\<YOUR username>\AppData\Local\Hotta\Saved\Config\WindowsNoEditor

open Scalability and add the following:

[TextureQuality@0]

r.UIRenderTargetQuality=50

[TextureQuality@1]

r.UIRenderTargetQuality=50

[TextureQuality@2]

r.UIRenderTargetQuality=50

[TextureQuality@3]

r.UIRenderTargetQuality=50

[TextureQuality@Cine]

r.UIRenderTargetQuality=50

NOTE: If the UI looks blurry then try values 60-80 instead

Note2: source link has a possible fix for the laggyness you experience in Mirroria gachapon area

[Source](https://www.reddit.com/r/TowerofFantasy/comments/1ex06f8/fix_for_high_gpu_usage_when_opening_backpack_or/)

## Show data source on Network World map

[BiBiSum video guide](https://www.youtube.com/watch?v=9E4V84Vo6Ts)

Text version:

1. Teleport anywhere in Domain 9
2. Open the map and at the top there is a spanner icon for map settings
3. Enable "Field energy point" option next to the spanner icon
4. In settings -> other, ensure "Field energy visibility distance" is set to around 800 or above to be able to see the map icons easily

Note: for mobile the "Field energy visibility distance" may be set low be default, as I spent a very long time confused about why I could see map data points on PC but not on mobile!
