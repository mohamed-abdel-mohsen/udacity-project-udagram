# Hosting a Full-Stack Application



In this project we have learned how to take a newly developed Full-Stack application built for a retailer and deploy it to a cloud service provider so that it is available to customers. we have used the aws console to start and configure the services the application needs such as a database (RDS) to store product information and a web server allowing the site to be discovered by potential customers. 


### Dependencies:

In this Project i used and setup my Environment using :

- Node v14.15.1 (LTS) by using NVM node version model to downgrade from node 16 to 14.

- Yarn & NPM 

- AWS CLI v2

- A RDS database running Postgres.

- A S3 bucket for hosting uploaded pictures.

- A EB to setup my environment.



### Installation
First of all i start to run and deploye the code on my local machine before taking any steps further by using Yarn & NPM.


## Testing

This project contains two different test suite: unit tests and End-To-End tests(e2e). Follow these steps to run the tests.

1. `cd starter/udagram-frontend`
1. `npm run test`
1. `npm run e2e`

There are no Unit test on the back-end

## Unit Tests:
  Unit tests are using the Jasmine Framework.

### End to End Tests:
The e2e tests are using Protractor and Jasmine.

## Front-End Link from AWS S3:
- http://mohsen-udagram.s3-website-us-east-1.amazonaws.com


## Built With

- [Angular] - Single Page Application Framework
- [Node] - Javascript Runtime
- [Express] - Javascript API Framework



