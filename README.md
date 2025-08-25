# Bucket List Tracker App

A **React** application to manage your bucket list items, integrated with **AWS Amplify** for backend services and hosting.

## Features
- User authentication (Login/Signup) with Amplify Auth
- CRUD operations for bucket list items
- Upload and store images with S3
- Real-time data via AWS AppSync GraphQL API
- Frontend hosted on AWS Amplify Hosting

## Tech Stack
- **Frontend**: React, Vite, Amplify UI  
- **Backend**: AWS Amplify, AppSync, Lambda  
- **Database**: DynamoDB  
- **Storage**: S3  
- **API**: GraphQL  

## Setup & Run
```bash
git clone https://github.com/EngrKevin/Bucketlistapp.git
cd bucketlistapp
npm install
npm run dev

Open http://localhost:5174/ in your browser.

Deployment
git add .
git commit -m "Update app"
git push origin main
amplify push

Services Used 🛠

AWS Amplify: Frontend & backend hosting
AWS AppSync: GraphQL API
DynamoDB: Data storage
S3: Image storage
