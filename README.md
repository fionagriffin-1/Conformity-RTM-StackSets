# Conformity-RTM-StackSets

Deployment of RTM across all the accounts using stack sets approach. You can follow the steps mentioned below:

Template URL: https://s3-us-west-2.amazonaws.com/cloud-conformity-public-us-west-2/monitoring/event-bus-template.yml

CloudConformityAccountId: 717210094962

EventBusSources:aws.s3,aws.ec2,aws.elasticloadbalancing,aws.autoscaling,aws.cloudformation,aws.iam,aws.dynamodb,aws.rds,aws.lambda,aws.cloudfront,aws.organizations,aws.config,aws.guardduty,aws.cloudtrail,aws.route53domains,aws.kms,aws.route53,aws.sts,aws.ecs,aws.securityhub,aws.signin,aws.macie
 
Deploy to all accounts, all regions set failure tolerance to 100% allowed in case you have disabled regions e.g. HK / Bahrain

