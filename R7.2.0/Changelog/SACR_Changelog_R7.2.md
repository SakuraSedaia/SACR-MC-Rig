# Sakura's Advanced Character Rig

SACR R7.2 is a sub-version release to remedy a bunch of issues currently present in hotfix patch 7.1.1 as well as add some minor features to enhance the rig. Main fixes include various performance optimizations, driver fixes, file size reductions, and consistent naming.

## File Info

Release: R7.2<br>
Blender 4.4<br>
Scripts: 0

---

## File Changes

### Scene

- Renamed Scene to match Major Version
- Default "Color Management > View Transform" set to AgX.
- Default "Color Management > Look" Set to Base Contrast.

### Timeline

- Set default Keying Set to nothing
- Playback Sync set to "Frame Dropping" instead of "Play Every Frame"

### Drivers Editor

- Organized Armature Drivers by Type

---

## Outliner

### Outliner Adjustments

- Renamed Eyelashes to replace Lash Name with a number in order
- Steve Arm Meshes Renamed to be Arm.4x4.(side)
- Alex Arm Meshes Renamed to be Arm.3x4.(side)
- Renamed the Majority of bones and objects to meet a consistent style, leaving Limb Controls untouched to keep compatability
- Fixed naming of Right Leg IK Locator
- Removed "Armor." Prefix from Armor Objects, opting just for the piece name
- Eyelashes now included into the "Accessories" Collection
- Unmarked Master Collection as an Asset

---

## Armature

### Armature Adjustments

- Implemented Square Mouth option for Facerig.
- Fixed Rotation lock for Mouth Bone Shapes.
- Locked Z-Axis control for Jaw and Cheek controls.
- Added Limits to 4 of the Middle Corner Bones to prevent unintended Z-fighting.
- Arm IK & Stretch Can now be smoothly switched between instead of snapping between states.
- Separate Control for Wrist IK Auto-Rotation.
- Edited Bone Colors for the Arms.
- Additional Drivers added for hidding the Arm IK Locators and Pointers.
- Improved functionality of the IK System.
  - Adjusted Leg and Arm Armature for new IK System.
  - Removed IK modifier from Upper Arm and Leg Bones.
  - Edited IK modifier on Forearm and Shin Bones
- Shaped Controllers can be switched from Solid to Wireframe Displays
- Fixed Alex Arm Transform Fix modifiers on Shoulder Bones
- Removed Half Pixel Downward Adjustment on Slim Arm Transform
- Removed 16 Redundant Angular Ankle Bones
- Ankles now rely on Transform Modifiers instead of Driver controlled restricters
- Removed Dozens of redundant/duplicate drivers
- Recolored Arm IK Pointer Bones to match their respective limb
- Right Arm IK Pointer no longer shows when Right Arm IK is not active
- Removed redundant Custom Properties from Addons
- Integers switched to Booleans where applicable

---

## Mesh

### Mesh Adjustments

- Enabled Optimized Display on the Subdiv modifier on the face mesh.
- Added new 3x3x12 Arm Mesh option
- New Square & Round Mouth now uses the same facemesh and bones
- Added Driver to Extrude Head.
- Fixed Eyebrow Driver.
  - Eyebrow Driver used Armor Toggle instead of No Face.
- Re-enabled Armor Collection.
- Increased Rendered Subdiv on all Meshes
  - Face Objects raised to 4
  - Torso & Arms Raised to 2
- Renamed all Armor to follow a more logical naming scheme
- Renamed all Shape Key groups to match their parent object, removing any redundant extrude shape keys
- Removed Redundant BoneShapes
- Removed redundant Custom Properties from Addons
- Condensed all "Smooth by Angle" Geometry Node groups into one
- Fixed Improper UVs on the bottom of the Head
- Re-added Sparkle Objects

---

## Material

### Adjusted Features

- Updated Base shader to R4.1
  - Removed Double Layer Emit, caused issues with other more complex shaders
- Updated Iris shader to R9, resolving severe performance drops
  - Simplified Pupil/Iris Shader, significantly improving performance
  - Removed Sparkles from Shader, caused severe performance drops
- Updated Sclera Shader to R9
- Upgraded Eye Sparkle Shader to only show the emissive in camera.

## Lite Rig Changes (From 7.2)

- Removal of all objects in the "Accessories" collection
- Simplified Mesh Geometry
- Supporting Bones for the Hair rig removed
- All Properties associated with removed meshes deleted
- All Materials associated with removed meshes deleted
- Eyesparkle Removed
- Iris Shader simplified
  - Removed Pupils
- Sclera Shader Simplified
- Removed Lattices
- Removed all Bevel and Subdivision modifiers
