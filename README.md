# HaxeOpenUI5Externs 
(WARNING - Placeholder Project - NOT READY FOR USE)

Currently using yuidoc to parse openui5, but that will probably need to be changed
## Requirements
 NodeJS (https://nodejs.org/)
 
 Haxe & HaxeLib

```
npm -g install yuidocjs
haxelib git buildhx https://github.com/ddamerell53/buildhx.git
```

Make sure the node executable is available on your PATH along with the yuidoc executable installed above using npm.  If you find that yuidoc is not available it probably means the node_modules\\.bin directory is not on your PATH.

## Developing HaxeOpenUI5Externs 
```
  git clone https://github.com/ddamerell53/HaxeOpenUI5Externs.git
  cd HaxeOpenUI5Externs
  openui5_build.bat
```

You will find the externs in the output folder.

To make changes to the externs that are built alter the build file build_openui5.xml

You may need to make changes to the buildhx and yuidocjs projects to fill in gaps in the OpenUI5 documentation


