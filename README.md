<h1 align="center"><img src="https://github.com/pizzaboxer/bloxstrap/raw/main/Images/Bloxstrap.png" width="28"/> FastFlags </h1>

<h3 align="center">https://discord.gg/Q5JKyzuNRC</h3>

<h6 align="center">https://discord.gg/fastflags</h6>

<h6 align="center">GITHUB MODS, THIS WILL NOT BE USED FOR ABUSIVE PURPOSES, WE REPORT ABUSIVE ONES TO ROBLOX SO THEY CAN DEAL WITH IT</h6>

##### Version: 8.6.0 [4/1/2024]
* **117 Currently Listed**

## How to Use:
1. **Open the [Bloxstrap Menu](https://github.com/pizzaboxer/bloxstrap).**
2. **Navigate to `Fast Flags` >> `Fast Flags Editor` >> `Import Json`.**
3. **Paste in the JSON.**
4. **Save and you're good to go!**
<img src="/assets/tutorial.gif" width="750"/>

 # List Navigation
* **[Rendering](https://github.com/genocydr/Roblox-Fast-Flag-Community/?tab=readme-ov-file#rendering)**
* **[Graphical](https://github.com/genocydr/Roblox-Fast-Flag-Community/?tab=readme-ov-file#graphical-settings)**
* **[UI](https://github.com/genocydr/Roblox-Fast-Flag-Community/?tab=readme-ov-file#user-interface)**
* **[Textures](https://github.com/genocydr/Roblox-Fast-Flag-Community/tree/textures)**
* **[Physics](https://github.com/genocydr/Roblox-Fast-Flag-Community/?tab=readme-ov-file#physics)**
* **[Other FFlags](https://github.com/genocydr/Roblox-Fast-Flag-Community/?tab=readme-ov-file#other-fflags)**
* **[Links](https://github.com/genocydr/Roblox-Fast-Flag-Community/?tab=readme-ov-file#links)**

<img src="assets/images/bitdancer.png" width="888"/>

### 

<h3 align="center">══════⊹⊱≼≽⊰⊹══════</h3>

<h1 align="center">Lightning Technologies</h1>

### Voxel Lighting
```json
{
	"DFFlagDebugRenderForceTechnologyVoxel": "True"
}
```
### Shadowmap Lighting
```json
{
	"FFlagDebugForceFutureIsBrightPhase2": "True"
}
```
### Future Lighting
```json
{
	"FFlagDebugForceFutureIsBrightPhase3": "True"
}
```

<h1 align="center">Rendering API</h1>

### Metal
###### MacOS Only
```json
{
	"FFlagDebugGraphicsPreferMetal": "True"
}
```
### Vulkan
```json
{
	"FFlagDebugGraphicsDisableDirect3D11": "True",
	"FFlagDebugGraphicsPreferVulkan": "True"
}
```
### OpenGL
```json
{
	"FFlagDebugGraphicsDisableDirect3D11": "True",
	"FFlagDebugGraphicsPreferOpenGL": "True"
}
```
### Direct X 10
```json
{
	"FFlagDebugGraphicsPreferD3D11FL10": "True"
}
```
### Direct X 11
```json
{
	"FFlagDebugGraphicsPreferD3D11": "True"
}
```

<h1 align="center">Graphical Settings <sup>& other stuff</sup></h1>

### Draws a circle under avatars
```json
{
	"FFlagDebugAvatarChatVisualization": "True",
	"FFlagEnableInGameMenuChromeABTest2": "False"
}
```
### Smoother Terrain
```json
{
	"FFlagDebugRenderingSetDeterministic": "True"
}
```
### Graphics Quality Level
```json
{
	"FIntRomarkStartWithGraphicQualityLevel": "1"
}
```
### Low Quallity Terrain Textures
###### 4 for less quality 16, 32, 64 for higher quality
```json
{
	"FIntTerrainArraySliceSize": "4"
}
```
### Disable Shadows
```json
{
	"FIntRenderShadowIntensity": "0"
}
```
### Preserve rendering quality with display setting
```json
{
	"DFFlagDisableDPIScale": "True"
}
```
### Low Graphics Quality w/ Max Render Distance/FRM Quality Levels
###### Explanation: 1-6 Are low graphics, Above 6 are high graphics. Like the 1-21 graphics slider
```json
{
	"DFIntDebugFRMQualityLevelOverride": "1"
}
```

<h4 align="center">FRM Levels</h4>

```
Low

1 = 3
2 = 2
3 = 6

High

4 = 7
5 = 11
6 = 14
7 = 15 
8 = 17
9 = 18
10 = 21
```

### Low Render Distance
###### [FRM](https://github.com/genocydr/Roblox-Fast-Flag-Community/?tab=readme-ov-file#frm-levels)
```json
{
	"DFIntDebugRestrictGCDistance": "1"
}
```
### Disable Wind
```json
{
	"FFlagGlobalWindRendering": "False",
	"FFlagGlobalWindActivated": "False"
}
```
### Limits light updates
```json
{
	"FIntRenderLocalLightUpdatesMax": "8",
	"FIntRenderLocalLightUpdatesMin": "6"
}
```
### Disables fade in and fade out animation every light update
```json
{
	"FIntRenderLocalLightFadeInMs": "0"
}
```
### Makes avatars shiny 
###### [everything goes black on <3] ***[DFIntDebugFRMQualityLevelOverride is there to set your graphics to 10, You can change it to anything above 3: [Click here to view](https://github.com/genocydr/Roblox-Fast-Flag-Community/?tab=readme-ov-file#frm-levels) ]***
```json
{
	"DFIntRenderClampRoughnessMax": "-640000000",
	"DFIntDebugFRMQualityLevelOverride": "6"
}
```
### Disable PostFX
```json
{
	"FFlagDisablePostFx": "True"
}
```
### Pause Voxelizer/Disable Baked Shadows
```json
{
	"DFFlagDebugPauseVoxelizer": "True"
}
```
### Gray Sky
###### Only applies to games with the default skybox
```json
{
	"FFlagDebugSkyGray": "True"
}
```
### Disable Player Shadows
```json
{
	"FIntRenderShadowIntensity": "0"
}
```
### Force LOD on Meshes
```json
{
	"DFIntCSGLevelOfDetailSwitchingDistance": "0",
	"DFIntCSGLevelOfDetailSwitchingDistanceL12": "0",
	"DFIntCSGLevelOfDetailSwitchingDistanceL23": "0",
	"DFIntCSGLevelOfDetailSwitchingDistanceL34": "0"
}
```
### Lighting Attenuation
```json
{
	"FFlagNewLightAttenuation": "True"
}
```
### Enable GPULightCulling
###### Combine with [Lighting Attenuation]https://github.com/genocydr/Roblox-Fast-Flag-Community/?tab=readme-ov-file#lighting-attenuation) for better vision
```json
{
	"FFlagFastGPULightCulling3": "True"
}
```
### Frame Buffer
###### Explnation: 0 makes white screen 1-3 makes other players have laggy movement, 4 is stable has better performance than 10 and less input lag
```json
{
	"DFIntMaxFrameBufferSize": "4"
}
```
### High Quality Textures 
###### *[1-3]*
```json
{
	"DFFlagTextureQualityOverrideEnabled": "True",
	"DFIntTextureQualityOverride": "3"
}
```
### Lower Quality Textures 
###### *[1-3]*
```json
{
	"DFIntPerformanceControlTextureQualityBestUtility": "-1"
}
```
### No avatar textures
```json
{
	"DFIntTextureCompositorActiveJobs": "0"
}
```
### Remove Grass
```json
{
	"FIntFRMMinGrassDistance": "0",
	"FIntFRMMaxGrassDistance": "0",
	"FIntRenderGrassDetailStrands": "0",
	"FIntRenderGrassHeightScaler": "0"
}
```
### Force MSAA 
###### *[0, 1, 2, 4, 8]*
```json
{
	"FIntDebugForceMSAASamples": "4"
}
```
### ShadowMap Bias 
###### ***[Future & ShadowMap]***
```json
{
	"FIntRenderShadowmapBias": "75"
}
```
<h1 align="center">User Interface</h1>

### FPS Unlocker in Roblox Menu Settings
```json
{
	"FFlagGameBasicSettingsFramerateCap": "True",
	"DFIntTaskSchedulerTargetFps": "0"
}
```
### GUI Hiding Toggles
```json
{
	"FFlagUserShowGuiHideToggles": "True",
	"GuiHidingApiSupport2": "True"
}
```
### Darker Dark Theme
```json
{
	"FFlagLuaAppUseUIBloxColorPalettes1": "True",
	"FFlagUIBloxUseNewThemeColorPalettes": "True"
}
```
### Subscriptions Page
```json
{
	"FFlagLuaAppDevSubsEnabled": "True"
}
```
### No Transparency V4 Menu **(2023)**
```json
{
	"FStringInGameMenuModernizationStickyBarForcedUserIds": "UserID"
}
```
### Revert Old Report Menu
```json
{
	"FStringReportAbuseMenuRoactForcedUserIds": "null",
	"FFlagEnableReportAbuseMenuRoactABTest2": "False",
	"FFlagEnableReportAbuseMenuRoact2": "False",
	"FFlagEnableReportAbuseMenuLayerOnV3": "False"
}
```
### Custom MicroProfile Scale
```json
{ "DFIntMicroProfilerDpiScaleOverride":  "100" }
```
### Hides gui
```json
{ "FFlagDebugAdornsDisabled":  "True" }
```
### Dont Render UI
```json
{
	"FFlagDebugDontRenderUI": "True"
}
```
### Enable Audio Controller
```json
{
	"FFlagTrackerLodControllerDebugUI": "True"
}
```
### Disable Autocomplete
```json
{
	"FFlagEnableCommandAutocomplete": "False"
}
```
### Chrome UI TopBar
```json
{
	"FFlagEnableInGameMenuChrome": "True",
	"FFlagEnableReportAbuseMenuRoactABTest2": "True",
	"FFlagChromeBetaFeature": "True",
	"FFlagEnableInGameMenuChromeABTest2": "True"
}
```
### Pin Chat on Chrome UI
```json
{ "FFlagEnableChromePinnedChat":  "True" }
```
### Chrome UI Topbar Removal
```json
{
	"FFlagEnableInGameMenuChromeABTest2": "False",
	"FFlagEnableReportAbuseMenuRoactABTest2": "False"
}
```
### Disable Bubble Chat
```json
{ "FFlagEnableBubbleChatFromChatService":  "False" }
```
### Disable Selfview
```json
{ "FFlagCoreGuiTypeSelfViewPresent":  "False" }
```
### Remove VC Beta Badge
```json
{
	"FFlagVoiceBetaBadge": "False",
	"FFlagTopBarUseNewBadge": "False",
	"FFlagEnableBetaBadgeLearnMore": "False",
	"FFlagBetaBadgeLearnMoreLinkFormview": "False",
	"FFlagControlBetaBadgeWithGuac": "False",
	"FStringVoiceBetaBadgeLearnMoreLink": "null"
}
```
### Hide guis
###### ***Instructions: Replace "ID" with any group ID that you are in.***
| Key combination   | Action                                                                    |
| ----------------- | ------------------------------------------------------------------------- |
| Ctrl + Shift + B  | Toggles GUIs in 3D space (BillboardGuis, SurfaceGuis, etc)                |
| Ctrl + Shift + C  | Toggles game-defined ScreenGuis                                           |
| Ctrl + Shift + G  | Toggles Roblox CoreGuis                                                   |
| Ctrl + Shift + N  | Toggles player names, and other BillboardGuis that show up above a player |
```json
{
	"DFIntCanHideGuiGroupId": "ID"
}
```
### Disable Fullscreen Title Bar
```json
{
	"FIntFullscreenTitleBarTriggerDelayMillis": "3600000"
}
```
### Set Custom Font Size
```json
{
	"FIntFontSizePadding": "1"
}
```

<h1 align="center">Textures</h1>

### Fix Textures
```json
{
	"FFlagMSRefactor5": "False"
}
```
### No Textures
```json
{
	"FStringPartTexturePackTable2022": "{\"glass\":{\"ids\":[\"rbxassetid://9873284556\",\"rbxassetid://9438453972\"],\"color\":[254,254,254,7]}}",
	"FStringPartTexturePackTablePre2022": "{\"glass\":{\"ids\":[\"rbxassetid://7547304948\",\"rbxassetid://7546645118\"],\"color\":[254,254,254,7]}}",
	"FStringTerrainMaterialTable2022": "",
	"FStringTerrainMaterialTablePre2022": "",
	"FFlagMSRefactor5": "False"
}
```
<h1 align="center">Physics</h1>

### real hitbox for real
```json
{
	"FFlagHumanoidParallelFixTickleFloor2_PlaceFilter": "True;2573981315;6317172524;4999654929;189707",
	"FFlagFixMemoryPriorizationCrash": "True",
	"FIntUGCValidationTorsoThresholdFront": "100",
	"FIntUGCValidationTorsoThresholdSide": "100",
	"FIntUGCValidationTorsoThresholdBack": "100",
	"FIntUGCValidationLeftArmThresholdBack": "23",
	"FIntUGCValidationLeftArmThresholdFront": "25",
	"FIntUGCValidationLeftArmThresholdSide": "40",
	"FIntUGCValidationLeftLegThresholdBack": "40",
	"FIntUGCValidationLeftLegThresholdFront": "40",
	"FIntUGCValidationLeftLegThresholdSide": "36",
	"FIntUGCValidationRightArmThresholdBack": "23",
	"FIntUGCValidationRightArmThresholdFront": "25",
	"FIntUGCValidationRightArmThresholdSide": "40",
	"FIntUGCValidationRightLegThresholdBack": "40",
	"FIntUGCValidationRightLegThresholdFront": "40",
	"FIntUGCValidationRightLegThresholdSide": "38"
}
```
<h1 align="center">other fflags</h1>

### Disable In-game Advertisements
```json
{
	"FFlagAdServiceEnabled": "False"
}
```
### Disable Telemetry 
```json
{
	"FFlagDebugDisableTelemetryEphemeralCounter": "True",
	"FFlagDebugDisableTelemetryEphemeralStat": "True",
	"FFlagDebugDisableTelemetryEventIngest": "True",
	"FFlagDebugDisableTelemetryPoint": "True",
	"FFlagDebugDisableTelemetryV2Counter": "True",
	"FFlagDebugDisableTelemetryV2Event": "True",
	"FFlagDebugDisableTelemetryV2Stat": "True"
}
```
### Adjust Scroll Speed
```json
{ "FIntScrollWheelDeltaAmount": "140" }
```
### Surf the web inside of Roblox
###### Click the Beta badge or the 13+ badge to open the webview browser.
```json
{
	"FFlagTopBarUseNewBadge": "True",
	"FStringTopBarBadgeLearnMoreLink": "https://google.com/",
	"FStringVoiceBetaBadgeLearnMoreLink": "https://google.com/"
}
```
### Sounds use physical velocity and become distorted
###### <2017
```json
{
	"FFlagSoundsUsePhysicalVelocity": "True"
}
```
### Shows the state of a flag
```json
{
	"FStringDebugShowFlagState": "FLAG_HERE"
}
```
###### e.g
```json
{
	"FStringDebugShowFlagState": "DFIntTaskSchedulerTargetFps, ChannelName"
}
```
### MTU 
```json
{
	"DFIntConnectionMTUSize": "MTU_HERE"
}
```
### No Internet Disconnect 
###### *[You will still be kicked but the message wont show.]*
```json
{
	"DFFlagDebugDisableTimeoutDisconnect": "True"
}
```
### Quick Game Launch 
###### *[BUGGY]*
```json
{
	"FFlagEnableQuickGameLaunch": "True"
}
```
### Disable In-Game Purchases
```json
{
	"DFFlagOrder66": "True"
}
```
### Disable Chat
```json
{
	"FFlagDebugForceChatDisabled": "True"
}
```
### Limit audios that are being played
```json
{
	"DFIntMaxLoadableAudioChannelCount": "1"
}
```
### Custom Disconnect Message
```json
{
	"FFlagReconnectDisabled": "True",
	"FStringReconnectDisabledReason": "RFFC"
}
```
### Display FPS
```json
{
	"FFlagDebugDisplayFPS": "True"
}
```
### Applies cool colors to stuff
```json
{
	"FFlagDebugDisplayUnthemedInstances": "True"
}
```
### Disable Dynamic Heads Animations
###### https://roblox.fandom.com/wiki/Dynamic_Head
```json
{
	"DFIntAnimationLodFacsDistanceMin": "0",
	"DFIntAnimationLodFacsDistanceMax": "0",
	"DFIntAnimationLodFacsVisibilityDenominator": "0"
}
```
### failsafehumanoid
###### gray avatars
```json
{
	"FFlagFailsafeHumanoid_3": "True"
}
```
### Automatically unmutes your mic on join (VC)
```json
{
	"FFlagDebugDefaultChannelStartMuted": "False"
}
```
### Overlay that shows what you type 
```json
{
	"FFlagDebugTextBoxServiceShowOverlay": "True"
}
```
### opt-out Experience Language
###### Removes the Experience Language option in settings
```json
{
	"FIntV1MenuLanguageSelectionFeaturePerMillageRollout": "0"
}
```
### Disable New Chat Translation Settings
```json
{
	"FFlagChatTranslationSettingEnabled3 ": "False"
}
```
### VR Controller transparency
```json
{
	"FIntVRTouchControllerTransparency": "0"
}
```
### No sounds
```json
{
	"FFlagDebugRomarkMockingAudioDevices": "True"
}
```
### local rcc
[?](https://github.com/rsblox/local_rcc)
```json
{
	"FFlagDebugLocalRccServerConnection": "True"
}
```
### Exclusive Fullscreen
```json
{
	"FFlagHandleAltEnterFullscreenManually": "False"
}
```

<h1 align="center">Links</h1>

### [Make Your Own Custom Roblox Textures](https://github.com/GoingCrazyDude/roblox-custom-textures/blob/main/README.md) *[Github Repo Link]*
### [Bloxstrap](https://github.com/pizzaboxer/bloxstrap) *[Github Repo Link]*
### [NVIDIA Shaders Guide](https://github.com/catb0x/Roblox-Shaders-Guide) *[Github Repo Link]*
### [EnableAnselForRoblox](https://github.com/DED0026/EnableAnselForRoblox) *[Github Repo Link]*
### [potato fflags](https://github.com/catb0x/Roblox-Potato-FFlags) *[Github Repo Link]*
### [Bindable Lag Switch](https://github.com/Hermivore8151/Bindable-LagSwitch) *[Github Repo Link]*
### [MEGA FLAG LIST](https://discord.com/channels/1099468797410283540/1139962301991104582/1170417533355036712) *[Bloxstrap Server]*

<h4 align="center">‧⁺̣˚̣̣*̣̩⋆̩·̩̩୨˚̣̣̣̣͙୧·̩̩⋆̩*̣̩˚̣̣⁺̣‧ You've reached the bottom of the list! ‧⁺̣˚̣̣*̣̩⋆̩·̩̩୨˚̣̣̣̣͙୧·̩̩⋆̩*̣̩˚̣̣⁺̣‧୨</h4>

# List Information
* Creation Date: 9:46 PM 08/25/2023 
* Github Publish Date: 12/26/2023
* Maintained by [dan](https://discord.com/users/457151128665194527), [variable](https://discord.com/users/848525666622373890), [popbob](https://discord.com/users/702054592262701127), [hermivore](https://discord.com/users/559811983512305693), [genocydr](https://discord.com/users/1059157644012699730) & [kit](https://discord.com/users/761909750006022195)

###### creds to RFFC, RGC, and Bloxstrap

<h3 align="center">FastFlags 2024®<sup>eal</sup></h3>
