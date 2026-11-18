# Zombie Survival 3D

Kotlin + libGDX third-person Android survival shooter using the 64-model Quaternius Zombie Apocalypse Kit.

Download APKs and explicitly named complete Android Studio Source ZIPs from [Releases](https://github.com/rimul637/Zombie-Survival-3D/releases). GitHub’s automatic source archives contain repository documentation, not the complete game project.

## v1.2.0

- Camera-relative exploration facing and independent combat facing, smooth shoulder/orbit tracking and wall clearance.
- Fixed a near-zero residual simulation tick that incorrectly set locomotion to idle on slow frames.
- Calibrated procedural support-hand IK, original-mesh detachable magazines, shotgun reload motion and synchronized mechanical cues.
- Connected 188×188 finite district, about six times the earlier bounded area, with 36 buildings, roads, vehicles, props, five camps and physical perimeter walls.
- Spatial static-mesh caches, reduced AI ray allocations, conditional navigation refresh and particle/actor reuse.
- Original materials, lighting, 64 models, loadouts, eight-wave campaign, boss, menus, controls, icon and preferences retained.

The original pack has no authored reload clip; the new reload is procedural rig animation, not motion capture. Physical-device stable 60 FPS has not been certified. See TEST_RESULTS.md in the full source archive for actual build, desktop and Android test results.

## Update compatibility

v1.2.0 uses the same development signing certificate and application ID as v1.1.0, with a higher version code. Install over v1.1.0 without uninstalling to retain its local scores/settings. Historical v1.0.x APKs used a different, unrecovered key and cannot update directly to this signing lineage.
