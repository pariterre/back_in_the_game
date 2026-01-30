# back_in_the_game
Software that assists clinicians in assessing whether a player is ready for a return to the game

# STARTING

## Required packages

- Basketball Asset Pack
  - https://assetstore.unity.com/packages/3d/environments/basketball-asset-pack-166570
- Minimalist ArchViz Bedroom
	- https://assetstore.unity.com/packages/3d/environments/minimalist-archviz-bedroom-131093
- Midwest Park Football (Soccer) stadium
	- https://assetstore.unity.com/packages/3d/environments/midwest-park-football-soccer-stadium-125254
- Hospital Medical Office Kit
  - https://marketplace.unity.com/packages/3d/environments/hospital-medical-office-kit-165327 
- Runtime File Browser
  - https://assetstore.unity.com/packages/tools/gui/runtime-file-browser-113006

### Updating steps to use new packages
The *Hospital Medical Office Kit* needs to update the materials to use the URP compatible shaders. To do this, follow these steps:
1. In the *Project* window, navigate to the *Hospital Medical Office Kit* folder.
2. In the search bar, type "t:Material" to filter and show only material files.
3. Select all the material files (you can use Ctrl + A or Cmd + A).
4. In *Editor* menu, go to *Rendering* > *Materials* > *Convert Selected Built-in Materials to URP*.
5. Wait for the conversion process to complete.
