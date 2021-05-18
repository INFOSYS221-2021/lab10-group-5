# lab10-group-5
lab10-group-5 created by GitHub Classroom
brodie fogarty - bfog012 

What programming language was used in this tutorial?
  javascrpit
What were the keys and values in the hello-world sample test event template?
  {
    "key1": "value1",
    "key2": "value2",
    "key3": "value3"
  }
What can you use if you want to automate the creation and cleanup of lambda function, log groups and roles?

  You can automate the creation and cleanup of functions, log groups, and roles with AWS CloudFormation and the AWS Command Line Interface (AWS CLI).

Which line in the function code tries to retrieve the content type of the object?

  response = s3.get_object(Bucket=bucket, Key=key)
  
In the test event JSON, what information do you see about the S3 bucket?

  },
      "s3": {
        "s3SchemaVersion": "1.0",
        "configurationId": "testConfigRule",
        "bucket": {
          "name": "my-s3-bucket",
          "ownerIdentity": {
            "principalId": "EXAMPLE"
          },
          "arn": "arn:aws:s3:::example-bucket"
        },
What information do you see in the Execution Results tab after running test?

  Response
"image/jpeg"

Function Logs
START RequestId: 12b3cae7-5f4e-415e-93e6-416b8f8b66e6 Version: $LATEST
2021-02-18T21:40:59.280Z	12b3cae7-5f4e-415e-93e6-416b8f8b66e6	INFO	INPUT BUCKET AND KEY:  { Bucket: 'my-s3-bucket', Key: 'HappyFace.jpg' }
2021-02-18T21:41:00.215Z	12b3cae7-5f4e-415e-93e6-416b8f8b66e6	INFO	CONTENT TYPE: image/jpeg
END RequestId: 12b3cae7-5f4e-415e-93e6-416b8f8b66e6
REPORT RequestId: 12b3cae7-5f4e-415e-93e6-416b8f8b66e6	Duration: 976.25 ms	Billed Duration: 977 ms	Memory Size: 128 MB	Max Memory Used: 90 MB	Init Duration: 430.47 ms        

Request ID
12b3cae7-5f4e-415e-93e6-416b8f8b66e6
