##  beefy module(substrate polkadot-v0.9.33)

This is the concrete implementation of the centauri bridging protocol, based on IBC, Powered by light clients.

###     [beefy-light-client](algorithms/beefy/verifier/src/lib.rs)

This is a `no_std` compatible crate that contains functions for verifying BEEFY commitments and Parachain headers which have been finalized by the BEEFY protocol.

###     [beefy-prover](algorithms/beefy/prover/src/lib.rs)
This contains utility functions for assembling BEEFY proofs as well as parachain proofs from a running node, that can then be verified by the light-client crate.

###     [beefy-primitives](algorithms/beefy/primitives/src/lib.rs)

A `no_std` compatible crate which contains primitive types which are shared by both crates.