# Application infrastructure
In this project, Udegma is a full stack application which is deployed to [AWS](https://aws.amazon.com/)

## AWS Services
**Amazon RDS** manages the PostgreSQL relational database
* Endpoint: database-2.cccwfvaf9ten.us-east-1.rds.amazonaws.com

**Amazon S3** is an object storage which hosts Udagram static website (frontEnd)
* http://myudagram-bucket.s3-website-us-east-1.amazonaws.com/

**Amazon Elastic Beanstalk** used to deploy the application where the Udagram backend is uploaded
* http://udagram-api-dev.eba-rinype73.us-east-1.elasticbeanstalk.com/

## Architecture Diagram
![Architecture Diagram](./screenshots/architecture%20diagram.png)
