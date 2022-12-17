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

## Infrastructure : 
in this Project we have used 3 services from AWS 
- RDS: Amazon RDS is a relational database service that manages common database administration tasks, resizes automatically, and is cost-friendly.
i have used Relational DATABASE Service with Postgres Engine, We created called udagaram. 

- S3 : Amazon S3 is an object storage service that stores data as objects within buckets. An object is a file and any metadata that describes the file. A bucket is a container for objects. 
And we have used it to make static website for our clint side. 

 - EB : Elastic Beanstalk (EB) is a fairly straightforward way of setting up scalable applications. It uses Amazon Elastic Compute Cloud (EC2) instances, Amazon Simple Storage Service (S3) buckets, and load balancers to manage your application architecture for US . 

 ## App dependencies: 
- Node.js:  in this project we used many dependencies for this project, 
 we used nvm to downgrade node.js v16 to node.js v 14 since this project have been build with this version.

 - Express : Express is a minimal and flexible Node.js web application framework that provides a robust set of features for web and mobile applications.
- yarn : Yarn is a package manager that doubles down as project manager.

 - Angular : Angular is a platform and framework for building single-page client applications using HTML and TypeScript. Angular is written in TypeScript.

- Typescript: we hade to install version 3.4.5 since there was error occure from angular compiler requires this version. 

## Pipeline process: 
By connecting the CircleCl to our github to get noticed when any changes have been added by different developers, and adding Environment variables to circleCl. The 7 essential stages of a CI/CD pipeline So now we’ve seen what a pipeline is for..

- The trigger

- Code checkout

- Compile the code

- Run unit tests

- Package the code

- Run acceptance tests

- Delivery or Deployment

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



