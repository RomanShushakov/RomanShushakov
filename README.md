# Hi, I’m Roman 👋

I’m a software engineer focused on **GPU computing, numerical methods, and low-level performance-oriented systems**, with a strong interest in bringing **scientific and HPC-style workloads to modern web platforms**.

My work sits at the intersection of:
- **WebGPU / GPU compute**
- **WebAssembly (Rust → WASM)**
- **Numerical linear algebra & iterative solvers**
- **System-level performance and memory control**

---

## Featured Project

### 🔹 WebGPU-based Preconditioned Conjugate Gradient Solver  
**Repository:** [`fea_app`](https://github.com/RomanShushakov/fea_app)

A fully GPU-driven implementation of a **Preconditioned Conjugate Gradient (PCG)** solver with a **Block-Jacobi preconditioner**, designed and implemented from scratch using **WebGPU compute shaders**.

**Key aspects:**
- Sparse matrix–vector multiplication (CSR) on GPU
- Block-Jacobi preconditioning with LU factorization (block size = 6)
- GPU-side reductions (dot products → scalar results)
- Single-submit PCG iteration design to minimize CPU↔GPU synchronization
- Rust + `web-sys` bindings, no high-level abstractions hiding GPU behavior

This project demonstrates how **classic HPC algorithms** can be mapped efficiently to **modern GPU compute APIs in the browser**.

---

## Technical Focus

- **Languages:** Rust, WGSL, JavaScript / TypeScript
- **GPU / Compute:** WebGPU, compute pipelines, memory layouts, reductions
- **Numerical Methods:** Iterative solvers, preconditioning, sparse linear algebra
- **Systems Thinking:** Explicit buffer ownership, synchronization control, data locality

I value **clarity, correctness, and performance**, and prefer understanding systems end-to-end rather than relying on opaque frameworks.

---

## Background & Direction

My current focus is on:
- Bridging **scientific computing concepts** with **modern GPU APIs**
- Exploring how **WebGPU** can be used for non-graphics workloads
- Building reusable, well-structured GPU compute components

This profile reflects **hands-on engineering work**, not demos or abstractions.

---

## Links

- 💼 LinkedIn: https://linkedin.com/in/roman-shushakov-02194b1a1/

---

*I enjoy building things that make complex systems understandable and efficient.*

