# Security and Secret Handling

This repository is private, but private does not mean safe for secrets.

Never commit:
- passwords or recovery codes;
- API keys or access tokens;
- SSH/private keys;
- session cookies;
- `.env` files containing credentials;
- broker credentials;
- cryptocurrency seed phrases;
- unredacted customer or target data;
- confidential bug bounty program material that should not be retained here.

Use environment variables or an appropriate secret manager.
