---
layout: default
title: Code review is not limited to code-owners only
parent: Repository Policies
grand_parent: GitLab Policies
---


## Code review is not limited to code-owners only
policy name: repository_require_code_owner_reviews_policy

severity: LOW

### Description
It is recommended to require code review only from designated individuals specified in CODEOWNERS file. Turning this option on enforces that only the allowed owners can approve a code change. This option is found in the branch protection setting of the repository.

### Threat Example(s)
Users can merge code without being reviewed which can lead to insecure code reaching the main branch and production.



### Remediation
1. Make sure you have owner permissions
2. Go to the projects's settings -> Repository page
3. Enter "Protected branches" tab
4. select the default branch. Check the "Code owner approval"


