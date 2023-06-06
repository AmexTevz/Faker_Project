
The program runs from faker_data_main.py

It utilizes the Faker library and is currently limited to
first name (Fname), last name (Lname), age, job, and company.
More options can be added to faker_data_options.py from https://faker.readthedocs.io/en/master/

Insert the path to your preferred directory where you want 
CSV file to be created (csv_file_path).

Insert your PostgreSQL credentials (con).

1) It will ask for column names you want to include.
2) It will ask how many rows to create.
3) It will ask how to name the CSV file. (Will skip creation if left blank)
4) It will ask how to name the SQL table. (Will skip creation if left blank)

The program became a very convenient tool for rapidly creating files and tables for 
testing and exercising purposes in my company.

