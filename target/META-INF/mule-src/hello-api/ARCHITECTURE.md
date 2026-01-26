# Architecture

## Flow Diagram

```mermaid
graph LR
    Client[Client] --> Listener[HTTP Listener :8081]
    Listener --> APIKit[APIKit Router]
    APIKit --> Endpoint1[GET /hello]
    APIKit --> Endpoint2[GET /health]

```

## Connectors Used

| Connector | Version | Purpose |
|-----------|---------|----------|
| mule-http-connector | ${http.connector.version} | HTTP endpoints and requests |



## Configuration

*No configuration properties detected*

