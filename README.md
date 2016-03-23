# TumblessTemplates
CloudFormation templates to support quicker setup of Tumbless (https://github.com/matteobrusa/Tumbless)

Save time setting up your S3 bucket and user credentials for Tumbless using an AWS CloudFormation template.

- 1 - Pick a name for your S3 bucket and [Launch Template][a32eeccf] (or [Download Template][def765ae]).
- 2 - Create IAM credentials for 'SiteAdminS3User' IAM user (see shortcut link under the CloudFormation 'Resources' tab 'Create Access Key' within Security Credentials tab).
- 3 - Download a copy of Tumbless (https://github.com/matteobrusa/Tumbless).
- 4 - Update Public/admin.json with S3 bucket name and IAM credentials.
- 5 - Upload all the Tumbless code to your S3 bucket (see shortcut link to S3 bucket under the CloudFormation Stack 'Resources' tab).

[a32eeccf]: https://eu-west-1.console.aws.amazon.com/cloudformation/home?region=eu-central-1#/stacks/new?stackName=BasicTumbless&templateURL=https://github.com/caarl/TumblessTemplates/blob/master/BasicTumbless.template "Link to Launch Template in AWS eu-central-1"
[def765ae]: https://github.com/caarl/TumblessTemplates/blob/master/BasicTumbless.template "Download Template"
