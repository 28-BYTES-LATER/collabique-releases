# Collabique desktop releases

Signed and notarized Collabique desktop binaries for Apple Silicon Macs.
This repository contains distribution documentation and release assets only.

## Install

After the first stable release has been published:

```sh
brew tap 28-BYTES-LATER/28byteslater
brew install collabique
```

Opt into release candidates with:

```sh
brew install --cask 28-BYTES-LATER/28byteslater/collabique@rc
```

The channels conflict because both install `Collabique.app`. Final releases
update both channels; subsequent RC releases update only the RC channel.

Each release includes a signed macOS ARM64 ZIP, a SHA-256 checksum and a release
manifest. Stable versions use `vX.Y.Z`; candidates use `vX.Y.Z-rc.N`.
The first public candidate is [v0.1.0-rc.1](https://github.com/28-BYTES-LATER/collabique-releases/releases/tag/v0.1.0-rc.1). The source repository remains private.
