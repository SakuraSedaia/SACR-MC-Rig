# Sakura's Advanced Character Rig

## Latest Version: R7

--------
SACR Revision 7:

### Global Changes

- Simplified Armor Mesh and Material
  - No more extruded mesh
  - Extremely Simplified Materials
  - Only 1 Texture Included in rig
  - Individual Properties bone merged with main global properties
- Rig updated to Blender 4.1
- Pupils now separated to another object
  - New Material Added
  - New Object Added
  - Main Pupil Options removed from Iris Gen 6 (Only Textured Pupils Remain)
- Removed useless addon custom properties

### Mesh Changes

- Mouth now has 5 MC Pixels of Depth
- Teeth now a typical Horseshoe shape
- Remodeled Face Mesh, Fixing the Mouth Clipping Issue
- Reset all custom vectors
- Added Auto-Smoothing Modifier to Arms, Head, and Torso
- Adjusted Shapekey and Driver for Eye Sparkles

### Rig Changes

- Re-did Face Controls and Properties
- Face Properties split into 4 Bones (Total, Mouth, Eyes, and Eyebrows)
- Individual Eye Controls now always show
- Flip bone is now Togglable, Defaulted to Off
- Disabled "In Front"
- Updated and Added new Boneshapes
- Renamed Shapekey Objects in Driver's editors to match bone with "_shape"
- Replaced all "cos(var)" invert toggle expressions with "1-var"
- Condensed all variables to one character
- Molars are now Togglable, Defaulted to Off
- Hair Rig now Merged with base SACR Armature

### Material Changes

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

### Base File Settings

- Default Rendering Device set to "CPU"
- "Viewport Denoiser" set to "Off"
- "Viewport Noise Threshold" set to "Off"
- "Film > Transparent set" to "Off"
- "Color Management > Exposure" set to default
- Changelog is no longer an internal document, reducing file size even further
