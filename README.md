# nandu-org Scoop bucket

Official [Scoop](https://scoop.sh) bucket for [Nandu](https://nandu.ai) command-line tools.

## Install

```powershell
scoop bucket add nandu https://github.com/nandu-org/scoop-bucket
scoop install ndf
```

That's it. Then run `ndf login` to set your tokens.

## Available manifests

| Manifest | Description |
|---|---|
| `ndf` | Nandu Development Framework CLI — see [nandu-dev-framework-cli](https://github.com/nandu-org/nandu-dev-framework-cli) |

## Auto-update

The manifest carries `checkver` + `autoupdate` blocks pointing at the upstream
GitHub releases, so:

```powershell
scoop update *
```

…picks up new versions of `ndf` automatically once a release is published.
