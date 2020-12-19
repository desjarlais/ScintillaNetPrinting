# SintillaNetPrinting
Add print functionallity to ScintillaNet 3.x https://github.com/jacobslusser/ScintillaNET

[![Nuget](https://img.shields.io/nuget/v/ScintillaNetPrinting)](https://www.nuget.org/packages/ScintillaNetPrinting/)

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


## The SUO package
The SUO stands for [unofficial.ScintillaNET](https://www.nuget.org/packages/unofficial.ScintillaNET/) dependency which is updated with the recent pull requests build from this [ScintillaNET fork](https://github.com/VPKSoft/ScintillaNET) from the original [ScintillaNET](https://github.com/jacobslusser/ScintillaNET). The fork was made to try to keep up with the changes to the code base suggested by users as the official version is getting outdated for unknown reason(s) 🙄.

### Thanks to
* [JetBrains](https://www.jetbrains.com/?from=ScintillaNetPrinting) for their open source license(s).
* [![VPKSoft](https://circleci.com/gh/VPKSoft/ScintillaNetPrinting.svg?style=shield)](https://app.circleci.com/pipelines/github/VPKSoft/ScintillaNetPrinting) 

[![JetBrains](http://www.vpksoft.net/site/External/JetBrains/jetbrains.svg)](https://www.jetbrains.com/?from=SintillaNetPrinting)
