<div align="center">

<p>
  <img src="../assets/hero_zh-CN.svg" alt="Maya Thorne — 速度 · 规模 · 安全 — Linux 内核与底层并发架构" width="76%" />
  <img src="../avatar.svg" alt="Maya Thorne Monogram" width="21%" />
</p>

<p>
  <strong>Architecting Resilient Low-Level Systems, Kernel Modules &amp; High-Throughput Concurrency Primitives.</strong><br />
  <sub>Speed · Scale · Security — Engineering with clarity and conviction.</sub>
</p>

<p>
  <a href="../README.md">🇺🇸 English</a> · <a href="./ko.md">🇰🇷 한국어</a> · <strong>🇨🇳 中文</strong> · <a href="./es.md">🇪🇸 Español</a> · <a href="./hi.md">🇮🇳 हिन्दी</a><br />
  <a href="./ar.md">🇸🇦 العربية</a> · <a href="./pt-BR.md">🇧🇷 Português</a> · <a href="./ru.md">🇷🇺 Русский</a> · <a href="./fr.md">🇫🇷 Français</a> · <a href="./id.md">🇮🇩 Bahasa Indonesia</a>
</p>

<p>
  <a href="https://github.com/maya-thorne"><img src="https://img.shields.io/badge/Status-Kernel%20Ready%20%F0%9F%90%A7-1f2328?style=flat-square&logo=linux&logoColor=39d353" alt="Status" /></a>
  <a href="https://github.com/maya-thorne?tab=repositories"><img src="https://img.shields.io/badge/Focus-Systems%20%26%20Rust-1f2328?style=flat-square&logo=rust&logoColor=f74c00" alt="Focus" /></a>
  <a href="https://github.com/maya-thorne"><img src="https://img.shields.io/badge/Architecture-x86__64%20%2F%20ARM64-1f2328?style=flat-square&logo=cpu&logoColor=58a6ff" alt="Architecture" /></a>
  <a href="https://github.com/maya-thorne"><img src="https://img.shields.io/badge/Security-Memory%20Safe-1f2328?style=flat-square&logo=shield&logoColor=bc8cff" alt="Security" /></a>
</p>

</div>

---

<details>
<summary><h2 style="display:inline-block; margin:0;">💡 About & Engineering Ethos</h2></summary>

<br />

设计具有韧性的底层软件系统、Linux 内核模块以及高吞吐量并发原语。专注于机械同理心与零开销性能：

- **⚡ 零成本抽象与机械同理心 — 编写契合 CPU 缓存层级、内存对齐和分支预测器的代码，追求默认零开销。**
- **🐧 内核优先思维 — 将操作系统内核视为根本运行时而非黑盒。深入掌握 io_uring、eBPF 及无锁队列。**
- **🔒 不变式驱动正确性 — 尽可能在编译期强制安全性。严格的状态机转移、无锁环形缓冲区与持续模糊测试。**

<p align="center">
  <sub><em>"信任终端。追求确定性。消除摩擦。"</em></sub>
</p>

</details>

---

<details>
<summary><h2 style="display:inline-block; margin:0;">🚀 Projects & Solutions</h2></summary>

<br />

专为超低延迟与极致机械同理心设计的底层系统库、内核模块与并发通信原语：

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>🐧 <a href="https://github.com/maya-thorne?tab=repositories">nexus-kernel-core</a></h4>
      <p><em>实现零拷贝共享内存环形缓冲区与无锁 IPC 原语的高性能 Linux 内核模块。</em></p>
      <ul>
        <li><strong>⚡ io_uring / eBPF</strong>: High-throughput submission/completion rings</li>
        <li><strong>🔒 Memory Safe</strong>: Invariant-enforced concurrency boundaries</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h4>⚡ <a href="https://github.com/maya-thorne?tab=repositories">uring-reactor</a></h4>
      <p><em>基于现代 Linux io_uring 构建的亚微秒延迟异步 I/O 事件循环，消除系统调用开销。</em></p>
      <ul>
        <li><strong>⏱️ Sub-Microsecond</strong>: Zero syscall overhead event dispatching</li>
        <li><strong>🛡️ Lockless SPMC</strong>: Cache-aligned atomic ring sequencing</li>
      </ul>
    </td>
  </tr>
