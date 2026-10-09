<div align="center">

<p>
  <img src="../assets/hero_ru.svg" alt="Maya Thorne — Скорость · Масштаб · Безопасность — Ядро Linux и низкоуровневый параллелизм" width="76%" />
  <img src="../avatar.svg" alt="Maya Thorne Monogram" width="21%" />
</p>

<p>
  <strong>Architecting Resilient Low-Level Systems, Kernel Modules &amp; High-Throughput Concurrency Primitives.</strong><br />
  <sub>Speed · Scale · Security — Engineering with clarity and conviction.</sub>
</p>

<p>
  <a href="../README.md">🇺🇸 English</a> · <a href="./ko.md">🇰🇷 한국어</a> · <a href="./zh-CN.md">🇨🇳 中文</a> · <a href="./es.md">🇪🇸 Español</a> · <a href="./hi.md">🇮🇳 हिन्दी</a><br />
  <a href="./ar.md">🇸🇦 العربية</a> · <a href="./pt-BR.md">🇧🇷 Português</a> · <strong>🇷🇺 Русский</strong> · <a href="./fr.md">🇫🇷 Français</a> · <a href="./id.md">🇮🇩 Bahasa Indonesia</a>
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
<summary><h2 style="display:inline-block; margin:0;">💡 Инженерная философия и принципы</h2></summary>

<br />

Проектирование отказоустойчивых низкоуровневых систем, модулей ядра Linux и высокопроизводительных примитивов параллелизма:

- **⚡ Нулевые накладные расходы и механическое сочувствие — Код, оптимизированный под иерархию кэшей и выравнивание памяти.**
- **🐧 Приоритет ядра ОС — Восприятие ядра Linux как фундаментальной среды выполнения: io_uring, eBPF и lock-free очереди.**
- **🔒 Корректность на основе инвариантов — Безопасность на этапе компиляции, строгие автоматы состояний и фаззинг.**

<p align="center">
  <sub><em>"Мы верим в терминал. Сделай это детерминированным. Автоматизируй трение."</em></sub>
</p>

</details>

---

<details>
<summary><h2 style="display:inline-block; margin:0;">🚀 Проекты и решения</h2></summary>

<br />

Низкоуровневые системные библиотеки и модули ядра для сверхнизких задержек:

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>🐧 <a href="https://github.com/maya-thorne?tab=repositories">nexus-kernel-core</a></h4>
      <p><em>Высокопроизводительный модуль ядра Linux с кольцевыми буферами памяти без копирования и неблокирующим IPC.</em></p>
      <ul>
        <li><strong>⚡ io_uring / eBPF</strong>: High-throughput submission/completion rings</li>
        <li><strong>🔒 Memory Safe</strong>: Invariant-enforced concurrency boundaries</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h4>⚡ <a href="https://github.com/maya-thorne?tab=repositories">uring-reactor</a></h4>
      <p><em>Асинхронный цикл событий ввода-вывода на базе современного io_uring с задержкой менее микросекунды.</em></p>
      <ul>
        <li><strong>⏱️ Sub-Microsecond</strong>: Zero syscall overhead event dispatching</li>
        <li><strong>🛡️ Lockless SPMC</strong>: Cache-aligned atomic ring sequencing</li>
      </ul>
    </td>
  </tr>
</table>

<p align="center">
  <a href="https://github.com/maya-thorne?tab=repositories">🔗 Публичные репозитории</a> ·
  <a href="https://github.com/maya-thorne">📖 Спецификации архитектуры</a>
</p>

</details>

---

<details>
<summary><h2 style="display:inline-block; margin:0;">🚀 Ключевые возможности и архитектура</h2></summary>

<br />

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>⚙️ Ядро и низкоуровневые примитивы</h4>
      <p><em>Асинхронный ввод-вывод io_uring, обход ядра в сети и наблюдаемость в реальном времени.</em></p>
      <ul>
        <li><strong>⚡ io_uring &amp; Асинхронный I/O</strong>: Кольцевые буферы высокой пропускной способности без накладных расходов epoll.</li>
        <li><strong>🛡️ Kernel Bypass &amp; XDP</strong>: Быстрая фильтрация пакетов с eBPF/XDP и ускорение DPDK.</li>
        <li><strong>🔄 Lock-Free примитивы</strong>: Атомарные очереди SPMC/MPSC и барьеры памяти.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h4>🌐 Распределенные системы и параллелизм</h4>
      <p><em>Конкурентные конвейеры в стиле CSP и ПО с безопасной работой с памятью.</em></p>
      <ul>
        <li><strong>⚙️ Системные инструменты</strong>: Современный C23, асинхронный/unsafe Rust (no_std) и Zig.</li>
        <li><strong>📦 Передача данных без копирования</strong>: Кэш-выровненная сериализация через NVMe и сети 100GbE.</li>
        <li><strong>🎯 Проверка инвариантов</strong>: Верификация конечных автоматов и фаззинг.</li>
      </ul>
    </td>
  </tr>
</table>

</details>

---

<details>
<summary><h2 style="display:inline-block; margin:0;">⚡ Стек технологий и инструменты</h2></summary>

<br />

<p><em>Инженерный инструментарий для высокопроизводительных систем:</em></p>

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>⚙️ Низкий уровень и системы</h4>
      <ul>
        <li><strong>Языки: C23, Rust (Async/Unsafe/No_std), Zig, x86_64 / ARM64 Ассемблер</strong></li>
        <li><strong>Среда ядра: Модули ядра Linux, POSIX APIs, eBPF / XDP, io_uring</strong></li>
        <li><strong>Память и параллелизм: Lock-free атомики, SIMD, аллокаторы NUMA</strong></li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h4>🌐 Сети и инфраструктура</h4>
      <ul>
        <li><strong>Сети: Обход ядра (DPDK), epoll/kqueue, WebSockets, gRPC</strong></li>
        <li><strong>Наблюдаемость: bpftrace, perf, Valgrind, GDB, Prometheus</strong></li>
        <li><strong>Среда: Arch Linux, Debian, Docker, LLVM/Clang, Neovim / Tmux</strong></li>
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
<summary><h2 style="display:inline-block; margin:0;">🗺️ Проекты и дорожная карта</h2></summary>

<br />

<p><em>Активная дорожная карта и технические инициативы в низкоуровневой инфраструктуре:</em></p>

<ul>
  <li>🎯 Текущий фокус: Бенчмарки io_uring multi-ring polling и фаззинг модулей ядра</li>
  <li>🚀 Следующая веха: Неблокирующий планировщик SPMC work-stealing с привязкой NUMA</li>
  <li>🔮 Будущие исследования: Сетевой маршрутизатор потоков на eBPF с аппаратной разгрузкой</li>
</ul>

</details>

---

<details>
<summary><h2 style="display:inline-block; margin:0;">📊 Панель архитектуры и метрики</h2></summary>

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

## 📬 Связь и сотрудничество

Заинтересованы в обсуждении архитектуры низкоуровневых систем или ядра Linux?

[Профиль GitHub](https://github.com/maya-thorne) · [Публичные репозитории](https://github.com/maya-thorne?tab=repositories) · [Обсуждения](https://github.com/maya-thorne?tab=discussions) · [Написать письмо](mailto:zse4123jo@gmail.com)

<div align="center">
  <br />
  <sub>© 2026 Maya Thorne · Построено с механическим сочувствием · 🐧</sub>
</div>
