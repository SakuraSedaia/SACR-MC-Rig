# Sakura's Advanced Character Rig

## File Info

Dev Version: 8_A.1
Latest Stable: R7.1.1
Blender 4.3.2
Scripts: 0

---
Alpha 1

---

## Outliner

### Outliner Adjustments

- Lattice Collection added for user customizable Lattices
- Marked Master Collection as an Asset, allowing the rig to be imported through the Assets tab

## Armature 

### Armature Adjustments

- Reorganized Bone Collection Tree, making future editing easier
- Completely re-rigged the Face
  - Mouth, Eyes, and Eyelashes now use Bendy Bones, and have greatly improved controllability as standard
- Reorganized the entire Driver List
- All drivers on Modifier's "Enabled/Disabled" changed to change their influence
- Changed all references to "Fancy Feet" to "Ankle"
- Fixed Right IK Locator Name, Mirror now works properly
- "ArmK.Stretch.R" Renamed to "ArmIK.Stretch.R" in order to match Left side
- Removed 16 bones from Angular Fancy Feet
- Adjusted Bone Shape for Global properties
- Removed even more redundant Addon Bullcrap
- Updated Custom Property Drivers, now incorporating Booleans for toggle switches

### Armature Additions

- New Bendy style Ankle, able to be hot swapped with classic angular ankle.
- Added two new controllers for Torso

---

## Mesh

### Mesh Adjustments

- Remodeled Face Mesh to match new Armature
- All face related Meshes now contained in the Face Container
- Original Lattice objects turned into presets
  - Traditional Female deform removed, replaced with individual Taper, Bulge, and Breast controls
- Sclera now uses the same Gradient UV setup as the Irises
- Eyelashes Updated
  - Uses same Bendy Bones as eyes
  - Renamed to chronological names
  - Show/Hide Drivers now include "No Face" Check

### Mesh Additions

- New lattices added for easier mesh styling
- Nametag added to rig, Functionality using Geo Nodes
- Bendy Ankle mesh for new Bendy Ankle style

---

## Materials

### Material Adjustments

- Eye Sparkle now included in Iris Material
- Pupils now included in Iris Mateiral
- Iris Shader upgraded to Revision 8

### Material Additions

- Supporting Materials for Nametag
