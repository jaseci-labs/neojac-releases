# neojac releases

Prebuilt releases of neojac, the Jac compiler, for Linux x86_64, Linux aarch64,
macOS aarch64 and Windows x86_64.

## Install

```sh
curl -fsSL https://github.com/jaseci-labs/neojac-releases/releases/latest/download/install.sh | bash
```

The installer downloads the latest release for your platform, checks it against
its SHA-256 digest, and installs it under `~/.neojac`. Pass options after `--`:

```sh
curl -fsSL https://github.com/jaseci-labs/neojac-releases/releases/latest/download/install.sh | bash -s -- --version 0.1.10
curl -fsSL https://github.com/jaseci-labs/neojac-releases/releases/latest/download/install.sh | bash -s -- --uninstall
```

Each release is published here by neojac's release workflow. Its notes name the
source commit it was built from.
