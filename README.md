# Binary-Releases
Repo for binary releases.

Please check here for latest releases of Misc tools: https://github.com/ctn123/Binary-Releases/releases

# Tools Included:
- PS4 Save Mounter
  - **Note:** I'm not the original author of PS4 Save Mounter. I only tried to make it better.
    - Original Save Mounter can be found here: https://github.com/ChendoChap/Playstation-4-Save-Mounter
      - By ChendoChap
  - Universal Firmware support (5.05, 6.72, 7.0X, 7.5X)
    - Single ps4debug payload
  - Updated to ps4debug v1.1.13
  - Split Setup button into Patch and Get Users
  - Unpatch function so you don't need to reboot the PS4 after using Save Mounter
    - Failure to do this previously might result in a corrupted Save
  - Auto unmount and unpatch upon Save Mounter termination
    - In case you forget, just because, just in case
  - Option to get title ids from orbispatches
  - Option to specify port
  - Create Save
    - Option to snap to nearest MB
    - Text box to precisely key in MB save size
  - Store IP and Port in Config instead of a text file.
     - Port is now saved between runs
