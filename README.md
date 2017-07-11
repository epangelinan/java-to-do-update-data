# _Java To Do Update Data_

#### _{Brief description of application}, {Date of current version}_

#### By _**{List of contributors}**_

## Description

_{This is a detailed description of your application. Its purpose and usage.  Give as much detail as needed to explain what the application does, and any other information you want users or other developers to have. }_

## Setup/Installation Requirements

* _At terminal, enter postgres_
* _In a different terminal window, enter psql_
* _Create the databases and tables as follows. In psql, enter:_
* _CREATE DATABASE to_do;_
* _\c to_do;_
* _CREATE TABLE tasks (id serial PRIMARY KEY, description varchar, categoryId int);_
* _CREATE TABLE categories (id serial PRIMARY KEY, name varchar);_
* _CREATE DATABASE to_do_test WITH TEMPLATE to_do_
* _To run the program, go into the project folder on the terminal and enter gradle run_
* _In the browser, enter localhost:4567_

## To Backup Databases:
* _Clear the tables:  from psql, enter:_
* _DELETE FROM tasks;_
* _DELETE FROM categories;_
* _DROP DATABASE to_do_test;_
* _In your "normal" terminal window, not psql, enter: pg_dump to_do > media.sql_
* _Add changes via add . and commit your changes_
* _Upload project to Github._

## To Restore Databases:
* _Clone the database from Github_
* _Connect to psql and run: CREATE DATABASE to_do;_
* _Run the following command in the terminal (not psql): psql to_do < media.sql_
* _Confirm success.  Switch to psql and run:  \c to_do_
* _Then run: \dt_

## Known Bugs

_{Are there issues that have not yet been resolved that you want to let users know you know?  Outline any issues that would impact use of your application.  Share any workarounds that are in place. }_

## Support and contact details

_{Let people know what to do if they run into any issues or have questions, ideas or concerns.  Encourage them to contact you or make a contribution to the code.}_

## Technologies Used

_{Tell me about the languages and tools you used to create this app. Assume that I know you probably used HTML and CSS. If you did something really cool using only HTML, point that out.}_

### License

*{Determine the license under which this application can be used.  See below for more details on licensing.}*

Copyright (c) 2016 **_{List of contributors or company name}_**
