# SACR Revision E7.1 Prototype 1

### Global Changes

### Mesh Changes

- New Face Mesh added for new Square/Round mouth switcher.
- Removed Hat Layer for Extrude Head.
- Added Driver to Extrude Head.
- Fixed Eyebrow Driver.
  - Eyebrow Driver used Armor Toggle instead of No Face.
- Re-enabled Armor Collection.
- Added "Face." Prefix to all Face Objects
- Increased Rendered Subdiv on all Meshes
  - Face Objects raised to 4
  - Torso & Arms Raised to 2

### Rig Changes

- Implemented Square Mouth option for Facerig.
- Fixed Rotation lock for Mouth Bone Shapes.
- Locked Z-Axis control for Jaw and Cheek controls.
- Added Limits to 4 of the Middle Corner Bones to prevent unintended Z-fighting.
- Arm IK & Stretch Can now be smoothly switched between instead of snapping between states.
- Separate Control for Wrist IK Auto-Rotation.
- Adjusted Fancy Feet, Allowing for more freedom of movement and better tracking
- Edited Bone Colors for the Arms.
- Additional Drivers added for hidding the Arm IK Locators and Pointers.
- Improved functionality of the IK System.
  - Adjusted Leg and Arm Armature for new IK System.
  - Removed IK modifier from Upper Arm and Leg Bones.
  - Edited IK modifier on Forearm and Shin Bones
- Deform Controllers can be switched from Solid to Wireframe Displays

### Driver Changes

- Organized Armature Drivers by Type

### Base File Settings

- Default "Color Management > View Transform" set to AgX.
- Default "Color Management > Look" Set to Base Contrast.