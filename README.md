# Nelo Studio updates

Official update distribution for compatible Nelo Studio devices. Releases are downloadable without an account. Studio verifies the official Ed25519 signature and package hashes before installation.

Use **Settings → Updates** on a Studio with the trusted updater installed. Each update is checked against the device's supported hardware profile and installed runtime. Device settings, pairing, messages, and personal media are not part of the update package.

This repository contains release artifacts and distribution information. Development source and device state are maintained separately. Downloading an archive does not bootstrap trust: an existing trusted updater and public key must already be provisioned on the device.

Official signing public key (Ed25519, hexadecimal):

```
985071ae4e0bcd99eee61830afa2d81023cd74f8844b7087f30331b5fd1db136
```

The signing private key is never included in releases or installed on Studio.
