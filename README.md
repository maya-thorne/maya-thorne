<div align="center">

<p>
  <img src="./hero.svg" alt="Maya Thorne — Speed · Scale · Security — Linux Kernel &amp; Low-Level Concurrency" width="76%" />
  <img src="./avatar.svg" alt="Maya Thorne Monogram" width="21%" />
</p>

<p>
  <strong>Architecting Resilient Low-Level Systems, Kernel Modules &amp; High-Throughput Concurrency Primitives.</strong><br />
  <sub>Speed · Scale · Security — Engineering with clarity and conviction.</sub>
</p>

<p>
  <strong>🇺🇸 English</strong> · <strong>🇰🇷 한국어</strong> · <strong>🇯🇵 日本語</strong> · <strong>🇨🇳 中文</strong> · <strong>🇪🇸 Español</strong> · <strong>🇩🇪 Deutsch</strong><br />
  <strong>🇸🇦 العربية</strong> · <strong>🇧🇷 Português</strong> · <strong>🇷🇺 Русский</strong> · <strong>🇫🇷 Français</strong> · <strong>🇮🇩 Bahasa Indonesia</strong>
</p>

<p>
  <a href="https://github.com/maya-thorne"><img src="https://img.shields.io/badge/Status-Kernel%20Ready%20%F0%9F%90%A7-1f2328?style=flat-square&logo=linux&logoColor=39d353" alt="Status" /></a>
  <a href="https://github.com/maya-thorne?tab=repositories"><img src="https://img.shields.io/badge/Focus-Systems%20%26%20Rust-1f2328?style=flat-square&logo=rust&logoColor=f74c00" alt="Focus" /></a>
  <a href="https://github.com/maya-thorne"><img src="https://img.shields.io/badge/Architecture-x86__64%20%2F%20ARM64-1f2328?style=flat-square&logo=cpu&logoColor=58a6ff" alt="Architecture" /></a>
  <a href="https://github.com/maya-thorne"><img src="https://img.shields.io/badge/Security-Memory%20Safe-1f2328?style=flat-square&logo=shield&logoColor=bc8cff" alt="Security" /></a>
</p>

</div>

---

<details open>
<summary><h2 style="display:inline-block; margin:0;">💡 Engineering Ethos &amp; Philosophy</h2></summary>
<br />

I engineer resilient low-level software, high-performance concurrency primitives, and deterministic kernel telemetry systems. My design philosophy is anchored on three core pillars:

- **⚡ Zero-Cost &amp; Mechanical Sympathy** — Write code that respects cache hierarchies, memory alignment, and branch predictors. Strive for zero-overhead abstractions that translate directly into clean machine instructions.
- **🐧 Kernel-First Thinking** — Treat the operating system kernel not as an opaque black box, but as the foundational runtime. Master virtual memory, non-blocking I/O (io_uring), lockless ring buffers, and eBPF tracing.
- **🔒 Invariant-Driven Correctness** — Enforce safety at compile-time wherever possible. Strict state machine transitions, robust fuzzing suites, and defensive error handling that never panic in mission-critical paths.

<p align="center">
  <sub><em>"In the terminal we trust. Make it deterministic. Automate the friction away."</em></sub>
</p>

</details>

---

<details open>
<summary><h2 style="display:inline-block; margin:0;">⚡ Technology Stack &amp; Technical Tooling</h2></summary>
<br />

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>⚙️ Low-Level &amp; Systems</h4>
      <ul>
        <li><strong>Languages</strong>: <code>C23</code>, <code>Rust (Async/Unsafe/No_std)</code>, <code>Zig</code>, <code>x86_64 / ARM Assembly</code></li>
        <li><strong>Kernel Runtimes</strong>: Linux Kernel Modules, POSIX APIs, eBPF / XDP, <code>io_uring</code></li>
        <li><strong>Memory &amp; Concurrency</strong>: Lock-free atomics, SIMD vectorization, NUMA-aware allocators</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h4>🌐 Distributed &amp; Infrastructure</h4>
      <ul>
        <li><strong>Networking</strong>: Kernel-bypass networking (DPDK), high-concurrency epoll/kqueue, WebSockets</li>
        <li><strong>Observability</strong>: <code>bpftrace</code>, <code>perf</code>, <code>Valgrind</code>, Prometheus telemetry</li>
        <li><strong>Environment</strong>: Arch Linux, Debian, Docker, LLVM/Clang toolchains, Neovim / Tmux</li>
      </ul>
    </td>
  </tr>
</table>

<br />

<p align="center">
  <img src="https://skillicons.dev/icons?i=c,rust,linux,bash,git,docker,neovim,python&theme=dark" alt="Technical Stack Icons" />
</p>

</details>

---

<details open>
<summary><h2 style="display:inline-block; margin:0;">📊 Dynamic Telemetry &amp; GitHub Metrics</h2></summary>
<br />

<div align="center">
  <p>
    <a href="https://github.com/maya-thorne">
      <img src="https://github-readme-stats.vercel.app/api?username=maya-thorne&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9&icon_color=39d353" alt="Maya Thorne's GitHub Stats" />
    </a>
    <a href="https://github.com/maya-thorne">
      <img src="https://streak-stats.demolab.com?user=maya-thorne&theme=tokyonight&hide_border=true&background=0d1117&ring=39d353&fire=f74c00&currStreakLabel=58a6ff" alt="GitHub Streak Stats" />
    </a>
  </p>
</div>

</details>

---

<details>
<summary><h2 style="display:inline-block; margin:0;">🚀 Architectural Focus &amp; Ongoing Research</h2></summary>
<br />

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>📡 High-Throughput Kernel-Bypass I/O</h4>
      <p><em>Exploring zero-copy asynchronous messaging and deterministic kernel queues.</em></p>
      <ul>
        <li>Benchmarking ring-buffer throughput under saturated 10GbE network loads</li>
        <li>Eliminating context-switch overhead via custom eBPF packet filters and XDP</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h4>🛡️ Formal Verification &amp; Fuzzing</h4>
      <p><em>Continuous fuzz testing and symbolic execution for memory safety.</em></p>
      <ul>
        <li>Automated mutation testing pipelines integrated with LLVM libFuzzer and AFL++</li>
        <li>Zero-leak invariant guarantees across complex multi-threaded state machines</li>
      </ul>
    </td>
  </tr>
</table>

</details>

---

## 📬 Connect &amp; Transmission

Interested in low-level systems architectures, compiler internals, or kernel engineering discussions?

[GitHub Profile](https://github.com/maya-thorne) · [Public Repositories](https://github.com/maya-thorne?tab=repositories) · [Discussions](https://github.com/maya-thorne?tab=discussions) · [Send an Email](mailto:zse4123jo@gmail.com)

<div align="center">
  <br />
  <sub>© 2026 Maya Thorne · Built with mechanical sympathy · 🐧</sub>
</div>
