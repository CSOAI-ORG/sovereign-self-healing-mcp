# Sovereign Self-Healing MCP

> **The only self-healing infrastructure MCP with cryptographic governance.**
>
> Every remediation is Ed25519-signed, BFT Council-approved, and EU AI Act compliant.

[![Sovereign](https://img.shields.io/badge/CSOAI-Sovereign-00d4ff)](https://csoai.org)
[![EU AI Act](https://img.shields.io/badge/EU%20AI%20Act-Article%209%2F13%2F15%2F26%2F50-22c55e)](https://csoai.org/compliance)
[![Sigil](https://img.shields.io/badge/Attestation-Ed25519%20Sigil-5b21b6)](https://proofof.ai)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![PyPI](https://img.shields.io/badge/PyPI-pip%20install%20sovereign--self--healing--mcp-3775a9)](https://pypi.org/project/sovereign-self-healing-mcp/)

## What Makes This Sovereign

| Feature | What It Means |
|---------|-------------|
| **Sigil Bus (Ed25519)** | Every remediation action is cryptographically signed. Tamper-proof audit trail. |
| **BFT Council** | Critical decisions require 3-of-5 Byzantine Fault Tolerant consensus. No single point of failure. |
| **28-Domain Compliance** | Auto-remediation rules vary by industry domain (Finance, Healthcare, Energy, etc.). |
| **EU AI Act Built-In** | Articles 9, 13, 15, 26, 50 — risk management, transparency, bias, FRIA, watermarking. |
| **NIST AI RMF** | Govern, Map, Measure, Manage — all four functions implemented. |
| **ISO 42001** | AI management system controls mapped to auto-remediation policies. |

## 🚀 Quick Start

```bash
# Install via pip
pip install sovereign-self-healing-mcp

# Or via Smithery
npx -y @smithery/cli@latest install sovereign-self-healing-mcp --client claude

# Or via uvx (fastest)
uvx sovereign-self-healing-mcp
```

## ✨ Tools

| Tool | Description | Governance |
|------|-------------|------------|
| `node_health_check` | Check CPU, memory, disk, GPU | Auto + attested |
| `cluster_health_check` | Check all 9 nodes | Auto + attested |
| `restart_service` | Restart failed service | Auto if safe, council if critical |
| `auto_remediate` | Fix common issues | **28-domain compliance check first** |
| `gpu_orchestration` | Allocate GPU across cluster | Auto + attested |
| `failover_decision` | Determine failover action | **BFT Council vote** |
| `cost_report` | Infrastructure cost breakdown | Read-only |
| `compliance_check` | Check if issue is auto-remediable | **28-domain rules** |
| `council_propose` | Propose critical action to BFT Council | Governance layer |
| `council_vote` | Cast vote on pending proposal | Governance layer |
| `council_status` | Check proposal status | Governance layer |
| `verify_attestation` | Verify Ed25519 sigil on any action | Cryptographic proof |

## 🛡️ Compliance by Design

Every tool call goes through the **Sovereign Governance Layer**:

```
Issue Detected → Domain Classification → Compliance Check → [Auto | Council | Block] → Sigil Sign → Log
```

- **Finance domain:** `disk_full` → Auto-remediate. `data_loss` → BFT Council.
- **Healthcare domain:** `backup_verify` → Auto. `phi_exposure` → BFT Council + manual review.
- **Energy domain:** `load_balancer_shift` → Auto. `grid_disconnect` → BFT Council + safety isolation.

## 🏛️ Part of the Sovereign Temple

This MCP server is part of **[CSOAI Sovereign Temple](https://github.com/CSOAI-ORG/sovereign-temple)** — the open-source sovereign AI governance infrastructure.

| Component | Purpose |
|-----------|---------|
| [Sigil Bus](https://github.com/CSOAI-ORG/sovereign-temple) | Ed25519 attestation chain for every agent action |
| [BFT Council](https://github.com/CSOAI-ORG/sovereign-temple) | Byzantine Fault Tolerant consensus for governance |
| [28-Domain Engine](https://csoai.org) | 280 data sources, 28 industry domains, $0 cost |
| [Horus Intel](https://app.csoai.org/horus) | Weekly competitive intelligence for AI governance |
| [HIVE 1](https://proofof.ai) | Enterprise compliance attestation (51 MCP servers) |

## 📜 License

MIT © [CSOAI-ORG](https://github.com/CSOAI-ORG) · UK Companies House 16939677

---

<sub>Built with 💜 by CSOAI Labs · Sovereign AI Governance</sub>
