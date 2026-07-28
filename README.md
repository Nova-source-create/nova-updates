# Nova Updates

Official update repository for Nova.

This repository is used to distribute signed Nova release metadata
and public release artifacts.

## Security

Nova release manifests are authenticated using Ed25519 signatures.

Private release signing keys are never stored in this repository.

Release artifacts are additionally protected by SHA-256 verification.

## Important

Only public release artifacts and public update metadata belong here.

Private keys, credentials, environment files and development secrets
must never be committed.
