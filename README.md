# Hi, I'm Roman 👋

I'm a software engineer interested in **GPU computing, numerical software, HPC, and performance-oriented systems**.

I currently work professionally as a full-stack engineer, while my personal work focuses increasingly on **Rust, GPU execution, numerical computing, and heterogeneous systems**.

Before moving into software engineering, I worked in mechanical / structural engineering and used **ANSYS and Abaqus** for finite-element analysis. That background is still a major influence on the kinds of software problems I enjoy exploring: numerical methods, solvers, parallel computation, and the systems underneath them.

## Selected projects

### [GPU Systems Lab](https://github.com/RomanShushakov/gpu_systems_lab)

A hands-on exploration of GPU-oriented systems programming in Rust, progressing from low-level interoperability to a small heterogeneous compute framework.

The project covers:

- Rust ↔ C / C++ FFI
- Vulkan compute with `ash`
- explicit GPU resource ownership and synchronization
- GPU memory pooling and suballocation
- device-local memory and staging transfers
- compute graphs and dependency scheduling
- multi-workgroup reductions and numerical GPU kernels
- CPU / GPU execution backends
- JSON-driven mini compute framework
- ARM64 cross-compilation
- Vulkan workloads on **NVIDIA Jetson Orin Nano via Slurm**

The lab intentionally builds these layers explicitly rather than hiding them behind a high-level GPU framework.

---

### [FEA App](https://github.com/RomanShushakov/fea_app)

A browser-based finite-element–style application built from scratch using **Rust, WebAssembly, WebGL, and WebGPU**.

It explores the pipeline from engineering data structures to numerical execution and visualization:

- FEM-style assembly
- sparse linear algebra
- CG / PCG iterative solvers
- Block-Jacobi preconditioning
- GPU compute kernels and reductions
- WebGPU computation
- WebGL visualization
- Rust compiled to WebAssembly

Related experiments include [`wgpu_solver_backend`](https://github.com/RomanShushakov/wgpu_solver_backend) and [`wgpu_solver_slurm`](https://github.com/RomanShushakov/wgpu_solver_slurm), extending the solver path from browser GPU execution toward native and scheduled workloads.

---

### [AI Platform](https://github.com/RomanShushakov/ai_platform)

An experimental infrastructure lab for understanding how AI workloads fit into heterogeneous compute environments.

It combines experiments around:

- Rust-based tooling
- Slurm scheduling
- K3s
- RAG pipelines
- llama.cpp inference
- LoRA fine-tuning
- shared storage and GPU workloads
- Raspberry Pi + NVIDIA Jetson hardware

The focus is on understanding the infrastructure layers rather than building a production AI platform.

---

## What I'm interested in

My main technical interests are:

- **GPU computing** — Vulkan, WebGPU, compute shaders
- **Numerical computing** — sparse linear algebra, iterative solvers, FEM
- **HPC and heterogeneous execution** — scheduling, GPU workloads, distributed compute infrastructure
- **Rust and systems programming**
- **WebAssembly and browser-native compute**
- building abstractions without losing sight of what happens underneath them

I particularly enjoy projects that connect multiple layers:

**algorithms → memory → GPU execution → runtime → infrastructure**

## Tech

**Languages:** Rust · TypeScript · JavaScript · Python

**GPU / Compute:** Vulkan · `ash` · WebGPU · WGSL · WebGL · `wgpu`

**Systems / HPC:** Slurm · Linux · Ansible · NFS · Apptainer · ARM64 · NVIDIA Jetson

**Web / Backend:** Angular · Vue · NestJS · Node.js · Redis · Kafka · Kubernetes

**Numerical:** sparse matrices · CG / PCG · Jacobi / Block-Jacobi · FEM concepts

---

I'm currently especially interested in opportunities around **Rust, GPU computing, numerical software, HPC, and performance-oriented engineering**.
