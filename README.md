<p align=center><img src="https://i.imgur.com/OxDiSBk.jpg"></a></p>

**<p align=center>RG ARC version of the Crystal Theme for TheRA</p>**
Original project: https://github.com/dm2912/Crystal<br>
Based off of the RGB10 ArkOS fork: https://github.com/farfenkugell/es-theme-farfenkugell_crystal

<br>
<p>Demo Video:</p>

 [<img src=https://img.youtube.com/vi/KzD_yMF4iSk/0.jpg width=40%>](https://www.youtube.com/watch?v=KzD_yMF4iSk)

<br>


### <p align=center>--== ==--</p>

Main changes are: 

- Made compatible with 4:3 resolution by replacing system images with alternate 640 x 480 versions based around prominent Female Characters. Theme should also work on other 4:3 handhelds using EmulationStation(i.e. 353v/ArkOS).
- Systems that are WIP have the same placeholder art.
- Stock widescreen images removed and replaced with farfenkugell's 720p revision as a fallback
- Modified TheRA Logo added for Cpu Scripts/Advanced Options
- Scrape images on the device, not computer, as it will make sure images are proper size and prevent pixelation on gamelist
+ See licence file for sources, credits and licence

### <p align=center>--== ==--</p>

**01-13-2024:**

*First Release. Most of the common systems are here, many still WIP such as specific Arcade Machines(CPSII, CPSIII).*

<br>

## <p align=center>--== Temporary Installation Instructions ==--</p>
###### *Will investigate Thememaster Support for TheRA RC1.
###### *Instructions assume you are on a Windows Based PC that is unable to view partitions formatted in EXT4. In this example we will transfer the files via SSH with Filezilla. 

Step 1: Click on the green "Code" button near the top of the main page and select to "Download Zip". Once downloaded right click on the zip file in your Download Folder, select Extract All and then click on "Extract" when the new Window opens.

Step 2: Open Filezilla and connect to your RG ARC. On the left side go into the folder you extracted(i.e. es-theme-retrogirls_crystal-master). There should be another folder inside named es-theme-retrogirls_crystal-master. This will be the folder you want to transfer.

<p align=center><img src="https://i.imgur.com/Q7xzYTJ.png"></a></p>

Step 3: On the right side change the server directory to: /etc/emulationstation/themes and upload the es-theme-retrogirls_crystal-master folder and it's contents into this directory. Press the Start Button -> Quit -> Restart EmulationStation and you should now be able to see the theme as an option by pressing the Start Button in the Main Menu -> UI Settings -> Theme

<br>

If you have any questions, comments or suggestions I can be found in the #rg_arc channel on the RetroHandhelds Discord: https://discord.com/invite/retrohandhelds
