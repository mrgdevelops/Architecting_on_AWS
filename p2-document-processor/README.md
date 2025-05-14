Created a fully managed, serverless, and event-driven solution on AWS that leverages the managed AI service (Textract) for automated document processing.
The solution is easily adaptable and scalable for processing and storing any company's documents. It supports PDF, PNG, and other formats.

Just for fun, I tested it on a Mercadona 1996 receipt - it worked fine despite the barely visible date.

Characteristics:

- Fully serverless solution
- Event-driven architecture (leverages S3 event notifications)
- Extremely cost-effective (uses AWS Free Tier only)

Services used:

- S3
- IAM
- Lambda with Python
- DynamoDB
- SES (Simple Email Services)
- Amazon Textract
- CloudWatch (logging & debugging)

#AWS #AI
