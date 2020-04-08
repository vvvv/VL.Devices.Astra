# VL.Devices.Astra
Set of nodes to use the Astra depth camera from Orbbec in VL.
Currently using version 2.1.0 of the Astra SDK.

Requirements:
* [Orbbec Camera Driver >= 4.3.0.10](https://orbbec3d.com/develop/)
* A recent vvvv version (VL must be >= 2019.2-0269)

Note that body tracking requires an extra license available in the [Orbbec Store](http://shop.orbbec3d.com/), otherwise it only works for 30 minutes per launch!

## Using the library
In order to use this library with VL you have to install the nuget that is available via nuget.org. For information on how to use nugets with VL, see [Managing Nugets](https://vvvv.gitbooks.io/the-gray-book/content/en/reference/libraries/dependencies.html#_manage_nugets) in the VL documentation. As described there you go to the commandline and then type:

    nuget install VL.Devices.Astra -pre

Once the VL.Devices.Astra nuget is installed and referenced in your VL document you'll see the category "Astra" under "Devices" in the nodebrowser. Demos can be found via the helpbrowser.