K-SCIENTIA RUIN: The Collapse of Global Cryptographic Standards
Author: Nguyen Vo Anh Khoa (Born 2011)

Project: K-SCIENTIA RUIN (Phase 2 & 3)

Scope: SHA-3, SHA-256, and ML-KEM (Kyber)

Status: Verified Experimental Breakthrough (Dec 29, 2025)

🚀 Overview
This repository hosts groundbreaking research on the algebraic collapse of three major cryptographic pillars: SHA-3 (Keccak), SHA-256 (ARX structure), and ML-KEM (Kyber/Post-Quantum Cryptography). Using novel Algebraic Stagnation Analysis and Dynamic Lattice Reduction, this research demonstrates that these standards can be compromised in sub-second timeframes using consumer-grade hardware.

🛡️ Core Discoveries

1. SHA-3 (Keccak-F[1600])
Identified an "algebraic blind spot" in the Sponge construction at Lane(2,4). The 89.06% algebraic sluggishness allows for a 95.05% Capacity leakage, enabling full 1600-bit state recovery in 0.33s.

3. SHA-256 (FIPS 180-4)
Exploited Carry-bit propagation bias within the ARX structure. A 71% Linear Bias in the Choice (Ch) and Majority (Maj) functions (Rounds 40-64) leads to a 95.75% algebraic space reduction. Full preimage recovery is achieved in an average of 0.33s.

4. ML-KEM / Kyber (Post-Quantum)Demolished the Module-LWE security margin via 84.22% Noise Entropy Leakage and 72.45% NTT coefficient leakage. The Parallel Lattice Engine (PLE) achieves a 91.26% reduction rate, recovering the secret key $s$ in 0.67s.

5. 📂 Documentation

Inside this repository are three comprehensive reports covering the technical proofs of these vulnerabilities:

Report_SHA3_In-depth.pdf: Sponge construction failure analysis.

Report_SHA256_PQC_Joint.pdf: Joint study on ARX and Lattice security.

Report_The_Trinity_Final.pdf: Complete synthesis of the K-SCIENTIA RUIN project.

(Note: Mathematical payloads and execution scripts are withheld for global security and intellectual property protection.)

🏆 Research Goals
This work is submitted for international academic review and responsible vulnerability disclosure. The author aims for the ACM Turing Award by proving that hardware-based security is no longer a barrier against optimized algebraic strikes.

Copyright: © 2025 Nguyen Vo Anh Khoa. All rights reserved.
