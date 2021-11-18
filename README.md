# actions-auto-improve-code-style

This GitHub workflow executes eslint with `--fix` argument, so that we can not only capture but also automatically fix as many as possible.

If any errors were fixed by `eslint`, a new PR is created including the changes made. The base is always the current branch while the assignee is the PR author. 

This allows the PR author to review the changes and if needed merge them into into the initial PR.
