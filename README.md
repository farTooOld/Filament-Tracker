# Filament-Tracker
An App for Tracking Fused Filament (for 3D Printing)

Release of the app (11/17/2016)

##** OVERVIEW **

[ Double mouse Click = DC ]

This app simply adds-up incremental amount values - they can be Cost, Number of Items, donuts eaten… Basically anything with a number associated. The number can be irrelevant if just making a ’To-Do’ list but a number must be entered.

The app uses the SQLite DataBase - think in terms of Similarity to a Spreadsheet app such as MS Excel:  One app with multiple Spreadsheets, or, in this case, One app with multiple Tables.

Consider these Use options:
* 1 - Enter the incremental data and it will keep running totals.
* 2 - Or, Start by entering an amount (such as Acct Balance or Amount of Filament on the spool) then, enter ‘negative’ amounts; this way they will subtract from starting balance.

Printing your results / Table:
Click ‘Table Manager’, DC desired Table from Current Tables and Click the “Write .txt File”  - this generates a standard .txt file to open in your favorite Text Editor / App . The filename will be “ OUTfile_your_Table’s_Name.txt “ and is located in the app’s folder.

##** INSTALLING the APP **

This is a Java-coded app and should run on All computers.  It was specifically intended for Java 8 (1.8, to be correct) but was also tested in Java 7, Runtime Environments (JRE).

Unzip the file to a desired location (recommend it’s own Folder).  Unzipping should generate 4 (four) files:
* FFTracker.jar  - the App
* OUTfile_homeboy.txt  - default Table used by the App
* dufuss.db - the database
* icns & .png    - icns (icon for OSX,) or use the .png for other systems or make your own
* (Note: if you delete 'homeboy' you'll need to re-create it ! )

##** RUNNING the APP **

DC the FFtracker.jar to run it.
It should open and indicate it’s using the ‘homeboy’ table but, the table is not yet fully committed;  Click Table Manager, then, click List Tables, then, DC ‘homeboy’ in the Current Tables list panel to fully commit it.

Although you can use ‘homeboy’, I recommend leaving it alone. Your real goal is to have Tables for each ‘thing’ you want to track, Examples:
* eSun_pla_BLK
* Makerbot_abs_GRY
* Checking Acount

Thus, for each ‘thing’, simply Create New Table.  (Note: if you create a New Table with an existing name, it will overwrite the data in the table. This is a Good Thing since you may want to keep the tablename but start afresh without actually doing the typing…). You can delete Tables by entering the TableName and clicking Delete.
