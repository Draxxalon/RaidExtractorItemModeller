# RaidExtractorItemModeller
This tool takes the memory extraction details from the RaidExtractor tool, and the processed data dump


Requires The RAidExtractor tool found at: 
https://github.com/LukeCroteau/RaidExtractor/releases

Also requires Power BI Desktop, found at:
(For those who can, I reccommend the Win10 app store version, as it will self-update to latest versions).
https://powerbi.microsoft.com/en-us/downloads/

Latest version of the RSL Mined data sheet can be found at:
https://docs.google.com/spreadsheets/d/16KNDJZSxabwUxaWIU7zzvsntlnAMYBYfQ-7ZZHNZLFQ/edit#gid=1173182022
Requires the All-champ info (in depth) tab to be saved as an .xls file.  See point 2 below for file name requirements.

How to use:

1 - Download raidextractor.pbit, save it wherever you want.

2 - Download RSL Mined Champ_Skill Info.xlsx, save in as C:\RaidExtractor\RSL Mined Champ_Skill Info.xlsx.  I have included a version here, but there may be updated versions at the source location noted above.

3 - Download the raid extractor tool (save it wherever you want)

4 - Download + install Power Bi Desktop

5 - Ensure Raid is running on your PC

6 - Run  RaidExtractor.exe and choose "Save Json".   Save the file as C:\RaidExtractor\RaidData.json

7 - Go to the location where you saved the .pbit file & open it (should open power bi).

8 - It should load the data in the saved .json file.   If not, hit the "Refresh" button

NOTE:  The file name and location noted in steps 2 and 6 is REQUIRED!  And no, I cannot make it more flexible.
