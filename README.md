<p align="center">
    <img src="https://github.com/mbchb/AWS_cleanup_unused_EIPs/blob/main/Architecture.png>
</p>
<p>
Developed a serverless solution utilizing AWS Lambda, Python, and Boto3 to automate the cleanup of unused Elastic IPs (EIPs) in AWS accounts. The Lambda function is triggered by Amazon EventBridge, scheduled to run every Friday at 6:00 PM IST. It identifies and deletes EIPs that are not associated with any EC2 instances, optimizing resource utilization and reducing unnecessary costs.
</p>
