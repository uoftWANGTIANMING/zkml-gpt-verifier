# zkml-gpt-verifier

Zero-Knowledge verified GPT inference using Halo2, RISC-Zero, and ezkl.  
ETHOnline 2025 Hackathon project.

---

## Project Goal
Prototype system for zk-verified GPT inference.  
The aim is to enable trustless verification of AI model outputs on-chain.  
This project investigates the intersection of ZKML and AI infrastructure, focusing on:  
- Custom proof systems with Halo2  
- ML inference proofs with ezkl  
- Verifiable execution with RISC-Zero zkVM  

---

## Tech Stack
- Halo2 (zk-SNARK circuits)  
- ezkl (ML proof generation)  
- RISC-Zero (zkVM verification)  
- Rust + Python  

---

## Roadmap
- [x] Repository initialized (Day 0)  
- [ ] Run Halo2 test-circuit example  
- [ ] Install and run ezkl with toy MLP  
- [ ] Run RISC-Zero hello world proof  
- [ ] Integrate ezkl proof inside RISC-Zero  
- [ ] Minimal GPT inference demo  
- [ ] Submission to ETHOnline 2025  

---

## Progress Log
**Day 0 (Sept 13, 2025)**  
- Repository created: `zkml-gpt-verifier`  
- MIT License added  
- Initial README committed  

**Day 1 (Sept 14, 2025)**  
- Planned: run Halo2 test circuit  
- Planned: publish initial project log  

---

## Notes
Research notes and setup logs will be organized under `/notes`:  
- `notes/halo2_intro.md` — Halo2 circuit learning notes  
- `notes/ezkl_setup.md` — ezkl installation and test logs  
- `notes/design-notes.md` — Initial design sketch for GPT verifier  

---

## License
MIT
