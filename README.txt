Thracia 776 Stat Calculator
Developed by WendyM0th
Ver 1.1

~~~~~~~~~~~~~~~~~~~~~~~~~

1.1 UPDATE:
Added dismounted stats, custom growths scaling, unit resetting, and growths display.
Fixed a bug relating to scrolls making growths go into the negatives, and a crash if the user inputs nothing.

~~~~~~~~~~~~~~~~~~~~~~~~~

This is a calculator for Thracia 776, with more flexibility around levelling and scroll assignment.
To use, select a character (no capitalisation). I've included multiple names for each character, but if all else fails use the name the .org wiki uses for them (https://fireemblemwiki.org/wiki/List_of_characters_in_Fire_Emblem:_Thracia_776).

When choosing levels, you can use the 'help' command to see available commands, which are
help - displays commands.
scrolls - displays scroll data.
i - inverts growths.
p - provides promotion bonuses and resets unit level.
d - reclasses the unit to a dancer. if promoted, uses the thief fighter -> dancer penalty, otherwise thief -> dancer penalties
s - displays current stats
b - returns to unit selection. displays unit stats before leaving.
e - ends program. displays unit stats before leaving

level commands work in two parts. first, write the target level, and then write all the scrolls. inputs must be space separated.
example: 13 nj fj will level a unit to lvl 13 while applying the njorun and fjalar boosts.

This calculator runs on command line, and as such you cannot just double click to make it run. Open your computer's command prompt, then type 'java -jar [file location]' you can get the file location by right clicking the jar file and selecting "copy as path". Make sure to remove the quotation marks after pasting it in the command prompt.

~~~~~~~~~~~~~~~~~~~~~~~~~

Issues
If there are any inaccuracies with the program, or otherwise any glitches, please report them to me (WendyM0th is my discord username, reach me there).
Note that an average ending with a strange nine (eg 10.59 when it should be 10.60) is an issue with the double variable type.

~~~~~~~~~~~~~~~~~~~~~~~~~

Credits
Information for this program was gathered from:
Veylebot on Discord
fireemblemwiki.org
Serenes Forest