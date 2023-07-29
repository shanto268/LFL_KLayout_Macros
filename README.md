# LFL KLayout Macros:

Some KLayout macros that I use to speed up NBR design work...

## Installation:

## Custom PCell Library:

1. **Launch KLayout**: Start the KLayout application on your system.

2. **Add Macro Directory to KLayout**: In KLayout, go to `Macro Development` > `Macros` > `Add Location To Search Path`. In the dialog box that opens, navigate to the location of this repository on your system and click `Open`. This will add the directory to KLayout's macro search path, and KLayout will automatically load all `.lym` files in that directory.

3. **Execute the `RunLibrary.lym` Macro**: After adding the directory, all the macros in the directory will be loaded automatically. To load all the PCells into the library, you need to execute the `RunLibrary.lym` macro. You can do this by going to `Macro Development` > `Macros`, selecting the `RunLibrary.lym` macro, and clicking on the `Run` button. This macro will register all the custom PCells and add them to your library.

## Other Functional Macros:

1. **Load the Functional Macro Files**: In KLayout, go to `Macro Development` > `Macro` > `Run/Debug Macro`. In the dialog box that opens, navigate to the location of this repository on your system. You will see multiple `.lym` files. Select each functional macro file (`GetCouplingCapStats.lym`, `GetPolygonLength.lym`, `PathToCPW.lym`, `ViewLayoutCenter.lym`) and click `Open` to load them one by one.

2. **Run the Macros**: After loading each macro file, you can run the macros by selecting them and clicking on the `Run` button. Repeat this step for each macro file you've loaded.

3. **Use the Macro Functions**: The functions provided by the macros can now be used. The specific usage will depend on the functions provided by each `.lym` macro file.
