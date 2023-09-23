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
The frontend was build using Angular-Ionic. To run the frontend locally, make sure you are in the root folder and run the following commands below in order:

```
1. cd udagram/udagram-frontend
2. npm install
3. npm run start
```
The frontend will be running at `http://localhost:4200/`