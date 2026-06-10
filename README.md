# APT_analysis_reports
This repo contains report.json files of various APT families. The reports are generated using cuckoo sanbox

## Currently Added

**Energetic Bear:** An APT group arributed to Russia\
**Gorgon Group:** An APT group arributed to Pakistan

## Complete Analysis

Github doesnt allow large files to be uploaded, so I uploaded full analysis to my Google Drive

https://drive.google.com/drive/folders/1tX2vwYmsbe2orNCF7qUT1JHFsy9vqtR2?usp=sharing

## Note:

The files are in xz format for maximum compression. To extract, use the following commands

### Linux

Step 1: Recombine all parts into one archive

```
cat <APT_Family_Name>.tar.xz.part-* > <APT_Family_Name>.tar.xz

tar -xJf <APT_Family_Name>.tar.xz
```
### Windows

Step 1: Recombine

```
copy /b <APT_Family_Name>.tar.xz.part-* <APT_Family_Name>.tar.xz

7z x <APT_Family_Name>.tar.xz
7z x <APT_Family_Name>.tar
```