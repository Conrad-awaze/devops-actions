# Composite Action Setup


## Inputs

| Name               | Description                              | Type           | Default | Required |
| ------------------ | ---------------------------------------- | -------------- | ------- | -------- |
| `aws-region`       | AWS region of your aws account           | `string`       | -       | yes      |
| `aws-account-id`   | AWS account id                           | `string`       | -       | yes      |
| `application-name` | Name of application/ECR name             | `string`       | -       | yes      |
| `dockerfile-path`  | Path to Dockerfile                       | `string`       | `.`     | no       |
| `mutable-ecr`      | Determine the ECR's mutability           | `bool`         | `true`  | no       |


## Outputs

| Name      | Description                    |
| --------- | ------------------------------ |
| `example` | An example of an output value  |



## How do you use these modules?
