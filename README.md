# NoteNest Auth Service

NoteNest Auth Service manages authentication and authorization across the NoteNest platform.

It integrates with Amazon Cognito for secure identity management.

## Responsibilities

- User registration and login flow
- JWT token validation
- Role based authorization
- Secure API Gateway authorizers
- Token verification middleware

## Architecture

Built using:

- AWS Lambda
- Amazon Cognito User Pools
- Amazon API Gateway
- CloudWatch Logs

Authentication Flow:

1. User authenticates via Cognito
2. JWT token issued
3. API Gateway validates token
4. Authorized Lambda executes business logic

## AWS Always Free Tier Usage

- Cognito User Pools
- Lambda free tier
- API Gateway free tier
- CloudWatch logging

## Security Model

- JWT based authentication
- Role based access control
- No password storage in custom database
- All APIs protected with Cognito authorizers

## Portfolio Value

Demonstrates secure serverless authentication and distributed API protection.
