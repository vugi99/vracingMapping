# vracingMapping

#### This content is meant to be used as an addition to the Nanos ADK, so you have to create a new project with the ADK
* You can just git clone the [ADK repo](https://github.com/nanos-world/assets-development-kit) in the 'Documents/Unreal Projects' folder.
* Rename the 'assets-development-kit' folder so you won't have duplicates if you create new ADK projects later

#### Content Setup
* Dowload as ZIP then extract in 'adk project'/Content folder OR git clone this repo in the 'adk project'/Content folder.
* The files on this repo need to be in a folder named 'vracingMapping'.
* Open the project then create your Asset Pack folder.

#### Placeholders
* RaceStart : map your race start
* RaceEnd : map your race end
* Spawn : players spawns at the start of the race (set incrementing IDs for each spawn)
* Checkpoint : to add a new checkpoint to the race, set the ID corresponding to the checkpoint number in the race, first checkpoint is ID 1! and second is ID 2 and so on

#### Exporting
* Go to vracingMapping/Generator right click on the blueprint, then press generate map config (Ctrl-A to select output)
* Copy the output to a Packages/map-package/Server/Index.lua file
* Load the map using the map-package with the vracing gamemode
