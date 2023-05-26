# Welcome to your CDK JavaScript project

This is a blank project for CDK development with JavaScript.

The `cdk.json` file tells the CDK Toolkit how to execute your app. The build step is not required when using JavaScript.

## Useful commands

* `npm run test`         perform the jest unit tests
* `cdk deploy`           deploy this stack to your default AWS account/region
* `cdk diff`             compare deployed stack with current state
* `cdk synth`            emits the synthesized CloudFormation template

# Prerequisite

1. cd to CDK folder

```bash
cd cdk
```

2. Create .env file

```bash
touch .env
echo "CDK_DEFAULT_ACCOUNT=$AWS_ACCOUNT_ID" >> file.txt
echo "CDK_DEFAULT_REGION=$AWS_REGION" >> file.txt

```

2. Synth and deploy CDK

```bash
npm install
npm run cdk:deploy
```