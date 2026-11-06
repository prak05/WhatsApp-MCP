<div align="center">

# ⚡ WhatsApp-MCP Protocol Bridge
### Model Context Protocol (MCP) Gateway & Automated Messaging Agent Runtime
**Engineered by [PRAKHAR SHARMA](https://github.com/prak05) • [Interactive Portfolio](https://prak05.github.io/prak05/)**

<br/>

<a href="https://prak05.github.io/prak05/" target="_blank">
  <img src="https://img.shields.io/badge/🌐_LIVE_PORTFOLIO-prak05.github.io%2Fprak05-FF002D?style=for-the-badge&logo=safari&logoColor=white&labelColor=171717" height="34" alt="Live Portfolio Website" />
</a>
<a href="https://github.com/prak05/WhatsApp-MCP">
  <img src="https://img.shields.io/badge/⚡_ARCHITECTURE-FAST__MCP-FF002D?style=for-the-badge&logo=github&logoColor=white&labelColor=171717" height="34" alt="Architecture" />
</a>
<a href="mailto:prakharsx05@gmail.com">
  <img src="https://img.shields.io/badge/✉_INITIALIZE_DISPATCH-prakharsx05%40gmail.com-171717?style=for-the-badge&logo=gmail&logoColor=FF002D&labelColor=171717" height="34" alt="Contact Email" />
</a>

<br/><br/>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=18&pause=1200&color=FF002D&center=true&vCenter=true&width=650&lines=FastMCP+2.0+Protocol+Bridge;Agentic+Tool+Execution+%26+Event+Streaming;Zero-Trace+Session+Sandboxing" alt="Typing SVG" />
</p>

[![License: MIT](https://img.shields.io/badge/License-MIT-FF002D.svg?style=flat-square)](LICENSE)
[![Protocol: FastMCP 2.0](https://img.shields.io/badge/Protocol-FastMCP_2.0-171717?style=flat-square&logo=anthropic&logoColor=FF002D)](#)
[![Mesh: Dual-Branch Safe](https://img.shields.io/badge/Mesh-Dual--Branch_Safety-171717?style=flat-square&logo=git&logoColor=FF002D)](#)
[![Architect: Prakhar Sharma](https://img.shields.io/badge/Architect-Prakhar_Sharma-171717?style=flat-square&logo=visualstudiocode&logoColor=white)](https://github.com/prak05)

</div>

---

### 💻 Active Node HUD & System Specification

```yaml
System Node    : WhatsApp-MCP Gateway
Domain         : Agentic Interoperability & Communication Protocols
Architecture   : FastMCP 2.0 Server + Headless Messaging Daemon
Security       : Zero-Trace Sandboxing & Local Session Key Ring
Throughput     : Sub-50ms Protocol Dispatch Latency
Preservation   : Dual-Branch Safety (Ex / main)
Lead Architect : Prakhar Sharma (RIET CSE '27 • Kerala, India)
```

---

## 🏛️ System Architecture Topology

```mermaid
flowchart LR
    A["Claude / Antigravity Agent"] -->|"JSON-RPC / stdio"| B["FastMCP Server Core"]
    B -->|"Tool Dispatch"| C["Session Controller"]
    C -->|"Headless Browser"| D["WhatsApp Web Client"]
    D -->|"E2EE WebSocket"| E["WhatsApp Mesh"]
    E -->|"Inbound Event"| C
    C -->|"State Push"| B
    B -->|"Formatted Response"| A

    style A fill:#171717,stroke:#FF002D,stroke-width:2px,color:#F5F2F0
    style B fill:#252323,stroke:#FF002D,stroke-width:2px,color:#F5F2F0
    style C fill:#252323,stroke:#74121F,stroke-width:1px,color:#F5F2F0
    style D fill:#1b1b1b,stroke:#393434,stroke-width:1px,color:#F5F2F0
    style E fill:#171717,stroke:#FF002D,stroke-width:2px,color:#F5F2F0
```

---

## ⚡ Core Capabilities & Bento Matrix

<table width="100%" border="0" cellspacing="0" cellpadding="8">
  <tr bgcolor="#252323">
    <th align="left" width="30%"><font color="#FF002D">CAPABILITY</font></th>
    <th align="left" width="50%"><font color="#F5F2F0">TECHNICAL ARCHITECTURE</font></th>
    <th align="center" width="20%"><font color="#FF002D">STATUS</font></th>
  </tr>
  <tr bgcolor="#1b1b1b">
    <td><b>FastMCP 2.0 Integration</b></td>
    <td>Native Model Context Protocol tool declarations enabling LLMs to query chats, send dispatches, and stream message payloads.</td>
    <td align="center"><code><font color="#FF002D">ACTIVE</font></code></td>
  </tr>
  <tr bgcolor="#202020">
    <td><b>Zero-Trace Security</b></td>
    <td>Session tokens and authentication states remain strictly confined within containerized volumes. Zero credential leakage.</td>
    <td align="center"><code><font color="#FF002D">HARDENED</font></code></td>
  </tr>
  <tr bgcolor="#1b1b1b">
    <td><b>Dockerized Execution</b></td>
    <td>Multi-stage container orchestration with embedded Chrome dependencies and automatic reconnection resilience.</td>
    <td align="center"><code><font color="#FF002D">CONTAINERIZED</font></code></td>
  </tr>
</table>

---

## 🚀 Quickstart & Daemon Execution

```bash
# Clone the repository
git clone https://github.com/prak05/WhatsApp-MCP.git
cd WhatsApp-MCP

# Launch via Docker Compose
docker-compose up -d

# Verify agent registration in MCP settings
cat <<EOF >> ~/.config/claude/claude_desktop_config.json
{
  "mcpServers": {
    "whatsapp": {
      "command": "docker",
      "args": ["exec", "-i", "whatsapp-mcp-bridge", "node", "index.js"]
    }
  }
}
EOF
```

---

<div align="center">

<sub>Architected with extreme precision by <b>Prakhar Sharma</b> • Supported by <b>Google DeepMind Antigravity</b> • Dual-Branch Mesh (Ex / main)</sub>

</div>
