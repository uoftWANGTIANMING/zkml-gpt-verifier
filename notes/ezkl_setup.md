# ezkl Setup Notes

## Installation
- Installed dependencies: Python 3.10+, Rust stable
- Cloned `ezkl` repository
- Built with `cargo build --release`

## First Run
- Tested example MLP circuit
- Verified proof generation
- Verified on-chain verifier contract (optional step)

## Observations
- CLI interface is straightforward
- Witness generation requires ONNX model
- Proof times increase with model size

## Next Steps
- Try LeNet example
- Export a small GPT-2 layer to ONNX and test with ezkl
- Benchmark proving time and memory
