# MuleSoft_MovieDB







This is a basic Representation of a SQLite Database for movies that you like that can be added in a DB file using jdbc------------------------------


-> First i create a Database called movies1 using the jdbc and java code itself.

-> Then we check the connection is present or not by using the connect class that is made.

-> After database is made and connection is checked, now we create a table called as moviereview where we store the name, actor name, actress name, 
   director and year of release.
   
-> In this Database there is also a AUTOINCREMENT PRIMARY KEY called id which gives keys to each entry.

-> Also there is constraint over the year of the movies so that no single digits can be entered for years.

-> After entering the database using insert class in the code i made 2 queries accordingly i.e.) one for selecting all, 
   and other one for selecting movies with a particular actor name.
   
-> In the names VARCHAR is used if there is any number in the name of the movie or the name of people working on it.(Don't think there will be though ;) ).




# WORKING :------------

-> The working method was using command line to setup and test each and every stuff in the process.

-> sqlite3 was used to check the database in realtime, that whether the changes made is correct or not.

-> Jar file used for compilation was sqlite as well.

-> The main code for everything is present in Connect.java inside the MuleSoft folder as you go inside the Connector Folder.

# HOW TO MAKE IT WORK:::::::::::::::::::::::::::::::::::::

1.) TO SEE DATABASE --------

        -> To see the database just open the DB folder in the cmd and type in sqlite3 DATABASE NAME and it will open the database and use it as a simple database.
        -> .tables will show the tables.
        -> SELECT * from moviereview will show everything in the table.
2.) TO RUN THE CODE --------
        
        -> To run the code setup the folder in a IDE and add sqlite jar file as a execution enviroment accordingly and run the code it will work fine (as long as the directories are correct).
        -> Elseway you can compile the java file using "  javac Connect.java  " and execute by using "  java -classpath ".;sqlite-jdbc-3.36.0.3.jar" net.sqlitetutorial.Connect  " in the cmd.
        
