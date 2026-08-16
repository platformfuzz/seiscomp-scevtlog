# seiscomp-scevtlog

![CI](https://github.com/platformfuzz/seiscomp-scevtlog/actions/workflows/ci.yml/badge.svg)
![Build and Release](https://github.com/platformfuzz/seiscomp-scevtlog/actions/workflows/build-and-release.yml/badge.svg)

Unofficial SeisComP scevtlog image built with public gsm. Not gempa-supported.

The process logs events from the messaging bus.

**Package:** [ghcr.io/platformfuzz/seiscomp-scevtlog](https://github.com/platformfuzz/seiscomp-scevtlog/pkgs/container/seiscomp-scevtlog)

## Run

```bash
docker pull ghcr.io/platformfuzz/seiscomp-scevtlog:latest
docker run --rm ghcr.io/platformfuzz/seiscomp-scevtlog:latest
```

`SCMASTER_HOST`, `SEEDLINK_HOST`, and `DB_HOST` can be overridden at run time.

## Build

```bash
docker build -t seiscomp-scevtlog:test .
docker run --rm seiscomp-scevtlog:test
```
