<div align="center">

<p>
  <img src="../assets/hero-ko.svg" alt="Maya Thorne — 속도 · 확장성 · 보안 — 리눅스 커널 및 저수준 동시성 아키텍처" width="76%" />
  <img src="../avatar.svg" alt="Maya Thorne Monogram" width="21%" />
</p>

<p>
  <strong>Architecting Resilient Low-Level Systems, Kernel Modules &amp; High-Throughput Concurrency Primitives.</strong><br />
  <sub>Speed · Scale · Security — Engineering with clarity and conviction.</sub>
</p>

<p>
  <a href="../README.md">🇺🇸 English</a> · <strong>🇰🇷 한국어</strong> · <a href="./zh-CN.md">🇨🇳 中文</a> · <a href="./es.md">🇪🇸 Español</a> · <a href="./hi.md">🇮🇳 हिन्दी</a><br />
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

<details open>
<summary><h2 style="display:inline-block; margin:0;">💡 엔지니어링 철학 및 핵심 원칙</h2></summary>
<br />

- **⚡ 제로 비용 및 기계적 공감 — 캐시 계층 구조, 메모리 정렬 및 분기 예측기를 존중하는 코드를 작성하며, 불필요한 런타임 오버헤드를 배제합니다.**
- **🐧 커널 퍼스트 사고 — 운영체제 커널을 불투명한 블랙박스가 아닌 근본적인 런타임으로 다룹니다. 가상 메모리, io_uring, eBPF 및 락프리 링 버퍼를 마스터합니다.**
- **🔒 불변식 기반 무결성 — 컴파일 타임에 안전성을 강제합니다. 엄격한 상태 머신 전이, 지속적 퍼징(Fuzzing) 검증 및 견고한 오류 처리 파이프라인을 구축합니다.**

<p align="center">
  <sub><em>"우리는 터미널을 신뢰한다. 결정론적으로 만들어라. 불필요한 마찰을 자동화하라."</em></sub>
</p>

</details>

---

<details open>
<summary><h2 style="display:inline-block; margin:0;">⚡ 기술 스택 및 도구 생태계</h2></summary>
<br />

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>⚙️ 저수준 시스템 및 커널</h4>
      <ul>
        <li><strong>Languages</strong>: <code>C23</code>, <code>Rust (Async/Unsafe/No_std)</code>, <code>Zig</code>, <code>x86_64 / ARM Assembly</code></li>
        <li><strong>Kernel Runtimes</strong>: Linux Kernel Modules, POSIX APIs, eBPF / XDP, <code>io_uring</code></li>
        <li><strong>Memory &amp; Concurrency</strong>: Lock-free atomics, SIMD vectorization, NUMA-aware allocators</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h4>🌐 분산 시스템 및 인프라</h4>
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
<summary><h2 style="display:inline-block; margin:0;">📊 실시간 텔레메트리 및 GitHub 지표</h2></summary>
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

## 📬 연결 및 협업 채널

저수준 시스템 아키텍처, 컴파일러 내부 구조 또는 커널 엔지니어링 논의에 관심이 있으신가요?

[GitHub Profile](https://github.com/maya-thorne) · [Public Repositories](https://github.com/maya-thorne?tab=repositories) · [Discussions](https://github.com/maya-thorne?tab=discussions) · [Send an Email](mailto:zse4123jo@gmail.com)

<div align="center">
  <br />
  <sub>© 2026 Maya Thorne · Built with mechanical sympathy · 🐧</sub>
</div>
