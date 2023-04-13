https://gusiol.medium.com/desenvolvimento-na-aws-s3-e-sqs-sem-custos-com-localstack-f525d015ca48

https://dev.to/goodidea/how-to-fake-aws-locally-with-localstack-27me

https://docs.localstack.cloud/getting-started/

``` bash
aws --endpoint-url=http://localhost:4566 s3api create-bucket --bucket localstack-bucket-example

aws --endpoint-url=http://localhost:4566 s3api put-bucket-acl --bucket localstack-bucket-example --acl public-read

aws --endpoint-url=http://localhost:4566 s3 cp sample.html s3://localstack-bucket-example/
```