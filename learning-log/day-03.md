&#x20;Day 3 - 4 Oct 2026



&#x20;What I did

\- Recalled why a pre-signed URL beats a bucket policy

\- Created a Lambda function (Python) that returns JSON, tested it (200), and read its logs in CloudWatch

\- Created a DynamoDB table `day3-bookings` with partition key `bookingId`

\- Added items with different attributes and types

\- Answered the Lambda vs EC2 and DynamoDB vs RDS scenario



&#x20;What I learned

\- Lambda only runs and bills when triggered, so it suits spiky traffic

\- API Gateway is the front door that passes requests to Lambda

\- DynamoDB suits simple key lookups; RDS suits relational data and flexible queries

\- Only the DynamoDB key has a restricted type; other attributes can be any type

\- Route 53 is DNS, the phone book that turns names into addresses



&#x20;What confused me

\- 



&#x20;What I need to revisit

\- WSL timeout error

\- Connect the Lambda to DynamoDB with an IAM role (Project 1)

\- Delete the S3 bucket during Day 7 review



&#x20;What I'm doing tomorrow

\- Day 4: Linux commands

