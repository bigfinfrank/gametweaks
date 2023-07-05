# Black Ops 3 Game Tweaks

## config.ini

- disable fps limit
- disable vram limit
- minimize input latency
- unhide in-game graphics options
- increase graphics quality (past what is normally possible via in-game setings

**Entering the video/graphics settings menu will always prompt you to save changes. if you hit save changes (whether or not *you* made any changes), it'll undo some of the config.ini tweaks.**

`G:\SteamLibrary\steamapps\common\Call of Duty Black Ops III\players\config.ini`

```ini
//
//Gameplay
//

//Frame rate cap (0 for none)
MaxFPS = "0" // 0 to 1000

//Show current framerate on screen
DrawFPS = "0" // 0 or 1

//Toggle framerate smoothing
SmoothFramerate = "0" // 0 or 1

//Horizontal field of view in degrees assuming 16:9 aspect ratio
FOV = "103" // 65 to 120

SplitscreenOrientation = "0" // 0 or 1

//Enable network voice chat
VoiceChat = "0" // 0 or 1

//Enable occlusion of sound behind solid surfaces
SoundOcclusion = "1" // 0 or 1

//Mouse smoothing amount
MouseFilter = "0" // 0 to 10

MouseAcceleration = "0" // 0 to 1

MouseSensitivity = "2.19369" // 0.1 to 30

//Mouse vertical sensitivity
MouseVerticalSensitivity = "0.022" // -1 to 1

//Enable vertical look with the mouse
MouseVerticalLook = "1" // 0 or 1

//Maximum number of simultaneous human corpses
CorpseCount = "32" // 1 to 32

//Number of frames the driver is allowed to enqueue, a lower value improves input latency but may decrease performance. Set it to 0 to use the system default, usually 3.
MaxFrameLatency = "1" // 0 to 4

//0 use two threads, one thread update frame N while the second render N-1. 1 concatenate update and render. 2 concatenate update render and frame presentation.
//0 is the default for the best performance, 1 and 2 improve latency but require a powerful CPU.
SerializeRender = "2" // 0 to 2

//
//Setup
//

//Set to zero to force auto-detect to run at startup
AutoDetectHasRun = "1" // 0 or 1

//Clear to check driver against recommended
LastDriverNvidia = "53598" // 0 or bigger

//Clear to check driver against recommended
LastDriverAMD = "0" // 0 or bigger

//Fraction of video memory usage to target
VideoMemory = "1" // 0.75 to 1

//Hide graphics options that are too demanding for the user's video card
RestrictGraphicsOptions = "0" // 0 or 1

//
//Display
//

// 0 - Windowed, 1 - Fullscreen, 2 - Fullscreen Window
FullScreenMode = "1" // 0 to 2

//Window X position
WindowX = "0" // -8192 to 8192

//Window Y position
WindowY = "0" // -8192 to 8192

WindowSize = "2560x1440" // any text

RefreshRate = "164.999" // 1 to 240

//Monitor index to use for fullscreen
Monitor = "1" // 0 to 8

//Vsync only applies in fullscreen
Vsync = "0" // 0 or 1

//Percentage of window resolution that the 3D scene renders at
ResolutionPercent = "100" // 50 to 200

//Color spaces for monitor output
DisplayGamma = "sRGB" //  sRGB, rec.709, or rec.709 - Limited

//Set to 3 to enable triple buffering, useful to prevent large framerate drops when vsync is enabled
BackbufferCount = "2" // 2 to 3

//
//Graphics
//

//LOD's to drop on models, lower numbers are higher quality
MeshQuality = "0" // 0 to 2

//0 - Force 2x anisotropic filtering, 1 - Per material, 2 - Force 16x anisotropic filtering
TextureFilter = "2" // 0 to 2

//Number of mips to drop on streamed textures, lower numbers are higher quality
TextureQuality = "0" // 0 to 3

//Number of mips to drop on effects and dynamic decals, lower numbers are higher quality
TextureQualityFX = "0" // 0 to 15

//Number of mips to drop on reflections, lower numbers are higher quality
TextureQualityProbes = "0" // 0 to 16

//Number of mips to drop on sun shadows, lower numbers are higher quality
TextureQualityBakedSunShadows = "0" // 0 to 2

//Force lowest mips to stay loaded instead of streaming
TextureLowDetailResident = "1" // 0 or 1

DisableDynamicLightShadows = "0" // 0 or 1

DisableDynamicSunShadows = "0" // 0 or 1

//Resolution of spot light shadows
SpotShadowTextureSize = "6144" // 128 to 8192

//Resolution of omni (point) light shadows
OmniShadowTextureSize = "1536" // 128 to 2048

//Enable multi-sampled soft shadows
ShadowFiltering = "1" // 0 or 1

//Number of lights with otherwise static shadows to force characters shadows on
ActorShadows = "16" // 0 to 16

//Enable volumetric sun and light shafts
VolumetricLightingEnabled = "1" // 0 or 1

//Number of raymarch samples for sunlight
VolumetricLightingMaxSunSamples = "256" // 1 to 256

//Number of raymarch samples for local lights
VolumetricLightingMaxLightSamples = "256" // 1 to 256

//Skip every other sample if color is constant
VolumetricLightingSkipSunSamples = "0" // 0 or 1

//Skip every other sample if color is constant
VolumetricLightingSkipLightSamples = "0" // 0 or 1

//Enabled order-independent transparency
OIT = "1" // 0 or 1

//Maximum number of overlapping transparency layers
OITLayers = "16" //  8, 9, 12, or 16

//Screen-space ambient occlusion method
SSAOTechnique = "GTAO Ultra Quality" //  Disabled, HEMIAO, GTAO Low Quality, GTAO Medium Quality, GTAO High Quality, or GTAO Ultra Quality

//Anti-aliasing technique
AATechnique = "Filmic SMAA T2x" //  None, FXAA, SMAA 1x, Filmic SMAA 1x, SMAA T2x, or Filmic SMAA T2x

//Per-object motion blur
MotionBlur = "Off" //  Off, Auto, or On

MotionBlurQuality = "High" //  Low, Medium, or High

//Better lighting for skin
SubsurfaceScattering = "1" // 0 or 1

//If true, the game will switch back to fullscreen once it get back the focus after losing it on Alt+Tab or similar events. If false, the game stay window and can be switch back to fullscreen with Alt+Enter
AutoRestoreFullscreen = "1" // 0 or 1

//Set to 1 or 2 to display an ingame overlay of the frame performance over time.
ShowPerformanceGraph = "0" // 0 to 16

//Reduces memory reservations on systems with low GPU memory.
StreamMinResident = "0" // 0 or 1
```

## delete loading movies ([steam guide](https://steamcommunity.com/sharedfiles/filedetails/?id=557719129))

this will reduce loading times substantially, most of these are the solo-only zombies intro cutscenes (ex. the "hey you~" shadows of evil video)

rename (ex. prefix with `_` or append `.bak`) or delete the following files in `G:\SteamLibrary\steamapps\common\Call of Duty Black Ops III\video`:

- `bo3_global_logo_logosequence.mkv` - game startup intro - deleting this will make the game window entirely black until the main menu loads
- `zm_castle_loadingmovie.mkv` - der eiesendrache
- `zm_factory_load_factoryloadingmovie.mkv` the giant
- `zm_frontend_load.mkv` - zombies forest interstitial loading video - can prevent you from getting stuck
- `zm_genesis_loadingmovie.mkv` revelations
- `zm_island_loadingmovie.mkv` zetsubou no shima
- `zm_prototype_loadingmovie.mkv` nacht der untoten
- `zm_stalingrad_loadingmovie.mkv` gorod krovi
- `zm_theater_fs_loadingmovie.mkv` kino der toten
- `zm_tomb_loadingmovie.mkv` origins
- `zm_zod_load_zodloadingmovie.mkv` shadows of evil

## fast_restart, map_restart & disconnect binds ([steam guide](https://steamcommunity.com/sharedfiles/filedetails/?id=1122433143))

fast_restart for quickly restarting maps that aren't super custom, map_restart for restarting (mostly custom maps) that break when using fast_restart, disconnect to keep gobblegums without alt+f4/task manager-ing the game.

replace or add `bind l fast_restart` and `bind p map_restart` to both of the following files:

- `G:\SteamLibrary\steamapps\common\Call of Duty Black Ops III\players\bindings_0.cfg`
- `G:\SteamLibrary\steamapps\common\Call of Duty Black Ops III\players\bindings_1.cfg`

## T7patch (RCE, remote crash, A.B.C error and FPS bug fixes ([steam guide](https://steamcommunity.com/sharedfiles/filedetails/?id=2924410249))

"A new and improved community patch for a large list of Black Ops III exploits.", can be found in this repo: https://github.com/shiversoftdev/t7patch