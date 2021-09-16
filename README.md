# Serverless Rom Scraping

AWS Step Functions serve as a really good initiator for Fargate processes as they can be triggered by a schedule or a HTTP Request.
AWS Step Functions can also trigger Notifications via SNS for when processes fail or complete.
AWS Step Functions is also serverless by default, requiring no compute resources until it's executed.

## Getting Started

### Set up your environment file

1. Copy `.env.example` to `.env.development` or `.env.production` depending on which environment you're configuring
2. Add your values to the environment dotenv file.

