# unit-challenge
AWS Unit challenge repository

## Create Stack
To create the stack just use the template unit-challenge-template.json

Please use the **token** provided in the email on **OAuthToken parameter**.

## Testing the project
1. Go to the code pipeline github-events-pipeline
2. Open Amazon S3 repository sing the link from Deploy stage
3. Upload a txt file
4. Check that file was deleted
5. Check CloudWatch logs

## Lambda Policy
You can find the lambda policy on AllowLambdaReadWriteS3AndLogsPolicy file.
