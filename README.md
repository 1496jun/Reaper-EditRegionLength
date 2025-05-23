## Change Region Length (REAPER Lua Script)


![image](https://github.com/user-attachments/assets/ea466b93-bda8-4827-bd53-eaacf06ebcfd)

↓

![image](https://github.com/user-attachments/assets/6ef741a0-2327-459a-88c4-0683a9786639)



This REAPER Lua script allows you to **extend or shorten the length of regions** within the currently selected time range by a user-specified number of seconds.  
It is especially useful for batch editing multiple regions without manually adjusting each one.

### Features
- Simple GUI input to enter the number of seconds (positive to extend, negative to shorten)
- Only affects regions entirely within the current time selection
- Automatically skips regions that would become zero or negative in length

### Usage
1. Select a time range in REAPER where the target regions are located.
2. Run the script.
3. Enter the number of seconds to extend or shorten.
4. The script adjusts the length of all regions within the selected time range accordingly.


### How to Install This REAPER Lua Script Manually

This repository contains a Lua script for REAPER.  
You can install it manually by following the steps below.
*This script is not currently distributed through ReaPack.

1. **Download the Lua file**
   - Click on the `EditRegionLength.lua` file in this repository.
   - Download raw file.
     
2. **Move the file to REAPER's Scripts folder**

   - In REAPER, go to `Options > Show REAPER resource path in explorer/finder`.
   - This will open the REAPER resource directory.
   - Inside this folder, open the `Scripts` folder (create it if it doesn't exist).
   - Move the downloaded `.lua` file into this `Scripts` folder.

3. **Load the script into REAPER**

   - In REAPER, go to `Actions > Show action list`.
   - Click the `ReaScript` tab.
   - Click the `Load...` button.
   - Navigate to the `Scripts` folder and select the `EditRegionLength.lua` file.
   - Click `Open`.

4. **Run the script**

   - Once loaded, you will see the script in the Action List.
   - Select it and click `Run`, or assign it to a shortcut key.



### Disclaimer

This script is provided **as-is** without any warranty.  
Use it **at your own risk**. Always make a backup of your REAPER project before running scripts that modify project data.
