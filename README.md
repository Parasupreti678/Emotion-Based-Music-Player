# emotion-based-music-player

Nearly all sorts of human emotions have a direct relationship with the particular music genre, and most people think that music is expressive and that its expressivity can be easily tied to people's emotions. The normal way to tell if a person is feeling happy, sad, angry, scared, depressed, or tender is by looking at their facial expressions. Humans' emotions can be altered by music, which may also have an impact on their mood and health. One of the first methods for treating some psychological illnesses is musical therapy. An intelligent system that organizes a music collection based on the genres each song conveys and then suggests a well-suited music playlist to the psychiatrist for the patients based on their facial expressions is created by the combination of musical therapy and facial emotion detection. The picture is put through facial recognition and emotion recognition. the patients' techniques. The tunes that go with The greatest playlist for this emotion is then suggested. results in calming and relaxing patients.

This is a project using machine learning for detecting emotions based on the expression of the users. The interface is made up of HTML, CSS and JS, and the main code is of Python.


This code is developed in Ubuntu Linux, with eel , opencv and Python downloaded.  
For running the code in Windows or Mac, certain path changes are required.


Please make sure you have the following in your machine...

Note: I have downloaded python using Anaconda.

Python version: 3.6.5 (Try to download all python modules)(Important modules: glob, os, numpy, random, argparse, time)
Eel version: 0.9.10 (download link: https://github.com/ChrisKnott/Eel)
Opencv version: 3.4.3 (Full opencv module. Fisherface module is must)
Chrome browser is needed (eel library is specifically designed for chrome)

Download all the files in a folder. Open terminal in the same folder. 

Type the command 'python capture.py' in terminal. 

A window will open in chrome browser having the interface of the player. Select emotion mode from the right bottom corner. This will start the webcam. Face will be scanned in the ending of the currently playing song. You can manually move the song controller near the end to start the function. 

When emotion is detected, you can see the name of the emotion in the terminal open.

Refer to READIT.odt for more info.
