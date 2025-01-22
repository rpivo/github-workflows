# github workflows

### cdk

Additional setup:

1. You have to add the module names as options for the `stack` input.
2. Requires a role named `cicd-role` to be provisioned in gthe AWS account (setting this up is out of scope for these docs). You need to set up an OIDC identity provider for GitHub within the AWS account.

Required secrets:

- `AWS_ACCOUNT_ID`

### terraform

Additional setup:

1. You have to add the module names as options for the `stack` input.
2. Requires a role named `cicd-role` to be provisioned in gthe AWS account (setting this up is out of scope for these docs). You need to set up an OIDC identity provider for GitHub within the AWS account.

Required secrets:

- `AWS_ACCOUNT_ID`
