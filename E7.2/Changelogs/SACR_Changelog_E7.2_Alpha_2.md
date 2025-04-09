# Sakura's Advanced Character Rig
Second Alpha Build of SACR R7.2, this build focuses far more on optimizations and naming consistencies, updating drivers, and some lingering issues remaining on SACR R7.1.1

## File Info

Dev Version: E7.2 Alpha 2
Latest Stable: R7.1.1
Blender 4.4
Scripts: 0

---

# Changes

## File Changes

### Timeline

- Playback Sync set to "Frame Dropping" instead of "Play Every Frame"

---

## Outliner

### Outliner Adjustments

- Renamed the Majority of bones and objects to meet a consistent style, leaving Limb Controls untouched to keep compatability
- Fixed naming of Right Leg IK Locator

---

## Armature 

### Armature Adjustments

- Removed 16 Redundant Angular Ankle Bones
- Changed the 8 primary Angular Ankle bones to use Transform Modifiers instead of Drivers, reducing the number of buggy interactions
- Removed Dozens of redundant/duplicate drivers
- Recolored Arm IK Pointer Bones to match their respective limb
- Right Arm IK Pointer no longer shows when Right Arm IK is not active
- Removed more redundant Custom Properties from Addons


---

## Mesh

### Mesh Adjustments

- Renamed all Armor to follow a more logical naming scheme
- Renamed all Shape Key groups to match their parent object, removing any redundant extrude shape keys
- Removed Redundant BoneShapes
- Removed more redundant Custom Properties from Addons

