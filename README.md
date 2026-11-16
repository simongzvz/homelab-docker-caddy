# Self-Hosted Cloud Lab (Docker & Caddy Reverse Proxy)

## Architektur
- **OS & Hardening:** Ubuntu 26.04 LTS (Hetzner Cloud VPS), SSH Key-Only Auth, UFW Firewall (Ports 22, 80, 443)
- **Reverse Proxy & TLS:** Caddy mit automatischen Let's Encrypt Zertifikaten
- **Services (Docker Compose):**
  - **Uptime Kuma:** Service Monitoring & Alerting
  - **Portainer CE:** Container Management
  - **Memos:** Lightweight Knowledge Base (SQLite)
