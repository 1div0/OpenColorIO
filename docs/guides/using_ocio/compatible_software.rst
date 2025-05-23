..
  SPDX-License-Identifier: CC-BY-4.0
  Copyright Contributors to the OpenColorIO Project.

.. _compatiblesoftware:

Compatible Software
===================

The following software all supports OpenColorIO (to varying degrees).

If you are interested in getting OCIO support for an application not listed
here, please contact the ocio-dev mailing list.

If you are a developer and would like assistance integrating OCIO into your
application, please contact ocio-dev as well.


3ds Max (Autodesk)
******************

Website : `<https://www.autodesk.com/products/3ds-max/overview>`__

Supported Version: >= 2024

Documentation :

- `Color Management <https://help.autodesk.com/view/3DSMAX/2024/ENU/?guid=GUID-AF6FB34D-5453-4AE2-A987-388A4BB5AAFD>`__

- `OCIO color management in Autodesk 3DS Max 2024.1 <https://youtu.be/dlwDiLsPWgI?feature=shared>`__


After Effects
*************

An OpenColorIO plugin is available for use in After Effects.

Website: `<http://www.adobe.com/products/aftereffects.html>`__

Documentation :

- See `src/aftereffects <http://github.com/AcademySoftwareFoundation/OpenColorIO/tree/main/src/aftereffects>`__ if you are interested in building your own OCIO plugins.

- Pre-built binaries are also available for `download <http://fnordware.blogspot.com/2012/05/opencolorio-for-after-effects.html>`__, courtesy of `fnordware <http://www.fnordware.com>`__.


Anchorpoint
***********

Anchorpoint is a file browser and asset manager for VFX, animation and real-time projects. It supports OCIO configs to display OpenEXR with the correct color profile.

Website: `<https://www.anchorpoint.app>`__

Documentation :

- `Display OpenEXR with OpenColorIO <https://www.anchorpoint.app/features/color-management>`__


Arnold (Autodesk)
*****************

Website : `<https://www.autodesk.com/products/arnold/overview>`__

Documentation :

- `Color Management <https://help.autodesk.com/view/ARNOL/ENU/?guid=arnold_user_guide_ac_color_management_html>`__


Blender
*******

Blender has integrated OCIO as part of it's redesigned color management system.

Website: `<http://www.blender.org/>`__

Supported Version: >= 2.64

Documentation:

- `Blender 2.64 Release Notes <https://archive.blender.org/wiki/index.php/Dev:Ref/Release_Notes/2.64/>`__

- `Color Management <https://archive.blender.org/wiki/index.php/Dev:Ref/Release_Notes/2.64/Color_Management/>`__



C++
***

The core OpenColorIO API is available for use in C++. Minimal code examples are also available in the source code distribution. 

Website: `<http://github.com/AcademySoftwareFoundation/OpenColorIO/tree/main/include/OpenColorIO>`__

Examples:

- `ocioconvert <https://github.com/AcademySoftwareFoundation/OpenColorIO/tree/main/src/apps/ocioconvert>`__

- `ociodisplay <https://github.com/AcademySoftwareFoundation/OpenColorIO/tree/main/src/apps/ociodisplay>`__

Documentation:

- :ref:`developing`

- :ref:`developers-usageexamples`


cineSync (ftrack)
*****************

Website : `<https://cospective.com/cinesync/>`__

Documentation :

- `Colour Grading <https://www.cinesync.com/manual/latest/Colour_Grading.html>`__


Clarisse (Isotropix)
********************

Website: `<https://www.isotropix.com/products>`__

Documentation:

- `Managing Looks with OpenColorIO <https://www.isotropix.com/learn/tutorials/managing-looks-with-opencolorio-ocio>`__


ColorBox (AJA)
**************

In-line HDR/SDR Algorithmic and LUT Color Transforms. Available as a standalone unit (ColorBox) and also as an openGear card (OG-ColorBox).

Website : `<https://www.aja.com/products/colorbox>`__

Website : `<https://www.aja.com/products/og-colorbox>`__

Supported Version : >= 3.0


CryEngine (CryTek)
*******************

CryEngine is a real-time game engine, targeting applications in the motion-picture market. While we don't know many details about the CryEngine OpenColorIO integration, we're looking forward to learning more as information becomes available.

Website: `<https://www.cryengine.com/>`__


Disguise
********

Disguise is an integrated hardware and software platform powering the world's biggest live events, immersive experiences and virtual production stages. OpenColorIO is integrated into the Designer software, allowing users to manage the color spaces of all content sources and physical output devices.

