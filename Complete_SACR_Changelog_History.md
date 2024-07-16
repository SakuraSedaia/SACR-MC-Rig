# SACR Complete Changelog

## SAMR V1

### Initial Release, no changes

-----

## SAMR V1.5 Changelog

- Re-rigged Torso
- Wrists
- Global & Local IK
- Controlls to toggle objects and object modes

-----

## SACR R1

Complete Rig Overhaul, too many changes to list

-----

## SACR R1.1

### R1.1 Changes

- Fixed IK Arm Switcher
- Adjusted Torso Deforms
- Edited Boneshapes
- Adjusted Subdivision Surface
- Tweaked Alex Arms to MC Java 1.8 Positions
- Fixed Materials Head
- Extrude Heads now selectable
- Issue with Advanced Controller Fixed

### R1.1 Additions

- Teeth
- Easy HD Eye UV Adjuster

### R1.1 Removed

- Extrude Rig deleted

-----

## SACR R2

### R2 Changes

- Face Options moved to new Face Control Panel
- Tweaked Mouth Controls
- Tweaked Alex Arms
- Tweaked Wrists
- New Global Material Object
- Adjustment to Torso Weight Paint and Modifiers

### R2 Additions

- IK leg Switchers
- Armour
- Face Control Panel
- Female Torso Deformations
- Updated Mouth Controls
- Basic Emotion Controller
- Pupils Scale with Rig
- Molars Added

### R2 Removed

- Automatic HD Pupil UV's

-----

## SACR R3

Rig was completely rebuilt from scratch, only Materials were carried over from SACR R2

### R3 Changes

- Sakura Rig User Interface Gen 2
  - The Rig Interface was updated with a new layout, using both sliders and custom properties to control rig
- Armor Rework
  - Armor was reworked with a new structure which shoudl provide a significant improvement to R2, being compacted into a single nodegroup which will allow for easier customizability
- Pupil Material Improvements
  - Pupils were split inot two nodegroups to improve user experience
- Eyebrow Material Optimization
- Driver Optimization
- Fixed Z-Fighting on Limbs
- High Poly Eye Optimizations
  - Combined Eyes into one mesh
- Bone Shape redesign
  - New Bone Shapes should be easier to use
- Bone Scale adjustments
  - Default scale set to 0.623
- Default Material Values Optimized and Improved
- Facerig improvements
- Torso uses Bendy Bones instead of traditional Weight Paints
- Changed Material from Advanced Mesh to 2 layer cube
- Leg IK/FK system Rework
  - IK legs use both IK and FK, credit to ZophieKat's BPS V3 rig
- Rig Version System changed to Revisions from Version

### R3 Additions

- BPS Style Fancy Feet

-----

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

-----

## SACR R5

### R5 Fixes

- UV Mappings fixed and re-aligned
- Removed Unused and broken settings
- Removed Broken Drivers

### R5 Changes

- Changed how Pupils are Scaled
- Arm Anchor point changed
- Updated and Simplified Boneshapes
- Changed Eyebrow Thickness to Shapekey
- Improved Female Deform
- Updated Default Workspace
- Updated Image Names
- Armature and Master Collection names updated
- Armature and Mesh collections fused
- Updated ArmIK to Match Leg IK
- Updated Eyebrow Controls
- Updated Skeleton Layer organization
- Default skin and materials set for Steve skin

### R5 Added

- Separate Emission Mask Inputs for each Eye
- Pupils + Custom Pupil Support
- Stretch to Legs
- Shapekey to Lattices for Custom Deforms
- Restrictions on scale, allowing for easy Child Preset creation
- Stretch to Arms
- Added a two step toggle on Eyes and Eyebrows
- Added a Separate toggle for Mouth
- Added easy smoothing on arms & torso

### R5 Removed

- Round Eyes
- Complete HD Skin Compatability
- Diffuse Material
- Round Eye
  - NOTES To have HD Eyes properly enabled, you must now manually add the "UV Map" and "Image" nodes. Set the UV Map node to the "HD_Map" UV and connect it to your Texture, same with HD Eyewhites. Connect the Texture to the first colour input of both Left and Right

-----

## SACR Revision 5.1

### R5.1 Fixed

- Flipped Eyebrow Normals
- Alex Arm Normals

### R5.1 Changes

- Added Separate SSS Colour Input
- Expanded and Restructured Iris and Eyewhite Material
- Reorganized and Simplified Default UI

### R5.1 Additions

- Rigged Hair

### R5.1 Removed

- Diffuse Shader Option

-----

## SACR R5.2

### R5.2 Fixed

- Iris Scaling not working

### R5.2 Changes

