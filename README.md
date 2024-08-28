# Sakura's Minecraft Character Rig
SACR is a lightweight rig designed by an Animator for Animators

# Changelogs
## SACR R4

### R4 Changes

- SSS Support
- Skin Material Rework
  - Diffuse/Principled Slider now included
- Boneshape Improvements
- Fixed Subdivision Surface issues on facerig

### R4 Additions

- Fancy Wrist Support for IK Arms
- Molars re-introduced from SACR R2

-----

## SACR R4.1.1

### Fixed

- Parented Eyelashes to new Parent Empty
- Various Performance Improvements

### Changes

- Updated Shader format to SACR Gen 2 Shader
  - All Materials now use the Gen 2 skin shader as default
  - SSS now Standard
- Eyebrow Control Scheme updated
- Cleaned up and optimized outliner
- SACR now easily extrudable as default
- Tweaked Chest and Hop bone Pivots
- Hip and Pelvis boneshapes remodeled
- Pupils given an offset to give a less derpy feel
- Removed Subdivision from everything except the head and eyebrows
- Remodeled Primary Pupil and Mouth control bone shapes
- Updated Rig Text Formatting
  - Rig Versionis now a solid object, and the text above is changed to be the Character name, also extruded
- Face Materials Split
  - Eyes, Pupils, and Eyebrow mats have all been split into two materials each, 6 materials total
  - Gen 2 SACR Shader now used
- Default Rig Materials and Textures updated
  - Textures
    - Uses Sakura's base skin
  - Materials
    - Eyes now match Sakura's skin
    - Eyebrows Changed to Black
    - Additional Changes due to Gen 2 Shader upgrade
- Slim Arms adjusted
  - Now has two modes, a 1.16 (Only Slim) mode and a 1.8 mode (Slim and Lowered)
- Compressed Outliner
- Compressed Rig into two files, development build now private
  - Extrude > Standard
  - Old Standard > Lite

### Additions

- Derp Controls for Eyes
- HD Compatability for all builds (Even Extrude)
- Emission Compat for eyebrows

### Removed Features

- Remvoed MC Damage Hue from Materials
- Removed Gradiant World Setup
- Anti-lag has been removed (Use Render Properties > Simplify ya shmuck)
- Armor has been booted entirely

-----

## SACR R4.1.2

### R4.1.2 Fixed

- Fixed Attributes in SACR Gen 2 Material
  - Texture Brightness and Global Illum Attr swapped
  - Texture Brightness renamed to Luminance
- Default Pupil Mode reset to Square
- Removed Texture limit
- Merged IK/FK Toggle in the Custom Properties

### R4.1.2 Changes

- Default Arm Mesh changed to 4px arms
- Defauult Rig Textures Changed and Edited
- Smooth Shading replaced with Subdiv Modifier on Torso
- Updated Boneshapes
- Updated Pupil and Eyewhite Materials to Gen 3 (Combined Materials)

### R4.1.2 Additions

- Added Extrude Head
- Added HD Eyewhites into Eyewhite Material by Default

-----

## SACR R4.2

### R4.2 Fixes

- Fixed Parenting of Extrude Meshes
- Disabled Denoiser by default
  - For older systems that don't support SSE4.2
- Re-enabled Extras and Origins in viewport display settings
- Leg Lattice Alignment
- Fixed Eye Gradient UV's
- Teeth Alignment
- Fixed Emissions Controls for Eyewhites not working
- Fixed Subdivision Surface
  - Removed Deprecated Drivers
- Optimized Memory Usage

### R4.2 Changes

- Edited Default Material Values
- Changed Default Textures
  - Skin Changed to Medieval (No Face)
  - HD Eye changed to Medieval (With Face)
  - HD Eye White
- Boneshape Redesign
- Dropped LTS Tag (Final R4 build)

### R4.2 Additions

- Easy Parent Objects

### R4.2 Removed

- Leg IK/FK Hybrid System