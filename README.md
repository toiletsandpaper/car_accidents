# Inspecting affect of road bumps and pits on car accident in Russia

## What is it about?

This set is totaly unrepresentive, because major part of accident is "self-handled" by drivers.
For example: you would never waste your time on waiting inspectors to write a report that you have a flat tire because of this road pit in the middle of the night.
You'll just change that tire and move on without any report. So because of that - this data is useless, but applied methods to this "research" is well working to make other researches.

## Folder Structure

All data will be collected `in-script`, becuase its to large to store on github, even in LFS.

NOTE: All files totally **will take ~7.5 GB of your disk memory**. This is totally unefficient, because I've wanted to save fixed version and .csv for DataFrame, so fell free to fix and even make pull requests.

```none
📂car_accidents
 ┣ 📂data
 ┃  ┣ 📂csv
 ┃  ┃  ┗ 📄data.csv
 ┃  ┣ 📂fixed
 ┃  ┃  ┣ 📄Adygeya.geojson
 ┃  ┃  ┣ ... .geojson with fixed points in featurecollection
 ┃  ┃  ┗ 📄Zabaykal-skiy_kray.geojson
 ┃  ┣ 📄altaiskii-krai.geojson
 ┃  ┣ ... .geojson with not-fixed points in featurecollection
 ┃  ┗ 📄zabaikalskii-krai.geojson
 ┣  📂Russia_geoJSON
 ┃  ┣ 📄Adygeya.geojson
 ┃  ┣ ... .geojson with region's polygons to fix data
 ┃  ┗ 📄Zabaykal-skiy_kray.geojson
 ┣ 📜.gitattributes
 ┣ 📜.gitignore
 ┣ 🔑LICENSE
 ┣ 📄README.md
 ┣ 📒russian_car_accidents.ipynb
 ┗ 📄sets.txt
```
