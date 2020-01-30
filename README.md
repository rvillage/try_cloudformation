# try_cloudformation

## validation

```
$ aws cloudformation validate-template --template-body file://vpc.yml
```

## deploy

```
$ aws cloudformation deploy --template-file vpc.yml --stack-name try-cfn --tags Name=try-cfn
```
