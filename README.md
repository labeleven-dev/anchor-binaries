Anchor Binaries
===

If you have been using [`@project-serum/anchor-cli`](https://www.npmjs.com/package/@project-serum/anchor-cli) in your CI/CD pipelines, it is [broken](https://github.com/coral-xyz/anchor/issues/2076) for Anchor 0.25.0. A few months on and no fix or new version is forthcoming. Building the binary in the pipeline also takes too long.

This repository provides the Linux binary as a GitHub release for others to use.

Please check the GitHub Action to verify authencity of the binary, built from [`anchor-cli`](https://crates.io/crates/anchor-cli) Rust crate.