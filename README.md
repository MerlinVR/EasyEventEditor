# Easy Event Editor
Drop in replacement for the default Unity event editor drawer that allows listener reordering and a few other things

<img src="https://i.imgur.com/WC8HNid.gif" width="60%" height="60%" />

## Features
* Drag and drop reordering of Unity Event listeners in the inspector
* Gives easy access to private, internal, and obsolete methods/properties that Unity usually hides
* Allows editing of multiple of the same component type on the same object
* Provides an Invoke button on each event which executes the methods in the list (make sure you are in play mode if they are runtime only!)

## Installation
1. Grab the EasyEventEditor.cs script by [downloading the zip](https://github.com/Merlin-san/EasyEventEditor/archive/master.zip) and put it somewhere in your project files or download [the most recent release](https://github.com/Merlin-san/EasyEventEditor/releases/latest) and open the .unitypackage in Unity.
2. You will now have the event dragging enabled by default, but to enable the other features you will need to open the EEE settings menu.
3. Open the settings menu under Editor->Easy Event Editor Settings and enable what you want. These settings will persist between projects, though you'll need to re-import the event editor script.

      <img src="https://i.imgur.com/V7DcLee.png" width="50%" height="50%" />
