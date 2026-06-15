# Lizard-CP-ABE Overview

**Defensive Publication — June 2026**

**The Problem**  
Classical CP-ABE (Ciphertext-Policy Attribute-Based Encryption) relies on bilinear pairings over elliptic curves. These are vulnerable to quantum computers via Shor’s algorithm, creating harvest-now-decrypt-later risks for long-lived sensitive data.

**The Solution — Lizard**  
Lizard-CP-ABE is a post-quantum, hardware-native CP-ABE system based on Ring-LWE. It delivers the same expressive policy-based access control while being efficient on constrained cryptographic hardware (FPGA/ASIC/secure elements).

Core innovations:
- Fractal self-similarity + cellular automata + percolation for ultra-efficient policy evaluation
- Full Ring-LWE security reduction
- Integrated features: mediator-aided revocation, puncturable forward security, certified deletion

**Purpose**  
Public defensive publication of the Lizard-CP-ABE concept to establish prior art for post-quantum fine-grained access control.

**License**: CC0 1.0  
**Contact**: Shoel Lowy — lowy_s@blockchaindnafoundation.org