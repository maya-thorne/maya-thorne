<div align="center">

<p>
  <a href="https://github.com/maya-thorne"><img src="../assets/hero_ru.svg" alt="Maya Thorne — Speed · Scale · Security — Linux Kernel &amp; Low-Level Concurrency" width="76%" /></a>
  <a href="https://github.com/maya-thorne"><img src="../avatar.svg" alt="Maya Thorne Monogram" width="21%" /></a>
</p>

<p>
  <strong>Architecting Resilient Low-Level Systems, Kernel Modules &amp; High-Throughput Concurrency Primitives.</strong><br />
  <sub>Speed · Scale · Security — Engineering with clarity and conviction. 🚀 ( •̀ᴗ•́ )و</sub>
</p>

<p>
  <a href="../README.md">🇺🇸 English</a> · <a href="./ko.md">🇰🇷 한국어</a> · <a href="./zh-CN.md">🇨🇳 中文</a> · <a href="./es.md">🇪🇸 Español</a> · <a href="./hi.md">🇮🇳 हिन्दी</a><br />
  <a href="./ar.md">🇸🇦 العربية</a> · <a href="./pt-BR.md">🇧🇷 Português</a> · <strong>🇷🇺 Русский</strong> · <a href="./fr.md">🇫🇷 Français</a> · <a href="./id.md">🇮🇩 Bahasa Indonesia</a>
</p>

<p>
  <a href="https://github.com/maya-thorne"><img src="../assets/badges/badge-status.svg" alt="Status" /></a>
  <a href="https://github.com/maya-thorne?tab=repositories"><img src="../assets/badges/badge-focus.svg" alt="Focus" /></a>
  <a href="https://github.com/maya-thorne/github-org-map"><img src="../assets/badges/badge-architecture.svg" alt="Architecture" /></a>
  <a href="https://github.com/maya-thorne/github-org-map-private"><img src="../assets/badges/badge-systems.svg" alt="Systems" /></a>
</p>

</div>

---

<details>
<summary><h2 style="display:inline-block; margin:0;">⚡ About &amp; Engineering Ethos</h2></summary>

<br />

Architecting resilient low-level software systems, Linux kernel modules, and high-throughput concurrency primitives. Engineering centered around mechanical sympathy and zero-overhead performance:

- ⚡ **Zero-Cost &amp; Mechanical Sympathy** — Code engineered to respect CPU cache hierarchies, memory alignment, and branch predictors. Zero-overhead abstractions by default.
- 🐧 **Kernel-First Architecture** — Treating the operating system kernel not as an opaque abstraction, but as the foundational runtime. Deep instrumentation with io_uring, eBPF, and lockless queues.
- 🛡️ **Invariant-Driven Correctness** — Compile-time safety guarantees, deterministic finite-state machine transitions, lock-free ring buffers, and continuous fuzzing validation.

<p align="center">
  <sub><em>(⌐■_■) 💻 "In the terminal we trust. Make it deterministic. Automate the friction away."</em></sub>
</p>

</details>

---

<details>
<summary><h2 style="display:inline-block; margin:0;">🚀 Core Systems &amp; Infrastructure Architecture</h2></summary>

<br />

Высокопроизводительные распределенные среды выполнения, сетевые примитивы обхода ядра и криптографически верифицированные топологические движки.

### 🛠️ Производственные системы и топологические движки

