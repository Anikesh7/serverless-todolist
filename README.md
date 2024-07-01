# Serverless Todo List Application

This is a simple todo list application built using AWS services such as S3, CloudFront, Route 53, DynamoDB, and Lambda. It allows users to create, delete, and view todo items.

## Live Demo

[Live Demo](https://serverless.quizbotiq.me)

## Architecture

The application is built using the following AWS services:

- **S3**: Used to host the static website.
- **CloudFront**: CDN for faster content delivery.
- **Route 53**: DNS service for routing traffic to the website.
- **DynamoDB**: NoSQL database for storing view count.
- **Lambda**: Serverless compute service used for the backend logic.
