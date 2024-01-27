<p align=center><img src="https://i.imgur.com/OxDiSBk.jpg"></a></p>

**<p align=center>RG ARC version of the Crystal Theme for TheRA</p>**
Original project: https://github.com/dm2912/Crystal<br>
Based off of the RGB10 ArkOS fork: https://github.com/farfenkugell/es-theme-farfenkugell_crystal

<br>
<p>Demo Video:</p>

 [<img src=https://img.youtube.com/vi/sd1je__NzhY/0.jpg width=40%>](https://www.youtube.com/watch?v=sd1je__NzhY)

<br>


### <p align=center>--== ==--</p>

Main changes are: 

- Made compatible with 4:3 resolution by replacing system images with alternate 640 x 480 versions based around prominent Female Characters. Theme should also work on other 4:3 handhelds using EmulationStation(i.e. 353v/ArkOS).
- Systems that are WIP have the same placeholder art.
- Stock widescreen images removed and replaced with farfenkugell's 720p revision as a fallback. 
- Sega Themed TheRA Logo added for Cpu Scripts/Advanced Options
+ Scrape images on the device, not computer, as it will make sure images are proper size and prevent pixelation on gamelist
+ See licence file for sources, credits and licence

### <p align=center>--== ==--</p>

**01-25-2024:**

*v0.1: First Release. Most of the common systems are here, many still WIP.*

<br>

## <p align=center>--== Manual Installation Instructions ==--</p>

###### *Instructions assume you are on a Windows Based PC that is unable to view partitions formatted in EXT4. In this example we will transfer the files via SSH with [Filezilla](https://filezilla-project.org). 

- Step 1: Download the latest version on the [releases](https://github.com/GHROTIC/es-theme-retrogirls_crystal/releases) page and extract the zip as a folder (i.e. /es-theme-retrogirls_crystal).

- Step 2: In Filezilla Select File -> Site Manager. When creating a New Site select the Protocol as SFTP and enter the IP address of your RG ARC. You can obtain this by pressing the Start Button in the Main Menu of your RG ARC(When connected to Wifi it will show at the bottom center of the screen).

##### Logon Type: Normal<br> Login: ark<br> Password: ark

After pressing Connect you should now be able to access your RG ARC's file system remotely.

<p align=center><img src="https://i.imgur.com/F1blbWZ.png"></a></p>

- Step 3: On the left side find the es-theme-retrogirls_crystal folder you extracted in your Windows Downloads Directory(This will be the folder you want to transfer). On the right side change the server directory to: /etc/emulationstation/themes and upload the es-theme-retrogirls_crystal folder and it's contents into this directory. You should now be able to see the theme as an option on your RG ARC by pressing the Start Button in the Main Menu -> UI Settings -> Theme.

<br>

If you have any questions, comments or suggestions I can be found in the #rg_arc channel on the RetroHandhelds Discord: https://discord.com/invite/retrohandhelds
