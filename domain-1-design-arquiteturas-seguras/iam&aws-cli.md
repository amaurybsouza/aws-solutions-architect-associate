# IAM: Users & Groups
- IAM = Identity and Access Management, Global service.
- Root account: created by default, shouldn't be used os shared.
- Users are people within your organization and can be grouped
- groups only contain users, not other groups
- users don't have to belong to a group, and user can belong to multiple groups.

![aws](https://github.com/amaurybsouza/aws-solutions-architect-associate/blob/main/images/aws1.png)

# IAM MFA Overview

## IAM - Password Policy
- strong passwords = higher security for your account
- in AWS, you setup a password policy:
  - set a minimum password lenght
  - require specific character types:
    - including uppercase letters
    - lowercase letters
    - numbers
    - non-alphanumeric characters

  - allow all IAM users to change their own passwords
  - require users to change their password after some time (password experation).