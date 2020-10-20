![N|Solid](https://i.imgur.com/TfMhdNG.png)

A fork of Magnum Opus by Lively, tweaked for long-term replayability & countless hours of settlement building.

# **_INTRODUCTION_**
Please read this guide in its entirety. Every part of it is important, and I cannot guarantee a stable game if you do not follow the directions.

Full documentation (including changelogs) can be found [on my github for Valhalla.](https://github.com/xVal429/Valhalla)

A list of my progress can be found [on my Trello board for Valhalla.](https://trello.com/b/GyFIQ79U/valhalla)

Before we start, there are some basic things that you should know;
- This list is a fork of Magnum Opus by Lively. Do not contact Lively for support. 
- This list is designed to be played on ‘Very Hard’ difficulty with some aspects of Survival Mode combined into it, specifically how stimpaks work & riskier combat.
- This list assumes you have a somewhat modern PC with at least 4GB+ of VRAM.
- This list also assumes you have somewhat basic knowledge of core mods such as the MCM (Mod Configuration Menu).

I cannot fix issues with the list unless you report them to me, however I am not a wizard. I’m a novice modder and may take a while to fix some bugs/do some tweaks. 
# **_INSTALLATION & SETUP_**
#### **_Requirements Before Installing:_**

  *  Current build version of [Wabbajack](https://www.wabbajack.org/#/).  
  *  Clean install of Fallout 4, **without the official Hi Def DLC**.  Note that if you previously used BiRatBec's Workbase and replaced the texture archives in Fallout 4\data, you will need to make a backup of these and verify files to obtain the original, unmodified texture archives.
  *  A Nexusmods account. Nexus Premium is highly recommended for automatic download support.  
75 gigabytes of free space. Note that this number does NOT include your Fallout 4 installation.
That’s 25.1 GB for downloads, 39.1 GB for installation, and a little extra wiggle room to be safe.

Once Fallout 4 is installed, run it once through Steam. This will establish registry keys and allow Wabbajack to locate the game on your PC.

### **_Installation Instructions:_**

1. Download the latest version of Wabbajack.
2. Create a new folder at the root of a drive (Example: D:\Wabbajack).
3. Place the Wabbajack.exe into this new folder.
4. Download the Valhalla.wabbajack file from the [Valhalla Google Drive](https://drive.google.com/drive/u/0/folders/1-ReP39R6OpbM-ewKpJ4fBD2Fcwl3oTz5)
4a. Run Valhalla.wabbajack after putting it somewhere.
5. In “Installation Location” choose a blank folder at the root of a drive (example: D:\Valhalla). **DO NOT** install your modlist to the same folder where you put Wabbajack.exe.  **DO NOT** install into your Steam game path.
6. The “Download Location” will update automatically. You can change it if you want.
7. Click the "Play" arrow.
8. Make sure to accept the Nexus API request if your browser asks for it.
9. When Wabbajack completes the installation (you can check the Wabbajack.current.log to confirm it completed successfully), you may close the program.

#### **_Post Installation Instructions:_**

Navigate back to your Valhalla installation folder.  
Open “Game Folder Files”  
Copy everything in this folder.  
Paste it into your Fallout 4 directory (steam/steamapps/common/Fallout 4).  
  *  Just to be really clear about this: do not copy/paste the entire folder. Only the **contents** of Game Folder Files.

##### _This section is **optional but highly recommended**. It can be done at any time before or after installation._

Go to [BiRaitBec’s Modding Guide](https://www.nexusmods.com/fallout4/mods/23556?tab=description).  
Manually download the **WorkBase** file.  
Manually download the **Main Repack** files (Part One, Part Two, and Part Three).  
  *  You can use Performance/Quality repacks as well if you like. I only use Main. Entirely up to you.  
 
Extract the WorkBase file with 7zip.  
You should have three folders inside of Workbase: OriginalBa2, PatchedBa2, and PatchedFiles.  
Navigate to your Fallout4/Data folder and **copy** these 15 files:  

* 'Fallout4 - Textures1.ba2'  
* 'Fallout4 - Textures2.ba2'  
* 'Fallout4 - Textures3.ba2'  
* 'Fallout4 - Textures4.ba2'  
* 'Fallout4 - Textures5.ba2'  
* 'Fallout4 - Textures6.ba2'  
* 'Fallout4 - Textures7.ba2'  
* 'Fallout4 - Textures8.ba2'  
* 'Fallout4 - Textures9.ba2'  
* 'DLCworkshop01 - Textures.ba2'  
* 'DLCworkshop02 - Textures.ba2'  
* 'DLCworkshop03 - Textures.ba2'  
* 'DLCRobot - Textures.ba2'  
* 'DLCCoast - Textures.ba2'  
* 'DLCNukaWorld - Textures.ba2'  

**Paste** these files into your **WorkBase/OriginalBa2** folder.
**Extract** Main Repack Part One into a new folder.
Inside the new folder, you should see another folder called “**textures**”. **Cut** this textures folder and **paste** it into **Workbase/PatchedFiles**.
**Repeat the previous two steps** for Part Two and Part Three of the Main Repack archives.
Run the **installer.bat** file inside of WorkBase.
When it is done, copy and paste all of the files inside of the PatchedBa2 folder into your Fallout4/Data folder AFTER WABBAJACK IS FINISHED INSTALLING.
  *  Alternatively, you can make a new folder inside Valhalla/mods and paste the archives into there, then activate the new mod in Mod Organizer 2. This will keep your Fallout 4 installation completely clean.  
  
After all of these steps are complete, you may delete the WorkBase folder. If you have the space, I advise making a backup of both the vanilla ba2 files as well as the patched ba2 files. It will save you the trouble of having to redownload them again later.

*Note that you CANNOT use the HD DLC for BiRaitBec’s texture optimization. You’ll see missing textures everywhere if you do.*



**Optional:** If you want to avoid the hassle of future updates from Bethesda:
  *  Open Steam  
  *  Right-click Fallout 4 in your Library  
  *  Click Properties  
  *  Go to the Updates tab, and change the Automatic Update option to “Only update this game when I launch it.”  
*Since we’re always launching from F4SE, it will never automatically update again.*  

**Optional:**  Install any ENB you want to use, as long as it’s compatible with NAC. I suggest [Photorealistic Commonwealth X.](https://www.nexusmods.com/fallout4/mods/6796?_)
Disable ‘ENB Lights Overhaul’ and ‘PRC X - Institute Patch' if you are not using an enb. If you’re not using PRC (Photorealistic Commonwealth), disable ‘PRC X - Institute Patch’.

### _That’s it! Launch Mod Organizer 2 inside the Valhalla folder. From now on, you must launch Fallout 4 via the “F4SE” option in Mod Organizer 2._

Now, we still have a little bit of work left to do, but we’re almost done. Before you go any further, you should cap your FPS at 60. You can do this through your gpu driver settings, enabling vsync, or setting an fps limiter in your enb settings (if you choose to add one). 
If you choose to enable vsync, you need to open the ini editor in Mod Organizer 2. At the top of the window, there are three .ini files listed. Select the Fallout4Prefs.ini and look for the line **iPresentInterval=0** under the **[Display]** heading, then change it to a **1**, so the end result is **iPresentInterval=1**.  

Now we can launch the game. Once you finish character customization, you’ll have two options when you try to leave. Take note that this modlist uses **Start Me Up - Basic Version**.  

**DO NOT PRESS C DURING CHARACTER CREATION.** This is a known bug with LooksMenu. The Clothes option WILL LOCK YOUR GAME.

**This is a memory, I don’t want to relive this**: You wake up in Vault 111 as Nate. Everything else is normal.  
**This is a memory, stay here a while**: Vanilla Fallout 4 intro.  

#### MCM Settings:

**_DO THESE AS SOON AS YOU EXIT THE CRYO POD_**

_Note: Anything involving hotkeys can be set up however you like. These are simply the way I have them set up for myself._

### Better Locational Damage;
	Mod Settings:
		Stronger Bleedings: Off
		Brutality: Off
		Stab And Break: On
### Companion Command;
	Command Companion: U
	Trade With Companion: CTRL+U
### Crafting Mastery;
	Ammo Crafting Difficulty: Hard Alt
### FallSouls;
    Console: Off
    PauseMenu: Off
    MessageBoxMenu: Off
    SPECIALMenu: Off
### Faster Workshop; 
	Start Workshop Mode: G
### Game Configuration Menu ( GCM )
	Difficulty
		Damage Taken
			Very Hard: Set to 3
		Damage Done
			Very Hard: Set to 1.5 (Remember, this list has Better Locational Damage which already makes the weapons a bit more powerful even if you dont get a headshot.)
		Effect Duration
			Very Hard: Set to 10
		Effect Magnitude
			Very Hard: Set to 0.1
### More AGOMBz;
	More Attacks
		Far Harbor Creatures
			Allow Far Harbor Creatures Attacks On The Island: On
			Allow Far Harbor Creatures Attacks Worldwide: Off
		Nuka-World Creatures
			Allow Nuka-World Creatures Attacks On Nuka-World: On
			Allow Nuka-World Creatures Attacks Worldwide: Off
	More… Disable
		Disable Radstags Attacks: On
### Workshop Framework;
	Settlement Gameplay
		Allow Max NPCs By Charisma: Off
		Robots Count Towards Max Population: Off
### Workshop Plus;
	Options
		Autosave Timer: 10
		Fly In Workshop Mode: Off
		Increase Speed In Workshop Mode: 0%
		Invulnerability in Workshop Mode: Off
		Invisibility in Workshop Mode: Off
		Clear the weather in Workshop Mode: Off
		Prevent Fall Damage in Workshop Mode: On
		Unlimited Carry Weight in Workshop Mode: Off
	Hotkeys
		 Undo: [
		 Redo: ]
		 Save: \
		 Toggle Flight: ‘
### Zebrina’s Workshop Devices
        Complex Recipes: On

#### Holotape Settings:

**_DO THESE AS SOON AS YOU EXIT VAULT 111_**
When you leave the Vault, open your Pip-Boy and navigate to the MISC tab.
* Settings Holotape -> Beantown Interiors

Load that holotape, and do the following;
* Customize Options -> Other Options -> Mod Compatability -> Enable Insidejobs Compatability

Last but certainly not least, head to _‘Apparel’_ and bind _NAC X SETTINGS MENU_ to a key if you wish. I like using =. While you’re here do the following  ***if you use an ENB, use the item and click ‘Enable NAC Patch for ENB’.***

### _That’s it! You’re all good to go and you should be ready to explore the Commonwealth._


#### CREDITS
Thank you to all the authors of the mods I’ve included in this list. Without you, this list isn’t possible. Thank you for sharing your work publicly and as such allowing me to compile this list for other people. If you don’t want your mod included in my list, please let me know. -Val

Thank you to the Wabbajack team for developing Wabbajack itself.

A huge thank you to LivelyDismay#7243 for letting me make a fork of Magnum Opus, and for providing a ton of assistance with modding.

Thank you to Leon_DP#0420 for wanting me to make a Wabbajack because he’s lazy and likes to use the exact same mods as me.

And last but certainly not least, thank you for downloading this list and/or at the very least reading this documentation.


