<h3>README for May 8, 2024 Lake Michigan mission</h3>

These data were collected on May 8, 2024 over Lake Michigan, using the following observation pattern:
<ul>
  <li>Launch 1 at Station 1</li>
  <li>Launch 2 at Station 2</li>
  <li>Launch 3 at Station 3</li>
  <li>Launches 4 and 5 at Station 5 (launch attempt at Station 4 failed)</li>
  <li>Launch 6 at Station 4</li>
  <li>Launches 7, 8, and 9 at Station 3</li>
  <li>Launch 10 at Station 2</li>
  <li>Launch 11 at Station 1</li>
</ul>

The filename convention is YYYY-MM-DD_hhmm, where the time refers to the time at which the rawinsonde was first paired with the receiver. The actual release time is typically 7-15 min later. The raw and processed data contain this information.

There are six files per sounding:
<ul>
  <li>A KML file for loading into Google Earth, depicting the rawinsonde's path in three dimensions.</li>
  <li>A raw_history file, which contains the full raw data.</li>
  <li>Two SHARPpy files, a text file containing the processed sounding data in SHARPpy format and a PNG image visualizing said data.</li>
  <li>A .sounding file, which contains the processed sounding data in Windsond's format.</li>
  <li>A .sounding.csv file, which contains the processed sounding data in .csv format.</li>
</ul>

The processed data have undergone Windsond's automated quality controls, radiation correction, etc. They have not undergone any further QC. We have metadata describing the surface water temperature for each launch that will be added at a later date.
