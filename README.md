# gofile-get

[![basher install](https://www.basher.it/assets/logo/basher_install.svg)](https://www.basher.it/package/)

download files from gofile.io links

## install

```bash
basher install gnomegl/gofile-get
```

## usage

```bash
gofile-get https://gofile.io/d/contentid
```

download shared files from gofile.

## options

- `-p, --password` - password for protected links
- `-d, --download-dir` - output directory
- `-w, --workers` - parallel downloads (default: 5)
- `-l, --list` - list files without downloading
- `-j, --json` - output file info as json

## config

```bash
export GF_DOWNLOADDIR="/path/to/downloads"
export GF_TOKEN="your_token"
```

## requirements

- curl
- jq