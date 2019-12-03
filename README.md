# Codepipeline With email Notification and Slack Integration 

This cloudformation template, creates a codepipeline with lambda deploy. This does not use AWS Codedeploy.
It will create AWS SNS topic, create subscription Lambda deploy for notifying Slack.
It has conditional operator to work based of environment types.

Please note that this will also create IAM roles.

## AWS Services used

* AWS Codepipeline
* AWS SNS
* AWS Cloudformation
* AWS Lambda

## Authors

* Sourav Sinha
