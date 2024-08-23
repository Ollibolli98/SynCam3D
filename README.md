# 3D-Camera-system
This is a repository with files and manuals for the project "Developing a synchronized 3D camera system to estimate fish metrics".

When all hardware has been setup this repository has the most important files and manuals for users to initiate recording and process footage.

When the footage has been captured and transferred from the virtual desktop to a machine with the necessary softwares this is the following process:

STEP 1: Make sure the machine you are using has all the softwares correctly installed. A guide to FFMPEG and Python installlation is in this repository

STEP 2: Save the .mjpeg file in a directory (name it something easy fx. 3D_footage).

Step 3: Open the Terminal/Cmd-prompt on the machine.

STEP 4: Change the directory to the directory with the footage, example given: -cd path/to/desired/directory

STEP 5: Call the Python script from this repository. The command called has four variables (ORIGINAL_FOOTAGE.mjpeg, CONVERTED_FOOTAGE.mp4, LEFT_CAMERA_FOOTAGE.mp4, RIGHT_CAMERA_FOOTAGE.mp4). Example given: python -
split_test.py -NAME.mjpeg -NEW_NAME.mp4 -LEFT_VIDEO.mp4 -RIGHT_VIDEO.mp4

STEP 6: The processed files should all be downloaded to the same directory

STEP 7: Transfer the desired files (only left and right needed) to a machine that runs MAC OS, for calibration and video analysis in VidSync
