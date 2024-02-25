# AWS_cleanup_unused_EIPs
I've developed an AWS Lambda function using Python and Boto3 to automatically delete unused Elastic IPs (EIPs) in your AWS account. This solution helps optimize resources and reduce unnecessary costs by removing EIPs that are not associated with any EC2 instances. The Lambda function is triggered by Amazon EventBridge every Friday at 6:00 PM.
