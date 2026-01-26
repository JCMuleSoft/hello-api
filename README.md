# hello-api

Simple REST API with /hello and /health endpoints

## Type

- **Project Type:** HTTP API
- **Runtime:** Mule 4.x
- **Java:** 17

## Purpose

Simple REST API with /hello and /health endpoints

## Setup

### Prerequisites

- Docker
- Bun runtime

### Local Development

```bash
# Build
~/.pai/mule-container/mule-build.sh .

# Test locally
~/.pai/mule-container/mule-local-test.sh .
```

## API Endpoints

| Method | Path | Description |
|--------|------|-------------|
| GET | `/hello` | - |
| GET | `/health` | - |



## Connectors

| Connector | Version | Purpose |
|-----------|---------|----------|
| mule-http-connector | ${http.connector.version} | HTTP endpoints and requests |





## Exchange

- **Group ID:** `pending`
- **Asset ID:** `hello-api`
- **Version:** `1.0.0`

## Status

![Lifecycle](https://img.shields.io/badge/lifecycle-initialize-blue)
![Coverage](https://img.shields.io/badge/coverage-0%25-red)
