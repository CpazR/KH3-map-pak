# MapPak - A dependency mod for KH3 custom map creation assets

## What this mod does?

This also includes other additionally funcitonality for custom mods

## How to use this mod?

### For modders:

### TODO: Finalize this

For map modders, it should be as simple as copying the contents of the `projectAssets` folder into your `contents` folder in your Tres game proejct.

**DO NOT MODIFY THEESE ASSETS!** This is simply for compatability between different map mods that use these assets.

For more customized assets, make a child blurprint of the desired base asset.

Move the newly created child asset into your mod directory to prevent compatability issues. Use a file explorer outside of unreal to avoid unnecessary linker files.

## Uploading your map:

When using MapPak and uploading to nexus, be sure to do the following:

- Link MapPak as a dependency on nexus
- ***DO NOT COOK THE MAPPAK DIRECTORY IN YOUR TRES-GAME PROJECT***
  - Can exclude by going to edit -> project settings -> project -> packaging -> directories to never cook
    - Add `Mods/MapPak`