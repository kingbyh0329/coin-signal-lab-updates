# Coin Signal Lab Updates

Public update host for Coin Signal Lab Next.

- Stable manifest: `stable.json` (created only after the first production-signed release)
- Release archives: GitHub Releases
- Signing: Ed25519; the production private key is stored only in the GitHub `production` Environment secret and is never committed here.
- Application clients pin the public key and reject unsigned or mismatched releases.

The repository intentionally does not store user research data, checkpoints, credentials, or signing private keys.
