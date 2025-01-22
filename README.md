# github workflows

### terraform

Additional setup:

1. You have to add the module names as options for the `module` input.
2. Requires a role named `cicd-role` to be provisioned in gthe AWS account (setting this up is out of scope for these docs)

Required secrets:

- `AWS_ACCOUNT_ID`
