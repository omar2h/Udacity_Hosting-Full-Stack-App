# Application infrastructure
In this project, Udagram is a full stack application which is deployed to [AWS](https://aws.amazon.com/)

## AWS Services
**Amazon RDS** manages the PostgreSQL relational database
* Endpoint: database-1.cccwfvaf9ten.us-east-1.rds.amazonaws.com

**Amazon S3** is an object storage which hosts Udagram static website (frontEnd)
* http://udagramapp-bucket.s3-website-us-east-1.amazonaws.com/

**Amazon Elastic Beanstalk** used to deploy the application where the Udagram backend is uploaded
* http://udagramapi-env.eba-z3gysyck.us-east-1.elasticbeanstalk.com/

## Architecture Diagram
![Architecture Diagram](./diagrams/architecture%20diagram.png)
