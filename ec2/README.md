```
aws cloudformation create-stack --template-body file://templates/single-instance.yml --stack-name single-instance --parameters file://parameters/single-instance.json --region us-east-1 --profile enopits

aws cloudformation update-stack --stack-name single-instance --template-body file://templates/instance-and-route53.yml --parameters file://parameters/instance-and-route53.json --region us-east-1 --profile enopits

```

```
aws cloudformation create-stack --template-body file://templates/instance-and-route53.yml --stack-name route53-$(date +%s) --parameters file://parameters/instance-and-route53.json --region us-east-1 --profile enopits

```

```
```

```
```

```
```

```
```

```
```

```
```

```
```

```
```

```
```

```
```

```
```

```
```

```
```

```
```
