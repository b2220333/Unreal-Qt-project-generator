# Unreal-Qt-project-generator
This small console utility generates QtCreator projects for Unreal Engine 4 gameplay programming.
It should in theory work with any version of Unreal Engine 4 (not tested)

The tool can generate .pro files with:
<ul>
  <li>Configuration for Unreal Engine development (C++11 support, no Qt)
  <li>All your current source and header files (+ build.cs) included</li>
  <li>All Unreal Engine defines and includes added</li>
  <li>5 different build and launch targets, which are included in the Visual Studio project file (Debug game, Development Editor, Shipping, etc...)</li>
</ul>

For more information and a tutorial how to setup QtCreator see this post:
https://forums.unrealengine.com/showthread.php?59458-TOOL-Tut-WIN-Unreal-Qt-Creator-Project-Generator-(v0-1-Beta)

Info: I have only tested the tool on my computers with Windows 8.1, QtCreator 3.3.0/3.5.0 and Unreal Engine 4.4/4.5/4.8
