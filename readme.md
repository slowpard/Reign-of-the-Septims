# **Reign Of The Septims**

The goal of Reign Of The Septims is to provide a mod list that offers a larger selection of quality mods, while remaining fairly approachable, as well as familiarizing the user into Oblivion modding. Adequate stability and performance has been taken into account. The mod list must be installed in chronological order. This version of the guide assumes you are using **Wrye Bash** as your main mod manager.

It is very important to carefully read** ALL** of the instructions in the guide. This will prevent potential confusion and help understand what everything does and what to do. While the guide attempts to remain approachable, it still assumes the user has basic computer knowledge.

Sections that have **green text** are mandatory to follow. This is to ensure a quality experience in case the user does not wish to use the full mod list.

Users with low VRAM are advised to limit their use of high resolution texture packs. Low end PC users in general may wish to avoid generating LOD as well, due to performance concerns.

We also have a Discord server[ here](https://discord.com/invite/UxACgBFh3m).

**<span style="text-decoration:underline;">Requirements</span>**



* A copy of the game with all DLCs from either [Steam](https://store.steampowered.com/app/900883/The_Elder_Scrolls_IV_Oblivion_Game_of_the_Year_Edition_Deluxe/) or [GOG](https://www.gog.com/game/elder_scrolls_iv_oblivion_game_of_the_year_edition_deluxe_the).
    * The Microsoft Store version is not supported.
* Approximately 60 GBs of free space.
* Windows 10 or higher (64-bit).
* A text editor ([Notepad++](https://notepad-plus-plus.org/) is recommended, but the default Windows notepad will work).
* An archiving tool ([7-Zip](https://7-zip.org/) is recommended).
* The latest GPU drivers (either[ NVIDIA](https://www.nvidia.com/Download/index.aspx),[ AMD](https://www.amd.com/en/support) or[ Intel](https://www.intel.com/content/www/us/en/search.html#q=&sort=relevancy&f:@tabfilter=%5BDownloads)).
* An account on [Nexus Mods](https://www.nexusmods.com/) and [AFK Mods](https://www.afkmods.com/)?.


## Setup

**<span style="text-decoration:underline;">Enabling File Extensions</span>**

By default, the File Explorer will not show visible file extensions (such as .exe,.ini, .esp). File extensions being visible are necessary when going through the guide.



1. Open File Explorer.
2. Select the **View** tab at the top. (Windows 11 users will need to go to the **Show** section afterwards).
3. Enable **File name extensions**.

    

<p id="gdcalert1" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image1.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert2">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image1.png "image_tooltip")



**<span style="text-decoration:underline;">Key Terminology</span>**

There are two folders that will be referred to in the guide often:



* **Root** folder: Where the game is installed.
    * For Steam: Steam\steamapps\common\Oblivion
    * For GOG: GOG Galaxy\Games\Oblivion (unless you manually changed the installation path).
* **Data** folder: Where all of the game's assets are located.
    * For Steam: Steam\steamapps\common\Oblivion\Data
    * For GOG: GOG Galaxy\Games\Oblivion\Data

**<span style="text-decoration:underline;">Install Location</span>**

A clean installation is recommended to make sure the game is installed in a safe location. Here is what must be done:



1. **Avoid any default Windows folders:** Examples would be C:\Program Files, C:\Program Files x86, your Desktop, or your Documents folders.
2. **It is recommended to use an SSD**: Having Oblivion on an SSD will decrease stutter and improve loading times.

**<span style="text-decoration:underline;">Uninstalling the Game</span>**

Skip this and the following section if you have not installed Oblivion yet.

<span style="text-decoration:underline;">Steam</span>



1. Go to the Steam **Library**, and find **The Elder Scrolls: Oblivion.**
2. Right-click ->Manage ->Uninstall
3. Navigate to **Steam\steamapps\common** and, if present, delete the **Oblivion** folder.
4. Navigate to **Documents\My Games\Oblivion** and delete all INI files inside it.

<span style="text-decoration:underline;">GOG</span>



1. Go to the Installed tab, and find **The Elder Scrolls: Oblivion - Game Of the Year Edition Deluxe**.
2. Right-click ->Manage installation ->Uninstall

**<span style="text-decoration:underline;">Installing the Game</span>**

After the uninstall is complete, proceed with reinstalling Oblivion.

<span style="text-decoration:underline;">Steam</span>



1. Go to the Steam **Library**, and find **The Elder Scrolls: Oblivion**.
2. Right-click ->Manage ->Install

<span style="text-decoration:underline;">GOG</span>



1. Go to the Installed tab, and find **The Elder Scrolls: Oblivion - Game Of the Year Edition Deluxe**.
2. Right-click ->Manage installation ->Install

**<span style="text-decoration:underline;">Fresh INI File Generation</span>**

Generating INI files is needed to generate registry keys, and to prevent issues from running the game altogether.



1. Run the game from Steam, GOG Galaxy, or through OblivionLauncher.exe.
2. Click OK to both pop-ups that say **Detecting Video Hardware**.
3. If there aren't any pop-ups, navigate to Documents\My Games\Oblivion and delete the **Oblivion.ini**, then try again.
4. Select **Options**, then select the **Ultra High** preset.
5. Set the Resolution to your monitor's maximum resolution.
6. Select **Windowed** mode.
7. Click OK.
8. Click **Play **to** **launch Oblivion.
9. Immediately exit the game.

**<span style="text-decoration:underline;">Ini Tweaks</span>**

The following tweak will be necessary to prevent issues with certain mods in the guide:



1. Navigate to the **Documents\My Games\Oblivion** folder.
2. Open the **Oblivion.ini** and set the following ini suggestion:

    [General]


    bBorderRegionsEnabled=0



### **Mod Manager**

Why **Wrye Bash:**



* better in-game performance as it doesn’t rely on VFS
* better compatibility with mod packages for Oblivion
* significantly less manual actions for mod package installation
* generally more straightforward instructions
* easier to use 3rd party tools (e.g. tes4ll) 

**<span style="text-decoration:underline;">Wrye Bash</span>**

Download Wrye Bash [here](https://www.nexusmods.com/site/mods/591).

Download the Installer version only.



1. Run the executable.
2. Make sure that it is installed for Oblivion.
3. The location of Wrye Bash and its executable(Wrye Bash.exe) should be in the **Oblivion\Mopy** folder.
4. An **Oblivion Mods** folder should be made just outside the Oblivion folder.

**<span style="text-decoration:underline;">Wrye Bash Tutorial</span>**

**<span style="text-decoration:underline;">Installers Tab Setup</span>**

For Wrye Bash to function optimally, the Installers tab must be setup like this:



1. In the **Installers** tab, right-click on the **Package **column, and make sure **Enabled** is checked and **Skip Vanilla Content** is unchecked.

    

<p id="gdcalert2" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image2.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert3">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image2.png "image_tooltip")


2. In the **Installers** tab, click on **File** in the top left.
3. Select “**New Project…”**.

    

<p id="gdcalert3" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image3.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert4">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image3.png "image_tooltip")


4. Untick **Blank.esp**, and call it **"Original Game Data"**.
5. Click OK.

    

<p id="gdcalert4" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image4.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert5">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image4.png "image_tooltip")


6. Double-click on the **Original Game Data **project.
7. Copy the **Music**,** Shaders**,** Textures**, and** Video **folders,** **as well as the** vanilla DLC esps **(including** Knights**) from the Oblivion** Data **folder into the **Original Game Data** project.

    

<p id="gdcalert5" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image5.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert6">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image5.png "image_tooltip")


8. Install the **Original Game Data** project by right-clicking on it and selecting **Install…**.

    

<p id="gdcalert6" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image6.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert7">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image6.png "image_tooltip")



**<span style="text-decoration:underline;">Basic Installation</span>**

To install mods with Wrye Bash:



1. Drag and drop an archive into the **Installers** tab.

    

<p id="gdcalert7" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image7.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert8">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image7.png "image_tooltip")


2. Right-click on the newly added mod package.
3. Select **"Install…".**

**<span style="text-decoration:underline;">BAIN Installer Wizards</span>**

When installing BAIN Installer Wizards, be sure to check **Apply these selections**.



<p id="gdcalert8" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image8.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert9">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image8.png "image_tooltip")


**<span style="text-decoration:underline;">Sub-Packages</span>**

Located in the lower right pane in the **Installers** tab. They are made to give options to the user before installing.



<p id="gdcalert9" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image9.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert10">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image9.png "image_tooltip")


**<span style="text-decoration:underline;">Plugin Filter</span>**

Before fully installing a mod, you may want to use the **Plugin Filter** to prevent installation of esps or esms that you don’t want or need.



<p id="gdcalert10" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image10.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert11">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image10.png "image_tooltip")


**<span style="text-decoration:underline;">Unpacking To Project</span>**

For more control over individual files:



1. Right-click on a mod package.
2. Go to **Archive..**.
3. Click on **Unpack to Project(s)...**.

    

<p id="gdcalert11" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image11.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert12">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image11.png "image_tooltip")


4. Click on OK..

    

<p id="gdcalert12" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image12.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert13">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image12.png "image_tooltip")



    

<p id="gdcalert13" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image13.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert14">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image13.png "image_tooltip")



**<span style="text-decoration:underline;">Annealing</span>**

If you decide to uninstall mod packages or you see yellow or orange highlights:



1. Go to **Edit**.
2. Select **Anneal All**.

    

<p id="gdcalert14" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image14.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert15">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image14.png "image_tooltip")



**<span style="text-decoration:underline;">Redating</span>**

If plugins in the **Mods** tab are highlighted in red upon initially opening WB, they will require redating:



1. Press Ctrl+A and right-click on the highlighted mods.
2. Go to **"File.."** and then **"Redate..."**

    

<p id="gdcalert15" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image15.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert16">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image15.png "image_tooltip")


3. Click OK without typing anything.

    

<p id="gdcalert16" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image16.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert17">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image16.png "image_tooltip")



**<span style="text-decoration:underline;">BAIN Conversion File (BCF)</span>**

Some mods may have flawed file structures. This is what BCFs help resolve. Mods in the guide that have BCF in their instructions is where you must apply the BCF.

Download the "Wrye Bash BCFs Collection for Mods" [here](https://www.nexusmods.com/oblivion/mods/51885).



1. Make sure all of the individual **BCF.7z** files have been added into the **Oblivion Mods\Bash Installers\Bain Converters** folder (located just outside the **Oblivion** folder).

    

<p id="gdcalert17" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image17.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert18">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image17.png "image_tooltip")


2. In your Oblivion **Installers** tab, right-click on a mod package.
3. Go to **Archive **->**Bain Conversions **->**Apply**.

    

<p id="gdcalert18" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image18.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert19">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image18.png "image_tooltip")


4. Click OK.

    

<p id="gdcalert19" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image19.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert20">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image19.png "image_tooltip")


5. The original non-BAIN mod package can now be safely deleted.

    

<p id="gdcalert20" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image20.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert21">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image20.png "image_tooltip")



**<span style="text-decoration:underline;">General Installation</span>**

Keep these steps in mind when downloading and installing anything from the guide past this point:



1. Individual mods in the guide that have no instructions underneath them are straightforward downloads and installs.
2. When multiple mod files are in the same mod page(most will be hosted on Nexus), there will be **Download Instructions** that look like this:
    * Files
    * Main Files
    * Update Files
    * Optional Files
    * Miscellaneous Files
3. When some setup is needed to get a mod or tool running, they will be referred to as **Installation Instructions**.


### **Tools**

[LOOT - Load Order Optimisation Tool](https://www.nexusmods.com/site/mods/439/)

This tool will provide well sorted mods regardless of how much is installed from the guide, as well as providing the relevant Bash Tags, which ensures that the Bashed Patch works correctly.

**<span style="text-decoration:underline;">Installation Instructions</span>**



1. Run the executable to install.
2. Make sure the install path is set to its default (**C:\Program Files\LOOT** folder).

[TES4Edit](https://www.nexusmods.com/oblivion/mods/11536)

This tool gives the user options to clean mods, create manual patches, sort masters of plugins with incorrect masters order, etc.

**<span style="text-decoration:underline;">Installation Instructions</span>**



1. Copy the contents of the “Tes4Edit 4.x.x” folder to the Oblivion folder (not Data), so Oblivion.exe, TES4Edit.exe, and TES4EditQuickAutoClean.exe are in the same folder.

[DXVK](https://www.nexusmods.com/newvegas/mods/79299)

Greatly improves Oblivion performance. Due to some hardware not being able to support it, it is optional. It can be safely removed at any time. **This must be manually downloaded. **

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - DXVK 2.3.1
* Main Files DXVK 1.10.3 - Async(if GPU does not support Vulkan 1.3)

**<span style="text-decoration:underline;">Installation Instructions</span>**



* Extract all the contents of the archive into the Oblivion root folder.

[4GB Ram Patcher](https://www.nexusmods.com/oblivion/mods/45576)

Allows the game to use 4GBs of RAM. This significantly increases stability and reduces load times.

**Only needed for the Steam version. This must be manually downloaded.**

**<span style="text-decoration:underline;">Installation Instructions</span>**



1. When the download is completed, extract the 4gb patch.exe into the Oblivion root folder.
2. Double-click to run it.
3. Select the Oblivion.exe.

[Oblivion BSA Decompressor](https://www.nexusmods.com/oblivion/mods/49652)

Improves Oblivion performance. 

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Oblivion BSA Decompressor

**<span style="text-decoration:underline;">Installation Instructions</span>**



1. Extract the contents of the archive anywhere outside of the default Windows folders.
2. From the extracted archive, run Oblivion BSA Decompressor.exe.
3. Click **Decompress**, wait for the process to finish, then exit the program once finished.

[Oblivion Script Extender (xOBSE)](https://www.nexusmods.com/oblivion/mods/37952)

This essential resource greatly increases the modding capabilities of the game, allowing for several engine fixes and other complex mods that would normally not be possible. **This must be manually downloaded.**

**<span style="text-decoration:underline;">Installation Instructions</span>**



1. Extract the contents to the Oblivion folder(not Data).
1. It should look like this:

    

<p id="gdcalert21" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image21.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert22">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image21.png "image_tooltip")




### **Framerate Limiters**

Limiting the framerate has benefits such as improvements in frame pacing, as well as improved input latency by preventing the overworking of the GPU. This leads to an overall smoother experience.

**<span style="text-decoration:underline;">Option #1</span> -** RTSS

This is the recommended framerate limiter for most users.

Download RTSS [here](https://www.guru3d.com/download/rtss-rivatuner-statistics-server-download).

**<span style="text-decoration:underline;">Instructions</span>**



1. Open your System Tray and click on the RTSS icon to open it.
2. When the program window is opened, press the green **Add** button and select Oblivion.exe.
3. In **General properties** enable **Start With Windows**.
4. Set **Application Detection Level** to **Low**.
5. If your monitor supports VRR/FreeSync, set the **Framerate limit** at least to **3 frames below** the monitor’s refresh rate. If it doesn’t, set it at least **1 frame below **the monitor’s refresh rate.
6. Enter settings using the **Setup** button and enable **Passive Waiting**.

Your configuration should look similar to this:



<p id="gdcalert22" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image22.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert23">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image22.png "image_tooltip")


<p id="gdcalert23" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image23.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert24">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image23.png "image_tooltip")


**<span style="text-decoration:underline;">Option #2 </span>- **NVIDIA Control Panel

This is the recommended framerate limiter for NVIDIA users.

**<span style="text-decoration:underline;">Instructions</span>**



1. Right-click on the desktop.
2. Click **NVIDIA Control Panel**.
3. Go to **Manage 3D Settings** in the top left.
4. Click on the **Program Settings** tab in the right panel.
5. Select Oblivion.exe. If it's not present, add it manually.
6. Scroll down to **Max Frame Rate**, click it.
7. If your monitor supports VRR/Gsync, set the **Framerate limit** at least to **3 frames below** the monitor’s refresh rate. If it doesn’t, set it at least **1 frame below **the monitor’s refresh rate.
8. If you want to use VSync, enable it in the control panel.

Your configuration should look similar to this:



<p id="gdcalert24" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image24.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert25">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image24.png "image_tooltip")



## Mods


### **Core**

Create a marker by going to **File** on the top left of the Wrye Bash window, click **New Marker…**, then name the new marker “Core”.

[Engine Bug Fixes](https://www.nexusmods.com/oblivion/mods/47085)

Fixes several engine bugs.

[Blue’s Engine Fixes](https://www.nexusmods.com/oblivion/mods/52700)

Fixes a critical engine bug that resulted in memory corruption and crashes.

[AveSithis Engine Fixes](https://www.nexusmods.com/oblivion/mods/53911)

Corrects some more bugs in the game engine.

[OBL Mod Limit Fix](https://www.nexusmods.com/oblivion/mods/50066)

Fixes an engine bug that causes game breaking bugs the more esps/esms and BSAs that are in the data folder.

[Menu Alt-Tab Crash Fix](https://www.nexusmods.com/oblivion/mods/47954)

Prevents crashes while attempting to alt-tab.

[Weapon Drop Fix ](https://www.nexusmods.com/oblivion/mods/50223)

Corrects an issue with dropped weapons from enemies being easily lost.

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - SB_WeaponDropFix

**<span style="text-decoration:underline;">Installation Instructions</span>**



1. Apply the BCF.
2. In Sub-Packages select:
    * 00 Core
3. Install the mod.

[SkyBSA](https://www.nexusmods.com/oblivion/mods/49568)

Fixes major issues with how the game handles BSAs, forcing its behavior to allow loose files to automatically overwrite files within BSAs, regardless of timestamps.

[Let People Speak - Voice Management Overhaul System](https://www.nexusmods.com/oblivion/mods/53348)

Improves the efficiency of the voice management system, as well as a feature that accommodates mods that lack voice files.

[MenuQue - OBSE Plugin](https://www.nexusmods.com/Core/Libs/Common/Widgets/DownloadPopUp?id=1000004991&game_id=101)  

A hard requirement for the majority of UI mods.

**<span style="text-decoration:underline;">Installation Instructions</span>**



* Main Files - MenuQue **v16b**

**<span style="text-decoration:underline;">Installation Instructions</span>**



1. Apply the BCF.
2. Install the mod.

[AddActorValues](https://www.nexusmods.com/oblivion/mods/33248) 

Adds additional script functions.

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - AddActorValues

**<span style="text-decoration:underline;">Installation Instructions</span>**



1. Apply the BCF.
2. In Sub-Packages select:
    * Core 00
3. Install the mod.

[Blockhead](https://www.nexusmods.com/oblivion/mods/43752)

A powerful OBSE plugin that adds additional functions that allow for more complex changes to characters.

[Console Ignores Player?](https://www.nexusmods.com/oblivion/mods/52721)

Prevents potential issues when selecting your character while using the in-game console.

[Console Numpad Support (OBSE)?](https://www.nexusmods.com/oblivion/mods/49490/)

Allows the use of numpad keys while using the in-game console.

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Console Numpad Support

[Console Paste Support](https://www.nexusmods.com/oblivion/mods/49104)

Adds Ctrl+V as a hotkey to paste into the in-game console, as well as a few other helpful shortcuts.

[Faster Sleep Wait (OBSE)?](https://www.nexusmods.com/oblivion/mods/50517) 

Speeds up the sleep and wait menus.

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Faster Sleep Wait

[List Missing Mods On Load](https://www.nexusmods.com/oblivion/mods/52717)

Adds more detail on which mods are missing in a save.

**<span style="text-decoration:underline;">Download Instructions</span>**



* [?](https://www.nexusmods.com/oblivion/mods/52717)Main Files - List Missing Mods On Load

[No Inventory On Alt-Tab](https://www.nexusmods.com/oblivion/mods/52716)?

Helps make alt-tabbing more seamless.

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - No Inventory On Alt-Tab

[Unofficial Oblivion Patch](https://www.nexusmods.com/oblivion/mods/5296)

Fixes over 2,500 bugs (and 70,000 object placement errors).

**<span style="text-decoration:underline;">Installation Instructions</span>**



1. In Plugin Filter uncheck:
    * UOP Vampire Aging & Face Fix.esp (ORC already includes a fix).
2. Install the mod.

[Unofficial Shivering Isles Patch](https://www.nexusmods.com/oblivion/mods/10739)

Fixes a vast amount of bugs currently existing in the Shivering Isles expansion pack.

[Unofficial Oblivion DLC Patches](https://www.nexusmods.com/oblivion/mods/9969)

Fixes several bugs in the DLCs.

[Migck’s Miscellaneous fixes tweaks and ](https://www.nexusmods.com/oblivion/mods/42658)

[additions](https://www.nexusmods.com/oblivion/mods/42658)

Includes minor fixes and quality of life improvements.

[MigMaster Script Resources](https://www.nexusmods.com/oblivion/mods/45875/)

An addon to Migck Miscellaneous.

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - MigMaster

**<span style="text-decoration:underline;">Installation Instructions</span>**



1. In Plugin Filter uncheck:
    * SafeCloningFunction - Filter.esp
2. Install the mod.

[Simple Saves Plus \
](https://www.nexusmods.com/oblivion/mods/51122)Replaces the vanilla auto save and quick save features. **It is recommended to disable vanilla auto** saves** in-game.**

[ConsoleCommands](https://www.nexusmods.com/oblivion/mods/47637) 

Adds additional console and script commands to the game.

[RuntimeEditorIDs](https://www.nexusmods.com/oblivion/mods/40132) 

Allows the use of "player.addItem lockpick 100" in the console.

[MessageLogger](https://www.nexusmods.com/oblivion/mods/45870) 

A plugin for OBSE which logs error and warning messages from the game engine to help identify crashes.[Crash Logger](https://www.nexusmods.com/oblivion/mods/48503/)?

A DLL that logs raw crash data -- the instruction pointer, x86 register values, and an attempt at identifying the source DLL (and instruction pointer relative to its module base). 

[ConScribe](https://www.nexusmods.com/oblivion/mods/26510) 

Includes features such as console logging, and configuration exporting.

[Oblivion Display Tweaks](https://www.nexusmods.com/oblivion/mods/50348)

Includes a micro stutter tick fix, as well as a borderless windowed feature.

[Oblivion Display Tweaks Ini Preset](https://www.mediafire.com/file/jkwkit9mmuha7fv/Oblivion_Display_Tweaks-50348-1-3-1597794116.zip/file)

Disables a dysfunctional feature and enables borderless windowed mode.

[Oblivion Reloaded Combined(ORC)](https://www.nexusmods.com/oblivion/mods/51927) 

Greatly improves performance, improves general stability, prevents crashes when running high resolution texture packs, and provides enhanced shaders.

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - ORC193

[Oblivion Reloaded Combined Ini Preset](https://www.mediafire.com/file/bqlr5omwqdsltse/ORC_Custom_Configuration.7z/file)

Sets Oblivion Reloaded Combined to its most basic settings, ensuring that any intrusive features are disabled. It also improves the general visuals, while remaining faithful to the vanilla look.

[Whiteflame fix](https://www.nexusmods.com/oblivion/mods/50903?tab=files&file_id=1000029872) 

Fixes a bug for Oblivion Reloaded Combined(ORC) users due to changes to the fog system.

[FormID Finder](https://www.nexusmods.com/oblivion/mods/16704)

An extremely useful tool to troubleshoot in-game issues. Hold Alt + Right-Click on any object in game (incl. inventory and map markers) to identify the associated mod and access some relevant data.

**At this point, it is a good idea to activate all plugins (esps/esms), run LOOT, then launch the game and check if you can start a new game without issues.**

**<span style="text-decoration:underline;">LOOT Sorting Instructions</span>**



1. Launch LOOT via the LOOT icon by going to the bottom left of the Wrye Bash window.
2. Click on the **Update masterlist** button to receive the latest masterlist.
3. Click **Sort Plugins** whenever you make changes to your load order.
4. Click **Apply Sorted Load Order** after you have finished.

**<span style="text-decoration:underline;">Launching the game</span>**



1. At the bottom left of the Wrye Bash window, click on the Oblivion icon.
2. Start a new game.
3. Exit the game when you’re finished.


### **User Interface**

Create a new marker and name it “User Interface”.

[DarNified UI](https://www.nexusmods.com/oblivion/mods/48596)

Maintains the vanilla aesthetic, while properly porting the UI to the PC platform, and addressing various minor issues.

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - DarN BAIN wizard

**<span style="text-decoration:underline;">Installation Instructions</span>**



1. In the BAIN Installer Wizard:
    * All or Custom: select **Custom: All Selected**, click Next.
    * UI Elements: click Next.
    * Even more customizations!: select **Classic Inventory** and **Colored Local Map**, click Next.
    * Font Selection: select **Default**.
    * Font Size Selection: select **Large**, click Next.
    * Click Finish.
2. Go to your **Ini Edits** tab.
3. Click Apply on **DarN Font 1 - Default.ini**.
4. Click Apply on **DarN Fonts Large.ini**.

    

<p id="gdcalert25" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image25.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert26">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image25.png "image_tooltip")



[UHD Fonts for Darnified UI](https://www.nexusmods.com/oblivion/mods/49266)

Ultra High-Resolution fonts for Darnified UI, rebuilt using the original source TrueType fonts in 4x the resolution provided with Darnified UI.

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - HD Fonts for Darnified UI

[DarNifiedUI Config Addon](https://www.nexusmods.com/oblivion/mods/34792)

Allows you to save your in-game DarNified UI configuration settings.

[Colored World Map - Correct Cities](https://www.nexusmods.com/oblivion/mods/31809/)

Adds color to the Cyrodiil world map.

[nONatees colored Shivering Isles map](https://www.nexusmods.com/oblivion/mods/12797) 

Adds color to the SI world map.

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - nONatees_colored-SI-map-mod1.1.zip

**<span style="text-decoration:underline;">Installation Instructions</span>**



1. Apply the BCF.
2. In Sub-Packages select:
    * 01 Visually Divided
3. Install the mod.

[NorthernUIAway Hi-Res Local Map](https://www.nexusmods.com/oblivion/mods/48577)

NorthernUIAway will be used for the HD Local Map feature.

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - NorthernUIAway (Vanilla Style)

**<span style="text-decoration:underline;">Installation Instructions</span>**



1. Unpack the archive to a project.
2. Double-click the project.
3. Delete everything EXCEPT the **OBSE** folder.
4. Install the project.

    

<p id="gdcalert26" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image26.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert27">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image26.png "image_tooltip")



[NorthernUIAway Ini Preset](https://www.mediafire.com/file/e8pj1ml99nwkysj/NorthernUIAway_Custom_Configuratrion.7z/file)

Enables only what is needed for the high resolution local map.

[Pick Me - lockpicking interface retexture](https://www.nexusmods.com/oblivion/mods/48479)

Makes lockpicking look way better.

**<span style="text-decoration:underline;">Download Instructions</span>**



* Optional Files - Pick Me - BAIN

**<span style="text-decoration:underline;">Installation Instructions</span>**



1. In Sub-Packages select:
    * 00 Core
    * 01 Tumblers - Vanilla
    * 02 Wood Slab - Darker
    * 03 DarN UI
2. Install the mod.

[LINK Plus Plus](https://www.nexusmods.com/oblivion/mods/53352)

The Mod Configuration Menu for Oblivion. 

[Configuration Items Begone](https://www.nexusmods.com/oblivion/mods/53354)

Removes out of place inventory items added by mods like the UOP.

**<span style="text-decoration:underline;">Installation Instructions</span>**



* In the BAIN Installer Wizard:
    * Select both options.

[Extended UI](https://www.nexusmods.com/oblivion/mods/50135)

Provides several quality of life improvements to the user interface.

 \
[Display Stats](https://www.nexusmods.com/oblivion/mods/31855) \
Adds additional information to all items, such as a weight to value ratio.



* In Sub-Packages select:
    * 01 Darnified UI

[QZ Easy Menus Update](https://www.nexusmods.com/oblivion/mods/23404)

Adds additional shortcut key options.

[Map Marker Overhaul](https://www.nexusmods.com/oblivion/mods/26389)

Improves the visuals of the map markers, as well as adds new ones in appropriate locations.

**<span style="text-decoration:underline;">Download Instructions</span>**



1. Main Files - Map Marker Overhaul 3_9_3
2. Download the fixed **wizard.txt** [here](https://www.mediafire.com/file/9je949wijc1um73/Wizard.txt/file).

**<span style="text-decoration:underline;">Installation Instructions</span>**



1. Open the Map Marker Overhaul archive using 7zip.
    * Drag and drop the fixed **wizard.txt** into the **Map Marker Overhaul** archive.
    * Replace.
2. Install as normal.
3. In the BAIN Installer Wizard:
    * Select **Colored Map Icons**.
    * Select **Default Settings**.
4. Click Install.

[World Maps For All Worldspaces](https://www.nexusmods.com/oblivion/mods/48914)

Adds world maps and map markers to places that did not have them before..

[Quest Log Manager](https://www.nexusmods.com/oblivion/mods/32266)

Allows a means to hide several active quests to reduce clutter in the quest log.

**<span style="text-decoration:underline;">Installation Instructions</span>**



1. In Sub-Packages select:
    * 00 Core
    * Darnified UI
2. Install the mod.

[Progress Tracker - Quest Completionist's Companion](https://www.nexusmods.com/oblivion/mods/53328)

A quest completion tracker. Never miss a quest again.

[Enhanced Hotkeys](https://www.nexusmods.com/oblivion/mods/34735)

Adds additional hotkey slots.

[Stats Checker](https://www.nexusmods.com/oblivion/mods/44844)

Adds more information on player stats.

[Follower Status](https://www.nexusmods.com/oblivion/mods/53074)

Adds status bars to any NPC followers.

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Follower Status
* Optional Files - My Universal Fonts

[Better Enemy Health](https://www.nexusmods.com/oblivion/mods/53605)

Improves the enemy health UI.

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Better Enemy Health

[Colored Quests - Updated](https://www.nexusmods.com/oblivion/mods/49966)

Adds color to quest icons.

**<span style="text-decoration:underline;">Installation Instructions</span>**



1. Click Next on every selection.
2. Finish.

[Evandars Better Book Paper](https://www.nexusmods.com/oblivion/mods/26457)

Improves the visuals of the book paper.


### **Overhauls**

Create a new marker and name it “Overhauls”.

[Ascension - Immersive Vanilla "Overhaul"](https://www.nexusmods.com/oblivion/mods/50237)

Addresses the general core balance and scaling issues of Oblivion without making the gameplay excessively hardcore.

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Ascension
* Optional Files - Ascension - Bash Filter for Unofficial Patch

[Ascension - Better Clutter Icons](https://www.nexusmods.com/oblivion/mods/52127)

Improves the visuals of the clutter icons.

[Balanced Creature Stats?](https://www.nexusmods.com/oblivion/mods/49194)

Makes all creature levels static or enforces a maximum level for scaling with the player. Also balances and fixes creature stats logically across similar types, without altering the vanilla intention.

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Balanced Creature Stats
* Optional Files - Balanced Creature Stats - DLC Patch

[Balanced NPC Level Cap](https://www.nexusmods.com/oblivion/mods/50094)

Adds consistent level caps to 1,400+ NPCs from the base game and all DLCs.

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Balanced NPC Level Cap
* Optional Files - Balanced NPC Level Cap - DLC Patches

[Balanced Unleveled Rewards?](https://www.nexusmods.com/oblivion/mods/51050)

Removes level scaling from all leveled quest rewards and items, instead giving them balanced stats. No longer are items either brokenly overpowered or near useless.

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Balanced Unleveled Rewards - All-in-One

[Rebalanced and Unleveled Quest Gold Rewards - Mergeable](https://www.nexusmods.com/oblivion/mods/52823?tab=files&file_id=1000034041)

This rebalances and unlevels gold rewards for quests to make them less underwhelming and better fit quests circumstances rather than just simply unleveling all gold rewards, as in some cases the highest amount was still unfitting of the circumstances.	


### **Leveling**

Create a new marker and name it “Leveling”.

[Ultimate Leveling](https://www.nexusmods.com/oblivion/mods/49134)

Changes how the player character levels, removing the need for efficient leveling and making character development more diverse.

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Ultimate Leveling 1_9_5_2
* Optional Files - Patch

[Mercantile Experience Fix](https://www.nexusmods.com/oblivion/mods/50204)

Fixes a vanilla issue where you gain no experience selling or buying items.

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Mercantile Experience Fix - Buying and Selling

[Practical Training](https://www.nexusmods.com/oblivion/mods/50101)

Makes unused training sessions rollover into the next level, and training costs are now dependent on the trainer’s disposition and skill. 


### **Magic**

Create a new marker and name it "Magic".

[Av Latta Magicka - Oblivion Magic Overhaul](https://www.nexusmods.com/oblivion/mods/49096)

Adds all new spells and makes several improvements to the magic system.

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Av Latta Magicka

[Oblivion Magic Extender](https://www.nexusmods.com/oblivion/mods/31981) 

Extends the Oblivion magic system to make it more general and open to mod makers.

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - OBME v1_0

**<span style="text-decoration:underline;">Installation Instructions</span>**



1. Apply the BCF.
2. In Sub-Packages select:
    * 00 Core
3. Install the mod.

[FractionalMagicDamage ](https://www.nexusmods.com/oblivion/mods/37717)

Small obse plugin that prevents resistances & spell effectiveness from rounding magnitudes down to the nearest integer.

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - FractionalMagicDamage

**<span style="text-decoration:underline;">Installation Instructions</span>**



1. Apply the BCF.
2. Install the mod.

[De Rerum Dirennis - Alchemy Overhaul](https://www.nexusmods.com/oblivion/mods/53020)

Makes several improvements to Alchemy. It mainly adds more features to alchemy to make it more like how it operates in Skyrim and Morrowind. 

[Magic and Enchantment Effects Overhaul](https://www.nexusmods.com/oblivion/mods/48128)

Improves and adds diversity to the magic visual effects of the game.

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Magic and Enchantment Effects Overhaul V1.4

[Magic Visuals Overhaul](https://www.nexusmods.com/oblivion/mods/49300)

Adds particle effects to magic projectiles and enchanted bows/arrows.

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Magic Visuals Overhaul
* Main Files - Lightning Crash Fix
* Update Files - Detect Life Texture Fix

[Magic Visuals Overhaul - OBME Patch](https://www.nexusmods.com/oblivion/mods/49096?tab=files&file_id=1000024799) .

Patch to work with Oblivion Magic Extender.

[Magic Visuals Overhaul - Balls Remover (Patch)](https://www.nexusmods.com/oblivion/mods/53653)

Removes a jarring ball effect from healing spells.

[Better Summon Undead Effect](https://www.nexusmods.com/oblivion/mods/10418)

Improved summon undead effects.

[IMPROVED Fire Spell Animation](https://www.nexusmods.com/oblivion/mods/9058)

Improves fire spell animations.

[Convenient Open Spells](https://www.nexusmods.com/oblivion/mods/53163)

Looking at a locked object automatically selects the cheapest viable Open spell and switches back to the previously selected spell.

[Enchantment Cost Multiplier](https://www.nexusmods.com/oblivion/mods/50462)

Increases the uses of weapons enchantments.


### **Combat**

Create a new marker and name it "Combat".

[Combat Additions](https://www.nexusmods.com/oblivion/mods/49939)

Adds additional features and improvements to the combat, such as cleaving multiple opponents, charged shots, rolling, hitstop and more.

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Combat Additions BAIN

**<span style="text-decoration:underline;">Installation Instructions</span>**



1. In Sub-Packages select:
    * 00 Core
2. Install the mod.

[Idle Stagger and Recoil](https://www.nexusmods.com/oblivion/mods/44846) 

Adds a stagger and recoil animation when the NPC’s weapon is sheathed.

**<span style="text-decoration:underline;">Installation Instructions</span>**

In the BAIN Installer Wizard:



1. Select both **Vanilla creature Idle Recoil and Stagger files** and **Shivering Isles creature idle Recoil and Stagger files**.
2. Select **Yes** on the two following options.

[Better Blood](https://www.nexusmods.com/oblivion/mods/24448)

Improves the blood textures. 

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Better Blood v11 (ignore the update file)

**<span style="text-decoration:underline;">Installation Instructions</span>**



1. In Plugin Filter uncheck:
    * SkycaptainsBloodTime.esp
2. Install the mod.

[Better Blood skin decal fix](https://www.nexusmods.com/oblivion/mods/46344)

Fixes Blood decals.

[Normal Map for Better Blood](https://www.nexusmods.com/oblivion/mods/50547)

Further improves Better Blood with an improved normal map.

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Normal Map for Better Blood
* Main Files - ORC Better Blood Fix

[Darker Blood Splatter](https://www.nexusmods.com/oblivion/mods/53030)

Improves the blood splatter effect.

**<span style="text-decoration:underline;">Download Instructions</span>**



* Optional Files - Better Blood mod - Darker Blood Splatter

[Lich - Skeleton Hand-To-Hand Animations](https://www.nexusmods.com/oblivion/mods/48606)

Adds unarmed combat animations to liches.


### **Gameplay**

Create a new marker and name it "Gameplay".

[Cobl](https://www.nexusmods.com/oblivion/mods/21104) 

A resource and world enrichment mod. It adds ingredients, books, alchemical sorters, grinders, and more.

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Cobl

**<span style="text-decoration:underline;">Installation Instructions</span>**



* In the BAIN Installer Wizard:
1. Stable or Development: Select **Stable**.
2. Options: Select **Tweaks**.
3. Options: Select **Cobl Tweaks - SI**.
4. Miscellaneous: Do not choose anything.
5. Click Finish.

[Cobl for DLC Homes](https://www.nexusmods.com/oblivion/mods/53063)

Extends Cobl support to the DLC homes.

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Cobl for DLC Homes

[Cobl Unofficial Patch](https://www.nexusmods.com/oblivion/mods/51517)

Fixes bugs from the current version of Cobl.

**<span style="text-decoration:underline;">Installation Instructions</span>**



1. In Plugin Filter uncheck:
    * Salmo the Baker, Cobl.esp
    * Cobl - Buffet Plate and Hibernation Disabler.esp
2. Install the mod.

[KMM Higher-Res Welkynd Textures for Cobl Ayleid Meteoric Weapons](https://www.nexusmods.com/oblivion/mods/46187?tab=files&file_id=1000010862) 

Higher quality texture for Cobl Ayleid weapons.

[Pek COBL Book Jackets - Stand Alone](https://www.nexusmods.com/oblivion/mods/51953)

Book Jackets replacer for Cobl books.

[Pekkas COBL Books Jackets - Mergeable](https://www.nexusmods.com/oblivion/mods/52823?tab=files&file_id=1000034041) 

Bash Mergeable plugin for Cobl Book Jackets.

[Real tea](https://www.nexusmods.com/oblivion/mods/51830)

Replaces the textures of tea added by Cobl.

**<span style="text-decoration:underline;">Installation Instructions</span>**



1. In Sub-Packages select:
    * 00_Main
    * 01_CustomIcons
2. Install the mod.

[Crime has witnesses](https://www.nexusmods.com/oblivion/mods/22894)

Improves the crime system of Oblivion by allowing you to clear your bounty if you kill witnesses. 

[Crime Has Witnesses - Responsibility Tweak](https://www.nexusmods.com/oblivion/mods/33682)

Fixes an issue with companions being witnesses to your crimes.

[Sinderion’s Serendipity - Nirnroot Quest Reward](https://www.nexusmods.com/oblivion/mods/50129?tab=description)

Adds a useful perk upon completing Sinderion’s Serendipity. 

[SM DLC Plugin Refurbish](https://www.nexusmods.com/oblivion/mods/11474)

Delays DLCs in an immersive way.

**<span style="text-decoration:underline;">Installation Instructions</span>**



1. In Sub-Packages select:
    * 00 Full Lite Plugin
    * 02 Compatibility Plugins
2. Install the mod.

[SM DLC Plugin Refurbish - Voiced Addon BSA](https://www.nexusmods.com/oblivion/mods/52772?tab=files&file_id=1000033902) 

AI voice addon for SM DLC Plugin Refurbish. 

[No Annoying Conjurer Attack (Spell Tomes DLC fix)](https://www.nexusmods.com/oblivion/mods/47452)

Removes a conjurer always attacking the player on a new game.

[More Artifacts For Martin](https://www.nexusmods.com/oblivion/mods/49113)

Gives more artifact options to give to Martin In the Blood of the Daedra quest, such as DLC items and even items considered to be artifacts, like the Brush of Truepaint. 

[Vile Lair Vampirification - Mergeable](https://www.nexusmods.com/oblivion/mods/52823?tab=files&file_id=1000034036) 

Adds a quick option to become a vampire in The Vile Lair DLC.

[AI Voices for Vile Lair Vampirification](https://www.nexusmods.com/oblivion/mods/53010)

AI Voices for Vile Lair Vampirification.

**<span style="text-decoration:underline;">Installation Instructions</span>**



1. Apply the BCF.
2. In Sub-Packages select:
    * 00 Mergeable Version
3. Install the mod.

[Vile Lair DLC - Tweaks and Fixes](https://www.nexusmods.com/oblivion/mods/52213)

Enriches the Vile Lair DLC, such as changing the merchant inventory and buffing creatures. 

[Knights of the Nine - Improved Infamy System](https://www.nexusmods.com/oblivion/mods/50195)

Makes the Infamy System of KOTN more forgiving by overhauling how the Pilgrimage works. The Pilgrimage is no longer a reset of infamy, instead it keeps track of your current level of infamy and if it increases you can no longer use the Crusader’s Relics. 

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Knights Improved Infamy

[Knights - Fewer Condescending Comments](https://www.nexusmods.com/oblivion/mods/50154)

Less condescending comments for a Divine Crusader character with infamy.

[Guard Infamy Greeting Fix](https://www.nexusmods.com/oblivion/mods/52249)

Fixes a guard greeting issue caused by the UOP.

[Quest NPCs Run](https://www.nexusmods.com/oblivion/mods/49893?tab=files)

Previously walking quest NPCs now run.

**<span style="text-decoration:underline;">Download Instructions</span>**



* Optional Files - Quest NPCs Run - Reduced
* Optional Files - Quest NPCs Run - Filter Patch for Mods

**<span style="text-decoration:underline;">Installation Instructions</span>**



1. In Plugin Filter uncheck:
    * Quest NPCs Run - Emperor and Blades Run During Tutorial.esp
    * Quest NPCs Run - The Forlorn Watchman.esp
2. Install the mod.

[Alternative Beginnings](https://www.afkmods.com/index.php?/files/file/261-alternative-beginnings/)

An alternate start mod with various options to choose from.

**<span style="text-decoration:underline;">Download Instructions</span>**



1. In Plugin Filter uncheck:
    * Alternative Beginnings - Kvatch Intact.esp
2. Install the mod.

[Alternative Beginnings AI Voiced Addon](https://www.mediafire.com/file/ypqx3d4oqy18rzs/Alternative_Beginnings_-_VA.7z/file)

AI voice addon for Alternative Beginnings.


### **Equipment and Loot**

Create a new marker and name it "Equipment and Loot".

[Weapons Of Morrowind](https://www.nexusmods.com/oblivion/mods/45440)

Faithful recreations of Morrowind weapons added into the leveled lists.

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Weapons Of Morrowind

[Ascension - Weapons Of Morrowind Patch](https://www.nexusmods.com/oblivion/mods/50237?tab=description)

Ensures that weapon materials are carried over into the special loot lists.

**<span style="text-decoration:underline;">Download Instructions</span>**



* Miscellaneous Files - Ascension - Weapons of Morrowind Patch

[Jounk’s Polearms - Remixed and Remastered](https://www.nexusmods.com/oblivion/mods/53612)

Adds and visually overhauls Jounk's Polearms, as well as slightly revising its stats and leveled lists.

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Jounk’s Polearms - Remixed and Remastered 1.1

[Unique Artifacts for Unique People](https://www.nexusmods.com/oblivion/mods/49871)

Adds unique weapons to the notable characters in Oblivion and the DLC.

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Unique Artifacts for Unique People
* Optional Files - Unique Artifacts for Unique People - Patches

**<span style="text-decoration:underline;">Installation Instructions</span>**



1. In Sub-Packages select:
    * 02 Extended UI Weapon Backstory Descriptions
2. Install the mod.

[Colorful Clothing - Collection](https://www.nexusmods.com/oblivion/mods/53708)

Adds multiple new color versions of the middle and upperclass clothing sets into the game, as well as new gloves in multiple colors.

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Colorful Clothing - Collection - Seamless OCOv2
* Optional Files - Colorful Clothing - Collection Gloves Distribution

[AI Enhanced - Colorful Clothing Collection](https://www.nexusmods.com/oblivion/mods/53719)

Uses AI to improve the textures. 

**<span style="text-decoration:underline;">Download InstructionsDownload Instructions</span>**

[Travelling Equipment - Cloaks and Backpacks](https://www.nexusmods.com/oblivion/mods/50205)

Adds balanced cloaks and backpacks that can be worn together. The feather backpacks have a spell that the player automatically casts instead of a constant effect. 

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Travelling Equipment
* Optional - Travelling Equipment - Feather Backpacks

[A Rainbow of Treasures - New Gems and Gem Dust](https://www.nexusmods.com/oblivion/mods/51065)

Adds 7 new gems to the game and the ability to grind all 12 gems as well as pearls if you have any mortar & pestle in inventory. Right click on any gem to start grinding.

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files A Rainbow of Treasures - New Gems and Gem Dust

[Better Letters](https://www.nexusmods.com/oblivion/mods/5392)

Changes every generic letters, notes, recipes, instructions and the such with unique ones.

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Better Letters Version 1_3


### **Quests**

Create a new marker and name it "Quests".

[The Lost Spires](https://web.archive.org/web/20210225110856/http://www.lostspires.com/pages/downloads.htm)

Uncover the mysteries of ancient Tamriel as only one can, through the Archeology Guild. Scale the guild's ranks, and explore new, exotic locales to unravel a plot of sinister deceit, betrayal.

[The Lost Spires - Cleaned Up Scribe Store Ruins](https://www.nexusmods.com/oblivion/mods/50146)

The ruins aren’t as ruined now. 

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - The Lost Spires - Cleaned Up Scribe

[The Lost Spires - Tweaks and Enhancements](https://www.nexusmods.com/oblivion/mods/51037/)

Fixes bugs and enhances the overall experience of The Lost Spires.

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - LS - Assorted Fixes
* Main Files - LS - Optional Diary Narration
* Main Files - LS - Rodon Dakkon Dialogue Tweak
* Main Files - LS - Warlock Torch Fix

[Lost Spires Archaeology Guild Robe fix](https://www.nexusmods.com/oblivion/mods/49343)

Fixes normals from the Archaeology Guild Robe.

[Strotis Ayleid Clutter](https://www.nexusmods.com/oblivion/mods/41558)

Used as a resource for The Lost Spires - Enhanced Tomb.

**<span style="text-decoration:underline;">Installation Instructions</span>**



1. In Plugin Filter uncheck:
    * strotisAyleidClutter.esp
2. Install the mod.

[Strotis Ayleid Furniture](https://www.nexusmods.com/oblivion/mods/41670)

Used as a resource for The Lost Spires - Enhanced Tomb.

**<span style="text-decoration:underline;">Installation Instructions</span>**



1. In Plugin Filter uncheck:
    * strotisAyleidFurniture.esp
2. Install the mod.

[The Lost Spires - Enhanced Tomb](https://www.nexusmods.com/oblivion/mods/51414)

Enhances a certain tomb found during The Lost Spires' main quest by adding additional artifacts and items.

[The Ayleid Steps](https://www.nexusmods.com/oblivion/mods/16316)

Discover the ancient Ayleid teleporting network of Step stones, find out how to activate it, and then use the Steps to discover a new way of traveling around Cyrodiil, and search for new unknown Ayleid sites.

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - The Ayleid Steps

[The Ayleid Steps - Voiced Addon BSA](https://www.nexusmods.com/oblivion/mods/52772?tab=files&file_id=1000035348) 

AI voice addon using the vanilla voices. 

[The Ayleid Steps - The Guardian’s Atlas](https://www.nexusmods.com/oblivion/mods/51923)

Adds the Guardian's Atlas to Fefandor, reading it gives you quest markers to all the unexplored lost locations.

[The Ayleid Steps - Compatibility Patches](https://www.nexusmods.com/oblivion/mods/47142)

AIO compatibility patch for The Ayleid Steps.

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - The Ayleid Steps - Compatibility Patches

[The Well of Minlorada](https://www.nexusmods.com/oblivion/mods/38816)

Discover the secrets of the long-lost Ayleid city of Minlorada, and of the Great Ayleid Well legends speak of.

[AI Voice Addon for The Well of Minlorada](https://www.nexusmods.com/oblivion/mods/53401)

AI voice addon, using vanilla voices.

[Quest INIs for Progress Tracker](https://www.nexusmods.com/oblivion/mods/53886)

Patch for quest mods like The Lost Spires, Heart of the Dead, The Well of Minlorada, Hackdirt: The Deep Ones, Better Forts, and Bounty Quests 3.0.

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Progress Tracker INIs

[Progress Tracker Ini Mod Compendium](https://www.nexusmods.com/oblivion/mods/53942)

An additional patch for even more quest mods.

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Ini Mod Compendium


### **Locations**

Create a new marker and name it "Locations".

<span style="text-decoration:underline;">Location Addons</span>

[The Black Mirror - A Necromancer Shop](https://www.nexusmods.com/oblivion/mods/51499)

Adds a Necromancer store underneath the Imperial City.

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - The Black Mirror - A Necromancer Shop

[The Black Mirror - Voiced Addon Loose](https://www.nexusmods.com/oblivion/mods/52772?tab=files&file_id=1000035313) 

Voices The Black Mirror using AI. 

[Imperial City Canal Overhaul](https://www.nexusmods.com/oblivion/mods/49868)

Adds an interconnected network of canals around the Imperial City.

[Ice’s Waterfront Tunnel](https://www.nexusmods.com/oblivion/mods/51749)

Adds a Waterfront tunnel that connects to the Temple District.

[Bruma Guild Reconstructed](https://www.afkmods.com/index.php?/files/file/264-bruma-guild-reconstructed/)

Adds an option for the Bruma Mages Guild to be rebuilt.

[Bruma Guild Reconstructed AI Voiced Addon](https://www.mediafire.com/file/ogtq5irv6ekabxo/BrumaGuildReconstructed_-_Voice_Addon.zip/file)

AI voice addon for Bruma Guild Reconstructed.

[Navigable Niben River](https://www.nexusmods.com/oblivion/mods/53578)

Adds gatehouses with drawbridges at Leyawiin and Fort Redman and connects and deepens the Niben to enable ship travel.

[Gweden Farm Repopulated](https://www.nexusmods.com/oblivion/mods/52989/)

Repopulates Gweden Farm after completing its quest.

<span style="text-decoration:underline;">Arthmoor's Villages</span>

[Feldscar](https://www.afkmods.com/index.php?/files/file/249-feldscar/)

A small Nordic village in the lower Jerall Mountains, north of the Frostcrag area.

[Feldscar AI Voiced Addon](https://www.mediafire.com/file/ffsy9na6xx2rtba/Feldscar_-_VA.7z/file)

AI voice addon for Feldscar.

[Frostcrag Village](https://www.afkmods.com/index.php?/files/file/250-frostcrag-village/)

Frostcrag Village is a small Nordic settlement that sits in the shadow of Frostcrag Spire.

[Frostcrag Village AI Voiced Addon](https://www.mediafire.com/file/cvsdi6bja9gvi4t/Frostcrag_Village_-_VA.7z/file)

AI voice addon for Frostcrag Village.

[Gottshaw Village](https://www.afkmods.com/index.php?/files/file/251-gottshaw-village/)

Gottshaw Village is an expansion on the Gottshaw Inn. Has a quest. 

[Gottshaw Village AI Voiced Addon](https://www.mediafire.com/file/ko2oz4q3zxtqird/Gottshaw_Village_-_VA.7z/file)

AI voice addon for Gottshaw Village. 

[Molapi](https://www.afkmods.com/index.php?/files/file/252-molapi/)

Molapi is a small village built on the island just north of the city of Leyawiin. Also has a quest. 

[Molapi AI Voiced Addon](https://www.mediafire.com/file/9ox0y79v4742bxv/Molapi_-_VA.7z/file)

AI voice addon for Molapi.

[Reedstand](https://www.afkmods.com/index.php?/files/file/255-reedstand/)

Reedstand is a small Argonian settlement in Blackwood just to the north of Reedstand Cave.

[Reedstand AI Voice Addon](https://www.mediafire.com/file/xv1jon6va21br2l/Reedstand_-_VA.7z/file)

AI voice addon for Reedstand.

[Urasek](https://www.afkmods.com/index.php?/files/file/257-urasek/)

A mining support town situated alongside Fort Urasek.

[Urasek AI Voice Addon](https://www.mediafire.com/file/ed7bubxp6ll5j63/Urasek_VA.7z/file)

AI voice addon for Urasek.

[Vergayun](https://www.afkmods.com/index.php?/files/file/258-vergayun/)

It's the small fishing village with the funny name!

[Vergayun AI Voice addon](https://www.mediafire.com/file/z6fed24j8zsm2aa/Vergayun_-_VA.7z/file)

AI voice addon for Vergayun.

<span style="text-decoration:underline;">Location Overhauls</span>

[Landmarks Of Cyrodiil](https://www.nexusmods.com/oblivion/mods/49997?tab=files&file_id=1000030108)

Adds several points of interest and places to explore.

[Landmarks of Cyrodiil Compatibility Fix](https://www.nexusmods.com/oblivion/mods/50471)

Patches landscape issues with certain Unique Landscapes modules.

[Unique Landscapes - Arrius Creek](https://www.nexusmods.com/oblivion/mods/16818)

Overhaul of north and southeast Cheydinhal that adds a creek type landscape.

[Unique Landscapes - Imperial Isle](https://www.nexusmods.com/oblivion/mods/9531)

Overhauls the Imperial Isle.

[Unique Landscapes - Jerall Glacier](https://www.nexusmods.com/oblivion/mods/40731)

Overhaul that adds a glacier around the Jerall mountains.

[Unique Landscapes - Snowdale](https://www.nexusmods.com/oblivion/mods/33125)

Overhauls the Jerall mountains around Bruma.

[Unique Landscapes - The Heath](https://www.nexusmods.com/oblivion/mods/11165)

Overhaul that adds a wetland type landscape to Kvatch County.

[Unique Landscapes Compatibility Patches](https://www.nexusmods.com/oblivion/mods/13834) 

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - UL Compatibility Patches Compilation WIZBAIN v14


## Graphics


#### Character Visuals

Create a new marker and name it "Character Visuals".

[Oblivion Character Overhaul version 2](https://www.nexusmods.com/oblivion/mods/44676)

Makes characters look much better. 

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Oblivion Character Overhaul v203

[Oblivion Character Overhaul - Advanced Edition](https://www.nexusmods.com/oblivion/mods/52010)

Blends vanilla hair with the new models. 

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - OCOv2 - Advanced Edition (Vanilla Hairstyles)

[AI Enhanced - Oblivion Character Overhaul version 2](https://www.nexusmods.com/oblivion/mods/52135)

Makes the faces look even BETTER. 

**<span style="text-decoration:underline;">Download Instructions</span>**



1. Unpack the mod into a project.
2. Delete the textures\characters\nuska\**hair** folder.
3. Install the project.

[Ragdolls for Oblivion](https://www.nexusmods.com/oblivion/mods/51844)

Allows NPCs to have silly ragdolls when killed/knocked out. 

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Ragdolls - Main File
* Optional Files - Wraith Ragdoll - Optional File

[Ragdolls for Oblivion - Filter Patch for Mods](https://www.nexusmods.com/oblivion/mods/52804)

Allows the bashed patch to dynamically patch ragdolls to NPCs. 

**<span style="text-decoration:underline;">Download Instructions</span>**



* Ragdolls for Oblivion - Filter Patch for Mods

[Light compatible Skeleton](https://www.nexusmods.com/oblivion/mods/49080) 

A skeleton used for animations. 

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - SkeletonV5

**<span style="text-decoration:underline;">Installation Instructions</span>**



1. Apply the BCF.
2. Install the mod.

[Seamless - OCOv2](https://www.nexusmods.com/oblivion/mods/45859)

Makes it so that neck seams are nearly invisible. 

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - SR- OCOv2 44676

**<span style="text-decoration:underline;">Installation Instructions</span>**



1. In Plugin Filter uncheck:
    * EVE_ShiveringIslesEasterEggs.esp
2. Install the mod.

[Hand and arms fixes for clothes from junkacc11 Seamless mods and wtftesnexus" BBB for EVE Stock](https://www.nexusmods.com/oblivion/mods/51853)

Fixes arms and hands. 

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main File - 01 Seamless OCOv2 n HGEC Female clothes fixes

[New Brows for OCO v2](https://www.nexusmods.com/oblivion/mods/48199)

Better, detailed brows. 

[Detailed Mouth for OCOv2](https://www.nexusmods.com/oblivion/mods/47463/)

Also overhauls the mouth.

[Oblivion Texture Overhaul - Realistic Mouth ( Teeth plus ) ](https://www.nexusmods.com/oblivion/mods/51720)

Enhances teeth.

[better teeth](https://www.nexusmods.com/oblivion/mods/47522)

Further enhances teeth. Cyrodiil has a really good dentist! 

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - better teeth vanilla npc version

[New Eyes for OCO v2](https://www.nexusmods.com/oblivion/mods/46995)

Adds in more eyes for races. 

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - New Eyes for OCOv2

[Better OCOv2 Agemaps](https://www.nexusmods.com/oblivion/mods/53487)

Makes agemaps less extreme. 

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Better OCOv2 Agemaps

[OCOv2 Male Beard](https://www.nexusmods.com/oblivion/mods/48816)

Adds badass male beards. 

[OCOv2 Male Beard Extended](https://www.nexusmods.com/oblivion/mods/52238)

Beards, but even more awesome. 

[Distinct Nord Stubbles for OCOv2](https://www.nexusmods.com/oblivion/mods/50906)

Gives male nords facial hair even if they don’t have a beard. 

[Lifelike Eye Normalmaps](https://www.nexusmods.com/oblivion/mods/47467)

Enhances the reflection in eyes.

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Lifelike Eyes OCOv2 
* Optional Files - Extra detailed OCOv2 human eyes 

[Warpaints scars and face markings for OCO2](https://www.nexusmods.com/oblivion/mods/51511)

Adds additional face paint markings for character creation.

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Main File
* Main Files - Argonian and Khajiit patch
* Optional Files - Argonians patch for Seamless mod

[VKVII Oblivion Skin Khajiit](https://www.moddb.com/mods/vkvii-oblivion-skin-khajiit/downloads)

Like OCO but for Khajiit bodies. 

**<span style="text-decoration:underline;">Download Instructions</span>**



* Files - VKVII Oblivion Skin Khajiit - No New Hands

**Patch for OCOv2 is in the Late Loaders section.**

[VKVII Oblivion Skin Argonian](https://www.moddb.com/mods/vkvii-oblivion-skin-argonian/downloads)

Makes lizards look legendary. 

**<span style="text-decoration:underline;">Download Instructions</span>**



* Files - VKVII Oblivion Skin Argonian - No New Hands

**Patch for OCOv2 is in the Late Loaders section.**

[OCO 2 glowing nostrils fix](https://www.nexusmods.com/oblivion/mods/46342)

Essential fix for nostrils.

[Improved NPC Faces for OCOv2](https://www.nexusmods.com/oblivion/mods/51971)

Puts NPC faces more in line with vanilla. 

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Improved NPC Faces for OCOv2
* Optional Files - Better Baurus for OCOv2 (Younger Version)
* Optional Files - Better Martin for Oblivion Character Overhaul v2 (Vanilla Hair Version)
* Optional Files - Better Uriel Septim for OCOv2 (Vanilla Hair)
* Optional Files - More Bosmer-Esque Mankar Camoran

[Oblivion Character Overhaul v2 - DLC Addon](https://www.nexusmods.com/oblivion/mods/52405)

Extends OCO to the DLC NPCs. 

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Oblivion Character Overhaul v2 DLC Addon".

[Unused OCOv2 Eyes and DLC Characters Incorporated](https://www.nexusmods.com/oblivion/mods/52052)

Adds the unused eyes to NPCs. 

[OCO Face Updater - Fixes Normal and Age Maps on Load](https://www.nexusmods.com/oblivion/mods/53005)

Dynamically updates faces.

[OCOv2 - Filter Patch for Mods](https://www.nexusmods.com/oblivion/mods/51379)

A grand filter patch so that the bashed patch takes OCOv2 into account. 

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - OCOv2 - Filter Patch for Mods


#### Base Visuals

Create a new marker and name it "Base Visuals".

[Oblivion Upscaled Textures BSA](https://www.nexusmods.com/oblivion/mods/52977)

Uses AI to upscale textures. 

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Oblivion Upscaled Textures BSA - Part 1
* Main Files - Oblivion Upscaled Textures BSA - Part 2
* Main Files - Oblivion Upscaled Textures BSA - Part 3
* Main Files - Oblivion Upscaled Textures BSA - Part 4

[Bomret’s Texture Pack for Shivering Isles BSA](https://www.nexusmods.com/oblivion/mods/52977?tab=files&file_id=1000035522) 

The only Shivering Isles Texture Pack worth using. 

[Mesh Improvement Project](https://www.nexusmods.com/oblivion/mods/44501)

Increases detail with meshes. 

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Mesh Improvement Project

**<span style="text-decoration:underline;">Installation Instructions</span>**



1. In Sub-Packages select:
    * 00 Core
    * 10 Optional - IC Sign Textures
2. Install the mod.

[Mesh Improvement Project - Tweaks and Fixes](https://www.nexusmods.com/oblivion/mods/53031?tab=files&file_id=1000034899) 

Fix for MIP.

[Mesh Improvement Project - Glowing Signs Fixed](https://www.nexusmods.com/oblivion/mods/53169)

Another fix for MIP. 

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Mesh Improvement Project - Glow Fixes and UV Edits

[Improved Doors and Flora](https://www.nexusmods.com/oblivion/mods/8298)

Makes doors look sweet. 

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Improved Doors and Flora
* Main Files - IDFUpdate

[Improved Trees and Flora](https://www.nexusmods.com/oblivion/mods/8500)

Improves flora. 

[Improved Trees and Flora 2](https://www.nexusmods.com/oblivion/mods/11891)

Makes bark look sweet. 

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Improved Trees and Flora 2
* Main Files - ITF2Update
* Update Files - ITFBark2012

[Oblivion 2020 Retexture Project](https://www.nexusmods.com/oblivion/mods/49933)

A collection of pre-AI retextures. 

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - 2020 Retexture Project - Caves
* Main Files - 2020 Retexture Project - Farmhouses (AWLS)
* Main Files - 2020 Retexture Project - Landscapes and Rocks


#### Flora and Food Visuals

Create a new marker and name it "Flora and Food Visuals".

[Daydream - Grass Texture Atlas](https://www.nexusmods.com/oblivion/mods/49346) 

Improves grass atlas, which is the list of textures that makes up the various grass objects. 

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Daydream Grass Texture Atlas

[Coop's Daydream Grass Texture Edit no red poppys and let there be flowers](https://www.nexusmods.com/oblivion/mods/53430)

Tweaks Daydream to work better with the next mod. 

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Coop's Daydream Edit Type C

[Let there be Flowers](https://www.nexusmods.com/oblivion/mods/49616)

Adds more flowers to grass. 

[Let There Be Flowers Texture Tweak](https://www.nexusmods.com/oblivion/mods/52363)

Makes those flowers look better. 

**<span style="text-decoration:underline;">Installation Instructions</span>**



1. In Sub-Packages select:
    * Standard
2. Install the mod.

[Tree Bark HD Reduced](https://www.nexusmods.com/oblivion/mods/43504)

A downscale (yes you read that right) of an extremely bloated bark texture. 

[Improved Fruits Vegetables and Meats](https://www.nexusmods.com/oblivion/mods/10487)

We got the meats. 

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Improved Fruits Vegetables and Meats
* Update Files - IFVMUpdate

[TD_Premium Meat](https://www.mediafire.com/file/q0xp76akvh7r5h5/TD_Premium_Meat_BAIN.7z/file) 

The first mod from a Russian modding site.

**<span style="text-decoration:underline;">Installation Instructions</span>**



1. In Sub-Packages select:
    * 00 Core

[Harvest Flora](https://www.nexusmods.com/oblivion/mods/2037) 

Makes the model of plants reflect if they’ve been harvested or not, like in Fallout 3/NV, Skyrim, etc.

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Harvest Flora v3_0_1

[Basic harvest](https://www.nexusmods.com/oblivion/mods/51833)

Enhances harvest functions for mod-added plants. 

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - BasicHarvest_FilterPatch_v1.4

**<span style="text-decoration:underline;">Installation Instructions</span>**



1. In Sub-Packages select:
    * 00_CoreFilterPatch
2. Install the mod.

[Unofficial Oblivion Tree Patch](https://www.nexusmods.com/oblivion/mods/53079)

Patches trees for performance. 

[Unofficial Shivering Isles Tree Patch](https://www.nexusmods.com/oblivion/mods/53101)

Patches trees for SI. 

[TreeOPT](https://www.nexusmods.com/oblivion/mods/49150)

Optimizes the mushroom trees. 

[TD_Beautiful garden - flora replacer for TES IV: Oblivion](https://www.mediafire.com/file/qdifhs9q1og9xnv/TD_Beautiful_garden_2K_BAIN.7z/file) 

Greatly increases the detail of flora.

**<span style="text-decoration:underline;">Installation Instructions</span>**



* In Sub-Packages select:
    * 00 Core

[TD Beautiful Garden - Harvest Flora Add-On](https://www.nexusmods.com/oblivion/mods/53031?tab=files&file_id=1000034898)  

Patches BG to work with HF. 

[TD Mushroom High-poly Replacer](https://www.mediafire.com/file/yn44jc16tn773c6/TD_Mushroom_High-poly_Replacer_-_Harvest_Flora_BAIN.7z/file) 

The Mushroom Kingdom. 

[Little Baron Flower Pot Makeover - patched and adjusted](https://www.nexusmods.com/oblivion/mods/50792)

Don’t worry, it’s legal in Cyrodiil. 

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Little Baron Flower Pot Makeover - patched and adjusted

[EGO - Nirnroot Retexture](https://www.nexusmods.com/oblivion/mods/53574)

Makes nirnroots easier to spot. 

[Garlic - A Garlic Replacer](https://www.nexusmods.com/oblivion/mods/52670)

Most noticeable in Skingrad. 

[Sweet Rolls - A Sweet Roll Replacer](https://www.nexusmods.com/oblivion/mods/52645)

It’s pretty sweet. 


#### Weather and Atmosphere Visuals

Create a new marker and name it "Weather and Atmosphere Visuals".

[Aurora in Motion Everywhere](https://www.nexusmods.com/oblivion/mods/48893)

Adds the Northern Lights to certain weathers. 

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Aurora in Motion Everywhere - Original Version

[Better Rainbows](https://www.nexusmods.com/oblivion/mods/36566)

Not double. 

[Falling Leaves](https://www.nexusmods.com/oblivion/mods/44257) 

Adds falling leaves like in the Rift in Skyrim. 

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Falling Leaves V1_0 BAIN

**<span style="text-decoration:underline;">Installation Instructions</span>**



1. In Sub-Packages select:
    * 00 - Core Files
2. Install the mod.

[High Quality Snowflakes](https://www.nexusmods.com/oblivion/mods/49898?tab=files&file_id=1000033858) 

Makes the snowflakes more detailed. 

[moonreplacer](https://www.nexusmods.com/oblivion/mods/46924)

A beautiful replacer for the moon. 

[Improved Sky Textures](https://www.nexusmods.com/oblivion/mods/7694)

Some truly gorgeous sky textures. 

[Oblivion NightSkies Overhaul](https://www.nexusmods.com/oblivion/mods/50121)

The night skies are breathtaking with this. 

**<span style="text-decoration:underline;">Download Instructions</span>**

Main Files - Oblivion NightSkies Overhaul

**<span style="text-decoration:underline;">Installation Instructions</span>**



1. In Sub-Packages select:
    * 01 - MESHES - Nebula 1 & 2 + Overlay
    * 02 - TEXTURES - Stars - 2k
    * 03 - TEXTURES - Nebula 1 - Version 1 - 2k
    * 04 - TEXTURES - Nebula 2 - Version 1 (Vanilla 1k)
    * 05 - OVERLAY - Aurora - 2k
2. Install the mod.

[Realistic HD Night Sky](https://www.nexusmods.com/oblivion/mods/44951/)

Makes the night sky look closer to ours. 

[Improved LightBeam](https://www.nexusmods.com/oblivion/mods/45685) 

Makes dungeon godrays better. 

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Improved LightBeam

**<span style="text-decoration:underline;">Installation Instructions</span>**



1. Apply the BCF.
2. In Sub-Packages select:
    * 00 Core
3. Install the mod.

[Atmos4096](https://www.nexusmods.com/oblivion/mods/49978)

Adds 4k textures for various effects like fog and dust. 

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Atmos4096
* Main Files - DustCloud01-4096
* Main Files - GasClouds4096


#### Architecture and Landscape Visuals

Create a new marker and name it "Architecture and Landscape Visuals".

[Arena Of Awe - Retexture](https://www.nexusmods.com/oblivion/mods/53052)

Awwwww yiss. 

[Statues HD](https://www.nexusmods.com/oblivion/mods/43104) 

Not PSBoss but it’ll do. 

[VKVII Oblivion Imperial City](https://www.moddb.com/mods/vkvii-oblivion-imperial-city)

The most detailed IC Texture Pack worth using. 

**<span style="text-decoration:underline;">Download Instructions</span>**



* Files - VKVII Oblivion Imperial City (Medium Size)

[Gecko’s Fort Interior Textures](https://www.nexusmods.com/oblivion/mods/45996/)

Overhauls the textures of forts. 

[Gecko’s Imperial Dungeon Textures - 2K Parallax](https://www.nexusmods.com/oblivion/mods/46864/)

Makes the imperial dungeon tile set have detailed parallax textures.

[Gecko’s Ayleid Ruins Textures V2 - Parallax](https://www.nexusmods.com/oblivion/mods/46579/)

The only Ayleid Ruins textures worth using. 

[Ayleid Ruins Fixed - Mesh Replacer and Modder Resource](https://www.nexusmods.com/oblivion/mods/50875)

Adds further detail to Ayleid meshes. 

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Ayleid Ruins Fixed - Mesh Replacer and Modder Resource

[Ayleid Ruin Meshes Fixed for Gecko’s Parallax Ayleid Ruins](https://www.nexusmods.com/oblivion/mods/52667)

Patches the two to work together. 

[Ayleid and some Glow Maps Minor Fix](https://www.nexusmods.com/oblivion/mods/53411?tab=videos)

Adds a minor fix related to glow maps. 

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Ayleid Glow Fix
* Main Files - Improved glow maps for Oblivion Realm

[Farm fence retexture and UV maps](https://www.nexusmods.com/oblivion/mods/47355)

Ram Ranch. 

[Farm Fence Retexture Alternative Texture Options](https://www.nexusmods.com/oblivion/mods/53346)

Really rocks. 

**<span style="text-decoration:underline;">Installation Instructions</span>**



* In the FOMOD Installer:
    * Select **Grey**
    * Select **GreyNoHoles**
    * Finish. 

[Cheery Cheydinhal - Retexture](https://www.nexusmods.com/oblivion/mods/53049)

Makes Cheydinhal less bleak. 


    [Bruma retexture](https://www.nexusmods.com/oblivion/mods/44677)

Bruma… that’s where men are women. 

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Bruma Retexture 1.5 - 2K

[Leyawiin Woodland](https://www.nexusmods.com/oblivion/mods/46628)

Gives Leyawiin a more high fantasy vibe. 

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Leyawiin Woodland 2k

[Improved Chorrol](https://www.nexusmods.com/oblivion/mods/9500)

Adds more detail in a very vanilla friendly way. 

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Improved Chorrol
* Main Files - ChorrolUpdate
* Optional Files - Chorrol2011

[Leyawiin Woodland floor fix](https://www.nexusmods.com/oblivion/mods/48759) 

Fixes a floor. 

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Leyawiin Woodland floor fix

[Leyawiin Woodland 2k - Better Columns](https://www.nexusmods.com/oblivion/mods/52833?tab=files&file_id=1000035401) 

It was an inside job. 

[TD_aesthetics of garbage](https://www.mediafire.com/file/wbr17cwxkrcag06/TD_aesthetics_BAIN.7z/file) 

Not a garbage mod.

**<span style="text-decoration:underline;">Installation Instructions</span>**



* In Sub-Packages select:
    * 00 Core

[TD_Unique_Skingrad](https://www.mediafire.com/file/ue449qqfns2j48f/TD_Unique_Skingrad-BAIN.7z/file) 

Makes Skingrad look gothic.

**<span style="text-decoration:underline;">Installation Instructions</span>**



* In Sub-Packages select:
    * 00 Core

[VKVII Oblivion Anvil](https://www.moddb.com/mods/vkvii-oblivion-anvil)

Makes Anvil look like a rustic, washed out coastal town. 

**<span style="text-decoration:underline;">Download Instructions</span>**



* Files - VKVII Oblivion Anvil (Medium Low Size)

[Nice Ice a.k.a. The Hills Have Ice](https://www.nexusmods.com/oblivion/mods/45342)

I have no ice and I must scream. 

[better snow 2k](https://www.nexusmods.com/oblivion/mods/50157) 

Snow. Snow! Can’t have enough of it. 

[Oblivion Realm HD](https://www.nexusmods.com/oblivion/mods/43100) 

Changes all exterior textures in the Oblivion Realms. 

[Oblivion Caves retexture](https://www.nexusmods.com/oblivion/mods/47407)

Retextures the caves. 

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Oblivion Caves retexture 2K

[Oblivion Caves retexture 2K Enhanced](https://www.nexusmods.com/oblivion/mods/53031?tab=files&file_id=1000034892) 

E N H A N C E. 

[Strange Caves - A 2K Cave Retexture](https://www.nexusmods.com/oblivion/mods/49736)

Cave Johnson here. 

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - StrangeCaves2K
* Update Files - StrangeCaves_DirtNormalMap

[HiRez Architecture- Daedric Shrines](https://www.nexusmods.com/oblivion/mods/43442)

Adds further detail to shrines. 

[Ruined Ruins](https://www.nexusmods.com/oblivion/mods/44697)

The best fort ruin pack there is. 

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Completely Ruined Ruins v03
* Main Files - Completely Ruined Ruins v03 skirting

[AI Enhanced - Ruined Ruins](https://www.nexusmods.com/oblivion/mods/52851)

Actually this one is the best. 

[VKVII Oblivion Cathedrals](https://www.moddb.com/mods/vkvii-oblivion-cathedrals)

Enhances the detail of Cyrodiilic cathedrals - not ones from the planes of Oblivion. 

**<span style="text-decoration:underline;">Download Instructions</span>**



* Files - VKVII Oblivion Cathedrals (Medium Size)

[Animated Window Lighting System and Chimneys - AWLS](https://www.nexusmods.com/oblivion/mods/19628)

Adds dynamic lights to windows and smoke to chimneys. 

**<span style="text-decoration:underline;">Installation Instructions</span>**



* In the BAIN Installer Wizard:
    * Plugin: select **Advanced Smoking Chimneys**
    * Qarls Textures Pack: select **No** 
    * RAEVWD: select **No**
    * Bomrets Texture Pack: select **Yes**
    * Window Selection: select **No, pick for me**

[Snowy Roofs in Bruma for AWLS](https://www.nexusmods.com/oblivion/mods/49933?tab=files)

Makes the new roof mesh have snow. 

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - 2020 Retexture Project - Snowy Roofs in Bruma for AWLS

[Kvatch HD](https://www.nexusmods.com/oblivion/mods/45670)

Heroic. 

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Kvatch HD 
* Update Files - Kvatch HD 1.1 

[Khettienna’s Mini-Mods](https://www.nexusmods.com/oblivion/mods/46187) 

A bunch of retextures for tiny clutter items. 

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Khettienna’s Mini Mods Complete Bundle

**<span style="text-decoration:underline;">Installation Instructions</span>**



1. In Sub-Packages select:
    * KMM Chorrol Mages Guild UV Tweaks v1.0
    * KMM Crucible Sewage Retex v2.0
    * KMM Garridan’s Tears Retex v1.0
    * KMM Hourglass Sand Retex v1.0
    * KMM Leyawiin Woodland Stonewall Normalmap Fix v1.0
    * KMM Mist Ground Effect Reduced v1.0
    * KMM Paint Palette Retex v1.0
    * KMM SE Beds Improved UV v1.0 Stone
    * KMM Skingrad Modular Door UV Fix for Mikal33’s Improved Doors & Flora v1.0
    * KMM Yarn Retex v1.0
2. Install the mod.

[Improved Skulls and Bones and Ironwork](https://www.nexusmods.com/oblivion/mods/36075)

Bad to the Bone. 

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Improved Skulls and Bones and ironwork

[VKVII Oblivion Sidewalk Stonewall](https://www.moddb.com/mods/vkvii-oblivion-sidewalks-stonewalls)

Improves the sidewalk. 

**<span style="text-decoration:underline;">Download Instructions</span>**



* VKVII Oblivion Sidewalks Stonewalls (Medium Size)

[VKVII Oblivion Castles](https://www.moddb.com/mods/vkvii-oblivion-castles)

Makes the castles baller. 

**<span style="text-decoration:underline;">Download Instructions</span>**



* VKVII Oblivion Castles (Medium Size)


#### Creature Visuals

Create a new marker and name it "Creature Visuals".

[Beautiful Creatures - Spriggan](https://www.nexusmods.com/oblivion/mods/43285)

Better Spriggans.

[Beautiful Creatures - Spider Daedra](https://www.nexusmods.com/oblivion/mods/43297)

Better Spider Daedra.

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main File - Spider Daedra Replacer

[Improved Flame Atronach](https://www.nexusmods.com/oblivion/mods/45356) 

Flame on. 

**<span style="text-decoration:underline;">Download Instructions</span>**

Main Files - Improved Flame Atronachs

**<span style="text-decoration:underline;">Installation Instructions</span>**



1. Apply the BCF.
2. In Sub-Packages select:
    * 00 Core
    * 01 Optional Flame Replacer
3. Install the mod.

[Improved Frost Atronachs](https://www.nexusmods.com/oblivion/mods/49520)

Makes the frost atronachs cooler. 

[Improved Storm Atronachs](https://www.nexusmods.com/oblivion/mods/45536) 

It is the storm that is approaching. 

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Improved Storm Atronachs

**<span style="text-decoration:underline;">Installation Instructions</span>**



1. Apply the BCF.
2. In Sub-Packages select:
    * 00 Core
    * 02 Optional SharperShock Texture
3. Install the mod.

[Better minotaurs](https://www.nexusmods.com/oblivion/mods/49425)

Minos would be proud. 

[Better Lorgren Benirus](https://www.nexusmods.com/oblivion/mods/51263)

Improves the visuals for the Lich. 

**<span style="text-decoration:underline;">Download Instructions</span>**



* Better Lorgren Benirus - No Staff Edit

[Diverse Liches (Modders Resource)](https://www.nexusmods.com/oblivion/mods/51265) 

Gives more variants to liches. 

[Unique Liches](https://www.nexusmods.com/oblivion/mods/52362)

Adds a few unique models for unique liches. 

**<span style="text-decoration:underline;">Download Instructions</span>**



* Unique Liches Hood Version

[Coop's TW3 Horse Replacer with Animated Ears](https://www.nexusmods.com/oblivion/mods/53323)

Brings Roach into Cyrodiil. 

**<span style="text-decoration:underline;">Installation Instructions</span>**



* In the FOMOD Installer:
    * Misc: select **Armored Legion Horses**.
    * ArmoredManeFix: select **Mergeable Patch**.
    * KlenPatch: select **None**.
    * Bodies: select **None**.
    * Horns: Don’t select anything.
    * Finish.

[Coop's MOO and Vanilla Wolf Remesh](https://www.nexusmods.com/oblivion/mods/53384)

Enhances wolves. 

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Coop's Vanilla Wolf Revamp 2K

[Coop's MOO and Vanilla Crab Revamp](https://www.nexusmods.com/oblivion/mods/53435)

Filthy creatures. 

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Coop's Vanilla Crab Revamp

**<span style="text-decoration:underline;">Installation Instructions</span>**



* In the FOMOD Installer:
    * Pattern: select **VanillaLike**.
    * Shine: select **Muted**.
    * Misc: don’t select anything.
    * Finish.

[Faster Horse Dismount](https://www.nexusmods.com/oblivion/mods/50226)

Significantly faster. 

[Smoother Horse Animations ](https://www.nexusmods.com/oblivion/mods/45146)

A much needed set of new animations. 


#### Equipment Visuals

Create a new marker and name it "Equipment Visuals".

[Weapon Improvement Project](https://www.nexusmods.com/oblivion/mods/43852)

Makes weapons more detailed. 

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Weapon Improvement Project

**<span style="text-decoration:underline;">Installation Instructions</span>**



1. Unpack the mod into a project.
2. Delete the **meshes** and **textures** folders from that project.
3. Install the project.

[Weapon Improvement Project - fixes (NO ESP) v2 .7z](https://mega.nz/file/lGwSjY4K#Nn_RX412Fq8ObbvNJlpSU2ti00aoyZHSwI9Zc3rAkBs)

Fixes the meshes. 

[Knights of the Nine_Weapon Improvement Project Patch](https://www.nexusmods.com/oblivion/mods/46313)

Improves the KotN weapons. 

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Knights of the Nine Weapon Improvement Project Patch (**V2**).

[Artifacts Redone](https://www.nexusmods.com/oblivion/mods/49277)

Gives artifacts a much more detailed model. 

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Artifacts Redone
* Optional Files - Artifacts Redone - Calming Pants Replacer

**<span style="text-decoration:underline;">Installation Instructions</span>**



* In Sub-Packages for Calming Pants Replacer select:
    * 00 Core (Required)
    * 01 HGEC
    * 02 Robert Male
    * Seamless - OCOv2

[Artifacts Redone - HGEC Roberts Conversion](https://www.nexusmods.com/oblivion/mods/53787)

Converts the new models to HGEC/Roberts

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - HGEC -Artifacts Redone 1.2
* Main Files - Roberts -Artifacts Redone 1.1

[Visually Improved Staffs](https://www.nexusmods.com/oblivion/mods/38438)

Improves the staffs in a manner most visually. 

**<span style="text-decoration:underline;">Installation Instructions</span>**



1. In Sub-Packages select:
    * 00 Core
    * 01 Optional glowing
    * 02 Hrormirs Ice Staff
    * 03 Staff of Indarys
2. Install the mod.

[HiRes Iron Armor](https://www.nexusmods.com/oblivion/mods/30386)

Ever wanted Hi-Res armor? Here you go. 

[HiRes Iron Weapons](https://www.nexusmods.com/oblivion/mods/30357)

Irony not included. 

[Golden Elven Armor and Weapons](https://www.nexusmods.com/oblivion/mods/52876)

Gives a more regal feel to them. 

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Golden Elven Armor and Weapons
* Optional Files - Lindai and Nenalata Crowns

[Dwemer Metal - Armor and Weapons](https://www.nexusmods.com/oblivion/mods/52941?tab=description)

Metal for the metal god. 

[Ebony Armor Extended](https://www.nexusmods.com/oblivion/mods/52881)

Makes ebony armor look slightly more practical. 

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Dark Ebony Gold
* Main Files - Ebony Weapons Gold

[Golden Dagger for Weapon Improvement Project - Fix](https://www.mediafire.com/file/geq6ek8mecnjnj0/Golden_Dagger_for_Weapon_Improvement_Project_-_Fix.7z/file)

Fixes an issue with the golden dagger.

[Darker and Bloody Daedric Equipment](https://www.nexusmods.com/oblivion/mods/52887)

Makes it look pretty cool. 

[Darker Glass Armor](https://www.nexusmods.com/oblivion/mods/49351?tab=files&file_id=1000022289) 

Just like Morrowind. 

[Imperial Armors - Visual Edits](https://www.nexusmods.com/oblivion/mods/52936)

Makes the armor more similar to ones from Skyrim. 

**<span style="text-decoration:underline;">Installation Instructions</span>**



* Main Files - Imperial Dragon

[Mythic Amber Armor](https://www.nexusmods.com/oblivion/mods/37955)

Makes it worthy of an armor found in a daedric realm. 

**<span style="text-decoration:underline;">Installation Instructions</span>**



* Main Files - Mythic Amber Armor Final

[Townguards armor retexture](https://disk.yandex.ru/d/uqKk1dDLsNe9BA) 

Retextures the guard armor to be more detailed. 

**<span style="text-decoration:underline;">Installation Instructions</span>**



1. In Sub-Packages select:
    * Imperial Guard Armor Retexture 4K-2K (56MB)
    * Townguard Armor Retexture 2K (32MB)
2. Install the mod.

[Half-off Clavicusvile Mask remodel replacer](https://www.nexusmods.com/oblivion/mods/51113) 

Remodels the Masque. 

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Ho_Clavicusvile Mask Remodel Replacer

**<span style="text-decoration:underline;">Installation Instructions</span>**



1. Apply the BCF.
2. In Sub-Packages select:
    * 00 Core Textures
    * 01 Optional New Mesh
3. Install the mod.

[SI Mania Clothing Fix](https://www.nexusmods.com/oblivion/mods/52202)

Minor fix for an old SI bug. 

[Cutlass Retexture?](https://www.nexusmods.com/oblivion/mods/51704)

Are you a pirate? 

[Insanitys Umbra Sword Replacer](https://www.nexusmods.com/oblivion/mods/43762?tab=files&file_id=1000002213) 

It’s insane not to get this. 

[Magical Arrows](https://www.nexusmods.com/oblivion/mods/43666)

Adds a really nice effect to arrows. 


#### Miscellaneous Visuals

Create a new marker and name it "Miscellaneous Visuals".

[Improved Fires and Flames](https://www.nexusmods.com/oblivion/mods/38061)

Improves the god awful vanilla flames. 

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Improved Fires and Flames
* Optional Files - Optional torch

[Book Jackets Oblivion High Res BAIN](https://www.nexusmods.com/oblivion/mods/50033)

Adds much more detail to the book jackets. 

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Book Jackets Oblivion High Res BAIN - Cleaned and Bash Tags

**<span style="text-decoration:underline;">Installation Instructions</span>**



1. In Sub-Packages select:
    * 00 Core Assets
    * 01c Core Book Jackets ESP - Filter Version (Maximum Compatibility with Knights and UOP
2. Install the mod.

[Grimbots DLC Book Jackets](https://www.nexusmods.com/oblivion/mods/16247)

Adds more detailed book jackets to DLC books. 

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Shivering Book Jackets

[EGO - Spell Tomes Replacer](https://www.nexusmods.com/oblivion/mods/53295)

Makes the spell tomes into more beautiful books. 

[Book Jackets KOTN](https://www.nexusmods.com/oblivion/mods/27521)

Adds more detailed book jackets to the Knights of the Nine DLC books. 

[Book Jackets KOTN HD update](https://www.nexusmods.com/oblivion/mods/49307)

Now in HD. 

[Book Jackets for Misc DLC](https://www.nexusmods.com/oblivion/mods/49260)

Adds more detailed book jackets to the house DLC books.

[TD_Alternative Books Cover](https://www.mediafire.com/file/juypz88p1eluriz/TD_Alternative_Books_Covers_BAIN.7z/file) 

Makes the book covers more varied.

**<span style="text-decoration:underline;">Installation Instructions</span>**



* In Sub-Packages select:
    * 00 Core

[Glowing Fractured Soulgems](https://www.nexusmods.com/oblivion/mods/49962)

Makes the soul gems look way cooler. 

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Glowing Fractured Soulgems - All Colours with 1024 Textures

**<span style="text-decoration:underline;">Installation Instructions</span>**



* In Sub-Packages select:
    * 00 - Core Files
    * 01 - Textures - Skyrim Inspired Colours
    * 02 - Glow map - Fractured Glow
    * 03 - Meshes - Pulsing
* Install the mod.

[Icon Patch for Glowing Fractured Soulgems](https://www.nexusmods.com/oblivion/mods/50969)

Fixes the icons. 

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Icon Patch for Glowing Fractured Soulgems

[HiRes Silver and Gold Clutter](https://www.nexusmods.com/oblivion/mods/38546)

Keeps the clutter in the same vanilla sliver tone. 

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - HiRes Silver Clutter

[HiRes Pewter](https://www.nexusmods.com/oblivion/mods/38662)

More detail. 

[Vanilla Amulets fix for HGEC](https://www.nexusmods.com/oblivion/mods/47583)

Helps hide seams. 

[Retextured Amulets](https://www.nexusmods.com/oblivion/mods/47734)

Improves the textures of amulets. 

[Retextured Rings](https://www.nexusmods.com/oblivion/mods/47742)

To rule them all. 

[Improved Signs](https://www.nexusmods.com/oblivion/mods/9498)

This is a sign. 

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - ImprovedSignsComplete

**<span style="text-decoration:underline;">Installation Instructions</span>**



1. In Plugin Filter uncheck:
    * ImprovedSigns.esp
2. Install the mod.

[Retextured Inn Signs](https://www.nexusmods.com/oblivion/mods/48576)

Makes the Inn signs look better. 

[Retextured Road Signs](https://www.nexusmods.com/oblivion/mods/48235)

Makes the road signs clearer. 

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Retextured Road Signs

[EGO - Beverages and Bottles Replacer](https://www.nexusmods.com/oblivion/mods/53297)

Makes the bottles of beverages look way cooler. 

[Retextured Potions](https://www.nexusmods.com/oblivion/mods/49068)

Also makes potions really cool. 

**<span style="text-decoration:underline;">Download Instructions</span>**



1. In Sub-Packages select:
    * Core
    * Optional Slimy 
2. Install the mod.

[Paintings Variation](https://www.nexusmods.com/oblivion/mods/46482)

Changes paintings. 

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Paintings Variation 2.0
* Optional Files - Paintings Variation SI

[Faster Dungeon Doors](https://www.nexusmods.com/oblivion/mods/46889)

Open dungeon doors faster. 

[High-Res Varla and Welkynd Texture Replacer](https://www.nexusmods.com/oblivion/mods/36814) 

Gives beauty to these ancient artifacts. 

**<span style="text-decoration:underline;">Installation Instructions</span>**



1. In Sub-Packages select:
    * 01 Fixed UV Meshes w. 2x UV Scaling
    * 02 More Meshes w. New Iron Tex && 2x UV Scaling
2. Install the mod.

[HD Cobwebs](https://www.nexusmods.com/oblivion/mods/50488)

Cobbing time. 

[TD_Lower_Clutter](https://www.mediafire.com/file/vp9mdffv1larm39/TD_Lower_Clutter_BAIN.7z/file) 

Retextures the clutter for lower class items. 

[TD_Middleclass_Replacer v 3.0](https://www.mediafire.com/file/v17cy2ah0zaotr2/TD_Middleclass_Replacer_v_3.0_BAIN.7z/file) 

Replaces the models of some middleclass items. 

[TD_Middleclass v 3.1](https://www.mediafire.com/file/s15hvn3d2hikf4g/TD_Middleclass_v_3.1_BAIN.7z/file) 

Retextures them. 

[TD_Upperclass v 3.0](https://www.mediafire.com/file/0ggpbk8kp8w2qxi/TD_Upperclass_v_3.0_BAIN.7z/file) 

Makes the upperclass look more detailed. 

[TD_Upperclass v 3.1](https://www.mediafire.com/file/d3msrhd1ctnabhk/TD_Upperclass_v_3.1_BAIN.7z/file) 

Update file. 

[Darooz Upperclass clutter](https://www.nexusmods.com/oblivion/mods/41108/)

Classy. 

[Colovian Carpets - A rug and mat retexture](https://www.nexusmods.com/oblivion/mods/52995)

I can show you the world…

[VKVII Oblivion Mages Guild Clutter](https://www.moddb.com/mods/vkvii-oblivion-mages-guild-clutter/downloads)

Hi-Res retexture of magical related clutter. 

[HiRes Hay Bail Textures](https://www.nexusmods.com/oblivion/mods/27138)

Not a bail out. 

[Better Window Reflections](https://www.nexusmods.com/oblivion/mods/46774)

Replaces the vanilla god awful reflections. 

[Kinda Actually Decent Enviroment Map](https://www.nexusmods.com/oblivion/mods/48856)

Very decent. 

[Retextured Caves and Mines Doors](https://www.nexusmods.com/oblivion/mods/50943)

Compliments strange caves. 

[Luna's Ironwood Nut Retex](https://www.nexusmods.com/oblivion/mods/49242) 

N U T. 

[Azuras Star retexture](https://www.nexusmods.com/oblivion/mods/50362) 

By Azura! 

[Azuras Star Glow](https://www.mediafire.com/file/0toc9obo4wtuu5f/Azura_Star_Glow_fixed.7z/file)

Now glowing! 

[Darooz artsupplies](https://www.nexusmods.com/oblivion/mods/41122)

No more palette stacking! 

[Kaizits Animated Ingredients](https://www.nexusmods.com/oblivion/mods/46962)

Makes the ingredients animated. 

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Kaizits Animated Ingredients
* Update Files - Kaizits Animated ingredients v1.1

[Kaizits Animated Ingredients - No Shadows](https://www.nexusmods.com/oblivion/mods/53031?tab=files&file_id=1000034891) 

Removes shadows for increased performance. 

[Icons for Alchemy Apparatus](https://www.nexusmods.com/oblivion/mods/43782)

Improves UI. 

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Icons for Alchemy Apparatus
* Optional Files - Icons for novice Alembic and Retort

[Clickable Magic Gate](https://www.nexusmods.com/oblivion/mods/51375/)

You can now click it!

[VAs Better Gold with No Menu Icon - Loose](https://www.nexusmods.com/oblivion/mods/52833?tab=files&file_id=1000038041) 

Improves the detail of the actual gold items.

[Luxury Ayleid Chests](https://www.nexusmods.com/oblivion/mods/46929)

Makes the chests more detailed. 

[Luxury Ayleid Chests - Small Chest Glow](https://www.nexusmods.com/oblivion/mods/53031?tab=files&file_id=1000034896) 

Makes the chests glow. 

[Improved Chests](https://www.nexusmods.com/oblivion/mods/51815)

Adds several new chest models. 

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Improved Chests

[Savilla’s Stone Enhanced](https://www.nexusmods.com/oblivion/mods/52713)

Makes the stone more detailed. 

**<span style="text-decoration:underline;">Installation Instructions</span>**



1. In Sub-Packages select:
    * 01 - Iced Style (.esp FREE)
2. Install the mod.


### **Sounds**

Create a new marker and name it "Sounds".

[GOSH](https://www.nexusmods.com/oblivion/mods/45214/)

Massively overhauls the sounds of Oblivion.

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - GOSH v2-1

[Varied Spell Sounds](https://www.nexusmods.com/oblivion/mods/14799)

Improves the sound variety of spells. 

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - AgarVariedSpellSounds

[Symphony of Violence - Combat Sound Enhancement](https://www.nexusmods.com/oblivion/mods/13987)

Improves the general combat sound effects. 

[Consistent Beggar Voices](https://www.nexusmods.com/oblivion/mods/48336)

Fixes the inconsistencies with beggar voices.


### **Music**

Create a new marker and name it "Music".

[Oblivion Music Overdose 2](https://www.nexusmods.com/oblivion/mods/49881)

Includes some great music. 

**<span style="text-decoration:underline;">Download Instructions</span>**



* Optional Files - Oblivion Music Overdose 2 - Title Music NOT Replaced

[Oblivion Symphonic Variations Music Suite](https://www.nexusmods.com/oblivion/mods/11436) 

Adds some music in the style of Jeremy Soule. 

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Oblivion Symphonic Variations Remastered

**<span style="text-decoration:underline;">Installation Instructions</span>**



1. Apply the BCF.
2. Install the mod.


### **Late Loaders**

Create a new marker and name it "Late Loaders".

[Miscellaneous Patch Collection by Dispensation](https://www.nexusmods.com/oblivion/mods/52874?tab=description)

A huge patch collection for several mods.

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Miscellaneous Patch Collection by Dispensation

**<span style="text-decoration:underline;">Installation Instructions</span>**



1. In Sub-Packages select:
    * Av Latta Magicka - Migck’s Misc Elemental Fists Poison Patch
    * Oblivion Character Overhaul version 2 Patches
    * The Lost Spires Compatibility Patches
2. In Plugin Filter Check:
    * DispMiscPatch_Av Latta Magicka - Migck Misc Poison Fists Patch.esp
    * DispMiscPatch_OCOv2 - Adoring Fan No Check Beard.esp
    * DispMiscPatch_OCOv2 - VKVII Argonian and Khajiit Patch.esp
    * Check DispMiscPatch_TheLostSpires_LandmarksOfCyrodiil_Patch.esp
3. In Plugin Filter Uncheck:
    * DispMiscPatch_TheLostSpires_ArtifactsRemasterModPatch.esp
4. Install the mod.


## INI Presets

Create a new marker and name it “INI Presets”.

[ROTS Preset Compilation](https://www.mediafire.com/file/su2cleiaxl717ki/ROTS_Preset_Compilation.7z/file)

Every preset that is required for this guide to play as intended is included here.

List of Mods:

**Blockhead**

Disables a clunky change to the race menu controls.

**Migck Miscellaneous**

Disables the more intrusive settings.

**MigMaster**

Removes a pointless notification.

**Extended UI**

Enables additional QoL tweaks such as quick selling and buying shop items. Disables spell descriptions.

**QZ Easy Menus**

Assigns more appropriate shortcut keys.

**Map Marker Overhaul**

Removes intrusive features such as changes to the compass range

**Ascension**

Reverts some changes such as changes to the maximum carry weight and fatigue system.

**Av Latta Magicka**

Tunes the configuration more appropriately for Ascension.

**Ultimate Leveling**

Disables out of place features like horseshoes and enables the vanilla based skill usage leveling.

**Combat Additions**

Removes many intrusive features such as healing grass, combat ratings and lock-on mechanics.

**Crime Has Witnesses**

Sets the witness notifications to the least intrusive setting.


## Mod Cleaning

Mod cleaning is really simple: just open TES4EditQuickAutoClean.



1. Right-click on the TES4Edit icon.
2. Select **Quick Auto Clean**.
3. Select a plugin to clean.
4. Close when finished.
5. Repeat the procedure for all plugins requiring cleaning.

LOOT will show you what plugins need cleaning, but for your convenience we also provide a list of esps here: 

<span style="text-decoration:underline;">List of Mods:</span>



* DLCHorseArmor.esp
* DLCVileLair.esp
* DLCOrrery.esp
* DLCMehrunesRazor.esp
* DLCSpellTomes.esp
* DLCThievesDen.esp
* DLCBattlehornCastle.esp
* DLCFrostcrag.esp
* Knights.esp
* HeartOftheDead.esp
* The Lost Spires.esp
* The Lost Spires - Cleaned Up Scribe.esp
* GOSH Region Ambiance.esp
* Cliff_BetterLetters.esp
* IC Circular Canal.esp
* lNewGems.esp
* Harvest [Flora] - Shivering Isles.esp
* Harvest [Flora] - DLCFrostcrag.esp
* Better Rainbows.esp
* MinimalMagicEffects.esp

It would also be a good idea to update installation packages for the cleaned plugins:



1. Navigate to the **Installers** tab.
2. Right-click the package you want to update.
3. Select **Sync from Data**.
4. Only keep the .esp checked.

Hint: when packages and installed esps do not match, WB marks the tick box with an orange color, helping you to identify the packages you need to update.


## Bashed Patch

The Bashed Patch is primarily used for conflict resolution between your entire load order and merging leveled lists. Additionally, it allows you to save esp slots by merging those esps into the Bashed Patch.

This section will show the user how to apply this utility to their load order for the purposes of this guide.

**Before building your Bashed Patch, make sure to run LOOT to sort your load order.**

**<span style="text-decoration:underline;">Instructions:</span>**



1. Open Wrye Bash.
1. Go to the top-left of the **Mods** tab.
2. Go to **Edit**.
3. Go to **Active Plugins**.
4. Select **Deactivate All,** then in the same menu **Activate non-mergeable**.
5. Right-click on **Bashed Patch, 0.esp** -> **Rebuild Patch**.6.
6. Click OK when getting the notification on mergeable plugins.
7. Make sure that you have these categories enabled:

    

<p id="gdcalert27" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image27.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert28">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image27.png "image_tooltip")


8. Go to the **Leveled Lists** category and untick **Remove Empty Sublists**.
9. Go to **Tweak Actors/Assorted/Clothes/ **setting and make changes to your preferences (recommended settings below).
10. Click **Build Bashed Patch** on the bottom of the Update Bashed Patch, 0.esp window.


## Recommended Tweaks

The Bashed Patch is useful beyond simply conflict resolution. It even has tweaks packaged in that can be enabled.


### Tweak Actors:



* Enable "Irresponsible Creatures [All Creatures]".


### Tweaks Assorted:



* Enable "Armor Shows Amulets".
* Enable "Armor Shows Rings".
* Enable "Clothing Shows Amulets".
* Enable "Clothing Shows Rings".
* Enable "Magic: Script Effect Silencer".
* Enable "Nvidia fog fix". (enable for Nvidia GPUs)
* Enable "Bow reach fix".
* Disable "Default Icons" (requirement for Av Latta Magicka).
* Enable "No Light Flicker" (FPS boost).


### Tweaks Clothes:



* Enable "Gloves Show Rings".
* Enable "Robes show amulets".


### Tweak Settings:



* Enable "Arrow: Speed".
    * Right-click and select x2.0.
* Enable “Camera: Chase Tightness”
    * Right-click and select ChaseCameraMod (x24.75)
* Enable "Player:Horse Turning Speed".
    * Right-click on the option and set values to custom.
    * iHorseTurnDegreesPerSecond value to 80.
    * iHorseTurnDegreesRampUpPerSecond to 360.
* Disable "UOP Vampire Aging And Face Fix" (ORC already includes a fix).
* Enable "Warning: Exterior Distance To Hostiles".
    * Right-click on the option and set it to 1000.
* Enable "Warning:Interior Distance To Hostiles".
    * Right-click on the option and set it to 1000.

**<span style="text-decoration:underline;">Note #1:</span>**

Filter Patches are patches with Filter Bash tags that import records based on your current load order. Missing masters are normal, as the relevant records are merged into the Bashed Patch. **Filter Patches must be deactivated at all times.**

**<span style="text-decoration:underline;">Note #2:</span>**

It is recommended to rebuild your Bashed Patch whenever you make changes to your plugin load order.

**<span style="text-decoration:underline;">Note #3:</span>**

Depending on your load order, this process might take awhile.


## LOD

Create a new marker and name it "LOD".

In order for a proper display of distant objects and terrain, custom LOD generation will be needed. It is NOT required, especially if your system cannot handle it.

For additional information, check out [this](https://masserandsecunda.wordpress.com/wolf-tamriel/building-your-own-lod/). 


### **LOD Resources**

[Landscape Terrain Noise by Xerus](https://www.nexusmods.com/oblivion/mods/17300/)

Improves the look of distance LOD.

**<span style="text-decoration:underline;">Installation Instructions</span>**



1. Unpack the mod into a project.
2. Delete every folder EXCEPT** **the **Cyrodiil** folder. 
3. In the **Cyrodiil** folder, delete the **LandscapeLOD** folder from inside the **Textures** folder.
4. Move the **Textures** folder to the very front of the project.
5. Delete the **Cyrodiil** folder.
6. The expected result should look like this:

    

<p id="gdcalert28" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image28.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert29">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image28.png "image_tooltip")


7. Install the project.

[TES4LL - Missing textures for Landscape LOD generation](https://www.nexusmods.com/oblivion/mods/50159)

Adds missing textures necessary for LOD generation. 

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - TES4LL - Oblivion Vanilla - Missing Textures

[SI HM fix for TES4LL and MPGUI](https://www.nexusmods.com/oblivion/mods/49898?tab=files&file_id=1000033654) 

Fixes the Height Map for Shivering Isles. 

[Evenstars Colourwheel LOD Update](https://www.nexusmods.com/oblivion/mods/42190)

Improves LOD models. 

**<span style="text-decoration:underline;">Installation Instructions</span>**



1. In Sub-Packages select:
    * 00 Textures
    * 04 Statues and shrines
2. Install the mod.

[Optimized VWD](https://www.nexusmods.com/oblivion/mods/49595)

Less resources intensive VWD models. 

[VWD for Leyawiin](https://www.nexusmods.com/oblivion/mods/50052)

Adds VWD models to Leyawiin LOD. 

[VWD for Town Houses](https://www.nexusmods.com/oblivion/mods/50073)

Adds VWD models for town houses. 

[J3 Atlassed VWD 2](https://www.nexusmods.com/oblivion/mods/51732)

Adds several atlassed VWD models.

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - J3 Atlassed VWD 2 - Cyrodiil - BAIN installer
* Main Files - J3 Atlassed VWD 2 - Shivering Isles - BAIN installer
* Optional Files - J3 Atlassed VWD 2 - Cyrodiil - Ruins - ALL - Ruined Ruins (texture mod)
* Optional Files - J3 Atlassed VWD 2 - Shivering Isles - Bomret’s Texture Pack for Shivering Isles

**<span style="text-decoration:underline;">Installation Instructions</span>**



1. In the BAIN Installer Wizard for Cyrodiil:
    * Select **Performance (No Rocks)**
    * Finish.
2. In the BAIN Installer Wizard for Shivering Isles:
    * Select **Select All**
    * Finish.

[Bruma Frostcrag Spire LOD](https://www.nexusmods.com/oblivion/mods/49898?tab=files&file_id=1000033650) 

Adds LOD to Frostcrag Spire from Bruma.

**[Landscape LOD generator tes4ll-v5](https://www.nexusmods.com/oblivion/mods/40549)**

Used to generated landscape textures. 

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - Landscape LOD generator 5_15c

**<span style="text-decoration:underline;">Installation Instructions</span>**



* Extract the contents into the Oblivion data folder.

**<span style="text-decoration:underline;">LOD Generation Tools</span>**

Sort through LOOT and rebuild your Bashed Patch before you use the following tools.

**[Multi Purpose GUI](https://www.nexusmods.com/oblivion/mods/41447/)**

This tool is for generating terrain LOD.

**<span style="text-decoration:underline;">Download Instructions</span>**



* Main Files - mpgui_2_00

**<span style="text-decoration:underline;">Installation Instructions</span>**



1. Extract the contents of the setup.exe at a location of your choosing.
2. Run setup.exe and install in the following path:
    * C:\MPGUI

    [MPGUI Batch Files](https://www.nexusmods.com/oblivion/mods/49898?tab=files&file_id=1000033647)


    Batch files that automatically configures settings for you.


**<span style="text-decoration:underline;">Installation Instructions</span>**



1. Extract into the same location where the MPGUI files were installed (C:\MPGUI).
2. In the MPGUI folder, double-click on **DispensationBatchTamriel.mpb**.
3. Click on the **Plugins** tab.
4. Click on the **Plugins.txt** button. 
5. Go to the **Worldspace** tab and click on **Read Worldspaces**.
6. It might crash during the scanning process, if it does, just try again until it works.
7. Click on the **Start Process** tab.
8. Click on the **Click me if you are ready** button to generate the Tamriel landscape LOD.
9. When **Background reader finished** is displayed in the console log, it is done.
10.  Close MPGUI.
11. Repeat the steps for **DispensationBatchShiveingIsles.mbp**.

**[TES4LODGen](https://www.nexusmods.com/oblivion/mods/15781)**

This tool is for generating object LOD.

**<span style="text-decoration:underline;">Installation Instructions</span>**



1. When the download has finished, extract the contents of the archive into your Oblivion root folder.
2. Run TES4LODGen.exe

**<span style="text-decoration:underline;">Note #1: \
</span>**In general, regenerate terrain LOD using TES4LL and MPGUI whenever making mod load order changes that are in relation to landscape or texture edits. \
 \
**<span style="text-decoration:underline;">Note #2: \
</span>**In general, regenerate object LOD using TES4LODGen whenever making changes to your load order.

**<span style="text-decoration:underline;">Credits</span>**



* Moddinglinked - for the beginning portions of the guide
* Dispensation - Inspiration
* Slowpard - Advice and Editing
* Darkforce146 - Advice and Testing
* Tarnished/Mr7Digits - Advice and Testing
* Raven/ARavenOfManyHats - Advice and Editing
* Sunny - Advice, Editing and Testing
* Annalise - Advice and Testing
* Psymon - Advice and Testing
* Jyggalag - Advice and Testing
* Lorkhansheart - Advice
* Thatoneguy1337 - Advice and Editing
* CrestFallen223 - Support
* Voido - Advice, Editing and Testing


## FAQ and troubleshooting

**My game doesn’t load/I CTD on clicking “New Game”**

Before coming to the comments, try this:



1. Check for missing masters. Check that you don’t have esps with missing masters enabled. 

    Regenerate the **Oblivion.ini**. Delete the **Oblivion.ini** in My Documents\My Games\Oblivion\**Oblivion.ini** then launch the **Oblivion Launcher** (either via GOG, Steam, or directly clicking on the OblivionLauncher.exe) to regenerate the file. If the game launches (don’t pay attention to wrong resolution/fonts) reapply font tweaks for Darnified UI (see Installation Instructions for Darnified UI) and reapply bBorderRegionsEnabled=0 in the Oblivion.ini.

2. Restart your computer. Yes, we know, it sounds too obvious, but may help in certain cases and is pretty fast to do. 
3. Check for bugged esps. Try to launch Oblivion with only Oblivion.esm active. If it works, enable esps by groups, until you find the culprit.
4. Check if ORC or Oblivion Display Tweaks is the issue. Disable Oblivion Reloaded Combined and/or Oblivion Display Tweaks to see if it solves the issue. If it is indeed the case, some configuration for your particular setup might be required to achieve ultimate happiness.
5. If you use DXVK, try removing d3d9.dll from the Oblivion root folder to see if the problem still persists.

 \
 \
Congratulations, you have finished the Reign Of The Septims guide. You can now open Oblivion through Mod Organizer 2 and enjoy. Any feedback to improve the guide would be appreciated.









