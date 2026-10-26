# CSI-Dark-Motives-AiO-Fix

This all-in-one fix brings **CSI: Dark Motives** to modern Windows, with compatibility improvements and three display options.

- **Compatibility:** Fixes the bundled Shockwave 3D startup crash caused by modern graphics-driver detection.
- **CD check:** Loads the required files from the game installation dynamically, removing the CD-ROM requirement for a full installation.
- **Video playback:** Fixes cinematic artifacts, flickering and scenes showing through videos.
- **Rendering:** Fixes the reported Fill-mode panorama jitter and crashes when switching to static scenes.
- **Saves:** Stores profiles and progress in `Documents\CSI-Dark Motives\SavedGames`, avoiding Program Files write restrictions.

**Choose your display mode:**

- **Original:** Keeps the original 800×600 presentation.
- **Fit:** Scales to the desktop resolution while preserving 4:3 proportions, with borders where needed.
- **Fill:** Stretches the complete picture to the desktop resolution without cropping.

**Optional save migration tool:** Imports existing saves from the old installation-relative locations, including Windows VirtualStore, with backups. **New users do not need this tool.** Existing users whose saves are already in the Documents location do not need it either.

Tested on Windows 11. Windows 10 has not been tested. No separate Shockwave installation, dgVoodoo or external scaling application is required. 
