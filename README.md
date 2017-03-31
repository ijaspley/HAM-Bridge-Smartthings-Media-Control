# HAM-Bridge-Smartthings-Media-Control
Contains the Smartapps and Device Types for Smartthings Media Control via HAM Bridge

Install HAM Bridge http://solutionsetcetera.com/about-ham-bridge.html

Write the applescripts for Play iTunes, Pause iTunes, Skip Track iTunes, Back Track iTunes, Play Spotify, Pause Spotify, Skip Track Spotify, Back Track Spotify. For Spotify I used the commands I gained from installing Airfoil-API.

Point HAM Bridge to each script and name it (no spaces).

Add the device types for each of the buttons (add device handler as code).

Add the devices (just name them and tick the drop down boxes), they will be under Alexa Switch for Play/Pause and Simulated Alexa Switch for Skip and Prev.

Add the button smartapp (from code), it will be under Marketplace > My Apps > HAM and Switch 2

Put your HAM Bridge commands into the smartapp, use on for play, off for pause, both for skip and prev. You will need several instances of the smartapp configured (3 for each of iTunes and Spotify).

Add the Media Controller device type and add it as a device.

Add the Media Controller Config smartapp and configure it, it will be under Marketplace > My Apps > Media Set Up.

You will have a Smartthings Media Remote and can call on Alexa to turn on/off/skip/back for iTunes/Spotify, the buttons can also be added to Harmony Remotes.
