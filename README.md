# awselasticbeanstalk
AWS Beanstalk deployment 

I wanted to have my Webportfolio which currently on my desktop to be deployment on AWS. I found Elastic Beanstalk to be the answer as it offering Platform as Service and deploy on fly.

One of the issues that I had while deploying my Python flask application on to the AWS Beanstalk was, the code always gets deployed successfully but the application doesnot work,give an internal error. 

So finally I found that Beanstalk looks for a file called " application" on your root folder and I had to intiate Flask variable with application instead of app. 

With these two changes, I was able to deploy my Webportfolio to AWS finally. Feel free to use this and help me in making it better. Thanks ! 
