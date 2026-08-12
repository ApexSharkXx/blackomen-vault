# Security and Data Handling

This repository is public. Treat every commit, branch, pull request, issue, and artifact as publicly accessible.

Never commit:

- passwords, recovery codes, API keys, or access tokens;
- SSH keys, private keys, certificates, or credential-bearing `.env` files;
- session cookies, authenticated captures, or unredacted request data;
- customer data, target data, or personally identifiable information;
- private bug bounty scope or confidential program material;
- unreleased vulnerability details or evidence that could expose a target.

Use environment variables or an appropriate secret manager. Sanitize examples, captures, notes, and reports before publishing them.
