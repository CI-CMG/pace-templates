# PACE Template JSON and Excel Files

- [PACE Templates](#pace-templates)
  - [JSON Templates](#json-templates)
  - [Excel Templates](#excel-templates)

## JSON Templates
PACE internally creates JSON files to hold onto translator, metadata, and package objects. The provided templates allow you to create these objects directly. You can either insert them into the ".pace" directory that can be found in your home directory if you have booted up PACE on your local machine, or you can use the PACE command line interface to load them in. Follow the instructions at the top of the JSON template files.

In order to upload the JSON file to PACE via the command line, run a command formatted as such: ``pace-cli <object-type> create <file-name>.json``

## Excel Templates
The Excel templates here allow you to skip the work of creating translators as PACE has default translators for the excel spreadsheets. Should you make alterations to the template headers, you are able to alter the default translator in the user interface.