</table>

<p align="center">
  <a href="https://github.com/maya-thorne?tab=repositories">🔗 浏览公开仓库</a> ·
  <a href="https://github.com/maya-thorne">📖 探索系统架构规范</a>
</p>

</details>

---

<details>
<summary><h2 style="display:inline-block; margin:0;">🚀 Featured Capabilities & Architectures</h2></summary>

<br />

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>⚙️ 内核与底层原语</h4>
      <p><em>io_uring 异步 I/O、内核旁路网络与实时内核可观测性。</em></p>
      <ul>
        <li><strong>⚡ io_uring &amp; 异步 I/O</strong>: 绕过传统 epoll 开销的高吞吐量提交/完成环形流水线。</li>
        <li><strong>🛡️ 内核旁路 &amp; XDP</strong>: eBPF/XDP 可编程快速路径数据包过滤与 DPDK 加速。</li>
        <li><strong>🔄 无锁原语</strong>: SPMC/MPSC 原子队列、危险指针与严格内存屏障排序。</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h4>🌐 分布式系统与并发</h4>
      <p><em>现代 CSP 风格并发流水线与内存安全系统软件。</em></p>
      <ul>
        <li><strong>⚙️ 系统工具链</strong>: 现代 C23、异步/Unsafe Rust (no_std) 与 Zig 工具链精通。</li>
        <li><strong>📦 零拷贝数据流</strong>: NVMe 存储与 100GbE 网络上缓存对齐的内存序列化。</li>
        <li><strong>🎯 确定性状态机</strong>: 有限状态机精确验证与自动化模糊测试套件。</li>
      </ul>
    </td>
  </tr>
</table>

</details>

---

<details>
<summary><h2 style="display:inline-block; margin:0;">⚡ Technology Stack & Tooling</h2></summary>

<br />

<p><em>用于高性能系统与裸机运行时执行的工程工具链：</em></p>

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>⚙️ 底层与系统</h4>
      <ul>
        <li><strong>编程语言: C23, Rust (Async/Unsafe/No_std), Zig, x86_64 / ARM64 Assembly</strong></li>
        <li><strong>内核运行时: Linux Kernel Modules, POSIX APIs, eBPF / XDP, io_uring</strong></li>
        <li><strong>内存与并发: 无锁原子操作, SIMD 向量化, NUMA 感知内存分配器</strong></li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h4>🌐 分布式与基础设施</h4>
      <ul>
        <li><strong>网络通信: 内核旁路 (DPDK), epoll/kqueue, WebSockets, gRPC</strong></li>
        <li><strong>可观测性: bpftrace, perf, Valgrind, GDB, Prometheus 遥测</strong></li>
        <li><strong>开发环境: Arch Linux, Debian, Docker, LLVM/Clang 工具链, Neovim / Tmux</strong></li>
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

<details>
<summary><h2 style="display:inline-block; margin:0;">🗺️ Explore Projects & Roadmaps</h2></summary>

<br />

<p><em>涵盖底层基础设施的活跃技术路线图与规划：</em></p>

<ul>
  <li>🎯 当前重点: io_uring 多环轮询基准测试与内核模块模糊测试套件</li>
  <li>🚀 下一里程碑: 具备 NUMA 缓存绑定的无锁 SPMC 工作窃取调度器</li>
  <li>🔮 未来研究: 支持硬件卸载的 eBPF 驱动网络流路由器</li>
</ul>

</details>

---

<details>
<summary><h2 style="display:inline-block; margin:0;">📊 Architecture Dashboard & Delivery Metrics</h2></summary>

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

## 📬 Connect & Collaborate

对底层系统架构、Linux 内核机制或高性能并发原语的交流感兴趣？

[GitHub 个人主页](https://github.com/maya-thorne) · [公开代码仓库](https://github.com/maya-thorne?tab=repositories) · [讨论区 (Discussions)](https://github.com/maya-thorne?tab=discussions) · [发送电子邮件](mailto:zse4123jo@gmail.com)

<div align="center">
  <br />
  <sub>© 2026 Maya Thorne · 以机械同理心构建 · 🐧</sub>
</div>
