# Fallout 4 Preferences

Preferences location: `%USERPROFILE%\Documents\My Games\Fallout4`

## Skip intro videos

1. Open Fallout4.ini in the configuration file(s) location.
2. Find the section: [General]
3. Add these lines:

```
sIntroSequence=0
fChancesToPlayAlternateIntro=0 
uMainMenuDelayBeforeAllowSkip=0
```

## Smooth stuttering FPS (V-sync monitors)

Do not modify iFPSClamp. Modifying iFPSClamp causes the game to slow down when FPS drops below the stated value. 

1. Open Fallout4.ini in the configuration file(s) location.
2. Find the section: [Display]
3. Add this line:

```
iPresentInterval=0
```

1. Open NVIDIA Inspector to the "Fallot 4" profile.
2. Find the section: "Sync and Refresh"
3. Set these values:

```
Frame Rate Limiter: Off
Maximum pre-rendered frames: 1
Triple buffering: On
Vertical Sync Smooth AFR behavior: Off
Vertical Sync: 1/2 Refresh Rate (for 120Hz monitors)
```

1. Open C:\Program Files (x86)\Steam\SteamApps\common\Fallout 4\enblocal.ini.
2. Find the section: "Limiter"
3. Set these values:

```
EnableFPSLimit=true
FPSLimit=59.900002
```

## Smooth stuttering FPS (G-sync monitors)

1. Follow instructions for *Smooth stuttering FPS (V-sync monitors)*.
2. Open NVIDIA Inspector to the "Fallot 4" profile.
3. Find the section: "Sync and Refresh"
4. Set these values:

```
Frame Rate Limiter: Off
Maximum pre-rendered frames: 1
Triple buffering: Off
Vertical Sync Smooth AFR behavior: Off
Vertical Sync: Use the 3D application setting
```

## Change the Field of View

1. Open Fallout4.ini in the configuration file(s) location.
2. Find the section: [Display]
3. Add these lines:

```
fDefaultWorldFOV=XX
fDefault1stPersonFOV=YY
```

**Notes**
XX is your desired fov in third person.
YY is the desired fov in first person.

## Ultrawide 21:9 Monitor Support

Source: http://www.wsgf.org/forums/viewtopic.php?p=162915#p162915

1. Open Fallout4.ini in the configuration file(s) location.
2. Find the section: [Interface]
3. Add these lines:

```
fUIPowerArmorGeometry_TranslateW=0.00001
fUIPowerArmorGeometry_TranslateZ=14.0000
fUIPowerArmorGeometry_TranslateX=0.0001
fUIPowerArmorGeometry_TranslateY=265.0000
```

1. Open Fallout4Prefs.ini in the configuration file(s) location.
2. Find the section: [Display]
3. Add this line:

```
bComputeShaderDeferredTiledLighting=0
```

1. Install (manual) [Ultrawide Resolution Tweaks by hoodoomagic](http://www.nexusmods.com/fallout4/mods/990/)
2. Install (mod manager) [Widescreen fix by Daisuke](http://www.nexusmods.com/fallout4/mods/274/)
