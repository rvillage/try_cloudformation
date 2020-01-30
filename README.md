# try_cloudformation

## validation

```
$ aws cloudformation validate-template --template-body file://vpc.yml
```

## deploy

```
$ aws cloudformation deploy --template-file vpc.yml --stack-name try-cfn --tags Name=try-cfn
```

## itamae

```
$ bundle exec itamae ssh -i ** -h ** -u ** recipe.rb
```

## serverspec

```
$ bundle exec rake spec
```
