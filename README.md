# Zombie Survival 3D

Kotlin + libGDX third-person Android survival shooter using the Quaternius Zombie Apocalypse Kit (64 original glTF models).

Download builds and the **complete Android Studio Source ZIP** from [Releases](https://github.com/rimul637/Zombie-Survival-3D/releases). The automatically generated GitHub source archives contain this repository README, not the complete game project.

## v1.1.0 update

- Correct PBR diffuse environment lighting and BRDF lookup, preserved materials/UVs, distant restrained fog and shared identical texture atlases.
- Textured building details, animated survivors/zombies, improved muzzle alignment and reload motion.
- Scalable framed menus, icon HUD controls, circular joystick, fit-viewport touch coordinates and restart confirmation.
- All 64 original models retained, with an asset inventory in the source archive. New square 512-pixel launcher artwork included.

## Verified scope

SDK 35/Kotlin compilation, APK signing/alignment, packaged AndroidX startup dependencies, three native ABIs and all 83 original assets pass validation. Desktop OpenGL rendering and interaction checks pass at 1280×720 and 1600×720. Deterministic gameplay tests clear all eight waves, 104 infected and Patient Zero. See TEST_RESULTS.md in the full project for Android runtime test status. Physical-device 60 FPS has not been measured.

## Installation limitation

The original v1.0.1 development signing key was lost when the workspace reset. v1.1.0 uses a new development key and **cannot install over the differently signed v1.0.1**. Uninstalling the older app erases its local scores/settings. Keep the old installation if preserving those values is essential; an in-place update requires the original private key. The application ID and preference keys remain unchanged.
