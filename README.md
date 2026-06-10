# MayaPlugins
This is a collection of scripts that can be used as utility for Autodesk Maya. 

## Installation guide
1. Download the source code.zip of the [latest release](https://github.com/DeGekkeLamas/MayaPlugins/releases). 

2. Move all the files inside the .zip to `Documents\maya\scripts`.
     * Placing them in a subfolder of `Documents\maya\scripts` is supported, but all files from the .zip should be located in the same folder. 
     
3. In `Documents\maya\[YOUR MAYA VERSION]\scripts`, create a file named userSetup.mel and edit it in notepad or a different text editor to contain the text `source "llamaMenu.mel" ;`
     * If this file already exists, then add the text `source "llamaMenu.mel";` to it.
     * If you placed the files from step 2 in a subfolder, then that should be reflected in this step. For example, if the scripts are in a subfolder named LlamaScripts, then instead add the text `source "LlamaScripts/llamaMenu.mel" ;` to the file. 
     
4. Restart Maya to apply the changes made.

## What is included
- Control shapes: 
  - Recolor shapes: Edit the color of all selected curve objects without having to manually set it in the attribute editor.
  - Scale shapes: Change the scale of all selected curve objects without altering their transform, without needing to enter vertex selection mode.
  - Move shapes: Change the position of all selected curve objects without altering their transform or pivot, without needing to enter vertex selection mode.
- Geometry: 
  - Unfreeze transform: Allows you to "unfreeze" a transform by setting the position to a certain value without moving the actual geometry or pivot. 
