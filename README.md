This is a SQL console developed using sqlite3 and pandas in python. It aims to give the user the best of using SQL to execute queries and save the data into a local database.

Getting Started:
 1. Clone this repository into your local system.
 2. In the folder DS-SQL-master execute the DS-SQL.exe file
 3. You should see a cmd-line interface asking you to enter the path for the database file(As tested in Python 3.8, I had no issues in creating a new database by just giving the database name when prompted).
 4. You should see a prompt that starts with '>>>'
 5. Now you can go ahead and execute your SQL queries
 
 To read the data to a table from a csv file:
  1. type read_from_csv;
  2. When prompted enter the database name
  3. Also you would see a pop-up asking you to select the csv file
  4. If successful, you would get the data loaded into the given table
  5. To cross verify, try giving a SELECT query.
  
 Remember:
  Any query(including read_from_csv) will get executed iff it ends with a semi-colon(';')
  
Features of this application include:
1. Execute SQL queries
2. Load data to a table from a csv file

What's to be added in future:
1. Give an option to extract the data to a csv file
2. Execute SQL scripts

For any more additional queries or issues, feel free to mail me at dhinavahiaditya@gmail.com
