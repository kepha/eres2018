# ERES-2018

Demo using serverless framework to deploy nanoservices at AWS

# Install serverless framework

```
$ npm install serverless -g
```

# Install the dependencies

```
$ npm install aws-sdk --save
$ npm install uuid --save
```

# Configure your AWS Credentials

```
$ export AWS_ACCESS_KEY_ID=[AWS_ACCESS_KEY_ID]
$ export AWS_SECRET_ACCESS_KEY=[AWS_SECRET_ACCESS_KEY]
```

# Deploy do AWS

```
$ serverless deploy
```

# Test your application

```
endpoints:
POST - https://YOUR-APP-ID.execute-api.us-east-1.amazonaws.com/dev/todos
GET - https://YOUR-APP-ID.execute-api.us-east-1.amazonaws.com/dev/todos
GET - https://YOUR-APP-ID.execute-api.us-east-1.amazonaws.com/dev/todos/{id}
PUT - https://YOUR-APP-ID.execute-api.us-east-1.amazonaws.com/dev/todos/{id}
DELETE - https://YOUR-APP-ID.execute-api.us-east-1.amazonaws.com/dev/todos/{id}
```