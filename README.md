AWS System will send emails grabbing HTML email templates and a list of contacts from an S3 bucket.
-
Understanding The Components

**AWS Lambda** provides serverless compute capacity to run our application's backend logic. We'll utilize Lambda functions to handle incoming requests, business logic, and communication with other AWS services.

**Amazon S3** is a storage solution for our application that stores static assets such as HTML templates, pictures, and CSV files holding email lists or campaign data.

**AWS SES **(Simple Email Service) allows us to send mass emails to our subscribers. SES offers a dependable and scalable email delivery platform with capabilities such as email validation, bounce handling, and reputation management.

**Amazon EventBridge** enables us to manage and automate workflows by responding to events from various AWS services or custom sources. We'll utilize EventBridge to activate Lambda functions in response to certain events, such as new email subscriptions or campaign scheduling.

*there might be some time-delays in receiving the email, also it will be sent directly to your spam mailbox since I'm using an unverified domain.
