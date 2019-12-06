# p01
This program could download content of a SAP internal table into a file with UTF-8 encoding.
Data is downloaded in internal SAP format.
There is possibility to download column IDs and column descriptions.
File could be downloaded on the SAP server or on the user PC.
In order to download file on the SAP server the option “Run in background” have to be checked. If this option is not checked then the file is downloaded on the user PC. User could use selection criteria’s during data download to restrict the table contents which is going to be downloaded. Also user could specify and restrict table columns which are going to be used into the output file by typing column IDs.

Upload data from a file with UTF-8 encoding residing on the SAP server into SAP dictionary table is the other option. File have to have exactly the same dictionary structure as the dictionary table and have to be tab separated. During upload full file name could be specified (file + path) or just a file name in which case home directory is going to be used. Be careful when typing file name of files residing on the application server because lower/uppercase could be important.

I have added two buttons which call standard SAP transactions for download/upload of files from/to SAP server.

I hope this program will be useful for you and will help you to save time.