<table>
  <tr>
    <td width="50%" valign="top">
      <p align="center">
        <a href="https://github.com/maya-thorne/github-org-map">
          <img src="../assets/projects/github-org-map-banner.svg" alt="github-org-map banner" width="100%" />
        </a>
      </p>
      <h4><a href="https://github.com/maya-thorne/github-org-map">🗺️ github-org-map</a></h4>
      <p><em>Движок автоматизированного ежедневного топологического картирования репозиториев ядра Linux и параллелизма с хешированием конфиденциальности SHA-256.</em></p>
      <p>
        <a href="https://github.com/maya-thorne/github-org-map"><img src="../assets/badges/badge-license.svg" alt="Runtime: Linux &amp; POSIX" /></a>
        <a href="https://github.com/maya-thorne/github-org-map"><img src="../assets/badges/badge-actions.svg" alt="Engine: eBPF &amp; GitOps" /></a>
        <a href="https://github.com/maya-thorne/github-org-map"><img src="../assets/badges/badge-privacy.svg" alt="Privacy: Salted SHA-256 Mask" /></a>
      </p>
      <ul>
        <li>🔄 <strong>Непрерывное картирование</strong>: Ежедневный рабочий процесс GitHub Actions, картирующий репозитории ядра</li>
        <li>🛡️ <strong>Одностороннее хеш-маскирование</strong>: Одностороннее хеширование SHA-256 с солью для скрытия закрытых модулей ядра</li>
        <li>📊 <strong>Нативная векторная телеметрия</strong>: Движок на чистом 2D SVG без сторонних зависимостей с анимацией</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <p align="center">
        <a href="https://github.com/maya-thorne/github-org-map">
          <img src="../assets/projects/github-org-map.svg" alt="github-org-map telemetry" width="100%" />
        </a>
      </p>
      <h4><a href="https://github.com/maya-thorne/github-org-map-private">🔒 github-org-map-private</a></h4>
      <p><em>Изолированный сопутствующий телеметрический конвейер для низкоуровневых модулей ядра, анализа защиты от эксплойтов и закрытых исследований.</em></p>
      <p>
        <a href="https://github.com/maya-thorne/github-org-map-private"><img src="../assets/badges/badge-private.svg" alt="Security: Windows DPAPI Vault" /></a>
        <a href="https://github.com/maya-thorne/github-org-map-private"><img src="../assets/badges/badge-telemetry.svg" alt="Audit: Invariant Assertions" /></a>
        <a href="https://github.com/maya-thorne/github-org-map-private"><img src="../assets/badges/badge-format.svg" alt="Pipeline: Air-Gapped Dual-Track" /></a>
      </p>
      <ul>
        <li>🔐 <strong>Аппаратно-изолированное хранилище</strong>: Инкапсуляция секретов с шифрованием Windows DPAPI с аппаратной привязкой</li>
        <li>⚡ <strong>Детерминированные утверждения</strong>: Автоматические тесты, подтверждающие стойкость к поиску прообраза</li>
        <li>📜 <strong>Двойной аудит истины</strong>: Непрерывная сверка открытых маскированных артефактов с внутренним графом</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <p align="center">
        <a href="https://github.com/maya-thorne/bat2exe-ghidra-forensics">
          <img src="https://raw.githubusercontent.com/maya-thorne/bat2exe-ghidra-forensics/main/docs/assets/locales/en/banner.svg" alt="bat2exe-ghidra-forensics banner" width="100%" />
        </a>
      </p>
      <h4><a href="https://github.com/maya-thorne/bat2exe-ghidra-forensics">🔬 bat2exe-ghidra-forensics</a></h4>
      <p><em>Реверс-инжиниринг PE-бинарей с Ghidra MCP (упаковщики UPX/CLR/VB6), построчный анализ исходников 8 обфускаторов и многопроходный AST-движок деобфускации.</em></p>
      <p>
        <a href="https://github.com/maya-thorne/bat2exe-ghidra-forensics"><img src="https://img.shields.io/badge/Ghidra_MCP-Binary_RE-f43f5e.svg" alt="Ghidra MCP" /></a>
        <a href="https://github.com/maya-thorne/bat2exe-ghidra-forensics"><img src="https://img.shields.io/badge/Source_Teardown-8_Core_Tools-f59e0b.svg" alt="8 Tools" /></a>
        <a href="https://github.com/maya-thorne/bat2exe-ghidra-forensics"><img src="https://img.shields.io/badge/Engine-Python_AST-38bdf8.svg" alt="Deobfuscator Engine" /></a>
      </p>
      <ul>
        <li>🔬 <strong>Дизассемблирование Ghidra MCP PE</strong>: Глубокий анализ <code>bat2exe_12.exe</code>, <code>example.exe</code> и <code>BEDeCode.exe</code></li>
        <li>🛠️ <strong>Разбор 8 ключевых инструментов</strong>: Построчный анализ BatCloak, Somalifuscator, 0xidiz3r, хуков Exorcism и компиляторов Bat2Exe</li>
        <li>⚡ <strong>Многопроходный AST-движок</strong>: 6-проходный статический деобфускатор (<code>src/deobfuscator_engine.py</code>) и правила Sigma/YARA</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <p align="center">
        <a href="https://github.com/maya-thorne/batch-obfuscation-research">
          <img src="https://raw.githubusercontent.com/maya-thorne/batch-obfuscation-research/main/docs/assets/locales/en/banner.svg" alt="batch-obfuscation-research banner" width="100%" />
        </a>
      </p>
      <h4><a href="https://github.com/maya-thorne/batch-obfuscation-research">🛡️ batch-obfuscation-research</a></h4>
      <p><em>Мастер-архив обфускации, деобфускации и бинарного реверс-инжиниринга командных файлов Windows (cmd.exe) за 30 лет (1990s–2026).</em></p>
      <p>
        <a href="https://github.com/maya-thorne/batch-obfuscation-research"><img src="https://img.shields.io/badge/Archive-1990s--2026-10b981.svg" alt="30-Year Archive" /></a>
        <a href="https://github.com/maya-thorne/batch-obfuscation-research"><img src="https://img.shields.io/badge/Mirrors-48+_OpenSource-38bdf8.svg" alt="48+ Mirrors" /></a>
        <a href="https://github.com/maya-thorne/batch-obfuscation-research"><img src="https://img.shields.io/badge/Detection-Sigma_%26_YARA-a855f7.svg" alt="Sigma &amp; YARA" /></a>
      </p>
      <ul>
        <li>📜 <strong>30-летний архив эволюции</strong>: 48+ открытых репозиториев, исследования Mandiant и датасеты ИИ Hugging Face</li>
        <li>🧠 <strong>5-фазный парсер cmd.exe</strong>: Полное руководство по порядку раскрытия переменных и магазинным автоматам</li>
        <li>🌐 <strong>Документация на 10 языках</strong>: Локализованные технические руководства с темными неоновыми SVG-баннерами</li>
      </ul>
    </td>
  </tr>
