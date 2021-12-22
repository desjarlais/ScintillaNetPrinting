# SintillaNetPrinting
Add print functionallity to ScintillaNet 3.x https://github.com/jacobslusser/ScintillaNET

[![Nuget](https://img.shields.io/nuget/v/ScintillaNetPrinting.NET)](https://www.nuget.org/packages/ScintillaNetPrinting.NET/)

To Use it:

Include ScintillaNetPrinting folder in your porject along with ScintillaNet 3.x and reference it:


ScintillaNetPrinting.Printing printer = new ScintillaNetPrinting.Printing(ScintillaNet);

printer.PageSettings = new ScintillaNetPrinting.PageSettings() 
{ 
    ColorMode = ScintillaNePrinting.PageSettings.PrintColorMode.BlackOnWhite 
};

printer.Print();

or

printer.PrintPreview();

This is a copy and adaptation of original printing functionallity of ScintillaNet 2.6 version.


## The .NET package
The package ending with .NET is depended upon the new Scintilla 5 series [Scintilla.NET](https://www.nuget.org/packages/Scintilla.NET/) and is in active development. The other package's Scintilla dependency is no longer being maintained even though the codebase of the dependent software may be maintained.

### Thanks to
* [JetBrains](https://www.jetbrains.com/?from=ScintillaNetPrinting) for their open source license(s).
* [![.NET Desktop](https://github.com/VPKSoft/SintillaNetPrinting/actions/workflows/dotnet-desktop.yml/badge.svg)](https://github.com/VPKSoft/SintillaNetPrinting/actions/workflows/dotnet-desktop.yml)

[![JetBrains](http://www.vpksoft.net/site/External/JetBrains/jetbrains.svg)](https://www.jetbrains.com/?from=SintillaNetPrinting)
