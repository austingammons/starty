# starty

Python desktop app that allows setting and saving executables to run on the click of a button.
I use this application to quickly start multiple applications depending on what I want to do.
feel free to modify this python code to allow multiple savable files, I *might* release it myself within a month from 4/1/2023
don't hold your breath

# how to run locally

1. visit the code tab
2. click the green button with the text "<> code" to open a dropdown menu
3. select "download zip"
4. create a new folder on your desktop called "starty" or whatever you'd like
5. copy the "save.txt" and "app.py" files and paste them into the new folder that you just created from line 4
6. open the folder and double click on "app.py"
7. if on windows and prompted by "how do you want to open this?" choose python if available

note: if python is not available, you may need to download python to run this application

# how to use

1. once the application is running, click "Open File" button. a file explorer will be displayed
2. navigate to any folder that contains an executable or application file
3. click once on the file to highlight the file and click the button "Open" in the file explorer
4. you should now see the filepath in the white background section of the starty application
5. click the button "Run Apps" and verify the selected applications are started

# known issues

there may be an issue with saving selected executables. if you experience this issue, you can copy and paste file paths directly into 
the save.txt file. the filepaths need to be comma separated values. for example:

C:/Windows/notepad.exe,C:/Program Files/Jagex/RuneScape Launcher/RuneScape.exe,

if you attempt to run this application directly from the downloads folder, you may experience issues with the autosave feature.