Website: `<http://disguise.one/>`__

Supported version: >= 29.1

Documentation:


- `OpenColorIO Support <http://help.disguise.one/designer/colour-management/ocio.html>`__

- `Color Management <http://help.disguise.one/designer/colour-management/colour-management-overview.html>`__


DJV
***

Website: `<https://darbyjohnston.github.io/DJV/>`__


Flame (Autodesk)
****************

Website: `Autodesk Flame <https://www.autodesk.com/products/vred/overview>`__

Supported version: >= 2026

Documentation:

- `OCIO in Flame <https://help.autodesk.com/view/FLAME/2026/ENU/?guid=colour-management_opencolorio>`__


Gaffer
******

Gaffer is a node based application for use in CG and VFX production, with a particular focus on lighting and look development.

Website: `<http://www.gafferhq.org/>`__


Guerilla Render
***************

Composed of Guerilla Station and Guerilla Render, Guerilla is a Production-Proven Look Development, Assembly, Lighting and Rendering Solution designed for the Animation and VFX industries.

Website: `<http://guerillarender.com/>`__

Supported version: >= 2.2

Documentation:


- `OpenColorIO Support <http://guerillarender.com/doc/2.2/TD%20Guide_Technical%20Notes_OpenColorIO.html>`__

- `OCIO Management <http://guerillarender.com/?p=424>`__


Hiero (Foundry)
***************

Hiero ships with native support for OCIO in the display and the equivalent of Nuke's OCIOColorSpace in the Read nodes. It comes with the "nuke-default" OCIO config by default, so the Hiero viewer
matches when sending files to Nuke for rendering.

Website: `<https://www.foundry.com/products/hiero>`__

Supported version: >= 1.0


Houdini (SideFX)
****************

Website: `<https://www.sidefx.com>`__

Supported Version: >= 16

Documentation:


- `OpenColorIO Support <https://www.sidefx.com/docs/houdini/io/ocio.html>`__

- `What's new in Houdini 16 <https://www.sidefx.com/filmtv/whats-new-h16/>`__


Katana (Foundry)
****************

Website: `<http://www.thefoundry.co.uk/products/katana>`__

Documentation:

- `Managing Color <https://learn.foundry.com/katana/Content/ug/rendering_scene/managing_color.html>`__

- `Color Nodes <https://learn.foundry.com/katana/Content/rg/color_2d.html>`__


Krita
*****

Krita now support OpenColorIO for image viewing, allowing for the accurate painting of float32/OpenEXR imagery.

Website: `<http://www.krita.org/>`__

Documentation :

- `Krita Starts Supporting OpenColorIO <https://krita.org/en/item/krita-starts-supporting-opencolorio/>`__.


Mari (Foundry)
**************

Website: `<https://www.foundry.com/products/mari>`__

Supported Version: >= 1.4v1

Documentation:

- `Managing Colors in Mari <https://learn.foundry.com/mari/4.0/Content/user_guide/managing_colors/anaging_colors_in_mari.html>`__

- `Color Management <https://learn.foundry.com/mari/4.0/Content/user_guide/managing_colors/color_management.html>`__


Maya (Autodesk)
***************

Autodesk Maya is a 3D computer animation, modeling, simulation, and rendering software.

Website: `<https://www.autodesk.com/products/maya/overview>`__

Supported Version: >= 2016

Documentation:

- `Get Started with Color Management <https://help.autodesk.com/view/MAYAUL/2024/ENU/?guid=GUID-B260195C-A0FE-4F51-9EA2-099B61B7725A>`__

- `Color Management in Maya: Setting up a scene <https://youtu.be/bVYg8ZyljLs>`__

- `Color Management in Maya: Input Spaces <https://youtu.be/biGWwdqaimY>`__

- `Color Management in Maya: Previewing and Rendering <https://youtu.be/Pvxqc5NC_b4>`__

- `Color Management in Maya: Color Picking <https://youtu.be/mgKHMrJ8DIY>`__

- `Color Management in Maya: ACES default <https://youtu.be/FODVxXOIrvM>`__


Mocha Pro (Boris FX)
********************

Website: `<https://borisfx.com/products/mocha-pro>`__

Supported Version: >= 2020

Documentation: 

- `Color Management <https://borisfx.com/videos/opencolorio-mocha-pro-2020/>`__


Modo (Foundry)
**************

Website: `<https://www.foundry.com/products/modo>`__

Documentation:

- `Color Management <https://learn.foundry.com/modo/content/help/pages/rendering/color_management.html>`__


mrViewer
********

