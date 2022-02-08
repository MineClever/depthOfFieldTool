# depthOfFieldTool
DepthOfFieldTool is a user-defined MPxContext which provides enhanced viewport depth of field effect / workflow in Autodesk Maya.

![Example depth of field created with the depthOfFieldTool](/images/depthOfFieldStill1.png)
![Example depth of field created with the depthOfFieldTool](/images/depthOfFieldStill2.png)



# Video Tutorial:
[![Watch the video](/images/depthOfFieldStill4.png)](https://vimeo.com/674970811)



# How to install:

### Automated installation: (Requires Maya 2022 with Python 3.7)
1. Unzip the archive.
2. Drag and drop the "dragDropInstaller.py" into the Maya 3d viewport.
3. Follow the steps on screen.

### Manual installation:
1. Close all running instances of Maya.
2. Go to your Maya modules directory (create the "modules" folder if it does not exist):
```
(Windows) /Users/<username>/Documents/maya/modules/
(Mac OS X) $HOME/Library/Preferences/Autodesk/maya/modules/
(Linux)	$HOME/maya/modules/
```
3. Copy the "depthOfFieldTool" folder and "depthOfFieldTool.mod" file in the modules folder.

![depthOfFieldTool loaded in Maya](/images/depthOfFieldStill3.png)

4. Start Maya, the module will be loaded and the console should print out:
```
// Successfully imported plugin module 'depthOfFieldTool' v.X.X.X //
```



# How to use:
After loading the plugin in Maya, type `depthOfField` in the mel command line to activate the tool.
#### Mel:
```
depthOfField
```



# Supported Maya versions and platforms:
```
Windows: Maya 2022, 2020
Linux:   Maya 2022
MacOS:   Coming Soon
```

# Release Notes:
```
Version 1.0.0

Initial release
```
