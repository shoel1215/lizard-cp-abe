# Lizard-CP-ABE — Post-Quantum Hardware-Native Ciphertext-Policy Attribute-Based Encryption

**Defensive Publication — June 2026**

**The Problem**  
Current CP-ABE systems rely on bilinear pairings over elliptic curves. These are vulnerable to Shor’s algorithm on a cryptographically relevant quantum computer, creating harvest-now-decrypt-later risks for long-lived sensitive data such as genomic records.

**The Solution — Lizard**  
Lizard-CP-ABE is a Ring-LWE-based post-quantum replacement that delivers the same expressive policy-based access control while being hardware-native and efficient on constrained cryptographic hardware (FPGA/ASIC/secure elements).

**Key Differentiator**  
Fractal self-similarity + cellular automata + percolation for ultra-efficient policy evaluation directly in silicon.

Additional capabilities include mediator-aided revocation, puncturable forward security, and certified deletion.

**Purpose**  
Public defensive publication to establish prior art for a practical post-quantum CP-ABE construction.

See `Lizard_CP_ABE_Defensive_Publication.md` for full details.

**License**: CC0 1.0  
**Contact**: Shoel Lowy — lowy_s@blockchaindnafoundation.org

---
*Maintained for defensive publication and open cryptographic research only.*