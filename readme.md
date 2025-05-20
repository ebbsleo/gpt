This repository contains a sample CloudFormation template.

Recent updates:
- Added `TenantId` parameter to support tagging STS operations with the tenant identifier.
- Added `EnterpriseIdcRedirectUri` parameter so the TokenExchange Lambda can
  call `create_token_with_iam` using the authorization code flow.
