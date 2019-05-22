# Key Features
- Centralized control
- Shared access to your account
- Granular permissions
- Identity Federation
- Multifactor auth
- Provide temporary access for users/devices and services where neccessary
- Allows key rotation policy

# Terms
## Users
- End users
## Groups
- A collection of users
## Policies
- made up of documents, called policy documents
- formatted in JSON
## Roles
- assignable to AWS resources


### IAM is Universal and does not apply to regions
### The root account is the account created when first setup your AWS account and it's the sudo user that has complete Admin access
### New users won't have any permission when first created
### Access Key ID and Secret Access Keys can be assigned to new users when created
### Access keys are not the same as passwords. Cannot be used to login to the console but can be used for programmati access
### Access keys can only be viewed once when created
### Set up MFA for the root account
### Password policies can be customized and rotation policies can be set