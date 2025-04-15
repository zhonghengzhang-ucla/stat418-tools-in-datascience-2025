# Homework 1

Parse the web server access logs from the two files located at https://atlas.cs.brown.edu/data/web-logs/NASA_Jul95.log and https://atlas.cs.brown.edu/data/web-logs/NASA_Aug95.log. You may complete this assignment with one script using a combination of Awk/cut commands. Write both files to your local hw1 directory and create a NEW .sh file that can be run on files named:
NASA_Jul95.log
NASA_Aug95.log

Due date is Tuesday April 22, 2025 at 6pm. Please submit your script to the course github repo as a pull request to the homework submission folder here and the branch hw1-submissions.

Answer the following questions with your script and have any words to support your commands written as comments.

Answer the following for each file.

1. List the top 10 web sites from which requests came (non-404 status, external addresses looking in).
2. List the top 10 local web pages requested (non-404 status).
3. List the top 10 web browsers used to access the site. It is not necessary to get fancy and parse out all of the browser string. Simply print out the information that is there. Display the percentage of all browser types that each line represents.
4. List the number of 404 errors that were reported in the log. 
5. List the number of 500 errors that were reported in the log. 
6. What time of day is the site active? When is it quiet?
7. Is the traffic "real" or mostly the result of robots or automated processes?

Answer the following questions comparing the two:

