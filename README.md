# jtsunne/tap

Homebrew tap for [jtsunne](https://github.com/jtsunne) tools.

## Install

```bash
brew tap jtsunne/tap
brew install epm
```

## Tools

| Formula | Description |
|---------|-------------|
| [epm](https://github.com/jtsunne/epm-go) | Terminal dashboard for Elasticsearch cluster performance monitoring |

## Usage

```bash
epm http://localhost:9200
epm --insecure https://elastic:changeme@prod.example.com:9200
epm --interval 30s http://localhost:9200
```

## Update

```bash
brew update
brew upgrade epm
```
