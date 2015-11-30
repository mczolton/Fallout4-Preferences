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

## Smooth stuttering FPS

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
Maximum pre-rendered frames: 4
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
