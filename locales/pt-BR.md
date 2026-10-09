<div align="center">

<p>
  <img src="../assets/hero_pt-BR.svg" alt="Maya Thorne — Velocidade · Escala · Segurança — Kernel Linux e Concorrência de Baixo Nível" width="76%" />
  <img src="../avatar.svg" alt="Maya Thorne Monogram" width="21%" />
</p>

<p>
  <strong>Architecting Resilient Low-Level Systems, Kernel Modules &amp; High-Throughput Concurrency Primitives.</strong><br />
  <sub>Speed · Scale · Security — Engineering with clarity and conviction.</sub>
</p>

<p>
  <a href="../README.md">🇺🇸 English</a> · <a href="./ko.md">🇰🇷 한국어</a> · <a href="./zh-CN.md">🇨🇳 中文</a> · <a href="./es.md">🇪🇸 Español</a> · <a href="./hi.md">🇮🇳 हिन्दी</a><br />
  <a href="./ar.md">🇸🇦 العربية</a> · <strong>🇧🇷 Português</strong> · <a href="./ru.md">🇷🇺 Русский</a> · <a href="./fr.md">🇫🇷 Français</a> · <a href="./id.md">🇮🇩 Bahasa Indonesia</a>
</p>

<p>
  <a href="https://github.com/maya-thorne"><img src="../assets/badges/badge-status.svg" alt="Status" /></a>
  <a href="https://github.com/maya-thorne?tab=repositories"><img src="../assets/badges/badge-focus.svg" alt="Focus" /></a>
  <a href="https://github.com/maya-thorne"><img src="../assets/badges/badge-arch.svg" alt="Architecture" /></a>
  <a href="https://github.com/maya-thorne"><img src="../assets/badges/badge-security.svg" alt="Security" /></a>
</p>

</div>

---

<details>
<summary><h2 style="display:inline-block; margin:0;">💡 Filosofia de Engenharia e Princípios</h2></summary>

<br />

Arquitetura de sistemas de software resilientes de baixo nível, módulos de kernel Linux e primitivas de concorrência de alto rendimento:

- **⚡ Custo Zero e Simpatia Mecânica — Código que respeita hierarquias de cache de CPU e alinhamento de memória.**
- **🐧 Pensamento Focado no Kernel — O kernel Linux como runtime fundamental: io_uring, eBPF e filas sem bloqueio.**
- **🔒 Correção Baseada em Invariantes — Segurança aplicada em tempo de compilação com transições rigorosas de máquinas de estado.**

<p align="center">
  <sub><em>"No terminal nós confiamos. Torne-o determinístico. Automatize o atrito."</em></sub>
</p>

</details>

---

<details>
<summary><h2 style="display:inline-block; margin:0;">🚀 Projetos e Soluções</h2></summary>

<br />

Bibliotecas de sistemas de baixo nível e módulos de kernel para latência ultra-baixa:

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>🐧 <a href="https://github.com/maya-thorne?tab=repositories">nexus-kernel-core</a></h4>
      <p><em>Módulo de kernel Linux de alto desempenho implementando buffers de anel de memória de cópia zero e IPC lock-free.</em></p>
      <ul>
        <li><strong>⚡ io_uring / eBPF</strong>: High-throughput submission/completion rings</li>
        <li><strong>🔒 Memory Safe</strong>: Invariant-enforced concurrency boundaries</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h4>⚡ <a href="https://github.com/maya-thorne?tab=repositories">uring-reactor</a></h4>
      <p><em>Loop de eventos I/O assíncrono construído sobre io_uring com latência sub-microssegundo sem sobrecarga de syscalls.</em></p>
      <ul>
        <li><strong>⏱️ Sub-Microsecond</strong>: Zero syscall overhead event dispatching</li>
        <li><strong>🛡️ Lockless SPMC</strong>: Cache-aligned atomic ring sequencing</li>
      </ul>
    </td>
  </tr>
</table>

<p align="center">
  <a href="https://github.com/maya-thorne?tab=repositories">🔗 Navegar pelos Repositórios Públicos</a> ·
  <a href="https://github.com/maya-thorne">📖 Explorar Especificações de Arquitetura</a>
