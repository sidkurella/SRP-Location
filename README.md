# SILOS Location Calculation Code
This project represents the work of the Location Team on the SILOS project at the Monmouth University Summer Research Program 2015. In this repository are several Java source files for calculating location using a trilateration algorithm.
The code involves connecting to a database to download tag read records, using the relative signal strength indicator value to trilaterate its location, and uploading that to the database.

## Requirements
Should work on any relatively modern version of Java. Requires the MariaDB Connector/J .jar file to access the database.

## Installation
Run the corresponding class file to the Java file entitled [CircleInt.java](https://github.com/sli908/SRP-Location/blob/master/src/CircleInt.java) to connect to the database and update location records.
Please note: the files must be compiled first.

## Credits
Thank you to Professor Robert M. Kelly, Jr. of Monmouth University for supervising this project.
