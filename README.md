# github-oidc-cfn

Create OIDC Provider for github actions. To be used to retrieve temporary credentials from AWS. 


## Deployment
```bash
aws cloudformation deploy --stack-name github-oidc-povider --template-file github_oidc_template.yml --region us-east-1 --tags Environment=Prod manage_by=aaron.zhaocr@gmail.com
```
