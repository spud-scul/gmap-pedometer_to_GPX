# gmap-pedometer_to_gpx

By Spud for [SCUL](https://scul.org/) mission exports, tested only with
https://www.gmap-pedometer.com/ and with SCUL mission prompts for filename 
and track name.

This is simple bookmarklet that allows you to convert https://www.gmap-pedometer.com/ maps into GPX format, which can then be uploaded to HAL. I have not tested it with the other sites that the original script was built to handle. (See Acknowledgments below.)

## Instructions

Drag the following bookmarklet to your browser toolbar:
[gmap-pedometer_to_GPX](javascript%3A%28function%28%29%257Bvar%20script%253Ddocument.createElement%28%2527script%2527%29%253Bscript.src%253D%2527http%3A%2F%2Fspud.github.io%2Fgmap-pedometer_to_gpx.js.js%2527%253Bdocument.getElementsByTagName%28%2527head%2527%29%255B0%255D.appendChild%28script%29%253B%257D%29%28%29)



Visit a recording on https://www.gmap-pedometer.com. Wait for the map to load, then click the bookmarklet you dragged to the browser toolbar. You'll get two pop ups asking for the stardate and operation name, then the GPX file will download and a window will open with its content.

## Acknowledgements

* https://github.com/seafoodbuffet/gMapToGPX, 2025-05-29
* https://github.com/rjl20/gmaptogpx version 6.4j, 2011.07.12
* Gmap-pedometer elevation code courtesy of Mathew O'Brien.
* 3/05/2007 - HeyWhatsThat.com code by mk -at- heywhatsthat.com
* 10/09/2007 - Allpoints speed improvement by Kyle Yost
* 