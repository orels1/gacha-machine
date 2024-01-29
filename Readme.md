# Gacha Machine

![Miku Gacha](/Images/Preview.png)

This is a Miku-Inspired Gacha Machine made from scratch for a VRC Prefabs Miku Jam.

The design of the machine was based on the [incredible concept art](https://www.artstation.com/artwork/rJd90E) by Jimi Osborne-McNeilly.

## Process

- The machine was modeled in Blender 3.6 using MidPoly -> HighPoly -> LowPoly workflow
- Unwrapped with ZenUV and UVPackmaster
- Baked and texture painted in Marmoset Toolbag
- Stamps and alphas for the painting were created in Figma and Blender (rendered out as PNGs)
- Rigged to add all the moving parts in Blender
- Everything was imported into Unity 2022.3.6 and custom shaders were created utilizing orels Unity Shaders package

## Project Structure

- All of the Unity resources are in Assets/Miku Gacha folder, including the demo scene
- All of the "source" assets are in Root/Other Assets folder, including
  - Blender files for the machine itself and all the other meshes
  - Marmoset Toolbag file for the machine
  - All of the final Bake textures
  - Some alphas and stamp brushes created for the project
  - Aseprite files for the spritesheet animations

## Requirements

If you're going to set this up yourself - you'll need the following:

- Unity 2022.3.6f1 (or newer)
- VRChat SDK (if you want to upload it to VRChat)
- [orels Unity Shaders](https://shaders.orels.sh/)

Optional:

- AudioLink
- GestureManager

## License

Check [License.md](License.md) for more info.
