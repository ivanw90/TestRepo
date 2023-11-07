# TestRepo

1. Make 1st change to trigger action.
2. Make 2nd change after giving `sts:AssumeRoleWithWebIdentity` permission in AWS. -failed
3. Make 3rd change after change "token.actions.githubusercontent.com:sub" to "repo:*" - succeeded
4. Make 4th change and change the sub to "repo:ivanw90/*" (ivanw90) is the account name (user name)
5. 5th change after giving "iam:CreateUser" permission
6. th change to change the sub to "repo:ivanw-org/*" (ivanw-org is the org name under this account and the org doesn not own the repo)
