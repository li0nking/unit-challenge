# unit-challenge
AWS Unit challenge repository

## Create Stack
To create the stack just use the template unit-challenge-template.json

Just make sure to use the following authentication token (default):b32046adb38bea93863fb029c1536ecc4586e1f7

## Testing the project
1. Go to the code pipeline github-events-pipeline
2. Open Amazon S3 repository sing the link from Deploy stage
3. Upload a txt file
4. Check that file was deleted
5. Check CloudWatch logs

## Lambda Policy
You can find the lambda policy on AllowLambdaReadWriteS3AndLogsPolicy file.
