# Roblox is going to remove fflags ;c
# if this fast-flags collection don't work then i don't care!

# Random Fast Flags

### 21 graphics bar instead of 10
```json
{
"FFlagFixGraphicsQuality": "True"
}
```
### Force gray sky 
> [!NOTE]
>
> Only works for the game that has default sky-box. Games like Blade Ball won't work!
```json
{
"FFlagDebugSkyGray": "True"
}
```
### Disable player shadow
```json
{
"FIntRenderShadowIntensity": "0"
}
```
### Max render distance while on low graphics quality
```json
{
"DFIntDebugFRMQualityLevelOverride": "1"
}
```
### Limits Light Update
```json
{
"FIntRenderLocalLightUpdatesMax": "8",
"FIntRenderLocalLightUpdatesMin": "6"
"FIntRenderLocalLightFadeInMs": "0"
}
```
### Disable useless effect (Post Fx)
```json
{
"FFlagDisablePostFx": "True"
}
```
### Disable every shadow
> [!NOTE]
>
> Use Voxel to disable every shadow may cause light issues. But if you add "_PlaceFilter" and your game ID, you should be good
```json
{
"DFFlagDebugPauseVoxelizer": "True",
"DFFlagDebugRenderForceTechnologyVoxel": "True",
"FIntRenderShadowIntensity": "0"
}
```
### Make Level of Detail meshes
```json
{
"DFIntCSGLevelOfDetailSwitchingDistance": "1",
"DFIntCSGLevelOfDetailSwitchingDistanceL12": "1",
"DFIntCSGLevelOfDetailSwitchingDistanceL23": "1",
"DFIntCSGLevelOfDetailSwitchingDistanceL34": "1"
}
```
### Enable New Light Attenuation
> [!NOTE]
>
> Do NOT use other light technology when combine with this, otherwise it will be pixel
```json
{
"FFlagNewLightAttenuation": "True",
"FFlagFastGPULightCulling3": "True"
}
```
### Frame Buffer
```json
{
"DFIntMaxFrameBufferSize": "4"
}
```
### Low Texture Quality
```json
{
"DFFlagTextureQualityOverrideEnabled": "True",
"DFIntTextureQualityOverride": "0"
}
```
### Remove most other player texture (clothing)
```json
{
"DFIntTextureCompositorActiveJobs": "0"
}
```
### Disable grass
```json
{
"FIntFRMMinGrassDistance": "0",
"FIntFRMMaxGrassDistance": "0",
"FIntRenderGrassDetailStrands": "0",
"FIntRenderGrassHeightScaler": "0",
"FIntRenderGrassDensityMax": "0",
"FIntRenderGrassDensityMin": "0"
}
```
### Disable MSAA
```json
{
"FIntDebugForceMSAASamples": "0"
}
```
### Disable shadowmap bias
```json
{
"FIntRenderShadowmapBias": "0"
}
```
### Remove Chrome UI
```json
{
"FFlagEnableInGameMenuChromeABTest2": "False",
"FFlagEnableReportAbuseMenuRoactABTest2": "False"
}
```
### Disable Self-view
```json
{
"FFlagCoreGuiTypeSelfViewPresent": "False"
}
```
### Disable fullscreen title bar
> [!NOTE]
>
> Not fully disable it, but delay it for 1 hour
```json
{
"FIntFullscreenTitleBarTriggerDelayMillis": "3600000"
}
```
### Disable in game ad service
```json
{
"FFlagAdServiceEnabled": "False"
}
```
### Disable telemetry
> [!NOTE]
>
> Not fully disable it, only disable some telemetry
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
### Show flag state of a certain fast-flag
```json
{
"FStringDebugShowFlagState": "FFlagDebugSkyGray"
}
```
### Stay away from p2w!
> [!NOTE]
>
> Only disable in-game purchasing?? i don't know
```json
{
"DFFlagOrder66": "True"
}
```
### Custom disconnect message
```json
{
"FFlagReconnectDisabled": "True",
"FStringReconnectDisabledReason": "meow meow meow, you got disconnect by roblox!"
}
```
### Display FPS
```json
{
"FFlagDebugDisplayFPS": "True"
}
```
### Disable dynamic geads animations
```json
{
"DFIntAnimationLodFacsDistanceMin": "0",
"DFIntAnimationLodFacsDistanceMax": "0",
"DFIntAnimationLodFacsVisibilityDenominator": "0"
}
```
### Add some color to certain UI
```json
{
"FFlagDebugDisplayUnthemedInstances": "True"
}
```
### No zoom out limit
> [!NOTE]
>
> Only works for the game that uses default zoom limit!
```json
{
"FIntCameraMaxZoomDistance": "9999"
}
```
### Stop Tencent to spy on you!
```json
{
"FStringTencentAuthPath": "null"
}
```
### Fake Verify
> [!NOTE]
>
> Only you were able to see it!
```json
{
"FStringWhitelistVerifiedUserId": "You_Roblox_User_ID"
}
```
### Enable quick game launch
```json
{
"FFlagEnableQuickGameLaunch": "True"
}
```
### Cleaner ESC menu
```json
{
"FIntV1MenuLanguageSelectionFeaturePerMillageRollout": "0",
"FFlagChatTranslationSettingEnabled3": "False",
"FFlagDisableFeedbackSoothsayerCheck": "False"
}
```
### No gui for every game
```json
{
"FFlagDebugDontRenderUI": "True"
}
```
### Favorite button for UGC items
```json
{
"FFlagEnableFavoriteButtonForUgc":"True"
}
```

### There is more fast flags on roblox, i'm too lazy to write them down.


