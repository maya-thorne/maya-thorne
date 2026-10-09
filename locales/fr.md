<div align="center">

<p>
  <img src="../assets/hero_fr.svg" alt="Maya Thorne — Vitesse · Échelle · Sécurité — Noyau Linux & Concurrence Bas Niveau" width="76%" />
  <img src="../avatar.svg" alt="Maya Thorne Monogram" width="21%" />
</p>

<p>
  <strong>Architecting Resilient Low-Level Systems, Kernel Modules &amp; High-Throughput Concurrency Primitives.</strong><br />
  <sub>Speed · Scale · Security — Engineering with clarity and conviction.</sub>
</p>

<p>
  <a href="../README.md">🇺🇸 English</a> · <a href="./ko.md">🇰🇷 한국어</a> · <a href="./zh-CN.md">🇨🇳 中文</a> · <a href="./es.md">🇪🇸 Español</a> · <a href="./hi.md">🇮🇳 हिन्दी</a><br />
  <a href="./ar.md">🇸🇦 العربية</a> · <a href="./pt-BR.md">🇧🇷 Português</a> · <a href="./ru.md">🇷🇺 Русский</a> · <strong>🇫🇷 Français</strong> · <a href="./id.md">🇮🇩 Bahasa Indonesia</a>
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
<summary><h2 style="display:inline-block; margin:0;">💡 Philosophie d'Ingénierie & Principes</h2></summary>

<br />

Conception de systèmes logiciels bas niveau résilients, de modules du noyau Linux et de primitives de concurrence à haut débit :

- **⚡ Coût Zéro & Sympathie Mécanique — Code respectueux des hiérarchies de cache CPU et de l'alignement mémoire.**
- **🐧 Pensée Centrée sur le Noyau — Le noyau Linux comme runtime fondamental : io_uring, eBPF et files d'attente sans verrou.**
- **🔒 Correction par Invariants — Sécurité imposée à la compilation avec transitions strictes de machines d'états.**

<p align="center">
  <sub><em>"Dans le terminal nous avons confiance. Rendez-le déterministe. Automatisez la friction."</em></sub>
</p>

</details>

---

<details>
<summary><h2 style="display:inline-block; margin:0;">🚀 Projets & Solutions</h2></summary>

<br />

Bibliothèques système et modules de noyau conçus pour une latence ultra-faible :

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>🐧 <a href="https://github.com/maya-thorne?tab=repositories">nexus-kernel-core</a></h4>
      <p><em>Module de noyau Linux haute performance implémentant des mémoires partagées en anneau zéro-copie et IPC sans verrou.</em></p>
      <ul>
        <li><strong>⚡ io_uring / eBPF</strong>: High-throughput submission/completion rings</li>
        <li><strong>🔒 Memory Safe</strong>: Invariant-enforced concurrency boundaries</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h4>⚡ <a href="https://github.com/maya-thorne?tab=repositories">uring-reactor</a></h4>
      <p><em>Boucle d'événements E/S asynchrone construite sur io_uring avec latence sous la microseconde.</em></p>
      <ul>
        <li><strong>⏱️ Sub-Microsecond</strong>: Zero syscall overhead event dispatching</li>
        <li><strong>🛡️ Lockless SPMC</strong>: Cache-aligned atomic ring sequencing</li>
      </ul>
    </td>
  </tr>
</table>

<p align="center">
  <a href="https://github.com/maya-thorne?tab=repositories">🔗 Parcourir les Dépôts Publics</a> ·
  <a href="https://github.com/maya-thorne">📖 Explorer les Spécifications d'Architecture</a>
</p>

</details>

---

<details>
<summary><h2 style="display:inline-block; margin:0;">🚀 Capacités & Architectures en Vedette</h2></summary>

<br />

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>⚙️ Noyau et Primitives Bas Niveau</h4>
      <p><em>E/S asynchrones via io_uring, contournement du noyau en réseau et observabilité en temps réel.</em></p>
      <ul>
        <li><strong>⚡ io_uring &amp; E/S Asynchrones</strong>: Anneaux de haute performance contournant le coût de l'epoll hérité.</li>
        <li><strong>🛡️ Kernel Bypass &amp; XDP</strong>: Filtrage rapide de paquets avec eBPF/XDP et accélération DPDK.</li>
        <li><strong>🔄 Primitives Sans Verrou</strong>: Files atomiques SPMC/MPSC et ordonnancement strict des barrières mémoire.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h4>🌐 Systèmes Distribués et Concurrence</h4>
      <p><em>Pipelines concurrents style CSP et logiciels système à mémoire sécurisée.</em></p>
      <ul>
        <li><strong>⚙️ Outillage Systèmes</strong>: C23 moderne, Rust asynchrone/unsafe (no_std) et Zig.</li>
        <li><strong>📦 Flux Zéro-Copie</strong>: Sérialisation alignée sur le cache sur stockage NVMe et 100GbE.</li>
        <li><strong>🎯 Validation d'Invariants</strong>: Automates finis vérifiés et suites de fuzzing continu.</li>
      </ul>
    </td>
  </tr>
</table>

</details>

---

<details>
<summary><h2 style="display:inline-block; margin:0;">⚡ Pile Technologique & Outillage</h2></summary>

<br />

<p><em>Boîte à outils d'ingénierie pour systèmes haute performance :</em></p>

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>⚙️ Bas Niveau et Systèmes</h4>
      <ul>
        <li><strong>Langages : C23, Rust (Async/Unsafe/No_std), Zig, Assembleur x86_64 / ARM64</strong></li>
        <li><strong>Environnements Noyau : Modules Linux, APIs POSIX, eBPF / XDP, io_uring</strong></li>
        <li><strong>Mémoire & Concurrence : Atomiques lock-free, vectorisation SIMD, allocateurs NUMA</strong></li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h4>🌐 Distribué & Infrastructure</h4>
      <ul>
        <li><strong>Réseau : Contournement du noyau (DPDK), epoll/kqueue, WebSockets, gRPC</strong></li>
        <li><strong>Observabilité : bpftrace, perf, Valgrind, GDB, télémétrie Prometheus</strong></li>
        <li><strong>Environnement : Arch Linux, Debian, Docker, LLVM/Clang, Neovim / Tmux</strong></li>
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
<summary><h2 style="display:inline-block; margin:0;">🗺️ Explorer les Projets & Feuille de Route</h2></summary>

<br />

<p><em>Feuille de route active et initiatives techniques d'infrastructure bas niveau :</em></p>

<ul>
  <li>🎯 Objectif Actuel : Bancs d'essai de scrutation multi-anneaux io_uring et fuzzing</li>
  <li>🚀 Prochain Jalon : Ordonnanceur de vol de travail SPMC sans verrou avec affinité NUMA</li>
  <li>🔮 Recherches Futures : Routeur de flux réseau basé sur eBPF avec délestage matériel</li>
</ul>

</details>

---

<details>
<summary><h2 style="display:inline-block; margin:0;">📊 Tableau de Bord d'Architecture & Métriques</h2></summary>

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

## 📬 Connexion & Collaboration

Intéressé par les architectures de systèmes bas niveau, le noyau Linux ou la concurrence haute performance ?

[Profil GitHub](https://github.com/maya-thorne) · [Dépôts Publics](https://github.com/maya-thorne?tab=repositories) · [Discussions](https://github.com/maya-thorne?tab=discussions) · [Envoyer un E-mail](mailto:zse4123jo@gmail.com)

<div align="center">
  <br />
  <sub>© 2026 Maya Thorne · Bâti avec sympathie mécanique · 🐧</sub>
</div>
