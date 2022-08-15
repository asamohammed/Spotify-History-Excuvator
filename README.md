# Spoty Excuvator

*(Mac & Windows)*

App that lets you go "analyze" your Spotify streaming history


## Before using the app:
1. [Download Python3](https://www.python.org/downloads/)
2. [Download your Spotify data](https://www.spotify.com/us/account/privacy/)
    * (^ Link should take you to "Privacy Settings" Tab.)
    * Account -> "Privacy Settings" Tab -> "Request" (Scroll to the bottom)
    * Check your email to complete the request
   * Wait a few days for your data (Check email)
3. Clone repo OR download "spoty_exuvator_UI.py" (Everything required is in 1 file.)



## How to use the App:
1. Open "spoty_excuvator_UI.py" file and run it (See below on how to run the app)
2. Click the "Select Spotify Downloaded Data Folder" and a folder-selector should open (located at top-middle of screen)
3. Find and select the folder that you downloaded from Spotify
    * The label under the button should turn green and say "Sucessful"
4. Then select one of the 4 checkboxes options to display
5. Finally press the "Display Data" button (located at the bottom-left of screen)
    * The scrollable label should have your data displayed
6. Label above scroll area displays total time listened



## (Mac) How to run the app:
1. Using Terminal (No other downloads/apps needed)
    * Move the downloaded app folder to Desktop
    * Press Command+Spacebar -> Opens spotlight search
    * Type "Terminal" and open
    * Type "Python3 " (put a space after python3) then drag the "spoty_excuvato_UI.py" file into terminal window (this will copy file path)
    * Press Enter/Return to run the app
2. Using text exitor
    * [Sublime Text](https://www.sublimetext.com/download)
    * [Run python3 on sublime text](https://medium.com/@hariyanto.tan95/set-up-sublime-text-3-to-use-python-3-c845b742c720)



## (Windows) How to run the app:
1. Using Command Prompt (No other downloads/apps needed)
    * Move the downloaded app folder to Desktop
    * Press Window key -> Opens Windows search
    * Type "cmd" and open
    * In Command Prompt, type "Python3 " (put a space after python3) then drag the "spoty_excuvato_UI.py" file into Command Prompt window (this will copy file path)
    * Press Enter to run the app
2. Using text exitor
    * [Sublime Text](https://www.sublimetext.com/download) 
    * [Run python3 on sublime text](https://medium.com/@hariyanto.tan95/set-up-sublime-text-3-to-use-python-3-c845b742c720)



## Understanding your data:
After displaying your data
1. If you selected "Most Played Artist" checkbox:
    * This will display the artist and how many times you have listened to them (sorted ascending)
2. If you selected "Artist then Track" OR "Track then Artist" checkbox:
    * This will display how many times you have listened to a certain song (sorted ascending)
3. If you selected "Time per Artist (ms)" checkbox:
    * This will display how many seconds you have spent listening to a certain artist (sorted ascending)


Enjoy your data "analysis"!
