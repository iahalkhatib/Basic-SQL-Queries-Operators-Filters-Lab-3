![image](https://github.com/iahalkhatib/Basic-SQL-Queries-Operators-Filters-Lab-3/assets/170050432/7ecf1fb7-0e6b-4e48-b7e4-a14c6b181a26)

# Basic-SQL-Queries-Operators-Filters-Lab-3

# Task 1. Retrieve login attempts after a certain date

To investigate the recent security incident, I need to gather information about login attempts made after a specific date. 

To do this, I need to complete the SQL query by replacing X with the correct operator. Here’s how I would write it:

Complete the SQL query to retrieve data for login attempts made after '2022-05-09'. Replace X with the correct operator:

![image](https://github.com/iahalkhatib/Basic-SQL-Queries-Operators-Filters-Lab-3/assets/170050432/06cff4ae-a3eb-4195-92d7-0af9106f69e0)
![image](https://github.com/iahalkhatib/Basic-SQL-Queries-Operators-Filters-Lab-3/assets/170050432/746aeb33-1e1c-494a-9375-5ef7f4b7518b)


Now, based on my first query, I find a need to expand the date range to include 2022-05-09 in my search.

Complete the SQL query to retrieve data for login attempts that were made on or after '2022-05-09'. Replace X with the correct operator:

![image](https://github.com/iahalkhatib/Basic-SQL-Queries-Operators-Filters-Lab-3/assets/170050432/11345cb5-25ef-4c7e-a4eb-819a9bed3f72)
![image](https://github.com/iahalkhatib/Basic-SQL-Queries-Operators-Filters-Lab-3/assets/170050432/012483a4-68c1-47c6-9f67-43be9024a229)


# Task 2. Retrieve logins in a date range

In this task, I need to narrow the focus of the search. Login attempts made after 2022-05-11 shouldn't be included. 
I will use the BETWEEN and AND operators to return results between '2022-05-09' and '2022-05-11'.

Here's how I would write the query:

![image](https://github.com/iahalkhatib/Basic-SQL-Queries-Operators-Filters-Lab-3/assets/170050432/f466a8b5-7598-45b5-929a-ab5dc784a70b)
![image](https://github.com/iahalkhatib/Basic-SQL-Queries-Operators-Filters-Lab-3/assets/170050432/ee91dc4d-acf3-45a2-a644-ff957cf53cb3)

# Task 3. Investigate logins at certain times

In this task, I need to investigate logins that were made at certain times. 
To do this, I will filter the data in the login_attempts table by login time (login_time). 
My organization's typical work hours begin at 07:00:00, so I need to retrieve all login attempts made before 07:00:00 to learn more about the users who are logging in outside of typical hours.

Here's how I would write the query:

![image](https://github.com/iahalkhatib/Basic-SQL-Queries-Operators-Filters-Lab-3/assets/170050432/7220d5e2-3b20-49e8-a6fc-43c04e762c20)
![image](https://github.com/iahalkhatib/Basic-SQL-Queries-Operators-Filters-Lab-3/assets/170050432/3dd92a5a-a7e6-4532-a38f-ce23872de035)


To modify the query to return logins between '06:00:00' and '07:00:00', I would use the BETWEEN and AND operators:

![image](https://github.com/iahalkhatib/Basic-SQL-Queries-Operators-Filters-Lab-3/assets/170050432/62edd123-2187-4660-b765-0cc3c459625e)
![image](https://github.com/iahalkhatib/Basic-SQL-Queries-Operators-Filters-Lab-3/assets/170050432/ad28b158-ac79-4d3b-88e4-eea12b031882)


# Task 4. Investigate logins by event ID

To investigate login attempts based on event ID numbers and return only the event_id, username, and login_date fields from the login_attempts table for event IDs greater than or equal to 100, 

I would write the following SQL query:

![image](https://github.com/iahalkhatib/Basic-SQL-Queries-Operators-Filters-Lab-3/assets/170050432/62348752-baab-405f-b65c-140d0ddb681b)


![image](https://github.com/iahalkhatib/Basic-SQL-Queries-Operators-Filters-Lab-3/assets/170050432/6eb287c7-5df2-4746-a237-56604903b426)


To modify the query to return only login attempts with event_id between 100 and 150, I would use the BETWEEN and AND operators. Here's the updated query:

![image](https://github.com/iahalkhatib/Basic-SQL-Queries-Operators-Filters-Lab-3/assets/170050432/1a2107eb-82b3-4676-a2a3-c0b1ff125899)
![image](https://github.com/iahalkhatib/Basic-SQL-Queries-Operators-Filters-Lab-3/assets/170050432/f9e2fea6-87b6-469c-bf72-7aaa89ff00df)


I have completed this activity and practiced applying:

the WHERE keyword
the BETWEEN and AND operators
operators for working with numeric or date and time data types (for example, =, >, >=)
to filter data from a table.
