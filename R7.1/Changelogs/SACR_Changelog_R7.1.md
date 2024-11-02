# Sakura's Advanced Character Rig

## Latest Version: R7.1

--------
SACR Revision 7.1:

### Base File Settings

- Updated to Blender 4.2 LTS
- Default "Color Management > View Transform" set to AgX.
- Default "Color Management > Look" Set to Base Contrast.
- Performed Various Blend File Optimizations

--------

### Rig Changes

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
- Deform Controllers can be switched from Solid to Wireframe Displays
- Fixed `Global Mouth Position` not rotating the mouth as intended.
- Teeth now move according to `Global Mouth Position` as well as their respective Jaw.
- Fixed Polarity of the Cheek Bones, as Left was Right and Right was Left.
- Updated Face Control Boneshapes to have more consistent Fillets
- Reorginized Molar Controls and made each control more intuitive
- Fang Controls now enabled by Default
- Spacing on Face Controllers improved
- Removed redundant "mmd" and "ant-landscape" Custom Properties
- Adjusted Fancy Feet, Allowing for more freedom of movement and better tracking
- Fixed Misconfigured Transform Space on FF Deform Drivers
- Removed Deprecated Pupil Drivers

--------

### Driver Changes

- Organized Armature Drivers by Type
- Added Driver for Eyebrow Width Shapekey

--------

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
- Added Width Shapekey to the Eyebrow

--------

### Material Changes

- Upgraded SACR Iris & Sclera Material to Gen 7
  - Pupils now integrated back into Overall Iris Node Group
  - Simplified Color Handler Process
  - Simplified Luminance Process
  - Simplified Global Illumination Process
  - Condensed Gradiant/Heterochromatic Setup into a Nodegroup
  - Advanced Emission controls now easily accessible
- Deleted Pupil Material

--------

### Lite Rig Changes

- Long Hair Rig Removed
- Eyelashes Removed
- Armor Removed
- Extrude Head Removed
- Eye Sparkles Removed
- Extremely Simplified Mesh
- All Subdiv Modifiers removed
- All Autosmooth Modifiers removed
- Gradient on Iris and Sclera Materials Removed
