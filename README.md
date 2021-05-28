# CloudFormation Terraform Init

## Overview

CloudFormation template which can be used to init Terraform state bucket and state lock.

## Notes

Requirement for tag on TF user has been commented out, i.e.:

```
StringLike:
  'aws:PrincipalTag/Terraformer': '*'
```

## Credits

Initial version taken from https://thirstydeveloper.io/2021/01/17/part-1-organizing-terragrunt.html
