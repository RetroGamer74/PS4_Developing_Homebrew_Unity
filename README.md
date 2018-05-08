# PS4 Developing Homebrew Unity (4.55 by the way)
PS4 Developing HomeBrew with Unity is set of apps and info I've prepared for you, if you're interested on developing homebrew.

So this is all information you've got available from my repos.

Requirements
============

1.- Unity PS4

2.- SDK

Optional: Visual Studio if you want to also build the native code for the unjail plugin. If not you can use unjail with the already built library inluded.


Developments
============

1 - Unjail Plugin. Library PRX and C# sample to enable Unjail for the app you want to develop
=========================================================================================

Easy proof of concept to test the Unjail Plugin for Unity PS4. I made this plugin for all Unity PS4 developers to allow an app escalate privileges and get root. ( This feature is part of libHB from cfwprophet ).

https://github.com/RetroGamer74/PS4_Unity_Plugin_For_Running_Unjailed

2 - PS4-GBEmu Beta version and file scroll view. Unjailed.
==========================================================

An emulator App. It is a GBoy emulator, with many features, and a browser for files integrated. Gamepad and trackpad management. And many features for GUI interaction. Unjail included for testing also. You should connect your USB disk to your PS4 with a folder named ROMS in the root of your USB disk containing all files .gb as roms in there.

https://github.com/RetroGamer74/PS4_GBEmu_FileManager_Unjail

Video Sample: https://www.youtube.com/watch?v=GaqosWkmwGw

3 - Mediaplayer and File Manager. Unjailed.
===========================================

A media player with file browser and many other features. Similar to the one before, but this time with more file browsing features, and using common dialogs for PS4, la IME ( Keyboard on screen ). You can use this feature by selecting a file from the list and doing click on the Rename button, which is located on the right side. When you move over to the text box containing the name of the file, the keyboard will be shown. Change whatever you want with the keyboard and then press R2 to confirm. The text will appear in the textbox. So you've got the full procedure complete.

https://github.com/RetroGamer74/MediaPlayer_FileManager_Unjail

Video Sample: https://www.youtube.com/watch?v=RpoNpY6H9M4

4 - Source code C++/C for Unity Unjail Plugin ( Visual Studio 2015 Required )
=============================================================================

If you want to add Syscall to the Unjail Plugin you will need the full source code. You will need Visual Studio 2015 to build this, and of course the SDK.

https://github.com/RetroGamer74/PS4_UnjailPlugin_Unity_NativeCode


5 - How to compile and build Packages ( FPKG ) with Unity
=========================================================

Finally if you get further info about how to compile using Unity PS4 and create packages you can follow next tutorial:

https://github.com/RetroGamer74/HowToBuildWithUnityPS4FakePKG
