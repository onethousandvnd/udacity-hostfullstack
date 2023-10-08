### Description

When a user accesses a link to AWS S3 through the website and makes a request for data, the front-end hosted on AWS S3 will initiate a call to the back-end hosted on Elastic Beanstalk. Subsequently, the back-end will communicate with the database hosted on RDS to retrieve the required data based on the user's request.

## Backend API: 