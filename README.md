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


## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* Sourav Sinha
