<div align="center">

<p>
  <img src="../assets/hero_ar.svg" alt="Maya Thorne — السرعة · التوسع · الأمان — نواة لينكس والتزامن منخفض المستوى" width="76%" />
  <img src="../avatar.svg" alt="Maya Thorne Monogram" width="21%" />
</p>

<p>
  <strong>Architecting Resilient Low-Level Systems, Kernel Modules &amp; High-Throughput Concurrency Primitives.</strong><br />
  <sub>Speed · Scale · Security — Engineering with clarity and conviction.</sub>
</p>

<p>
  <a href="../README.md">🇺🇸 English</a> · <a href="./ko.md">🇰🇷 한국어</a> · <a href="./zh-CN.md">🇨🇳 中文</a> · <a href="./es.md">🇪🇸 Español</a> · <a href="./hi.md">🇮🇳 हिन्दी</a><br />
  <strong>🇸🇦 العربية</strong> · <a href="./pt-BR.md">🇧🇷 Português</a> · <a href="./ru.md">🇷🇺 Русский</a> · <a href="./fr.md">🇫🇷 Français</a> · <a href="./id.md">🇮🇩 Bahasa Indonesia</a>
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
<summary><h2 style="display:inline-block; margin:0;">💡 الفلسفة الهندسية والرؤية</h2></summary>

<br />

هندسة أنظمة برمجية منخفضة المستوى مرنة، ووحدات نواة لينكس، وأساسيات التزامن عالية الإنتاجية:

- **⚡ تكلفة صفرية وتوافق ميكانيكي — كود يراعي مستويات الذاكرة المؤقتة ومحاذاة الذاكرة وتنبؤ التفرع.**
- **🐧 التفكير المرتكز على النواة — التعامل مع نواة نظام التشغيل كبيئة تشغيل أساسية: io_uring و eBPF والقوائم غير المقفلة.**
- **🔒 صحة مدفوعة بالثوابت — فرض الأمان أثناء وقت الترجمة وحالات انتقال صارمة.**

<p align="center">
  <sub><em>"نثق في الطرفية. اجعلها حتمية. أتمتة كل العوائق."</em></sub>
</p>

</details>

---

<details>
<summary><h2 style="display:inline-block; margin:0;">🚀 المشاريع والحلول البارزة</h2></summary>

<br />

مكتبات برمجية ووحدات نواة مصممة لأقل زمن استجابة وتوافق ميكانيكي أقصى:

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>🐧 <a href="https://github.com/maya-thorne?tab=repositories">nexus-kernel-core</a></h4>
      <p><em>وحدة نواة لينكس عالية الأداء تطبق مخازن حلقية بذاكرة مشتركة دون نسخ وتزامن بين العمليات دون أقفال.</em></p>
      <ul>
        <li><strong>⚡ io_uring / eBPF</strong>: High-throughput submission/completion rings</li>
        <li><strong>🔒 Memory Safe</strong>: Invariant-enforced concurrency boundaries</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h4>⚡ <a href="https://github.com/maya-thorne?tab=repositories">uring-reactor</a></h4>
      <p><em>حلقة أحداث إدخال/إخراج غير متزامنة مبنية على io_uring بزمن استجابة أقل من ميكروثانية دون أعباء استدعاء النظام.</em></p>
      <ul>
        <li><strong>⏱️ Sub-Microsecond</strong>: Zero syscall overhead event dispatching</li>
        <li><strong>🛡️ Lockless SPMC</strong>: Cache-aligned atomic ring sequencing</li>
      </ul>
    </td>
  </tr>
</table>

<p align="center">
  <a href="https://github.com/maya-thorne?tab=repositories">🔗 تصفح المستودعات العامة</a> ·
  <a href="https://github.com/maya-thorne">📖 استكشاف مواصفات المعمارية</a>
</p>

</details>

---

<details>
<summary><h2 style="display:inline-block; margin:0;">🚀 القدرات والمعمارية المتميزة</h2></summary>

