# Opencart Language CSV Import Export
Converts all CMS Opencart language files to .csv files and vice versa

## Why do you need it?
To simplify the translation of the system. Working with csv files is much more comfortable than with arrays. Especially for translators.

### How to use?
The script was written and tested on php 7.1.2.

To start export from language import files, you need to:
1) Place the language pack in the array_original folder
2) Open console, run command
> php brain.php export
3) All generated files will be stored in the csv_output folder


To import from csv into language files, you must enter the command
1) Place the language pack in the csv_original folder
2) Open console, run command
> php brain.php import
3) All generated files will be stored in the array_output folder
4) 
