# Example Mod
This repo contains an example mod for UMC. You can use this as the base for you project if you wish!

## Building
In order to build this project you will need to create a "libs" folder under the ```UnderMineControl.Example``` directory and then add some of the games libraries to it! Unfortunately, I cannot provide them for legal reasons. The following libraries are required:

The following can all be found under the ```steamapps\common\UnderMine\UnderMine_Data\Managed``` directory.
* UnderMine.dll
* UnityEngine.CoreModule.dll
* UnityEngine.dll

The following can be found under the ```steamapps\common\UnderMine\BepInEx\plugins\UnderMineControl``` directory as long as [UnderMineControl](https://github.com/calico-crusade/underminecontrol) is installed. Alternatively, you can get it [here](https://github.com/calico-crusade/underminecontrol/releases)
* UnderMineControl.API.dll

## Manually installing the mod
To install your mod, create a folder in the ```steamapps\common\UnderMine\Mods``` directory with the name of your mod and then put your ```.umc``` file and your mod's ```.dll``` file.

Here is the example layout for ```UnderMineContro.Example```:
* ```steamapps\common\UnderMine\Mods\ExampleMod\examplemod.umc``` - This file tells the loader what files to load and some information about your mod
* ```steamapps\common\UnderMine\Mods\ExampleMod\UnderMineControl.Example.dll``` - This file contains the compiled code for you mod.