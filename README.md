# Important

After the Dialga and Palkia booster update, the game rebalanced the way godpacks were distributed to people in the Wonder Pick, making this script irrelevant or unusable. 

The last modification made is to provide a final QoL maintenance for reference purposes to ensure functionality if someone wants to use it as a base for another macro in the future, but further maintenance or implementations are now concluded.


#


<img align="center">![PtcgP FriendMacro By GaloXDoido](https://github.com/user-attachments/assets/9655286b-28e2-42c3-aea3-238664d91d1f)</img>

Video of usage

# PtcgP FriendMacro by GaloXDoido
A open source Macro WITH GUI to automatically add and remove friends in the Pokémon TCG Pocket game, made with AutoHotKey.

The code was heavily based on the open-source macro "Banana Macro PtcgP," created by [banana-juseyo](https://github.com/banana-juseyo/Banana-Macro-PtcgP).

I completely adapted the logic of the original Korean code to remove certain restrictions related to exclusive use by specific users and added localization for English, Spanish, and Brazilian Portuguese, along with a few other modifications.

If you liked it and want to support me in any way, please leave a like on my showcase on PtcgP, here's my friend code:  __5170263375029596__

이 코드는 banana-juseyo가 작성한 원본 코드를 기반으로 했습니다. 감사합니다!


#
**__How can I get it working?__**

The steps to use this macro are basically the same as [Arturo's Pokémon Trading Card Game Pocket Bot](https://github.com/Arturo-1212/PTCGPB), so I will take the liberty of reproducing the same steps here, with some relevant modifications.

__ATTENTION!!__

This script __REQUIRES AutoHotKey v2.0__. If you're using Arthuro's bot, you MUST install the updated AutoHotKey 2.0 version to use this script.

Don't worry — Arthuro's bot will continue to work, as AutoHotKey supports having multiple versions installed simultaneously on Windows.

If you try to run this script with an older AHK version, __it won't open at all__.

#

Step 1: Install the necessary programs
- [AutoHotKey v2.0](https://www.autohotkey.com/download/ahk-v2.exe) (It needs to be version 2.0. The macro will not run if you are using earlier versions of AHK.)
- [Global MuMu Player](https://adl.easebar.com/d/g/mumu/c/mumuglobal?type=pc&direct=1)

Step 2: Set-Up MuMu Player
- Install
- Recommended Settings **(Bold = Must have)**
  - CPU: 2
  - RAM: 2
  - Less resource usage
  - Forced use of discrete graphics
  - **Custom: 540 x 960 220 dpi**
  - **Screen brightness: 50**
  - **Screen style: Common**
  - FPS: 60
  - **Do not turn on the FPS display**
  - Close system sound
  - **Uncheck: Keep running in the background**
  - **Check: Enable Root Permissions**
  - Exit directly

Step 3: Install PTCGP
 - PTCGP Speed Mod [[Here]](https://modsfire.com/y6p37S9f7n2fD38) ** - *Thanks to nowhere_222 from the platinmods forum.*
- Drag and drop into your MuMu instance
  -# **If you are using the version of this mod with 3x speed, please use 2x speed with this bot as a precaution, since 3x has not been tested.
- Do not move the app from where it is placed on the home screen.
- Manually open the game.
- If you're using the new speed mod linked above then make sure to click the "PM" logo > cog wheel > save preferences > cog wheel > set speed to the one you will be running at > click minimize

Step 4: Windows settings
- **This macro was made to run with windows on 100% scale.** > Press windows key > Type "display settings" > Look for the scale setting and change it to 100% for all your monitors.
- all windows color filters off
- HDR off

Step 5: 
- Download this Bot zip on the releases tab
- Extract it by Right clicking the zip > extract

Step 6: 
- Run __FriendMacro.ahk__
- **On first run after pressing start, if prompted for super user access in each instance, select to allow forever.**


![FriendMacro Interface](https://github.com/user-attachments/assets/9e0d72a9-1296-4b46-b6e4-ac4077c17891)


FriendMacro's Interface

Step 7: Click on the Cogwheel button (⚙) and input your script settings
- Name of Mumu instance
- Delay in between actions
- Acceptance time in minutes
- Wait time between the end of acceptance phase and the beginning of deletion phase in minutes
- Language: The program's execution language.
  
- Click Save button to reload app

Step 8: Choose a button to start the macro:

- "Start" Button (▶️): Begins by accepting friend requests.

- "Start Without Friend Deletion Phase" Button (The ▶️🗑️🚫 button): Forever accepting requests, never entering the deletion phase.

- "Start from Friend Deletion" Button (The 👥🗑️ button): First clears the friend list, then automatically starts accepting requests.
  
 **Allow adb to run and through the firewall if it asks you**


# FAQ

__Q: Does it work on resolutions other than 1920x1080?__

A: It has not been tested on any other resolutions, but the Windows scaling __must be set to 100%__ for it to work correctly.

__Q: Can it be used with multiple instances?__

A: It hasn't been officially tested, but it is possible to copy multiple folders and run them. Some users have reported minor issues, but overall it works well.

__Q: "Error while update" appears when starting the macro.__

A: This can happen due to issues during the automatic update process. Re-download the macro file and try again.


# Modification and Redistribution

This project, as well as the original project it is based on, is licensed under GPL-3.0, allowing modifications and redistribution, provided that proper credit is given to both the original author, __banana-juseyo__, and __myself__.

# Credits

Technical Contributions:

 - __"banana-juseyo"__ for the original code on which this macro is based
    [Repository](https://github.com/banana-juseyo/Banana-Macro-PtcgP)
 - __"thqby"__ for WebView2 control in AutoHotkey
    [Repository](https://github.com/thqby/ahk2_lib)
 - __"TheArkive"__ for JXON_ahk2
    [Repository](https://github.com/TheArkive/JXON_ahk2)
