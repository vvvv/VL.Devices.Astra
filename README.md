# VL.Devices.Astra
A package for using the (now legacy) [Astra](https://www.orbbec.com/products/structured-light-camera/astra-series/) depth cameras by [Orbbec](https://www.orbbec.com/) in VL.

Try it with vvvv, the visual live-programming environment for .NET  
Download: http://vvvv.org

## Requirements:
* [Orbbec Camera Driver >= 4.3.0.10](https://www.orbbec.com/developers/astra-sdk/)

Currently using version 2.1.0 of the [Astra SDK](https://www.orbbec.com/developers/astra-sdk/).

Note that body tracking required an extra license from Orbbec, which is no longer available today. So it only works for 30 minutes per launch!

## Using the library
In order to use this library with VL you have to install the nuget that is available via nuget.org. For information on how to use nugets with VL, see [Managing Nugets](https://thegraybook.vvvv.org/reference/libraries/dependencies.html#manage-nugets) in the VL documentation. As described there you go to the commandline and then type:

    nuget install VL.Devices.Astra

Once the NuGet is installed and referenced in your VL document you'll see the category "Astra" under "Devices" in the nodebrowser. 

Demos are available via the Help Browser!
