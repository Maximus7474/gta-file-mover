# GTAV file mover

This script waws initially created to simplify the process of doing integrity checks and updates when using FiveM.
It's main purpose is to easily move files from one directory to the GTAV game one when Roleplaying with custom sound packs & weapon replaces.

# Setup
1. Create your folder where your modded files will be located and paste the path in set `"source=D:\Path\To\Modded\Files"`
2. Copy your path to your GTA V folder in `set "destination=E:\Path\To\Grand Theft Auto V"`
3. Add your modded files to the created directory
  - Make sure the folder structure is the same the game folder, if the rpf is supposed to go in `x64/audio/sfx/` then in the modded files folder (Point 1.) it should also be in a similar path.
  - The script will copy the files to their exact location where they are stored in, if the file is misplaced then it'll be misplaced in the game folder.

The script will prompt for admin access to allow people to use it when the source and destination targets are on differentt drives