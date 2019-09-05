<h1 align="center">
  VRS-Aircraft-Markers 🛩️ 
</h1>

<p align="center">
  <a href="https://github.com/dedevillela/VRS-Aircraft-Markers/blob/master/LICENSE">
    <img src="https://img.shields.io/badge/License-MIT-red.svg">
  </a>
  <a href="http://virtualradarserver.co.uk/Download.aspx">
      <img src="https://img.shields.io/badge/VRS-v2.4-blue.svg">
  </a>
  <a href="https://scrutinizer-ci.com/g/dedevillela/VRS-Aircraft-Markers/">
      <img src="https://img.shields.io/scrutinizer/g/dedevillela/VRS-Aircraft-Markers.svg">
  </a>
  <a href="https://scrutinizer-ci.com/g/dedevillela/VRS-Aircraft-Markers/build-status/master">
      <img src="https://img.shields.io/scrutinizer/build/g/dedevillela/VRS-Aircraft-Markers.svg">
  </a>
  <a href="https://github.com/dedevillela/VRS-Aircraft-Markers/releases">
      <img src="https://img.shields.io/github/release/dedevillela/VRS-Aircraft-Markers.svg">
  </a>
  <a href="https://saythanks.io/to/dedevillela">
      <img src="https://img.shields.io/badge/SayThanks.io-%E2%98%BC-1EAEDB.svg">
  </a>
</p>

Custom aircraft markers for Virtual Radar Server (a.k.a VRS). This plugin adds new markers and also highlights MLAT tracked aircrafts with different marker colors. The following are custom aircraft markers currently available:
- A225 marker for the Antonov An-225 Mriya; ![alt tag](https://raw.githubusercontent.com/dedevillela/VRS-Aircraft-Markers/master/A225-Selected.png)
- GLEX marker for the Bombardier Global Express, Gulfstream G-IV, V & VI, and the Dassault Falcon 50, 900, 2000, 7X & 5X; ![alt tag](https://raw.githubusercontent.com/dedevillela/VRS-Aircraft-Markers/master/GLEX_marker.png)
- E135 marker for the Embraer ERJ-135 & 145; ![alt tag](https://raw.githubusercontent.com/dedevillela/VRS-Aircraft-Markers/master/E135_marker.png)
- E39 marker for the Embraer KC-390. ![alt tag](https://raw.githubusercontent.com/dedevillela/VRS-Aircraft-Markers/master/E39_marker.png)

## Prerequisites
- VRS installed and running;
- VRS Custom Content Plugin installed and enabled.

## Instructions
- Clone or download the repo and unzip it into a directory on the machine where VRS is running. Ensure you do not place the files under the Virtual Radar Server directory, since they could be overwritten on upgrades;
- Edit the file "CustomAircraftMarkers.js", placing the <script> tag in the very first line of code, and the closing tag </script> on the last line as well;
- Activate the plugin by adding a new entry in the Custom Content Plugin options, pointing out the "CustomAircraftMarkers.js" file.
- Place the folder "\Web\images\markers" in your Web folder;
- Enjoy!

## Acknowledgments
This project was only possible thanks to the invaluable help of many individuals and communities, especially the creator of the VRS, Andrew Whewell, always solicitous in [![his forum](https://img.shields.io/badge/VRS-Forum-blue.svg)](https://forum.virtualradarserver.co.uk/); Andrew Hill, whose [![flights.hillhome.org](https://img.shields.io/badge/flights-hillhome.org-ADD6FF.svg)](http://flights.hillhome.org/) site inspired me deeply; and all of the [![ADS-B Brasil](https://img.shields.io/badge/ADS--B-Brasil-lightgrey.svg)](http://bradsb.com/forum/index.php) community, including Ramon Martins and Jaime Hempke, which together maintain the excellent site [![TrafegoAereo.com](https://img.shields.io/badge/Trafego-Aereo-yellowgreen.svg)](http://trafegoaereo.com/).

## Contributions
Feel free to download and share these files, suggest corrections, or send requests for more aircraft markers, as I'm constantly updating this repository with new functionalities.

## Other Projects

[![VRS Operator Flags](https://img.shields.io/badge/VRS-Operator_Flags-red.svg)](https://github.com/dedevillela/VRS-Operator-Flags)

[![VRS Custom Links](https://img.shields.io/badge/VRS-Custom_Links-yellow.svg)](https://github.com/dedevillela/VRS-Custom-links/)

[![VRS Country Flags](https://img.shields.io/badge/VRS-Country_Flags-green.svg)](https://github.com/dedevillela/VRS-Country-Flags)

[![VRS Silhouettes](https://img.shields.io/badge/VRS-Silhouettes-brightgreen.svg)](https://github.com/dedevillela/VRS-Silhouettes)



