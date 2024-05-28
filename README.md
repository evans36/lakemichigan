# Lake Michigan Windsond Observations
This repository contains data collected from Windsond launches over Lake Michigan from the University of Wisconsin-Milwaukee's <i>R/V Neeskay</i>. Data are stored in directories with a nn-mmddyyyy naming convention, where <i>nn</i> refers to the internal mission number.

Each mission typically begins around 0800 Central Daylight Time and ends around 1600 Central Daylight Time, with twelve to fifteen Windsond launches conducted per mission at intervals of 20 to 60 min.

Soundings have a filenaming convention of yyyy-mm-dd_hhmm.*, where the hour and minute are in local time (Central Daylight Time unless otherwise indicated) and refer to the time at which the sonde was first paired with its receiver (typically 1-5 min prior to launch). There are typically five files per launch:
<ul>
  <li>*.kml - contains the latitude, longitude, and altitude for each data point along the sounding's path</li>
  <li>*.sharppy.png - SHARPpy-generated visualization of the sounding</li>
  <li>*.sharppy.txt - sounding data in SHARPpy text format, with headers</li>
  <li>*.sounding - sounding data in Windsond format</li>
  <li>*.sounding.csv - sounding data in comma-separated format, with headers</li>
</ul>

Temperature data use version 2.4 of Windsond's radiation correction algorithm. Data are not quality controlled beyond standard Windsond internal quality-control procedures.

Missions conducted to date include:
<ul>
  <li><b>Mission 1 (1 June 2023)</b> - Fifteen soundings at five sites (1, 6, 11, 16, and 21 n. mi. east of Milwaukee, WI) launched between 0830 and 1600 Central Daylight Time on a sunny day with light southeasterly winds from the surface to 500 hPa and lake-surface water temperatures of 10-13°C (warmest nearshore).</li>
  <li><b>Mission 2 (14 September 2023)</b> - Fifteen soundings at eight sites in an 11 n. mi. north-south by 10 n. mi. east-west clockwise square, with due east from Milwaukee, WI as the square's southern leg, launched between 0900 and 1800 Central Daylight Time. Skies were mostly sunny, with land and water surface temperatures both near 21°C over the entire domain (somewhat warmer further inland over central Wisconsin).</li>
  <li><b>Mission 3 (8 May 2024)</b> - Eleven soundings at five sites (inner harbor, and 1, 2.25, 3.5, and 8.5 n. mi. east of Milwaukee, WI) launched between 0800 and 1500 Central Daylight Time. Skies were clear, with light lower-tropospheric westerly winds turning southeasterly through the day. Lake-surface water temperatures were between 10-15°C (with the gradient located within 3.5 n. mi. of shore) whereas land surface temperatures were in the low-mid 20s°C.</li>
  <li><b>Mission 4 (23 May 2024)</b> - Fourteen soundings at the same five sites as Mission 3, launched between 0800 and 1505 Central Daylight Time. Skies were clear offshore and partly cloud near shore, with light-to-moderate lower-tropospheric westerly winds weakening and turning onshore during the day. Lake-surface water temperatures were between 8.5-15°C (with the gradient again located within 3.5 n. mi. of shore) whereas land surface temperatures were in the mid-20s°C.</li>
</ul>

Overarching project goals and data collected during mission 1 (1 June 2023) were presented at the AMS's 32nd Conference on Weather Analysis and Forecasting:

<p><i>DeYoung, C., and C. Evans, 2023: <a href="https://ams.confex.com/ams/WAFNWPMS/meetingapp.cgi/Paper/425215">A Preliminary Assessment of the High-Resolution Rapid Refresh Model’s Ability to Predict the Great Lakes Lake-Breeze Front and Marine Atmospheric Boundary Layer</a>. Abstract, 32nd Conf. on Weather Analysis and Forecasting, Amer. Meteor. Soc., Madison, WI, 86.</i>

Collin DeYoung's M.S. thesis, defended in April 2024, analyzes data from missions 1 and 2. A publication is in preparation for submission to <i>Weather and Forecasting</i> based on these data. Mission 3 was coordinated with over-land rawinsonde launches and a suite of remotely sensed observations (Doppler and high-spectral resolution lidars, interferometer, and ceilometer) from the UW-Madison SSEC Portable Atmospheric Research Center, and a separate publication will be prepared later in 2024 based on these data.

A limited intercomparison of Windsond data with Vaisala rawinsonde data was also presented at the AMS's 32nd Conference on Weather Analysis and Forecasting. The Windsond data were found to be in excellent agreement with the Vaisala rawinsonde data except for temperature during the daytime, which is likely a function of not using the Windsond radiation correction algorithm on the collected temperature data.

<p><i>Diedrichsen, M., M. C. Coniglio, E. Rasmussen, and S. M. Waugh, 2023: <a href="https://ams.confex.com/ams/WAFNWPMS/meetingapp.cgi/Paper/425474">A Targeted Sounding and LiDAR Retrieved Wind Analysis of the 26 February 2023 Norman, OK Tornado</a>. Abstract, 32nd Conf. on Weather Analysis and Forecasting, Amer. Meteor. Soc., Madison, WI, 8.4.</i>
<hr>
<i><b>Questions, comments, etc.</b>: evans36-at-uwm-dot-edu, deyoungc-at-uwm-dot-edu</i>
