AWS System will send emails on a schedule, grabbing HTML email templates and a list of contacts from an S3 bucket.
-
Tools: Lambda, SES, S3, EventBridge, IAM

*there might be some time-delays in receiving the email, also it will be sent directly to your spam mailbox since I'm using an unverified domain.
