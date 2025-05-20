This repository contains a sample CloudFormation template.

Recent updates:
- Added a new `TenantId` parameter to support tagging STS operations with the
  tenant identifier.
- Added `EnterpriseIdcRedirectUri` and updated the TokenExchange Lambda to
  assume the cross-account role with this tenant tag before calling
  `create_token_with_iam` using an authorization code.
