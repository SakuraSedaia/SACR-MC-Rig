# Sakura's Advanced Character Rig

Some features in R7.2 were not properly implemented and some were completely broken. This hotfix is meant to fix those particular issues

## File Info

Release: R7.2.1<br>
Blender 4.5<br>
Scripts: 0

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

- Automatic Molar/Canine Adjustment relies on Cheek Bones instead of Jaw movement
- Molar/Canine Height/Width Properties now Mouth Custom Properties instead of Bone Controls
  - This is meant to help with adjustability and user experience
- Removed shapes and bones related to old Molar/Canine Adjustments
- Removed Redundant Sparkle Toggle in Eye Properties
- New Custom Property

---

## Mesh

### Mesh Adjustments

- Removed redundant UV Map from Eyebrow Object
- "Face Properties" text added to "Face Properties" bone container
- Teeth Material now applied to Teeth Meshes

---

## Material

### Adjusted Features

- Updated Eyebrow shader to R4.1
  - Added UV Map node to properly assign gradient/split color settings
- Updated Iris shader to R9.1
  - Moved Pupil toggle slider to "Pupil Settings", formerly "Pupil Color"
  - "Pupil Color" Panel renamed to "Pupil Settings"
- Updated Sclera Shader to R9.1

---

## Lite Rig Changes (From 7.2.1)

- Removal of all objects in the "Accessories" collection
- Simplified Mesh Geometry
- Supporting Bones for the Hair rig removed
- All Properties associated with removed meshes deleted
- All Materials associated with removed meshes deleted
- Eyesparkle Removed
- Removed Lattices
- Removed all Bevel and Subdivision modifiers
- Facerig Disabled by Default
- Mesh Collection Dissolved
- Disabled Selection of all Meshes
