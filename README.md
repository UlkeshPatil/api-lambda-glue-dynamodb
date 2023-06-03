# AWS_api_lambda_glue_dynamodb

![image](https://user-images.githubusercontent.com/124227342/229685525-3b5b84cb-e1fa-4207-9e72-76a1f8ca0c29.png)

Commandline command to create zip files for aws lambda
'''
pip install --platform manylinux2014_x86_64 --target=lambda_function_code --implementation cp --python 3.9 --only-binary=:all: --upgrade pymongo[srv] requests boto3
'''
Uploaded the ZipFile in aws lamba, given necessary permissions and configured environment variables.

Initiated weekly lambda trigger using  (CloudWatch Events).

Performed ETL using Glue Job

Store data from s3 to DynamoDB
