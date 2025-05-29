# gmap-pedometer_to_gpx

By Spud for [SCUL](https://scul.org/) mission exports, tested only with
https://www.gmap-pedometer.com/ and with SCUL mission prompts for filename 
and track name.

This is simple bookmarklet that allows you to convert https://www.gmap-pedometer.com/ maps into GPX format, which can then be uploaded to HAL. I have not tested it with the other sites that the original script was built to handle. (See Acknowledgments below.)

## Instructions

1. See https://spud-scul.github.io/gmap-pedometer_to_GPX/ for a page showing the bookmarklet. Drag it to your browser toolbar.

2. Visit a recording on https://www.gmap-pedometer.com. Wait for the map to load, then click the bookmarklet you dragged to the browser toolbar. You'll get two pop ups asking for the stardate and operation name, then the GPX file will download and a window will open with its content.

3. Upload the GPX to HAL using the [file upload interface](https://scul.org/HAL/index.php/Special:Upload).

4. Add it to the [Mission Routes](https://scul.org/HAL/index.php/Mission_Routes) page on HAL.

## Acknowledgements

* https://github.com/seafoodbuffet/gMapToGPX, 2013-10-10
* https://github.com/rjl20/gmaptogpx version 6.4j, 2011.07.12
* Gmap-pedometer elevation code courtesy of Mathew O'Brien.
* 3/05/2007 - HeyWhatsThat.com code by mk -at- heywhatsthat.com
* 10/09/2007 - Allpoints speed improvement by Kyle Yost
