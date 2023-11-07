# TestRepo

1. Make 1st change to trigger action.
2. Make 2nd change after giving `sts:AssumeRoleWithWebIdentity` permission in AWS. -failed
3. Make 3rd change after change "token.actions.githubusercontent.com:sub" to "repo:*" - succeeded
4. Make 4th change and change the sub to "repo:ivanw90/*" (ivanw90) is the account name (user name)
