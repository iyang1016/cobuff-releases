# Cobuff Releases

Public binary release repository for the `cobuff` npm package.

The Cobuff source repository can stay private. This repository must stay public so `npm install -g cobuff` users can download platform binaries without GitHub authentication.

## Current Release

Release: `v1.0.675`

Download page:

```text
https://github.com/iyang1016/cobuff-releases/releases/tag/v1.0.675
```

## Assets

| Asset | Platform | Size | SHA256 |
|---|---:|---:|---|
| `cobuff-darwin-arm64.tar.gz` | macOS Apple Silicon | 31,272,084 | `08BA7806CFC041BF50DAEF05B55A5C9096252FE20DB080E2BF943631A85D0A71` |
| `cobuff-darwin-x64.tar.gz` | macOS Intel | 33,030,777 | `F66097347BF87CEF5B5AB4C67122476827095DFA4C7C4E7A80FC73574C016C0B` |
| `cobuff-linux-arm64.tar.gz` | Linux ARM64 | 49,013,125 | `8CE0D37DAECD78B2DA018C53E7C5F0CA69CDCC3D6B9745B2FB9253EA651AA118` |
| `cobuff-linux-x64.tar.gz` | Linux x64 | 49,091,387 | `70DEB2E74AEC824D12528CCC4D4F9C51E552B282F64456B376505BDDA5DADDB3` |
| `cobuff-win32-x64.tar.gz` | Windows x64 | 49,304,015 | `9A3AB3F0F42F67C0A074097862030541B892707E406D7470D140762419E3B26E` |

## Release Rule

For each npm package version, create a matching GitHub release tag:

```text
v<version>
```

Upload all supported assets with exact names:

```text
cobuff-linux-x64.tar.gz
cobuff-linux-arm64.tar.gz
cobuff-darwin-x64.tar.gz
cobuff-darwin-arm64.tar.gz
cobuff-win32-x64.tar.gz
```
