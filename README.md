# breaktime
A small Bash script to display a countdown timer for use at a conference break.  
Shows current times for four mainland US time zones and when the conference will resume.

Requires [Figlet](https://github.com/cmatsuoka/figlet)

Usage: `breaktime <time in 24-hour format> <message>`

Example: `./breaktime 15:00 "Time's Up"`
  
![Screen Shot](https://github.com/pkobezak/breaktime/raw/master/Screen-Shot.png)

Screen shot using Mac OS Terminal, 24 point Andale Mono font.  Spacing is fixed for the default size positionable screen share box in Zoom.

Current limitations 
* Only displays countdown in minutes and seconds (limited to 60 minute countdown)
* Message to be displayed at countdown end may wrap if more than nine characters

Future work 
* Have selectable time zones to display
* Longer than 60 minutes countdown
* Centering based on terminal size
* Passthrough of Figlet font selection
* Test and fix any issues on other platforms (currently only tested on Mac OS)
