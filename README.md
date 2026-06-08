# APT_analysis_reports
This repo contains report.json files of various APT families. The reports are generated using cuckoo sanbox

## Currently Added

Energetic Bear: An APT group from arributed to Russia


## Note:

The files are in xz format for maximum compression. To extract, use the following commands

### Linux

Step 1: Recombine all parts into one archive

`
cat <APT_Family_Name>.tar.xz.part-* > <APT_Family_Name>.tar.xz

tar -xJf <APT_Family_Name>.tar.xz
`
### Windows

Step 1: Recombine

`
copy /b <APT_Family_Name>.tar.xz.part-* <APT_Family_Name>.tar.xz

7z x <APT_Family_Name>.tar.xz
7z x <APT_Family_Name>.tar
`