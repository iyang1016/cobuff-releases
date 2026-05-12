# Cobuff Releases

Public binary release repository for the `cobuff` npm package.

The Cobuff source repository can stay private. This repository must stay public so `npm install -g cobuff` users can download platform binaries without GitHub authentication.

## Assets

| Asset | Platform | Size | SHA256 |
|---|---:|---:|---|
| `cobuff-darwin-arm64.tar.gz` | macOS Apple Silicon | 31,272,098 | `C9DCF3F54D1B5C4A275E1EC36F11A6DEB8AA5D3A463C2126CB16FFA145050E06` |
| `cobuff-darwin-x64.tar.gz` | macOS Intel | 33,030,782 | `989684FD39066ABCD6977742F60AEB3C00697F1D58A63A322FE086D2F2B6A8E6` |
| `cobuff-linux-arm64.tar.gz` | Linux ARM64 | 49,013,156 | `ECB26EC263BFA26D7BDDEC306853827BBC204AE3077233C559580E26AE8805CA` |
| `cobuff-linux-x64.tar.gz` | Linux x64 | 49,091,400 | `3DD0A247B9486D8FD5560F0562141669255138A2B9F2DC71187EFFF86899F62B` |
| `cobuff-win32-x64.tar.gz` | Windows x64 | 50,543,254 | `90CCDAC04B13E244F0BD76F5F1F237A134F629EA7C68E9549A981779A00B71D2` |

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
