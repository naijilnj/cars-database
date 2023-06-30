# cars-database
The Cars Database is a project that leverages Python programming language to interact with PostgreSQL.

OG Dataset - https://data.world/dataman-udit/cars-data

The project starts by establishing a connection to the PostgreSQL database using Python's psycopg2 library.
After Connection, a New Database is Created called carsdatabase.
Then all the CSV files are imported from thr OG Dataset.

After creating the database, the project proceeds to create tables using SQL commands through Python.

![Screenshot (1181)](https://github.com/naijilnj/cars-database/assets/110610851/2c254c92-d73a-4f34-a051-d9f687fa0b12)

Data Model Design
It defines the relationships and constraints between tables, ensuring a logical and organized structure. 

![Untitled Diagram drawio](https://github.com/naijilnj/cars-database/assets/110610851/4483d672-e7e8-4495-bf13-b0856cd4829c)

Then all the Data from the Dataset is inserted into the Tables
Screenshots of the SQL shell - postgresql

Table 1 - carsdetails

![Screenshot (1191)](https://github.com/naijilnj/cars-database/assets/110610851/79f6b7a9-869c-4fe7-89b7-ebda59794919)

Table 2 - carscountry

![Screenshot (121)](https://github.com/naijilnj/cars-database/assets/110610851/1dd4401f-8668-4e73-a916-203e4b6b8896)

Table 3 - carsprice

![Screenshot (1221)](https://github.com/naijilnj/cars-database/assets/110610851/eeca1bcc-618c-4ebb-9c02-cf43efd1ced4)







