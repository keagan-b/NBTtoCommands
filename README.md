# NBTtoCommands
Pass in an NBT file, get a datapack back that will generate that NBT in your world.

## What It Does
By passing in an a NBT file, you are able to get the JSON back.
This script uses that data to create a Minecraft Datapack. By enabling the pack, then running `/function {function}`, it will build the NBT file in your world.

## What It Can Be Used For
 - Map Art! - Was originally created with map art in mind
 - Pixel Art
 - Structures
 - & anything from an NBT file! *With varying degrees of success*

### Installation & Usage
To run the script, download the zipped file from the Releases tab, and extract the downloaded file.
Run `Start.bat`, and move an NBT file into the same folder. Type the name of the file (*no `.nbt`*) into the console
The end result is a folder, which can be moved into your datapack files of the world.
Run `/datapack list`,  then `/datapack enable {name of pack}`. From there, simply run the command `/function {name of structure}` to start it!

*Be advised, large structures may cause server lag. Anything over 64,000 blocks will not be created, unless the max commands is turned up.*


### Resources
 - MapArtCraft, NBT Generator - [Website](https://rebane2001.com/mapartcraft//), [Github](https://github.com/rebane2001/mapartcraft/)
 - Python-NBT - [PyPI](https://pypi.org/project/Python-NBT/), [Github](https://github.com/TowardtheStars/Python-NBT)
