# shipstationAPI
This is a program that I developed using Shipstation's current API (as of December 2022), the goal was to clean the order data into the proper format used in spreadsheets at AJ Bednar Enterprises Inc. Using the doccumentation from https://www.shipstation.com/docs/api/ to connect with our current order and store data the information from https://medium.com/@jb.ranchana/write-and-append-dataframes-to-google-sheets-in-python-f62479460cf0 to connect to google drive and google sheets. I was able to read in order data sorted by newest to oldest so that it could be cleaned into its proper format and exported directly into our order data google sheet.

Next steps for this is to develop a simple user interface where the user can enter the number of new orders and the software will display the new orders to be added.

Future improvements for this would be to fully automate the software to add new orders to the spreadsheet in real time.
