# Lake Michigan Windsond Observations
This repository contains data collected from Windsond launches over Lake Michigan from the University of Wisconsin-Milwaukee's <i>R/V Neeskay</i>. Data are stored in directories with a nn-mmddyyyy naming convention, where <i>nn</i> refers to the internal mission number.

Each mission typically begins around 0800 Central Daylight Time and ends around 1600 Central Daylight Time, with between one and twenty Windsond launches conducted per mission at intervals of 10 to 60 min.

Soundings have a filenaming convention of yyyy-mm-dd_hhmm.*, where the hour and minute are in local time (Central Daylight Time unless otherwise indicated) and refer to the time at which the sonde was first paired with its receiver (typically 1-5 min prior to launch). There are typically five files per launch:
<ul>
  <li>*.kml - contains the latitude, longitude, and altitude for each data point along the sounding's path</li>
  <li>*.sharppy.png - SHARPpy-generated visualization of the sounding</li>
  <li>*.sharppy.txt - sounding data in SHARPpy text format, with headers</li>
  <li>*.sounding - sounding data in Windsond format</li>
  <li>*.sounding.csv - sounding data in comma-separated format, with headers</li>
</ul>

Temperature data use version 2.4 of Windsond's radiation correction algorithm. Data are not quality controlled beyond standard Windsond internal quality-control procedures.

Data collected during mission 1 (1 June 2023) were presented at the AMS's 32nd Conference on Weather Analysis and Forecasting:
<i>DeYoung, C., and C. Evans, 2023: <a href="https://ams.confex.com/ams/WAFNWPMS/meetingapp.cgi/Paper/425215">A Preliminary Assessment of the High-Resolution Rapid Refresh Model’s Ability to Predict the Great Lakes Lake-Breeze Front and Marine Atmospheric Boundary Layer</a>. Abstract, 32nd Conf. on Weather Analysis and Forecasting, Amer. Meteor. Soc., Madison, WI, 86.</i>

A limited intercomparison of Windsond data with Vaisala rawinsonde data was also presented at the AMS's 32nd Conference on Weather Analysis and Forecasting. The Windsond data were found to be in excellent agreement with the Vaisala rawinsonde data except for temperature during the daytime, which is likely a function of not using the Windsond radiation correction algorithm on the collected temperature data.
<i>Diedrichsen, M., M. C. Coniglio, E. Rasmussen, and S. M. Waugh, 2023: <a href="https://ams.confex.com/ams/WAFNWPMS/meetingapp.cgi/Paper/425474">A Targeted Sounding and LiDAR Retrieved Wind Analysis of the 26 February 2023 Norman, OK Tornado</a>. Abstract, 32nd Conf. on Weather Analysis and Forecasting, Amer. Meteor. Soc., Madison, WI, 8.4.</i>

<hr>
<i><b>Questions, comments, etc.</b>: evans36-at-uwm-dot-edu, deyoungc-at-uwm-dot-edu</i>
