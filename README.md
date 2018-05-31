# Alteryx GUI Automation Tools

A set of [Alteryx](https://www.alteryx.com/) Designer tools written using the Python SDK for the purpose of GUI (Graphical User Interface) automation. The tools provide a no-code solution to writing GUI Automated tests when used in conjunction with Alteryx Designer.

_Note: These tools are not actively supported by Alteryx._

## Setup

- Alteryx Designer must be installed. Alteryx Designer versions 2018.1 and greater are recommended.
- Double-click a .yxi file in the YXI_Installers directory to install a tool. Alteryx Designer should handle the install.

## Documentation

*General*

- [Variable-value data stream paradigm](https://alteryx.github.io/ui-automation-samples/Help_Pages/VariableValueDataStreamFormat.html)
- [Common Tool Options](https://alteryx.github.io/ui-automation-samples/Help_Pages/CommonToolOptions.html)

*Tool-Specific*

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;_Note: Tool documentation can also be accessed via Alteryx by clicking the tool's help icon_

- [GUIClick](https://alteryx.github.io/ui-automation-samples/Help_Pages/GUIClickToolHelp.html)
- [GUIGetInfo]()
- [GUIKeyboard]()
- [GUIScreenshot]()
- [GUIStartExe]()

## Simple Example
In the Examples folder, there is an Alteryx workflow that uses a number of these tools to automate MS Notepad

## Code
To access the source code for a tool, you can either: 1. Install the tools and open them at the location in which they were installed (usually C:\ProgramData or C:\Users\yourUsername\AppData\Roaming\Alteryx\Tools), or 2. Rename the .yxi file of the tool in question, replacing .yxi with .zip, and extract the zip file.

Option #1 is recommended as it will allow you to see changes you make to the tools in Alteryx immediately.