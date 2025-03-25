# aws-cheatsheet

### Limit EC2 Instance Permissions to itself
[ec2-self-management.policy.json](ec2-self-management.policy.json)
>[!NOTE]
> The AWS IAM condition context key `aws:ARN` is undocumented and the AWS web console UI will mark the usage of `aws:ARN` as an error, but don't let that bother you, it still works.
