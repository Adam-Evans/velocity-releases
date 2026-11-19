# Velocity releases

Signed release packages for the Velocity agent, plus the apt and yum repositories that serve them.

- **Releases:** the [Releases](../../releases) page holds the `.deb`, `.rpm` and `.tar.gz` packages for amd64, arm64 and armv7, with `checksums.txt` and its signature `checksums.txt.asc`.
- **Package repositories:** served from this repository's GitHub Pages site once the first release is published. The setup steps are in the Velocity Linux agent docs.

## Signing key

Every package and `checksums.txt` is signed with this OpenPGP key:

```
Velocity Release Signing
6FB8 CD91 799B C04B 8918 611A BB02 D14E 2540 4495
```

The public key is [`velocity-release-key.asc`](velocity-release-key.asc). Check that the fingerprint matches before you trust it:

```
gpg --show-keys velocity-release-key.asc
```

This repository only publishes builds. Source code, issues and security reports go to the main project.
