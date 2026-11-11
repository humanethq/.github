![Humanet](https://github.com/humanethq/.github/blob/main/profile/profile.png)

---

## Infrastructure & Runtimes for Isolated AI Execution

Humanet builds high-density isolation primitives, deterministic dataflow engines, and security tooling for running autonomous AI workloads in production and air-gapped environments.

### Core Products & Open-Source Tooling

* ⚡ **[Frame by Humanet](https://humanet.dev)** — High-density Firecracker microVM runtime for AI applications featuring automatic build-time cache sealing and wire-level Phantom Secret injection.
* 🛡️ **[`airgap-check`](https://github.com/humanethq/airgap-check)** — Zero-dependency static and dynamic (`--network none` + `UDP:53` DNS sinkhole) offline readiness, telemetry, and secret auditor for AI repositories.
* 🔒 **[`sandbox-check`](https://github.com/humanethq/sandbox-check)**: Zero-dependency in-guest auditor that tests what a sandboxed workload can still reach: cloud metadata (IMDS), proxy bypass, host gateway ports, capabilities and cgroup limits. Fail-closed exit codes for CI.

### Research & Experimental Kernels

* 🧬 **[CHSE Core Engine](https://github.com/humanethq/chse)** — Experimental hyperdimensional indexing kernel utilizing Vector Symbolic Architectures (`V ∈ {-1, +1}^10000`) and lock-free memory mapping for streaming telemetry.
* 📐 **[PIE Runtime](https://github.com/humanethq/pie)** — Compile-time causal dependency graph and write-path materialization engine designed for `O(1)` read-path state lookups.

---

<p align="center">
  <b><a href="https://humanet.dev">humanet.dev</a></b> • <b>Humanet</b>
</p>
