# neojac releases

Prebuilt releases of neojac, the Jac compiler: Linux x86_64 and aarch64, and
macOS on Apple Silicon (`.tar.gz`), and Windows x86_64 (`.zip`).

## Install

On Linux or macOS:

```sh
curl -fsSL https://github.com/jaseci-labs/neojac-releases/releases/latest/download/install.sh | bash
```

The installer downloads the latest release for your platform, verifies its
checksum, unpacks it under `~/.neojac`, and links `~/.local/bin/neojac` to it.
Pass options after `bash -s --`:

```sh
curl -fsSL https://github.com/jaseci-labs/neojac-releases/releases/latest/download/install.sh | bash -s -- --version 0.1.9
curl -fsSL https://github.com/jaseci-labs/neojac-releases/releases/latest/download/install.sh | bash -s -- --uninstall
```

On Windows, download `neojac-<version>-windows-x86_64.zip` from a release and
unpack it; `bin\neojac.exe` finds its runtime beside it.

Every release here is published by neojac's release workflow, and its notes
name the source commit it was built from.
