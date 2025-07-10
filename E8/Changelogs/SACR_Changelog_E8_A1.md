# Sakura's Advanced Character Rig

## File Info

Dev Version: 8_A.1
Latest Stable: R7.2
Blender 4.5
Scripts: 0

---
Alpha 1

---

## File Changes

### Workspaces

- Added more Default Workspaces

### Scene

- Renamed Scene to match Major Version

### Drivers Editor

- Deleted Redundant Drivers

---

## Armature

### Armature Adjustments

- Adjustments made to Rig Properties for Python Script Integration
- Split various system controls for further customizability
  - Mouth and Eyes can be toggled separately
  - Arm Thickness controls can be split
  - Eyelashes can now be toggled per side
- Implemented new Eyelid control system using Bendy Bones
- Remodelled Rig Properties boneshape
- Automatic Molar/Canine Adjustment relies on Cheek Bones instead of Jaw movement
- Molar/Canine Height/Width Properties now Mouth Custom Properties instead of Bone Controls
  - This is meant to help with adjustability and user experience
- Removed shapes and bones related to old Molar/Canine Adjustments

### Armature Additions

- Added new Bone Panel for controlling the facerig
- Added new Bone for storing deformation properties
- Lower Eyelids now have a Emotion Controller
- Boneshapes for new bones
- Preparations made for Finger Integration
- Preparations made for 2D Eye and Mouth options

---

## Mesh

### Mesh Adjustments

- Eyelashes 1 (Lilo) and 5 (DanoBadi) normals corrected
- Removed redundant UV Map from Eyebrow Object
- "Face Properties" text added to "Face Properties" bone container
- Teeth Material now applied to Teeth Meshes

### Mesh Additions

- Added two new Head Mesh variants for Eye/Mouth split toggles
- New Unibrow option
- 6 New Eyelash Styles (Credit to Endertainer)

## Material

### Adjusted Features

- Updated Eyebrow shader to R4.1
  - Added UV Map node to properly assign gradient/split color settings
- Updated Iris shader to R9.1
  - Moved Pupil toggle slider to "Pupil Settings", formerly "Pupil Color"
  - "Pupil Color" Panel renamed to "Pupil Settings"
- Updated Sclera Shader to R9.1
- Sparkle Shader reverted to basic Emission Node

---

## Python/Drivers

### Driver Adjustments

- Various expressions optimized
- Implemented new expressions for Python UI Integration

### Scripts Additions

- Python UI Addon has been implemented to improve rig controllability and usability
