# aws-cheatsheet

### Limit EC2 Instance Permissions to itself

[ec2-self-management.policy.json](ec2-self-management.policy.json)

The AWS IAM condition key `aws:ARN` represents the target instance ARN.

>[!NOTE]
> The condition key `aws:ARN` is an undocumented key and the AWS web console UI will mark the usage of `aws:ARN` as an error, but don't let that bother you, it still works.
