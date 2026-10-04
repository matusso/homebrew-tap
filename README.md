# homebrew-tap

Homebrew formulae for tools by [matusso](https://github.com/matusso). They
work on macOS and Linux (`amd64`, `arm64`).

| Formula | Description |
| --- | --- |
| [`nyxr`](https://github.com/matusso/nyxr) | Network scanner with service identification and packet capture |
| [`sslknife`](https://github.com/matusso/sslknife) | Swiss-army knife for TLS, certificates, PKI and SSH keys |

## Install

```sh
brew install matusso/tap/<formula>
```

or tap once and install by name:

```sh
brew tap matusso/tap
brew install nyxr sslknife
```

Upgrade with `brew upgrade <formula>`.

## Updates

Formulae under `Formula/` are generated and pushed by each project's release
workflow. Don't edit them by hand; changes are overwritten on the next release.