<br />

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>⚙️ النواة والأساسيات منخفضة المستوى</h4>
      <p><em>إدخال/إخراج غير متزامن عبر io_uring وشبكات تجاوز النواة وقابلية الرصد المباشر.</em></p>
      <ul>
        <li><strong>⚡ io_uring &amp; الإدخال غير المتزامن</strong>: مخازن حلقية عالية الإنتاجية تتجاوز أعباء epoll التقليدية.</li>
        <li><strong>🛡️ تجاوز النواة &amp; XDP</strong>: تصفية حزم سريعة عبر eBPF/XDP مع تسريع DPDK.</li>
        <li><strong>🔄 أساسيات دون أقفال</strong>: طوابير ذرية SPMC/MPSC وتسلسل صارم لحواجز الذاكرة.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h4>🌐 الأنظمة الموزعة والتزامن</h4>
      <p><em>خطوط معالجة تزامن بنمط CSP وبرمجيات أنظمة آمنة للذاكرة.</em></p>
      <ul>
        <li><strong>⚙️ أدوات الأنظمة</strong>: C23 الحديثة، ولغة Rust غير المتزامنة (no_std)، وأدوات Zig.</li>
        <li><strong>📦 تدفق بيانات دون نسخ</strong>: تسلسل ذاكرة بمحاذاة الذاكرة المؤقتة عبر NVMe وشبكات 100GbE.</li>
        <li><strong>🎯 التحقق من الثوابت</strong>: تحقق دقيق من آلات الحالات المحدودة واختبارات فحص الأعطال التلقائية.</li>
      </ul>
    </td>
  </tr>
</table>

</details>

---

<details>
<summary><h2 style="display:inline-block; margin:0;">⚡ مجموعة التقنيات والأدوات</h2></summary>

<br />

<p><em>مجموعة أدوات هندسية للأنظمة فائقة الأداء وبيئات التشغيل المباشرة:</em></p>

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>⚙️ المستوى المنخفض والأنظمة</h4>
      <ul>
        <li><strong>اللغات: C23, Rust (Async/Unsafe/No_std), Zig, x86_64 / ARM64 Assembly</strong></li>
        <li><strong>بيئات النواة: Linux Kernel Modules, POSIX APIs, eBPF / XDP, io_uring</strong></li>
        <li><strong>الذاكرة والتزامن: ذرات خالية من الأقفال, SIMD, مخصصات NUMA</strong></li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h4>🌐 التوزيع والبنية التحتية</h4>
      <ul>
        <li><strong>الشبكات: تجاوز النواة (DPDK), epoll/kqueue, WebSockets, gRPC</strong></li>
        <li><strong>قابلية الرصد: bpftrace, perf, Valgrind, GDB, Prometheus</strong></li>
        <li><strong>البيئة: Arch Linux, Debian, Docker, LLVM/Clang, Neovim / Tmux</strong></li>
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
<summary><h2 style="display:inline-block; margin:0;">🗺️ استكشاف المشاريع وخارطة الطريق</h2></summary>

<br />

<p><em>خارطة الطريق النشطة والمبادرات التقنية في البنية التحتية منخفضة المستوى:</em></p>

<ul>
  <li>🎯 التركيز الحالي: اختبارات أداء الاقتراع متعدد الحلقات لـ io_uring وفحص النواة</li>
  <li>🚀 المرحلة القادمة: مجدول سرقة العمل SPMC دون أقفال مع تثبيت كاش NUMA</li>
  <li>🔮 أبحاث مستقبلية: موجه تدفق شبكي مدعوم بـ eBPF وتفريغ العتاد</li>
</ul>

</details>

---

<details>
<summary><h2 style="display:inline-block; margin:0;">📊 لوحة معلومات المعمارية والمقاييس</h2></summary>

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

## 📬 التواصل والتعاون

هل ترغب في مناقشة معماريات الأنظمة منخفضة المستوى، أو نواة لينكس، أو التزامن عالي الأداء؟

[الملف الشخصي على GitHub](https://github.com/maya-thorne) · [المستودعات العامة](https://github.com/maya-thorne?tab=repositories) · [المناقشات](https://github.com/maya-thorne?tab=discussions) · [إرسال بريد إلكتروني](mailto:zse4123jo@gmail.com)

<div align="center">
  <br />
  <sub>© 2026 Maya Thorne · تم البناء بتوافق ميكانيكي · 🐧</sub>
</div>