mrViewer is a professional flipbook player, hdri viewer and video/audio playback tool. It supports OCIO input color spaces in images as well as display/view color spaces.

Website: `<https://mrviewer.sourceforge.io>`__

Documentation:

- `mrViewer Features <https://mrviewer.sourceforge.io/features.html>`__


Natron
******

Natron is an open source 2D compositor that ships with native support for OCIO. Standard configs are included however users can also point to custom configs in the color management section of the user preferences.

Website : `<https://natrongithub.github.io/>`__

Documentation :

- `Color Nodes <https://natron.readthedocs.io/en/rb-2.3/_groupColor.html>`__


Nuke (Foundry)
**************

Nuke ships with native support for OpenColorIO. There is also an available `"nuke-default" OCIO config <https://github.com/imageworks/OpenColorIO-Configs/tree/master/nuke-default>`__, which matches the built-in Nuke color processing. This profile is useful for those who want to mirror the native Nuke color processing in other applications (the underlying equations are also provided as python code in the config as well).

Website : `<https://www.foundry.com/products/nuke>`__

Supported Version: >= 6.3v7

Documentation:

- `OCIO Color Management <https://learn.foundry.com/nuke/content/comp_environment/configuring_nuke/using_ocio_config_files.html>`__

- `Color Nodes <https://learn.foundry.com/nuke/content/reference_guide/color_nodes/color_nodes.html>`__


OpenImageIO
***********

OIIO's C++ and Python bindings include several methods for applying color transforms to whole images, notably functions in the ImageBufAlgo namespace including **colorconvert()**, **ociolook()**, **ociodisplay()**, **ociofiletransform()**. These are also available as part of the *oiiotool* command line utility (--colorconvert, --ociolook, --ociodisplay, --ociofiletransform) and the *maketx* utility for preparing textures also supports **--colorconvert**. From C++, there is additional low-level functionality in the header **OpenImageIO/color.h** that are wrappers for accessing underlying OCIO color configurations and doing color processing on individual pixel values.

Website : `<http://openimageio.org>`__


PhotoFlow
*********

PhotoFlow supports OCIO via a dedicated tool that can load a given configuration and apply the available color transforms. So far the tool has been tested it with the `Filmic <https://github.com/sobotka/filmic-blender>`__ and `ACES <https://opencolorio.org/configurations/aces_1.0.3.html>`__ configs.

Website : `<https://github.com/aferrero2707/PhotoFlow>`__


Photoshop
*********

OCIO can be enabled via OpenColorIO settings. For more details see `OpenColorIO and tools with 32-bit mode <https://helpx.adobe.com/photoshop/using/opencolorio-transform.html>`__.

Photoshop Fnordware plugin
**************************

An OpenColorIO plugin is also available for use in Photoshop. The plug-in can perform color operations to an image as a filter and can also export LUTs and ICC profiles to be used by Photoshop.

Plugin binaries are available for `download <http://fnordware.blogspot.com/2017/02/opencolorio-for-photoshop.html>`__, courtesy of `fnordware <http://www.fnordware.com>`__.


Python
******

The OpenColorIO API is available for use in Python.

Website: `<https://pypi.org/project/opencolorio/>`__

Documentation:

- :ref:`developing`

- :ref:`developers-usageexamples`


RV (Autodesk)
*************

Website : `<https://www.autodesk.com/products/flow-production-tracking/overview>`__

OpenRV : `<https://github.com/AcademySoftwareFoundation/OpenRV>`__

Supported Version:  >= 4

Documentation : 

- For more details, see the OpenColorIO section of the `RV User Manual <https://aswf-openrv.readthedocs.io/en/latest/rv-manuals/rv-user-manual/rv-user-manual-chapter-eleven.html>`__.


Silhouette (Boris FX)
*********************

OCIO is natively integrated in Silhouette. Full support is provided for both image import/export, as well as image display.

Website : `<https://borisfx.com/products/silhouette/>`__

Supported Version: >= 4.5


Substance Designer (Adobe)
**************************

Website: `<https://www.substance3d.com/products/substance-designer/>`__

Supported version: >= 2019.3

Documentation:

- `Color Management with OpenColorIO <https://magazine.substance3d.com/substance-designer-winter-2019-color-management-with-opencolorio/>`__

- `Color Management <https://docs.substance3d.com/sddoc/color-management-188973971.html>`__


TouchDesigner (Derivative)
**************************

Website: `<https://derivative.ca/>`__

Documentation:

- `OpenColorIO TOP <https://derivative.ca/UserGuide/OpenColorIO_TOP/>`__


Unreal Engine (Epic Games)
**************************

Website : `<https://unrealengine.com>`_

Supported Version : >= 4.22

Documentation :

- `OCIO Plugin API <https://docs.unrealengine.com/en-US/API/Plugins/OpenColorIO/index.html>`_
- `Unreal Engine 4.22 Release Notes <https://docs.unrealengine.com/en-US/Support/Builds/ReleaseNotes/4_22/index.html>`_


Vegas Pro (Magix)
*****************

Vegas Pro uses OpenColorIO, supporting workflows such as S-log footage via the ACES colorspace.

Website : `<http://www.sonycreativesoftware.com/vegaspro>`__

Supported Version: >= 12


V-Ray (Chaos Group)
*******************

Website : `<https://chaosgroup.com>`__

Documentation :

- `OpenColorIO support <https://docs.chaosgroup.com/display/VRAY4MAX/OpenColorIO+Support>`__

- `VRayTexOCIO <https://docs.chaosgroup.com/display/VRAY4MAYA/VRayTexOCIO>`__


VRED (Autodesk)
***************

Website : `<https://www.autodesk.com/products/vred/overview>`__

Supported Version: >= 2025.3

Documentation :

- `Autodesk VRED 2025.3 <https://help.autodesk.com/view/VREDPRODUCTS/2025/ENU/?guid=color-vred-20253>`__



Apps w/icc or luts
******************

flame (.3dl), lustre (.3dl), cinespace (.csp), houdini (.lut), iridas_itx (.itx)
photoshop (.icc)

Export capabilities through ociobakelut::

    $ ociobakelut -- create a new LUT or icc profile from an OCIO config or lut file(s)
    $ 
    $ usage:  ociobakelut [options] <OUTPUTFILE.LUT>
    $ 
    $ example:  ociobakelut --inputspace lg10 --outputspace srgb8 --format flame lg_to_srgb.3dl
    $ example:  ociobakelut --lut filmlut.3dl --lut calibration.3dl --format flame display.3dl
    $ example:  ociobakelut --lut look.3dl --offset 0.01 -0.02 0.03 --lut display.3dl --format flame display_with_look.3dl
    $ example:  ociobakelut --inputspace lg10 --outputspace srgb8 --format icc ~/Library/ColorSync/Profiles/test.icc
    $ example:  ociobakelut --lut filmlut.3dl --lut calibration.3dl --format icc ~/Library/ColorSync/Profiles/test.icc
    $ 
    $ 
    $ Using Existing OCIO Configurations
    $     --inputspace %s      Input OCIO ColorSpace (or Role)
    $     --outputspace %s     Output OCIO ColorSpace (or Role)
    $     --shaperspace %s     the OCIO ColorSpace or Role, for the shaper
    $     --iconfig %s         Input .ocio configuration file (default: $OCIO)
    $ 
    $ Config-Free LUT Baking
    $     (all options can be specified multiple times, each is applied in order)
    $     --lut %s             Specify a LUT (forward direction)
    $     --invlut %s          Specify a LUT (inverse direction)
    $     --slope %f %f %f     slope
    $     --offset %f %f %f    offset (float)
    $     --offset10 %f %f %f  offset (10-bit)
    $     --power %f %f %f     power
    $     --sat %f             saturation (ASC-CDL luma coefficients)
    $ 
    $ Baking Options
    $     --format %s          the lut format to bake: flame (.3dl), lustre (.3dl),
    $                          cinespace (.csp), houdini (.lut), iridas_itx (.itx), icc (.icc)
    $     --shapersize %d      size of the shaper (default: format specific)
    $     --cubesize %d        size of the cube (default: format specific)
    $     --stdout             Write to stdout (rather than file)
    $     --v                  Verbose
    $     --help               Print help message
    $ 
    $ ICC Options
    $     --whitepoint %d      whitepoint for the profile (default: 6505)
    $     --displayicc %s      an icc profile which matches the OCIO profiles target display
    $     --description %s     a meaningful description, this will show up in UI like photoshop
    $     --copyright %s       a copyright field
    


See this `ocio-dev thread 
<https://lists.aswf.io/g/ocio-dev/topic/30498585>`__
for additional usage discussions.

When exporting an ICC Profile, you will be asked to specify your monitor’s
profile (it will be selected for you by default). This is because ICC Profile
are not LUTs per se. An ICC Profile describes a color space and then needs a
destination profile to calculate the transformation. So if you have an operation
working and looking good on the monitor you’re using (and maybe its
should choose its profile instead.
