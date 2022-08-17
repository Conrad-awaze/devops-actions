# Composite Action Setup


## Inputs

| Name               | Description                              | Type           | Default | Required |
| ------------------ | ---------------------------------------- | -------------- | ------- | -------- |
| `gh-pat`           | An example of a required input variable  | `secret`       | -       | yes      |
| `directory`        | An example of an optional input variable | `string`       | -       | no       |


## Outputs

| Name      | Description                    |
| --------- | ------------------------------ |
| `example` | An example of an output value  |



## How do you use these modules?

```yml

    - name: Security Analysis of Terraform
        uses: awazevr/security-analysis-action@main
        with:
            gh-pat: ${{ secrets.GH_PAT }}


```