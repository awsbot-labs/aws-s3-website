# aws-s3-website
Creates a single page www.example.com website in an Amazon Simple Storage Service bucket a CloudFront distribution and a Route53 alias DNS record.
```
  ./aws-s3-website create|update example.com ORIGINACCESSID
```
Requires the [aws-cli](http://aws.amazon.com/cli/) tools, and a [Route53](https://aws.amazon.com/route53/) domain.
