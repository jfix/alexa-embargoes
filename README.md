# alexa-embargoes

Alexa skill that interacts with a user who wants to know about upcoming OECD publication embargoes

## Requirements

* AWS account
* Node, npm
* Serverless installed (https://www.serverless.com)
* Have a skill preconfigured using the Amazon Developer Console (and have its Skill ID)

## What this does

This repository only contains the code for the Lambda function that will be called by Alexa when a user interacts with it. It's the business logic if you like.

## Deploy

From within the directory holding the code:
```
$ sls deploy
```
will deploy the whole service

```
$ sls deploy -f handler
```
will deploy only the function code (i.e. all stuff node, including any new modules etc.), but not create any resources or roles.
