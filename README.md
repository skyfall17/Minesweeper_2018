# Minesweeper_2018
Version of the classic Minesweeper game written in C++ using Visual Studio Code 2017 and SFML (Simple and Fast Multimedia Library). Allows for debugging to reveal locations of all mine tiles.

SFML Documentation:
https://www.sfml-dev.org/

Ignore the x64 in the screenshots below. x86 should replace x64.

How to run:

Running on Visual Studio Code 2019:

Step 1:

Download Visual Studio Code 2019
https://visualstudio.microsoft.com/downloads/

Step 2:

Create a new folder to store files.

Open Visual Studio. Click "Clone a repository"
![alt text](https://github.com/skyfall17/Minesweeper_2018/blob/master/screenshots/Capture_1.JPG)

Copy the repository web url from Github and paste in Repository location. Select the folder you created in Local path. Click "Clone".
![alt text](https://github.com/skyfall17/Minesweeper_2018/blob/master/screenshots/Capture_2.JPG)

Step 3:

Make sure the Windows SDK Version is set to the latest one (10.0). If not, install here, https://developer.microsoft.com/en-us/windows/downloads/windows-10-sdk/, and select it.
![alt text](https://github.com/skyfall17/Minesweeper_2018/blob/master/screenshots/Capture_3.JPG)

Select the dropdown next to "Debug" containing "x64". Select x86 from the "Active solution platform" dropdown and make sure the Platform is "Win32".
![alt text](https://github.com/skyfall17/Minesweeper_2018/blob/master/screenshots/86.JPG)

Step 4:

Select "Solution Explorer" under the "View" tab.
![alt text](https://github.com/skyfall17/Minesweeper_2018/blob/master/screenshots/Capture_4.JPG)

Right click on the "MinesweeperTestClass" project and click "Properties".

Make sure "All Configurations" is selected.
![alt text](https://github.com/skyfall17/Minesweeper_2018/blob/master/screenshots/Capture_5.JPG)

Click the "Linker" tab on the left-hand window and click in the "Additional Library Directories" box dropdown. Click "<Edit...>" and the ellipsis in the textbox.
![alt text](https://github.com/skyfall17/Minesweeper_2018/blob/master/screenshots/Capture_6.JPG)
![alt text](https://github.com/skyfall17/Minesweeper_2018/blob/master/screenshots/Capture_7.JPG)

Go into the first folder you created, click the "sfml" folder, and select the "lib" folder. Click "Ok" and "Apply".

Step 5:

Click on the "Input" tab under "Linker" and edit the "Additional Dependencies" box. Enter the values from the image below. Click "Ok" and "Apply".
![alt text](https://github.com/skyfall17/Minesweeper_2018/blob/master/screenshots/Capture_8.JPG)

Select "Debug" under "Configuration:" and edit the values to match those below. Click "Ok" and "Apply".
![alt text](https://github.com/skyfall17/Minesweeper_2018/blob/master/screenshots/Capture_9.JPG)

Step 6:

Click the "C/C++" tab on the left-hand window and click in the "Additional Include Directories" box dropdown. Click "<Edit...>" and the ellipsis in the textbox. Go into the first folder you created, click the "sfml" folder, and select the "include" folder. Click "Ok" and "Apply".
![alt text](https://github.com/skyfall17/Minesweeper_2018/blob/master/screenshots/Capture_10.JPG)

Repeat this step for the "Release" Configuration.  Click "Ok" and "Apply".

Step 7:

Look within the "Solution Explorer". Double-click on the "MinesweeperTestClass.cpp" file under "Source Files". The file should display on-screen.

Make sure "Debug" is selected next to the "x86" dropdown.

Select "Build Solution" under the "Build" tab.

Select "Start Debugging" under the "Debug" tab or press fn F5 on your keyboard.

If you come up with the error below, enter the folder you created and select the new "Debug" folder. Copy the files from the "bin" folder below and paste them into the Debug folder.
![alt text](https://github.com/skyfall17/Minesweeper_2018/blob/master/screenshots/error.JPG)
![alt text](https://github.com/skyfall17/Minesweeper_2018/blob/master/screenshots/Capture_11.JPG)

Run the program again and now you should be able to play Minesweeper!

The solution should appear in the "Solutions and Folders" menu. Select it to open the solution.
