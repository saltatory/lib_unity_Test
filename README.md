Git Submodules for Unity Demonstration
======================================

To share common libraries and code among game teams, we will use git submodules. This repository contains a simple script that outputs a Debug Log saying "git submodules for Unity libraries are cool!".

# Include the library

* In your Unity project, under `Assets/` create a folder for libraries `Assets/Libraries`.
* Clone this library (or another like it) as a submodule using `git submodule add <url>`

# Use the script

* Drag the script `Assets/Libraries/lib_unity_Test/LibraryScript` onto a scene object.
* Profit!
