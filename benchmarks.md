# 📊 Benchmarks & Telemetry
> **Raw Throughput, Hardware Scaling, and Production Data**

---

[← Back to Main Overview](index.md)

The following empirical telemetry was logged across distinct GPU architectures. All benchmarks demonstrate the maximum capacities of the U.M.E.R. engine under extreme stress-testing configurations.

### 🚀 Macroscopic Throughput (Physics Integration)
* **NVIDIA Pascal (Tesla P100):** Achieved a raw 1D physics integration throughput of 21,933 MCell/s.
* **AMD CDNA3 (MI300X):** Achieved a sustained macroscopic throughput of 18,102 MCell/s.
* **3D Temporal Coherence Speedup:** Sustained a topology throughput of 5,815.3 MCell/s in realistic 3D environments, surpassing the industry-standard NVIDIA Warp framework by a speedup of 1.52x.

### 🧠 Agentic Navigation & AI Limits
* **Maximum Frame Rate:** Sustained a strict 125 FPS executing a massive-scale (500,000 agents) wide-radius flocking algorithm.
* **Node Discovery Ceiling:** * NVIDIA Pascal (P100): Executed 6-way spatial neighbor queries at 127.99 GNode/s.
  * NVIDIA Turing (T4): Executed 6-way spatial neighbor queries at 76.35 GNode/s.

### 🔋 Power & Hardware Utilization
* **Energy Efficiency:** Operated at 53.9 MCell/W drawing 108.0 W during coherent physical regimes, compared to the standard baseline of 35.0 MCell/W drawing 109.5 W.
* **Warp Execution Efficiency:** Achieved a sustained 95.8% Warp Execution Efficiency, proving near-perfect parallel lockstep evaluation without critical branch divergence.
* **Effective Cache Bandwidth Limits:**
  * NVIDIA Pascal (P100): Scaled up to 2,068.87 GB/s effective bandwidth.
  * NVIDIA Turing (T4): Scaled up to 1,578.25 GB/s effective bandwidth.

---
*Powered by the U.M.E.R. Engine*
