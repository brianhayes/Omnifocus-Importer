Omnifocus Importer: A simple import action for Omnifocus and Alfred
============

A simple AppleScript that allows you to import a file to Omnifocus from [Alfred App](http://alfredapp.com/). You will need Alfred and the Powerpack to use this.

Installation
----------------

To install the Omnifocus Importer in Alfred double click on the extension file.

How to use
----------------

Once installed with Alfred this works as an action on the selected file. All to-dos in the file will be imported into a new project based on the file name. 

Notes
----------------
The file format should be as follows with one to-do per row, tab deliminated:

MM-DD-YYYY	MM-DD-YYYY	To-Do Name	Optional notes for the to-do.

This generally works best as an export from Excel. 


## Version History ##

### 1.0.2 - 2012-03-20 ###
- Made all dates not requried
- Added option for start date as first item. Format is now start date	end date	To-Do	Notes

### 1.0.1 - 2012-03-15 ###
- Corrected issue where the Growl notification icon was still set to Things. 
### 1.0.0 - 2012-03-14 ###

- Initial Release
