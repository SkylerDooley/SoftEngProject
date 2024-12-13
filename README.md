WPI CS3733 B Term 2024 Project
Submitted 12/13/2024

Important note: All of the pages opperate as intended except for admin/availability page due to the group not being able to complete the task in the given timeframe. 
The requirements and description can be found in the projectDescription.zip folder

Check group report for a more detailed breakdown of how the system works (located inside of the projectDescription folder)

This project was hosted on AWS using S3 Bucket, Lamabda Functions, RDS, and an API Gateway.
After this project was graded, the AWS resources that we used were removed to prevent the linked accounts from getting charged in the future. 
A short video of the implementation is linked in the projectDescription.zip folder to display the working application before it was removed from AWS.

The URL linked to this project is to the AWS hosted site which will no longer work once the resources are removed.
https://psiren-tables4u.s3.us-east-2.amazonaws.com/psiren-tables4u/index.html 


----------------------------------------------------
Notes for Users:

Admin Login Credentials:
    Username: admin
    Password: password
    
There no edge-case checking for when creating a table to ensure that you use a different table number for each table for that restaurant.

On the generate availability report, you may have to click the buttons 2+ times for them to load all of the contents, unsure why that is.
    Refresh the page to view report of another table/time.
    This page is very buggy but will show minor stats on a specified table at a specified time.
    Most of the functionallity is there except for the overall statistics.
