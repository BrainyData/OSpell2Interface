# OSpell2 Interface

The library implements the Omnis Studio interface for Brainy Data's external spell checker kernel. The library can be used as is to add spell checking to any Omnis Studio library.

To build the library you will require the OWrite and OSpell2 external components by Brainy Data.

If you do not have them, demo versions are available at https://www.brainydata.com/demos. Furthermore, additional files and libraries are required which can also be downloaded from the same location.

The specific downloads are:

https://www.brainydata.com/demos/software/owrite_document_manager.zip
https://www.brainydata.com/demos/software/jsowrite_demo_software_mac.zip
https://www.brainydata.com/demos/software/jsowrite_demo_software_win.zip

These downloads may include additional example libraries and files that are not required.

Please refer to the online documentation for further information.
https://www.brainydata.com/supportpublic/documentation.htm

## Contents

### OSpell2Interface

This folder contains the JSON source files for the Omnis library in Github.

To restore these files in Omnis Studio, click 'Libraries' in the Studio Browser, then click 'New Lib from JSON'. In the import dialog, navigate to this source folder (containing library.json), then specify a different location for the new Library. Click on Import and open the library in the Studio Browser.

Before importing, ensure you have loaded the OSpell2 library and installed the required external components.

To test your builds, simply replace the library with the identical name in the downloaded folders, with the ones you have just build.
