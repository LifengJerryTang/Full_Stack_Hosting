# Hosting a Full-Stack Application

## Application Link
- `http://udagram-jerry-bucket.s3-website-us-east-1.amazonaws.com/`

## Application Overview
The udagram application was provided for this project, which is a fairly simple application that includes all the major components of a Full-Stack web application. The goal of this project, on the other hand, is to learn how to host a fully functional full-stack application on AWS.

The following AWS Services are used
1. AWS S3 Bucket for the frontend
2. Elastic Beanstalk for the backend 
3. RDS for the PostgreSQL database

## Running the Backend Locally
The backend was built using the Node JS framework. To run the backend locally, follow the commands below in order:

```
1. cd udagram
2. source set_env.sh
3. cd udagram-api
3. npm install
4. npm run start
```
The backend will be running at `http://localhost:8100`

## Running the Frontend Locally
The frontend was build using **Angular-Ionic**. To run the frontend locally, make sure you are in the root folder and run the following commands below in order:

```
1. cd udagram/udagram-frontend
2. npm install
3. npm run start
```
The frontend will be running at `http://localhost:4200/`

## More Documentations
To learn more about the project dependencies, AWS architecture, and the CI/CD pipline, please see the **screenshots** folder and the **documentations** folder.

## Testing

This project contains two different test suite: unit tests and End-To-End tests(e2e). Follow these steps to run the tests.

1. `cd starter/udagram-frontend`
1. `npm run test`
1. `npm run e2e`

There are no Unit test on the back-end

### Unit Tests:

Unit tests are using the Jasmine Framework.

### End to End Tests:

The e2e tests are using Protractor and Jasmine.

## Built With

- [Angular](https://angular.io/) - Single Page Application Framework
- [Node](https://nodejs.org) - Javascript Runtime
- [Express](https://expressjs.com/) - Javascript API Framework

## License

[License](LICENSE.txt)