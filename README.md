x402BTC Lightning Network Daemon




<img width="1024" height="1024" alt="image" src="https://github.com/user-attachments/assets/761baf6d-f65e-4a7f-ac8a-d77a244198b0" />







The x402BTC Lightning Network Daemon (x402lnd) is a complete implementation of a
Lightning Network
 node built for the x402BTC ecosystem.

x402lnd provides pluggable back-end chain services, including:
btcd
 (full-node),
bitcoind
, and
neutrino
 (light client).

Built upon btcsuite
, the project offers modular, reusable Lightning Network libraries for developers building on x402BTC.

In its current version, x402lnd supports:

Creating and closing payment channels

Managing all channel states (including exceptions)

Maintaining an authenticated + validated channel graph

Network pathfinding and payment forwarding

Sending onion-encrypted payments

Updating advertised routing fees

Automatic channel management (autopilot
)

Lightning Network Specification Compliance

x402lnd fully complies with the Lightning Network specification (BOLTs)
.
BOLT stands for Basis of Lightning Technology — a globally maintained set of standards that x402lnd follows.

Current BOLT compliance:

 BOLT 1: Base Protocol

 BOLT 2: Peer Protocol for Channel Management

 BOLT 3: Bitcoin Transaction and Script Formats

 BOLT 4: Onion Routing Protocol

 BOLT 5: Recommendations for On-chain Transaction Handling

 BOLT 7: P2P Node and Channel Discovery

 BOLT 8: Encrypted and Authenticated Transport

 BOLT 9: Assigned Feature Flags

 BOLT 10: DNS Bootstrap and Assisted Node Location

 BOLT 11: Invoice Protocol for Lightning Payments

Developer Resources

x402lnd is developer-friendly and includes two primary RPC interfaces:

HTTP REST API

gRPC Service (Learn about gRPC
)

⚠️ These APIs are still evolving and may change in upcoming releases.

API Documentation:
📘 api.x402btc.network

Developer Guides, Tutorials, and Resources:
📚 docs.x402btc.network

📖 x402BTC Developer Guide

🧠 Step-by-Step Lightning Setup Guide

⚙️ Docker & Payment Flow Guide

Join our developer community on:
💬 Slack
 or
💻 IRC at irc.libera.chat

First-time contributors should start with the
🧩 Code Review Guidelines
.

Installation

To build from source, follow the Installation Instructions
.

Docker

To run x402lnd with Docker, see the Docker Setup Guide
.

IRC

Server: irc.libera.chat

Channel: #x402lnd

Webchat: Join Here

Safety

When operating a mainnet node, always review the
Operational Safety Guidelines
.

⚠️ Warning: x402lnd is beta software. Ignoring safety procedures can result in loss of funds.

Security

The developers of x402lnd take security and privacy very seriously.
If you identify a potential issue, please disclose it responsibly via email to
📧 security@x402btc.network
, preferably encrypted using our PGP key
(91FE464CD75101DA6B6BAB60555C6465E5BCB3AF), available here
.

Further Reading

Step-by-Step Send Payment Guide (Docker)

Contribution Guide

Lightning Developer Resources

x402BTC Ecosystem Overview
