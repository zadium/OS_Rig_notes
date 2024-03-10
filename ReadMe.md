# My Notes for Import and Rigging

Rotate it to direct Y- (Face to Y- Back to Y+)

Apply rotations and scales

## Import Dae

1 - Rotate mesh to face Y-

2 - Apply scale/rotations

## Bones

You can use it from the [SL Bento](https://wiki.secondlife.com/wiki/Project_Bento_Resources_and_Information) site or Onigiri/Bento Buddy

For tiny (or as you wish) meshes delete bones (mSpine1,mSpine2,mSpine3,mSpine4)

## Mirroring

1 - Cut in half

2 - Add Mirror modifier before Armature modifier using X axis

3 - Check used group vertices names of left side, must be exists in the mesh, both Left and Right groups, each used right group should have the left group (empty not assigned)

## Export

Use -X as direction

Use Z as top

## Import to OpenSIM/SL

LOD Medium as Above if it Hair

Optional set other LODs (lowers) to zero

Physic Cube, Analyse it if you like

Include Joins if you want to scale the body, no need it for Hair, Clothes

[Lod in FS](https://www.firestormviewer.org/lod-and-the-upcoming-firestorm-release-the-what-and-why/)

For Tiny meshes, shift down using Z Offset about -0.3