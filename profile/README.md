# Veil Systems

**Proof-gated private invoice settlement on Stellar**

InvoiceVeil lets a business register public invoice bounds, keep the exact amount private, and settle only when a Groth16 proof confirms the hidden amount falls inside the agreed range.

Proof-gated settlement. `settle_invoice` cannot succeed unless the Groth16 verifier passes

Private amounts. the exact value and its salt stay off-chain; only bounds, commitment, and status are public

Native BN254 verification. proofs are checked by a Soroban contract using Stellar's host functions

Code: https://github.com/invoiceveil-lab/invoiceveil

*`Soroban` · `Rust` · `Circom` · `Groth16` · `BN254` · `React`*