</p>

</details>

---

<details>
<summary><h2 style="display:inline-block; margin:0;">🚀 Capacidades e Arquiteturas em Destaque</h2></summary>

<br />

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>⚙️ Kernel e Primitivas de Baixo Nível</h4>
      <p><em>I/O assíncrono via io_uring, redes de desvio de kernel e observabilidade em tempo real.</em></p>
      <ul>
        <li><strong>⚡ io_uring &amp; I/O Assíncrono</strong>: Buffers de anel de alto rendimento contornando o custo do epoll legado.</li>
        <li><strong>🛡️ Kernel Bypass &amp; XDP</strong>: Filtragem rápida de pacotes eBPF/XDP e aceleração DPDK.</li>
        <li><strong>🔄 Primitivas Lock-Free</strong>: Filas atômicas SPMC/MPSC e ordenação rigorosa de barreiras de memória.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h4>🌐 Sistemas Distribuídos e Concorrência</h4>
      <p><em>Pipelines concorrentes no estilo CSP e software de sistemas com memória segura.</em></p>
      <ul>
        <li><strong>⚙️ Ferramentas de Sistemas</strong>: C23 idiomático, Rust assíncrono/unsafe (no_std) e toolchains Zig.</li>
        <li><strong>📦 Fluxo de Dados Zero-Copy</strong>: Serialização de memória alinhada em cache sobre NVMe e redes 100GbE.</li>
        <li><strong>🎯 Validação de Invariantes</strong>: Autômatos finitos verificados e suites automatizadas de fuzzing.</li>
      </ul>
    </td>
  </tr>
</table>

</details>

---

<details>
<summary><h2 style="display:inline-block; margin:0;">⚡ Pilha de Tecnologia e Ferramentas</h2></summary>

<br />

<p><em>Conjunto de ferramentas de engenharia para sistemas de alto desempenho:</em></p>

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>⚙️ Baixo Nível e Sistemas</h4>
      <ul>
        <li><strong>Linguagens: C23, Rust (Async/Unsafe/No_std), Zig, Assembly x86_64 / ARM64</strong></li>
        <li><strong>Runtimes de Kernel: Módulos Linux, POSIX APIs, eBPF / XDP, io_uring</strong></li>
        <li><strong>Memória e Concorrência: Atômicas lock-free, vetorização SIMD, alocadores NUMA</strong></li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h4>🌐 Distribuído e Infraestrutura</h4>
      <ul>
        <li><strong>Redes: Kernel-bypass (DPDK), epoll/kqueue, WebSockets, gRPC</strong></li>
        <li><strong>Observabilidade: bpftrace, perf, Valgrind, GDB, telemetria Prometheus</strong></li>
        <li><strong>Ambiente: Arch Linux, Debian, Docker, LLVM/Clang, Neovim / Tmux</strong></li>
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
<summary><h2 style="display:inline-block; margin:0;">🗺️ Explorar Projetos e Roteiro</h2></summary>

<br />

<p><em>Roteiro ativo e iniciativas técnicas em infraestrutura de baixo nível:</em></p>

<ul>
  <li>🎯 Foco Atual: Benchmarks de polling multi-anel io_uring e fuzzing de módulos</li>
  <li>🚀 Próximo Marco: Escalonador de roubo de trabalho SPMC lock-free com afinidade NUMA</li>
  <li>🔮 Pesquisa Futura: Roteador de fluxo de rede eBPF com descarregamento de hardware</li>
</ul>

</details>

---

<details>
<summary><h2 style="display:inline-block; margin:0;">📊 Painel de Arquitetura e Métricas</h2></summary>

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

## 📬 Conectar e Colaborar

Interessado em arquiteturas de sistemas de baixo nível, kernel Linux ou primitivas de concorrência?

[Perfil no GitHub](https://github.com/maya-thorne) · [Repositórios Públicos](https://github.com/maya-thorne?tab=repositories) · [Discussões](https://github.com/maya-thorne?tab=discussions) · [Enviar E-mail](mailto:zse4123jo@gmail.com)

<div align="center">
  <br />
  <sub>© 2026 Maya Thorne · Construído com simpatia mecânica · 🐧</sub>
</div>
