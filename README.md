# aws-login-notifications

Sends a notification to an SNS topic whenever someone logs in to the console.

Requires CloudTrail integration with CloudWatch logs ([see how](https://docs.aws.amazon.com/awscloudtrail/latest/userguide/send-cloudtrail-events-to-cloudwatch-logs.html)).

Deploy the provided template and supply the log group where CloudTrail writes the config along with the SNS topic. You'll get notified on each console sign in to your account (with a delay of ~15 minutes).
