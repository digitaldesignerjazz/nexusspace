# Mesh Networking Layer

**xMesh / NovaNet / QNET + Supporting Infrastructure**

This is the foundational connectivity layer of NexusSpace — resilient, decentralized, privacy-oriented mesh networks that everything else (agents, blockchain, monitoring, hardware) ultimately runs on or communicates through.

## Subdirectories

- `xmesh/` — Core xMesh implementation and experiments
- `novanet/` — NovaNet protocol and node software
- `qnet/` — QNET protocol, integration, and higher-level abstractions
- `configs/` — Yggdrasil configuration, Docker Compose files, monitoring setups, deployment playbooks

## Current Focus Areas
- Reproducible node deployment (Docker + systemd + monitoring)
- Hardware integration (Tenda Nova and similar)
- Privacy and traffic obfuscation techniques
- Monitoring dashboards and automated recovery
- First QNET-level abstractions and mesh-to-blockchain bridges

See `docs/current-state.md` and `docs/roadmap.md` for latest priorities.

Drop new code, configs, topology diagrams, and test results here.