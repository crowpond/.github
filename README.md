<p align="center">
  <a href="https://crowpond.github.io/docs/"><img src=".github/assets/hero.svg" alt="crowpond: a lake you can read to the bottom" width="100%"></a>
</p>

<p align="center">
  <a href="https://github.com/crowpond/gateway/actions/workflows/ci.yml"><img src="https://github.com/crowpond/gateway/actions/workflows/ci.yml/badge.svg" alt="CI"></a>
  <a href="https://github.com/crowpond/gateway/pkgs/container/gateway"><img src="https://img.shields.io/badge/image-ghcr.io%2Fcrowpond%2Fgateway-blue?logo=docker&logoColor=white" alt="Container image"></a>
  <a href="LICENSE"><img src="https://img.shields.io/badge/license-MIT-green" alt="MIT license"></a>
  <img src="https://img.shields.io/badge/PHP-8.3%20%7C%208.4%20%7C%208.5-777BB4?logo=php&logoColor=white" alt="PHP 8.3, 8.4 and 8.5">
  <img src="https://img.shields.io/badge/PostgreSQL-16-336791?logo=postgresql&logoColor=white" alt="PostgreSQL 16">
  <img src="https://img.shields.io/badge/arch-amd64%20%7C%20arm64-lightgrey" alt="amd64 and arm64">
  <a href="https://crowpond.github.io/docs/"><img src="https://img.shields.io/badge/docs-crowpond.github.io-informational" alt="Documentation"></a>
</p>

# crowpond gateway

## What is it?

crowpond is an open source **datalake**: you send it labelled data (JSON records, files, high-rate streams) and read it back through one REST API. Recent data lives in PostgreSQL, past days are archived as Parquet. Reads span both. Every stored object carries a STANAG 4774 confidentiality label bound to it per STANAG 4778.

The gateway is the core of it: the API, the storage and the archive job. The admin console is a separate app.

## Documentation

Installation (Docker Compose, Fly.io, Portainer), configuration, concepts and the API reference: **<https://crowpond.github.io/docs/>**