</table>

<p align="center">
  <a href="https://github.com/maya-thorne?tab=repositories">Browse Public Repositories</a> ·
  <a href="https://github.com/maya-thorne/github-org-map">Explore Systems Topology</a>
</p>

</details>

---

<details>
<summary><h2 style="display:inline-block; margin:0;">⚙️ Featured Capabilities &amp; Architectures</h2></summary>

<br />

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>🐧 Kernel &amp; Low-Level Primitives</h4>
      <p><em>Asynchronous I/O via io_uring, kernel-bypass networking, and real-time observability.</em></p>
      <ul>
        <li>🌀 <strong>io_uring &amp; Async I/O</strong>: High-throughput submission/completion ring queues bypassing legacy epoll overhead.</li>
        <li>⚡ <strong>Kernel Bypass &amp; XDP</strong>: Programmable eBPF/XDP fast-path packet filtering and DPDK user-space acceleration.</li>
        <li>🔒 <strong>Lock-Free Primitives</strong>: SPMC/MPSC atomic queues, hazard pointers, and memory barrier synchronization.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h4>🌐 Distributed Systems &amp; Concurrency</h4>
      <p><em>Modern CSP-style concurrency pipelines, zero-copy serialization, and memory-safe systems software.</em></p>
      <ul>
        <li>🛠️ <strong>Systems Tooling</strong>: Idiomatic modern C23, async and unsafe Rust (no_std), and Zig toolchains.</li>
        <li>📦 <strong>Zero-Copy Data Flow</strong>: Cache-aligned serialization over NVMe storage fabrics and high-bandwidth networking.</li>
        <li>🧪 <strong>Invariant Validation</strong>: State automaton verification, property-based testing, and automated fuzzing suites.</li>
      </ul>
    </td>
  </tr>
