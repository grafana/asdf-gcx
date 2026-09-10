# asdf-gcx

[asdf](https://github.com/asdf-vm/asdf) plugin for
[gcx](https://github.com/grafana/gcx), the unified CLI for managing Grafana
and Grafana Cloud resources.

This plugin installs the prebuilt release binaries published at
https://github.com/grafana/gcx/releases. It supports macOS (darwin) and
Linux, on amd64 and arm64.

## Install

```bash
asdf plugin add gcx https://github.com/grafana/asdf-gcx.git
```

Or, from a local checkout of this folder:

```bash
asdf plugin add gcx ~/workspace/github/grafana/asdf-gcx
```

## Use

```bash
asdf list-all gcx
asdf install gcx latest
asdf global gcx latest
gcx --version
```

## Dependencies

* `curl`
* `tar`
* `git` (used by `list-all` to read available versions from GitHub tags)
