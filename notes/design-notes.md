# Design Notes for zkml-gpt-verifier

## High-Level Idea
- Prove GPT inference correctness using zero-knowledge proofs.
- Enable trustless verification of model outputs on-chain.

## Components
1. **Halo2**: Custom circuit experiments  
2. **ezkl**: ML model proof generation  
3. **RISC-Zero**: zkVM wrapper to verify ezkl proofs  

## Initial Scope
- Start with a toy MLP model (classification task)
- Generate proof using ezkl
- Verify proof inside RISC-Zero VM

## Future Directions
- Scale to transformer blocks (attention layer)  
- Explore integration with Ethereum smart contracts  
- Optimize proof size and verification cost  
