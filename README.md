# Syntax highlighting and language features for PHREEQC

This extension brings syntax highlighting to PHREEQC in VSCode.
It borrows heavily from the syntax highlighting features from the original Notepad++ version.

[Notepad++ distribution](https://www.hydrochemistry.eu/)



## Usage

After installation, open a `.phr` file and edit it as you would any scripting language. syntax highlighting will appear and basic language functionality will be available (eg. commenting and indentation). Press Ctrl+F5 to run PHREEQC files directly from VS Code (if installed and added to path). A terminal must be open for the command to execute.

This package does not include a Phreeqc installation. If you need to install PHREEQC,you will have to do it yourself. Both distributions should work:

- [Appelo's webiste](https://www.hydrochemistry.eu/)
- [USGS](https://www.usgs.gov/software/phreeqc-version-3)

For Ctrl+F5 execution functionality, PHREEQC must be installed and added to your system PATH. For PhreePlot support (.ppi files), install [PhreePlot](https://www.phreeplot.org/) and ensure pp.exe is accessible in your PATH.


## Quickstart

Install it in VSCode marketplace or by downloading the .vsix file from the repository and you are ready to go!

<p align="center">
<img src="images/syntaxscreenrecording.gif" width=75%>
<br/>
<em>(Example file)</em>
</p>

## Installation

 1. Press install in the marketplace  
 or  
 2. Download this extension `.vsix` file and follow the following steps:
   
  2.1. Open Visual Studio Code.

  2.2. Open the Extensions View:

    2.2.1. Click on the Extensions icon in the Activity Bar on the side of the window Alternatively, you can open it by pressing Ctrl+Shift+X.
  2.3. Install from VSIX:

    2.3.1. Click on the ... (More Actions) button at the top of the Extensions view.
    2.3.2. Select Install from VSIX... from the dropdown menu.
    2.3.4.  Select the .vsix File:

A file dialog will open. Navigate to the directory where your .vsix file is located.
Select the .vsix file and click Open.
  2.4. Restart Visual Studio Code

## Disclaimer

This extension provides syntax highlighting and execution shortcuts for PHREEQC and PhreePlot files. The execution functionality runs external commands and does not interfere with how PHREEQC or PhreePlot process the scripts. Use it at your own risk.
This project is not an official PHREEQC or USGS project, nor it is endorsed by the authors of PHREEQC and related organizations.

## Uninstalling

When uninstalling this extension, keybindings and syntax highlighting are automatically removed. File encoding settings for .out and .sel files will remain in your VS Code settings. To remove these, go to Settings and search for "encoding" to reset any unwanted defaults.

## License

[MIT](https://choosealicense.com/licenses/mit/)

