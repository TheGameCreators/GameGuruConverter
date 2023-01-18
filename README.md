# The GameGuru Classic Converter Repository

This is not open source and remains the copyright of The Game Creators Ltd.

GameGuru Classic Converter is a tool from the GameGuru Classic product, and is used to convert X files to DBO files. 

Steam Product: https://store.steampowered.com/app/266310/?utm_source=githubrepo&utm_campaign=general&utm_medium=web

This Guru-Converter.exe is to be placed in the GameGuru Classic root folder.

This source code requires Visual Studio 2017 Community Edition and is compiled as a 32-bit executable.

NOTE: If anyone would like to convert this project so it compiles and runs in 64-bit, that would be much appreciated. The DirectX code used to do the X file parsing is 32-bit only and there was no clear way of performing the same parse using a 64-bit executable. If this can be converted, the whole converter can be embedded into the now 64-bit version of GameGuru Classic.

TIP: There are MANY files in this project set that are not required for the converter to setup, load a X file, save a DBO file and exit.  A good cleanup exercise on a separate branch might be to see just how many files can be removed from this repo and still allow the Guru-Converter.exe to be compiled and run successfully :)
