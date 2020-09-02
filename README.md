# HYSYS_data_import
The notebook featured in this repository takes data from some standard Aspen HYSYS reports (and an AspenTech developed VBA importer) and organizes it to facilitate analysis. 
This might help you if you, like me, have difficulty understanding Aspen HYSYS's VBA interface, but you still need to organize your simulation's outputs.

The code created is very raw, but I believe it can be of help in case anyone is having difficulty in listing all streams and all unit operations from an Aspen HYSYS simulation in a friendly way. Also, the simple exergy analysis conducted for the streams can be of help.

A VBA data import interface between HYSYS and Excel developed by Aspentech was used to prepare the data before further processing it in the notebook.
The spreadsheet is available in this link: https://esupport.aspentech.com/S_Article?key=110050 . Refer to it for details and to learn how to use it.
While this spreadsheet does import most of the relevant data, combining it with some other reports allowed for a friendlier showcasing of the data.
I felt more comfortable processing the files available in Python rather than with Excel's VBA, but it certainly could also be done that way.

Feel free to contact me at italosichi@gmail.com should you need any help in using/understanding the code.
And sorry for some snippets left in Portuguese. I wrote it to use it myself for my Master's thesis and later decided to share it on Github, but there are some places I felt a translation wasn't really necessary (such as columns names, for example), so they are still there.
