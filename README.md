# Rostock-Laage Airport (ICAO: ETNL) for Microsoft Flight Simulator (WIP)

This is an early work in progress of airport Rostock-Laage (ETNL) for the most recent MS Flight Simulator.

## Current Progress

- Runway 09/27 added
  - with overrun and markings
  - CALVERT approach lights (hopefully this is the correct light system). Unfortunately approach lights are placed on the overrun. I am currently unsure how to fix that.
  - PAPI4 lights
- Includes object for aerial imagery (satelite image) to be able to remove the pixelated ground textures around the airport. As I am unsure about the copyright of the created images, these files are not included in this repo.
  - Follow these steps to the create the satelite image yourself:
    - [Use this guide to create the images yourself](https://www.flightsim.com/vbfs/content.php?21225-How-To-Create-MSFS-2020-Scenery).
    - Follow steps 1-5 and then open the project using the ingame Developer-Mode.
    - The resulting package should then be compiled by MSFS and placed into the ```Packages``` subfolder where your cloned this repository.
  - A known issue is that the image disappears in-game when the camera is near ground. Unsure if this is a MSFS bug or I am doing something wrong.
  - If the mentioned guide is too complicated and you are fine with using the airport without it, then you can just grab the [latest release](https://github.com/Michaelvsk/msfs-etnl/releases/) and follow the [install guide](#installation-guide).

## Installation guide

1. Download the [latest release](https://github.com/Michaelvsk/msfs-etnl/releases/).
2. Find ```community``` folder of your MSFS installation ([Guide](https://www.flightsim.com/vbfs/content.php?21235-Finding-The-MSFS-2020-Community-Folder)).
3. Unzip the release zip into that folder so there is subfolder called ```mrthompson83-etnl```.
4. Start MSFS and go to world map. You should now be able to select ETNL as departure/arrival airport.

## Known issues
- A lot of stuff is missing in the current stage of this project. Only runway is more or less complete.

## Roadmap
- [x] Add runway
- [ ] Flatten airport aera
- [ ] Add taxiways
- [ ] Add aprons
- [ ] Find out how to add jetways and airport services
- [ ] Maybe custom objects for terminal and other buldings