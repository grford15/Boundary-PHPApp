# Boundary PHP Exercise 
  
Use this skeleton application to complete your assigned task, it demonstrates a simple example of a web service using the SLIM Framework, along with a method of connection to a PostgresSQL database.
  
This skeleton application was built using composer.
  
## Install the Application  
  
### Requirements

 - PHP 7.1+
 - PostgresSQL (https://www.postgresql.org/download/)
 - Composer - Follow instructions for your Operating System (https://getcomposer.org/).

### Running the App
first I ran ```psql -d postgres -a -f database/db.sql``` in the command line from the Project directory to create & populate the database.

Then: ```php -S localhost:8080 -t public``` to run the api.

## References
http://www.slimframework.com/docs/

## Sample Database
You can find a flat SQL to build a PostgreSQL schema in the /database/ directory, this schema will include all the data you need to make a head start
