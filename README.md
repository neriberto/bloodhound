# bloodhound

[![Docker Image CI for GHCR](https://github.com/neriberto/bloodhound/actions/workflows/publish-ghcr.yaml/badge.svg)](https://github.com/neriberto/bloodhound/actions/workflows/publish-ghcr.yaml)


## Install

```
docker pull ghcr.io/neriberto/bloodhound:latest
```

## Applications

* `HEDnsExtractor` - [github.com/HuntDownProject/hednsextractor](https://github.com/HuntDownProject/hednsextractor)
* `pdtm` - All tools from Project Discovery using the [github.com/projectdiscovery/pdtm](https://github.com/projectdiscovery/pdtm)
* `anew` - [github.com/tomnomnom/anew](https://github.com/tomnomnom/anew)
* mc - [Minio](https://min.io/) command line

## Usage Examples

1. Easy run, interactive mode getting a shell

```bash
$ docker run -it ghcr.io/neriberto/bloodhound:latest
```

2. Run and mapping local directories

```bash
$ docker run -it -v ./scripts:/app/scripts  ghcr.io/neriberto/bloodhound:latest
```