- Eye Pupil base controls Simplified
- Pupils now Scale according to Pupil Control
- Moved Pupil Control
- Fang Effectors now shown all the time

### R5.2 Added

- Square Mouth
- Labels on Control Panel
- Re-added Armour w/ Updated Control Interface

### R5.2 Removed

- Pupil Size (Value in Face properties)

-----

## SACR R6

### R6 Fixed

- Z Lock not enabled on certain face bones
- Duplicate Skin File
- Removed "PurgeThis" Material
- Renamed "EyeTex_Cat.png.001" to "EyeTex_Cat.png"
- Side Middle Control pins on Left eye not being weighted correctly
- Square mouth not being a square
- Changed Math Expression for Iris scale
- Teeth Material not applied to Teeth
- Named all objects with default names
- Matched "Mesh" names to "Object" names on all Objects

### R6 Changes

- Eyelash Lattice given more Loop Creases
- Camera no longer in "SACR" Collection
- General Optimizations
- Removed the random square in the "FaceControlPanel" object
- Rearanged Overall Rig Controls
- Enabled Smooth mode on Arms
- Changed Hair Rig obj name to "SARH V1"
  - SAHR stands for "Sakura's Advanced Hair Rig"
- Internal ID for SACR Armature changed to "SACR R3"
  - This is due to the current rig being based on the SACR R3 Architecture

### R6 Added

- Female Mesh modified and improved
- 5 more Eyelash types
- Added extra Arm-IK function to disable Wrist Autorotation
- Added "Master" Label to master rig collection

### R6 Removed

- Adjustable Iris Size (Due to new Expression being used to auto-scale Pupils)
- Removed Text on side of head

-----

## SACR R6.1

### 6.1 Fixed

- Eyewhite Heterochormia and Gradient

### 6.1 Changes

- Changelog now separate file, accessible on Website

### 6.1 Removed

- Armor completely removed, caused too much lag

-----

## SACR Revision 7

### R7 Global Changes

- Simplified Armor Mesh and Material
  - No more extruded mesh
  - Extremely Simplified Materials
  - Only 1 Armor Texture Included in rig
  - Individual Properties bone merged with main global properties
- Rig updated to Blender 4.1
- Pupils now separated to another object
  - New Material Added
  - New Object Added
  - Main Pupil Options removed from Iris Gen 6 (Only Textured Pupils Remain)
- Removed useless addon custom properties
- Collections now color coded
- Rig now has Lite and Standard Versions

### R7 Mesh Changes

- Mouth now has 5 MC Pixels of Depth
- Teeth now a typical Horseshoe shape
- Remodeled Face Mesh, Fixing the Mouth Clipping Issue
- Reset all custom vectors
- Added Auto-Smoothing Modifier to Arms, Head, and Torso
- Adjusted Shapekey and Driver for Eye Sparkles
- Adjusted Sharp-Bend 125 Shape Key
- Adjusted default Subdivision Surface modifier settings

### R7 Rig Changes

- Re-did Face Controls and Properties
- Face Properties split into 4 Bones (Total, Mouth, Eyes, and Eyebrows)
- Individual Eye Controls now always show
- Flip bone is now Togglable, Defaulted to Off
- Disabled "In Front"
- Added new Boneshapes and removed reduntant ones
- Renamed Shapekey Objects in Driver's editors to match bone with "_shape"
- Replaced all "cos(var)" invert toggle expressions with "1-var"
- Condensed all variables to one character
- Molars are now Togglable, Defaulted to Off
- Hair Rig now Merged with base SACR Armature

### R7 Material Changes

- Renamed Materials
- Fixed UV's for Eye whites
- Mouth Inside default color changed to a Dark Red
- SACR Base Shader updated to Gen 4
  - Reorganized Inputs
  - Blender Panels now Incorporated
  - Added new SSS Weight Input
  - Added Reflection light path to Emission Pass
- SACR Eyewhites Shader updated to Gen 2
- SACR Iris Shader updated to Gen 6
  - Pupil Control Completely stripped
  - Blender Panels now Incorporated
  - Removed All Drivers
- SACR Eyebrow Shader updated to Gen 3
  - Blender Panels now Incorporated
- All other Shaders updated to use the new Base Shader

### R7 Base File Settings

- Default Rendering Device set to "CPU"
- "Viewport Denoiser" set to "Off"
- "Viewport Noise Threshold" set to "Off"
- "Film > Transparent set" to "Off"
- "Color Management > Exposure" set to default
- Changelog is no longer an internal document, reducing file size even further

### R7 Lite Rig Specifics

- Hair Rig Removed
- Molars removed
- Super Optimized Mesh (Faces reduced by 75%)
- All Subdivision Surface modifires Removed
- Armor removed
