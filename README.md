# VL.Devices.Astra
Set of nodes to use the Astra depth camera from Orbbec in vl.

Be sure to have the [Orbbec Camera Driver >= 4.3.0.10](https://orbbec3d.com/develop/) installed.

Currently using SDK 2.0.19 valid until March 31, 2020 without a [license](http://shop.orbbec3d.com/Orbbec-Body-Tracking-License_p_55.html). After this date we need to update to the new [Orbbec Astra SDK](https://orbbec3d.com/develop/).

## Using the library
In order to use this library with vl you have to install the nuget that is available via nuget.org. For information on how to use nugets with vl, see [Managing Nugets](https://vvvv.gitbooks.io/the-gray-book/content/en/reference/libraries/dependencies.html#_manage_nugets) in the vl documentation. As described there you go to the commandline and then type:

    nuget install VL.Devices.Astra -prerelease

Once the VL.Devices.Astra nuget is installed and referenced in your vl document you'll see the category "Astra" under "Devices" in the nodebrowser.

VL help patches can be found here:

    "VL.Devices.Astra\help\"
