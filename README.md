installer
---------

TODO flow for the installer (a cross-platform executable jar):

* Ask if the user has purchased and installed Minecraft
    * If not, open minecraft.net in a browser and prompt to buy & install
    * Prompt to open the launcher and download an installation so forge can install
* Open consent form in the browser and prompt to fill it out
* Run the forge installer
* Copy herobraine.jar (TODO -- guarantee most recent version) to .minecraft/mods/
    * (The folder is located in %AppData% for Windows, /Users/<user>/Library/Application Support/minecraft on Mac, and ~/.minecraft on Linux)
* Prompt to open minecraft launcher and select '1.12 forge' profile, then launch
* Prompt to connect to mc.herobraine.stream with 'record' enabled
