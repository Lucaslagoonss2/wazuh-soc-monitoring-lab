# Wazuh Docker Setup

## Environment

- Windows 10
- Docker Desktop
- Wazuh 4.12.0
- Single-node deployment

## Deployment Steps

1. Cloned official Wazuh Docker repository
2. Generated TLS certificates
3. Started containers using Docker Compose
4. Validated Wazuh services

## Evidence

### Certificates Generated

![Certificates](certificates-generated.png)

### Docker Compose Running

![Docker Compose](docker-compose-running.png)

### Containers Running

![Containers](docker-desktop-containers.png)

### Wazuh Dashboard

![Dashboard](wazuh-dashboard-login.png)

## Status

✅ Wazuh Manager Running

✅ Wazuh Indexer Running

✅ Wazuh Dashboard Running

✅ TLS Certificates Generated

🔄 Windows Agent Deployment (Next Phase)

🔄 Sysmon Integration (Next Phase)