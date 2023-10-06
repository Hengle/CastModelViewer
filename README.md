# CastModelViewer

[![license](https://img.shields.io/github/license/echo000/CastModelViewer.svg)]()

CastModelViewer is a fork of the original [SEModelViewer](https://github.com/Scobalula/SEModelViewer/) that adds Cast model loading

## How to Use 

Using CastModelViewer is very easy, to use CastModelViewer you can either load a folder of models by clicking the folder or load a single model/specific models by clicking the folder with a sheet of paper, the folder load method will parse all subdirectories and load any *.semodel or *.cast files found. If loading a folder that was exported from Wraith, Greyhound, or Legion (folder name contains "models"), it will provide a prompt to ask if you'd like to use a faster loading method that makes assumptions about model names based off the folder names. While models are loading you're free to view other models, but some parts of the application may be disabled while models are loading.

With models loaded you can click a model and use the arrow keys on your keyboard to cycle through models, you can also disable texture loading to increase model load speeds.

If you'd like to stop the current task (loading models, loading bone counts, etc.) then you can click the X button or press *CTRL+X*, pressing *CTRL+SHIFT+X* or double clicking the X button will clear loaded models. 

Pressing *CTRL+C* will copy the selected model's name, pressing CTRL+SHIFT+C will copy its file.

## Requirements

* Windows 10 64Bit (Windows 7/8/8.1 should work, but untested)
* Microsoft .NET Framework 4.7.2

## License / Disclaimers

CastModelViewer is licensed under the MIT license and it and its source code is free to use and modify under the MIT. CastModelViewer comes with NO warranty, any damages caused are solely the responsibility of the user. See the LICENSE file for more information.

For the most part the tool is stable and works well, it's unlikely to receive new features but if any issues occur then feel free to open an issue with as much info as possible!

## Download

The latest version can be found on the [Releases Page](https://github.com/echo000/CastModelViewer/releases).

## Credits

* Scobalula: ([SEModelViewer](https://github.com/Scobalula/SEModelViewer/)) The original project this is fundamentally based on and would be impossible without
* DTZxPorter: ([SELibDotNet](https://github.com/dtzxporter/SELibDotNet), [Cast](https://github.com/dtzxporter/cast))
* Helix Toolkit: ([https://github.com/helix-toolkit/helix-toolkit](https://github.com/helix-toolkit/helix-toolkit))
