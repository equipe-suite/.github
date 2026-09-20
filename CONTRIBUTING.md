# Contributing to Equipe Suite

Equipe Suite uses independent product repositories with shared platform contracts.

Before changing a repository:

1. read its `suite.app.yaml`;
2. identify IAM, Billing and Data dependencies;
3. keep changes inside the repository's declared ownership boundary;
4. use a branch and pull request for production changes;
5. require the repository CI to pass;
6. run the documented postflight after production deployment.

Cross-product database changes require review of the contracts in `equipe-suite/data`.

Structural changes to the suite require an update to `equipe-suite/suite`.
