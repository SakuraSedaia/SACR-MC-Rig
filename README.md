# SACR-MC-Rig
Quite simply, SACR is a rig developed by Sakura for use in Blender in the creation of Minecraft Character based renders with a huge emphasis on a large feature package without the performance drawback typically associated with having all of those features.

SACR R6, released 2 years ago on Blender 2.93 has recieved a minor refresh to clean up two main issues present on the rig for Blender 3.3, being non-functional materials and extreme lag. SACR R6.1 is still offered as Blender 3.6 changed the file structure of blender save files, making it impossible to open or append newer rigs such as SACR R7 in versions older than Blender 3.6. 
## Changelog

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