# FormattedCountdown
A LUA script for OBS Studio 21.0 (or higher) that allows you to set a text source to act as a countdown timer using a specified format.

## Installation:

(Optional) Place the script in your "obs-studio\data\obs-plugins\frontend-tools\scripts\" directory.  
In OBS, go to "Tools -> Scripts" and add the "formatted-countdown.lua" script.

## Usage:

- Specify how many seconds the countdown should last.
- Specify how to format the countdown text. You can use the following tokens that will be substituted at runtime:
  - $h: hours
  - $m: minutes
  - $s: seconds
- Choose a text source.
- Specify text that will be displayed when the countdown is over.