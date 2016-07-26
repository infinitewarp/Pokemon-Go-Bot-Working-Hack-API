# Pokemon Go Working Bot Hack
[![Build Status](https://travis-ci.org/BoBeR182/Pokemon-Go-Bot-Working-Hack-API.svg?branch=master)](https://travis-ci.org/BoBeR182/Pokemon-Go-Bot-Working-Hack-API)
Bitcoin: 1HJ5kY14HMTjE3DfTEDr9YkRMxCS5PHPta

## USE WITH CAUTION! 
Niantic may ban you if you run the bot while signed in through your phone.
Softbans will happen if you teleport around the world too much.

## Important Announcement
If your bot stops working all of a sudden and doesn't move, input your latitude and longitude manually in pokebot.py. This happened because there is a limit to how many calls you can make for the API. Also, I won't be able to respond to all issues asap, due to the busy schedule ahead of me. I may go back to this project in a week or two. Cheers!

## Changes and updates
1. Now you can hatch and incubate eggs. In order to do this, change step size in the config.json file to like 1 or 2 or something like that. Step size corresponds to the meters traveled per server call.
2. Terminal/CMD output is so much more cleaner
3. Pokemon are transfered by CP IV criteria and you can get their candy
4. Easier and faster to level up and catch rare pokemon

## Instructions
1. Download or fork project and open up zip file.
2. Open up CMD/Terminal and change directory to that folder; for example, `cd Pokemon-Go-Bot-Working-Hack-API`
3. You need to install Python version 2.7 and have pip installed; if you don't have that, refer to tutorials on the web. (I recommend setting up a VirtualEnv)
4. Install the dependencies with: `pip install -r requirements.txt` If that doesn't work then just add `sudo` to the beginning.
5. Create a Google Maps Directions API key and activate it:
    1. Create it here: https://console.developers.google.com/projectselector/apis/credentials
    2. Then activate it here (select your project on the dropdown menu): https://console.developers.google.com/apis/api/directions_backend/overview?project=_
6. Then copy config.json.example to config.json file and put in your username, password, location, your google maps API key which you created earlier.
7. If you login into Pokemon Go with Google: `python pokebot.py -i 0` and `python pokebot.py -i 1` if you use Pokemon Trainer's Club
8. When running the bot for the first time add `--cache` to the end.
