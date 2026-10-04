&#x20;Day 2 - 3 Oct 2026



&#x20;What I did

\- Recalled IAM best practices and answered the Lambda/DynamoDB role question

\- Created an S3 bucket with public access blocked and uploaded a file

\- Tested the Object URL (Access Denied) and a pre-signed URL (worked)

\- Launched a t3.micro EC2 instance, then terminated it

\- Explored CloudWatch metrics and logs



&#x20;What I learnt
- Lambda should use an IAM role, not pasted access keys

\- Default deny, explicit Deny beats Allow, and least privilege

\- A pre-signed URL shares one file temporarily without opening the bucket

\- When something breaks, check CloudWatch logs first, then metrics, then add alarms



&#x20;What confused me

\- Which instance types count as free-tier eligible

\- How to read CloudWatch metrics properly



What I need to revisit

\- WSL timeout error (HCS\_E\_CONNECTION\_TIMEOUT)

\- Delete the S3 bucket during my Day 7 review



&#x20;What I'm doing tomorrow

\- Day 3: Lambda, API Gateway, DynamoDB, Route 53, and RDS