</table>

</details>

---

<details>
<summary><h2 style="display:inline-block; margin:0;">💻 Technology Stack &amp; Tooling</h2></summary>

<br />

<p><em>Engineering toolchain for high-performance systems and bare-metal runtime execution:</em></p>

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>⚙️ Low-Level &amp; Systems</h4>
      <ul>
        <li>🔤 <strong>Languages</strong>: C23, Rust (Async / Unsafe / no_std), Zig, x86_64 / ARM64 Assembly</li>
        <li>🐧 <strong>Kernel Runtimes</strong>: Linux Kernel Modules, POSIX APIs, eBPF / XDP, io_uring</li>
        <li>🧠 <strong>Memory &amp; Concurrency</strong>: Lock-free atomics, SIMD vectorization, NUMA-aware allocators</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h4>🌐 Distributed &amp; Infrastructure</h4>
      <ul>
        <li>⚡ <strong>Networking</strong>: Kernel-bypass (DPDK), epoll/kqueue, WebSockets, gRPC</li>
        <li>🔍 <strong>Observability</strong>: bpftrace, perf, Valgrind, GDB, Prometheus telemetry</li>
        <li>🖥️ <strong>Environment</strong>: Arch Linux, Debian, Docker, LLVM/Clang toolchains, Neovim / Tmux</li>
      </ul>
    </td>
  </tr>
</table>

<br />

<p align="center">
  <img src="../assets/icons/tech-stack.svg" alt="Technical Stack Icons" />
</p>

</details>

---

<details>
<summary><h2 style="display:inline-block; margin:0;">🗺️ Explore Projects &amp; Roadmaps</h2></summary>

<br />

<p><strong>Organization Map &amp; Topology</strong></p>

<p align="center">
  <a href="https://github.com/maya-thorne/github-org-map">
    <img src="../assets/projects/github-org-map.svg" alt="Organization map showing the maya-thorne workspace, public projects, and intentionally masked private work." width="520" />
  </a>
</p>

<p align="center">
  <sub>Private repositories appear only as masked labels.</sub><br />
  <a href="https://github.com/maya-thorne/github-org-map">Explore Topology &amp; Cartography →</a>
</p>

<br />

<p><em>Active roadmap and technical initiatives across low-level infrastructure:</em></p>

<ul>
  <li>🎯 <strong>Current Focus</strong>: io_uring multi-ring polling benchmarks and kernel module fuzzing harness</li>
  <li>🚀 <strong>Next Milestone</strong>: Lock-free SPMC work-stealing scheduler with NUMA cache-pinning</li>
  <li>🔬 <strong>Research Track</strong>: eBPF-driven network flow router with hardware offloading</li>
</ul>

</details>

---

<details>
<summary><h2 style="display:inline-block; margin:0;">📊 Architecture Dashboard &amp; Delivery Metrics</h2></summary>

<br />

<div align="center">
  <p>
    <a href="https://github.com/maya-thorne">
      <img src="../assets/stats/github-stats.svg" alt="Maya Thorne's GitHub Stats" />
    </a>
    <a href="https://github.com/maya-thorne">
      <img src="../assets/stats/streak-stats.svg" alt="GitHub Streak Stats" />
    </a>
  </p>
</div>

</details>

---

## 📬 Connect &amp; Collaborate

Interested in discussing low-level systems architectures, Linux kernel internals, or high-performance concurrency primitives? (ง •̀_•́)ง

🐙 🐙 [GitHub Profile](https://github.com/maya-thorne) · 📦 [Public Repositories](https://github.com/maya-thorne?tab=repositories) · 💬 💬 [Discussions](https://github.com/maya-thorne?tab=discussions) · ✉️ [Send an Email](mailto:zse4123jo@gmail.com)

<div align="center">
  <br />
  <sub>© 2026 Maya Thorne · Systems Architecture &amp; Kernel Engineering ( 💻 ˘◡˘ )</sub>
</div>
