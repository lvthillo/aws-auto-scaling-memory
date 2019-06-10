# aws-auto-scaling-memory

Detailed description is available [here](https://medium.com/@lvthillo/aws-auto-scaling-based-on-memory-utilization-in-cloudformation-159676b6f4d6?postPublishedType=initial).

Create stack and define your key pair as parameter.

```
$ aws cloudformation create-stack --stack-name auto-scaling-memory --template-body file://template.yml --capabilities CAPABILITY_NAMED_IAM
```
