## VertUI for FreeCAD Link

Vertical UI Setup for FreeCAD Link *aka* FreeCAD Linkstage3


![FIhuySJXsAkn46m](https://user-images.githubusercontent.com/70055734/148981429-52ed2d5a-4cbc-499a-b950-840fe178a066.jpg)


### Prerequistes

FreeCAD Link is an experimental branch of FreeCAD created by [@realthunder](https://github.com/realthunder) ([Patreon](https://patreon.com/thundereal)). It can be downloaded from his [repository](https://github.com/realthunder/FreeCAD_assembly3/releases/).


### Installation

Please backup your User/FreeCAD folder first. Or backup the parameters file by opening FreeCAD, going Tools -> Edit Parameters and clicking "Export"

#### Video instruction

Watch the installation procedure via clip  
[![VerticalUI Version 2](https://img.youtube.com/vi/1uMzNe8KwAw/0.jpg)](https://youtu.be/1uMzNe8KwAw "VertUI v2")

#### Text instruction

* Download the repo by either:
  * `git clone https://github.com/StudioPetrikas/FreeCADLink_VertUI`
  * Clicking the green "Code" button and selecting "Download ZIP"
    * Extract the ZIP
* Copy the `Gui` folder to your `User/FreeCAD` folder:
  * **Windows**: `%APPDATA%/FreeCAD` or `C:\Users\[USER]\AppData\Roaming\FreeCAD`
  * **Linux**/**macOS**: `~/.FreeCAD` or `/home/USER/.FreeCAD` or `/home/USER/.config/FreeCAD`
* Run FreeCAD Link
* Go to `Tools` > `Edit Parameters`
* Press `Merge` button > `From File`
* Select the `VertUI.FCParam` file
* Repeat that last 3 steps again (see note below)

**Important note**: Loading parameters is still experimental. There are issues that can be fixed by simply re-merging `VertUI.FCParam` multiple times.  
I have purposely avoided making a preset configuration, because I found it to be very inconsistent.

### Screenshots

TBD

## License

[LICENSE](LICENSE)
