# VL.Devices.Astra
A package for using [Astra](https://www.orbbec.com/products/#scroll-structured-light-camera) depth cameras by [Orbbec](https://www.orbbec.com/) in VL.

Try it with vvvv, the visual live-programming environment for .NET  
Download: http://visualprogramming.net

## Requirements:
* A recent vvvv version (>= 2020.1)
* [Orbbec Camera Driver >= 4.3.0.10](https://orbbec3d.com/index/download.html)

Currently using version 2.1.0 of the [Astra SDK](https://www.orbbec.com/developers/astra-sdk/).

Note that body tracking requires an extra license available in the [Orbbec Store](https://shop.orbbec3d.com/Orbbec-Body-Tracking-License), otherwise it only works for 30 minutes per launch!

## Using the library
In order to use this library with VL you have to install the nuget that is available via nuget.org. For information on how to use nugets with VL, see [Managing Nugets](https://thegraybook.vvvv.org/reference/libraries/dependencies.html#manage-nugets) in the VL documentation. As described there you go to the commandline and then type:

    nuget install VL.Devices.Astra

Once the VL.Devices.Astra nuget is installed and referenced in your VL document you'll see the category "Astra" under "Devices" in the nodebrowser. 

Demos are available via the Help Browser!
