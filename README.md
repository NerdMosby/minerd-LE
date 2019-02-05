# Bitcoin LE CPU miner
CPU miner adapted to LE technology. It supports stratum and can be used in pool mining.

Run ```minerd --help``` to list all options.

Example of pool mining:
```
minerd --url=stratum+tcp://[domain]:[port] -u [wallet] -p x --algo=sha256d -t [threads]
```

Download latest release from [here](../../releases).

## Unix Dependencies

- **libcurl**: https://curl.haxx.se/libcurl/
- **jansson**: http://www.digip.org/jansson/

You must have these libraries installed in your unix system.

## Build

For complete documentationm about how to build Bitcoin LE CPU miner, check  [here](BUILD.md).

