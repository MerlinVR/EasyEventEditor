# Easy Event Editor
Drop in replacement for the default Unity event editor drawer that allows listener reordering and a few other things

<img src="https://i.imgur.com/WC8HNid.gif" width="60%" height="60%" />

## Features
* Drag and drop reordering of Unity Event listeners in the inspector
* Gives easy access to private, internal, and obsolete methods/properties that Unity usually hides
* Allows editing of multiple of the same component type on the same object
* Provides an Invoke button on each event which executes the methods in the list (make sure you are in play mode if they are runtime only!)
* Adds hotkeys for editing events; hotkeys added are Add (Ctrl+A), Copy, Cut, Paste, Delete, and Duplicate

## Installation
1. Grab the EasyEventEditor.cs script by [downloading the zip](https://github.com/Merlin-san/EasyEventEditor/archive/master.zip) and put it somewhere in your project files or download [the most recent release](https://github.com/Merlin-san/EasyEventEditor/releases/latest) and open the .unitypackage in Unity. 

      If you want to install from the package manager, [download a zip](https://github.com/Merlin-san/EasyEventEditor/archive/master.zip) or clone the project and extract it to some directory outside of your project or into the `Packages` directory of your project. Then open the package manager and click the '+' button on the bottom left of the window, click "Add package from disk..." and navigate to the `package.json` file in the directory you extracted the zip to. For Unity 2019 and up you can add the package directly from the .git link that github gives you when you click the `Clone or download` dropdown.
      
2. You will now have everything enabled. To disable features that you don't want you will need to open the EEE settings menu.
3. Open the settings menu under Edit->Easy Event Editor Settings, or in 2018.3 and up open your editor Preferences and find the Easy Event Editor section. These settings will persist between projects, though you'll need to re-import the event editor script.

      <img src="https://i.imgur.com/V7DcLee.png" width="50%" height="50%" />
