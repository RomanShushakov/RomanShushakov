# Hello, I'm Roman 👋

I'm a software engineer currently working as a **full-stack developer**, with a strong personal interest in **numerical methods, GPU computing, and performance-oriented systems**.

My background is a bit unconventional:

- I studied **linear algebra, numerical methods, and mechanics** at university.
- I previously worked as a **mechanical / structural (FEA) engineer**, using tools like **ANSYS** and **Abaqus** for stress analysis.
- Over time, I became increasingly interested in how these systems work internally — both mathematically and computationally.
- That curiosity eventually led me into **software engineering**, where I took the most accessible entry path at the time: **web development**.

---

## What I work on now

Professionally, I work as a **full-stack engineer**, building web applications and systems end-to-end.

Alongside that, I maintain a set of personal projects that reconnect my engineering background with software development and computation:

- **Numerical linear algebra and iterative solvers**
- **GPU computing** for both *graphics* and *general computation*
- **Web-based compute** via **WebGL / WebGPU**
- **Rust** for performance-oriented and systems-level code
- Architectural patterns for **scientific and engineering software**

A central project in this space is:
- [`fea_app`](https://github.com/RomanShushakov/fea_app) — a browser-based finite-element–style application built from scratch.

It’s not intended to be a production FEA solver, but rather a way to understand the full pipeline:

- FEM-style data structures and assembly
- sparse linear algebra and solver workflows
- GPU compute kernels and reductions
- interaction between compute and visualization in modern browsers

As this work evolved, parts of the GPU solver path were extracted into a native backend:

- [`wgpu-solver-backend`](https://github.com/RomanShushakov/wgpu-solver-backend) — a **`wgpu`-based backend** for sparse iterative solvers (PCG with Block-Jacobi preconditioning), ported from the WebGPU implementation used in `fea_app`.

Supporting crates explore individual layers of the stack:

- `finite_element_method` — FEM building blocks and assembly helpers  
- `iterative_solvers` — CPU implementations of CG / PCG  
- `colsol` — direct-solver experiments (LDLᵀ / column-oriented elimination)

---

## Interests going forward

While I currently work in web development, my long-term interests are gradually shifting back toward:

- **numerical computing and solver development**
- **GPU-accelerated computation**
- **scientific and engineering software**
- and, step by step, **HPC-style workloads** — both native and browser-based

I enjoy learning by building things end-to-end, from mathematical formulations and data structures down to execution models, memory movement, and performance characteristics.

---

## Tech I enjoy working with

- **Languages**: Rust, TypeScript, JavaScript  
- **Compute & Graphics**: WebGPU, WebGL, wgpu  
- **Domains**: numerical methods, linear algebra, FEM concepts  
- **General**: performance-aware programming, system design, tooling  

---

Thanks for stopping by 🙂

