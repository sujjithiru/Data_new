# Dimension Tables

# users_table - users in the app
user_id, first_name, last_name, gender, level


# songs_table  - songs in music database
song_id, title, artist_id, year, duration


# artists_table - artists in music database
artist_id, name, location, lattitude, longitude

# time_table - timestamps of records in songplays broken down into specific units
start_time, hour, day, week, month, year, weekday.

# The project template includes three files:

# etl.py 
reads data from S3, processes that data using Spark, and writes them back to S3
# dl.cfg :
dl.cfg contains my AWS credentials

# README.md 
README.md provides discussion on my process and decisions

I finally exectuted etl.py using a command  in the terminal : $ python etl.py

# README.md 
README.md provides discussion on my process and decisions

I finally exectuted etl.py using a command  in the terminal : $ python etl.py
