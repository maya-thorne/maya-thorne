<div align="center">

<p>
  <img src="../assets/hero_hi.svg" alt="Maya Thorne — गति · पैमाना · सुरक्षा — लिनक्स कर्नेल और निम्न-स्तरीय समवर्ती आर्किटेक्चर" width="76%" />
  <img src="../avatar.svg" alt="Maya Thorne Monogram" width="21%" />
</p>

<p>
  <strong>Architecting Resilient Low-Level Systems, Kernel Modules &amp; High-Throughput Concurrency Primitives.</strong><br />
  <sub>Speed · Scale · Security — Engineering with clarity and conviction.</sub>
</p>

<p>
  <a href="../README.md">🇺🇸 English</a> · <a href="./ko.md">🇰🇷 한국어</a> · <a href="./zh-CN.md">🇨🇳 中文</a> · <a href="./es.md">🇪🇸 Español</a> · <strong>🇮🇳 हिन्दी</strong><br />
  <a href="./ar.md">🇸🇦 العربية</a> · <a href="./pt-BR.md">🇧🇷 Português</a> · <a href="./ru.md">🇷🇺 Русский</a> · <a href="./fr.md">🇫🇷 Français</a> · <a href="./id.md">🇮🇩 Bahasa Indonesia</a>
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
<summary><h2 style="display:inline-block; margin:0;">💡 मूल दर्शन और इंजीनियरिंग दृष्टिकोण</h2></summary>

<br />

लचीले निम्न-स्तरीय सॉफ्टवेयर सिस्टम, लिनक्स कर्नेल मॉड्यूल और उच्च-थ्रूपुट समवर्ती प्रिमिटिव का निर्माण:

- **⚡ शून्य लागत और यांत्रिक सहानुभूति — सीपीयू कैश और मेमोरी संरेखण का सम्मान करने वाला कोड।**
- **🐧 कर्नेल-प्रथम सोच — ऑपरेटिंग सिस्टम कर्नेल को एक बुनियादी रनटाइम के रूप में समझना: io_uring, eBPF और लॉक-मुक्त कतारें।**
- **🔒 अपरिवर्तनीय शुद्धता — कंपाइल-समय पर सुरक्षा प्रवर्तन और सख्त स्थिति मशीन संक्रमण।**

<p align="center">
  <sub><em>"टर्मिनल पर हमारा भरोसा है। इसे नियतात्मक बनाएं।"</em></sub>
</p>

</details>

---

<details>
<summary><h2 style="display:inline-block; margin:0;">🚀 प्रमुख परियोजनाएं और समाधान</h2></summary>

<br />

अल्ट्रा-लो लेटेंसी और अधिकतम यांत्रिक सहानुभूति के लिए डिज़ाइन किए गए सिस्टम लाइब्रेरी:

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>🐧 <a href="https://github.com/maya-thorne?tab=repositories">nexus-kernel-core</a></h4>
      <p><em>शून्य-प्रतिलिपि मेमोरी रिंग बफ़र्स और लॉक-फ्री आईपीसी लागू करने वाला उच्च-प्रदर्शन कर्नेल मॉड्यूल।</em></p>
      <ul>
        <li><strong>⚡ io_uring / eBPF</strong>: High-throughput submission/completion rings</li>
        <li><strong>🔒 Memory Safe</strong>: Invariant-enforced concurrency boundaries</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h4>⚡ <a href="https://github.com/maya-thorne?tab=repositories">uring-reactor</a></h4>
      <p><em>आधुनिक io_uring पर निर्मित सब-माइक्रोसेकंड लेटेंसी एसिंक्रोनस I/O इवेंट लूप।</em></p>
      <ul>
        <li><strong>⏱️ Sub-Microsecond</strong>: Zero syscall overhead event dispatching</li>
        <li><strong>🛡️ Lockless SPMC</strong>: Cache-aligned atomic ring sequencing</li>
      </ul>
    </td>
  </tr>
</table>

<p align="center">
  <a href="https://github.com/maya-thorne?tab=repositories">🔗 सार्वजनिक रिपॉजिटरी देखें</a> ·
  <a href="https://github.com/maya-thorne">📖 आर्किटेक्चर विवरण देखें</a>
</p>

</details>

---

<details>
<summary><h2 style="display:inline-block; margin:0;">🚀 प्रमुख क्षमताएं और आर्किटेक्चर</h2></summary>

<br />

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>⚙️ कर्नेल और निम्न-स्तरीय प्रिमिटिव</h4>
      <p><em>io_uring एसिंक्रोनस I/O, कर्नेल बाईपास नेटवर्किंग और रीयल-टाइम अवलोकन।</em></p>
      <ul>
        <li><strong>⚡ io_uring &amp; एसिंक I/O</strong>: पारंपरिक epoll ओवरहेड को दरकिनार करने वाले उच्च-थ्रूपुट रिंग बफ़र्स।</li>
        <li><strong>🛡️ कर्नेल बाईपास &amp; XDP</strong>: eBPF/XDP तेज़ पैकेट फ़िल्टरिंग और DPDK त्वरण।</li>
        <li><strong>🔄 लॉक-मुक्त प्रिमिटिव</strong>: SPMC/MPSC परमाणु कतारें और सख्त मेमोरी बैरियर अनुक्रमण।</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h4>🌐 वितरित प्रणालियाँ और समवर्ती</h4>
      <p><em>आधुनिक CSP-शैली पाइपलाइन और मेमोरी-सुरक्षित सिस्टम सॉफ्टवेयर।</em></p>
      <ul>
        <li><strong>⚙️ सिस्टम टूलचेन</strong>: आधुनिक C23, एसिंक्रोनस Rust (no_std) और Zig टूलचेन।</li>
        <li><strong>📦 शून्य-प्रतिलिपि डेटा प्रवाह</strong>: NVMe स्टोरेज और 100GbE पर कैश-संरेखित सीरियलाइज़ेशन।</li>
        <li><strong>🎯 अपरिवर्तनीय सत्यापन</strong>: परिमित स्थिति सत्यापन और स्वचालित फ़ज़िंग सूट।</li>
      </ul>
    </td>
  </tr>
</table>

</details>

---

<details>
<summary><h2 style="display:inline-block; margin:0;">⚡ प्रौद्योगिकी स्टैक और उपकरण</h2></summary>

<br />

<p><em>उच्च प्रदर्शन प्रणालियों के लिए इंजीनियरिंग टूलचेन:</em></p>

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>⚙️ निम्न-स्तरीय और सिस्टम</h4>
      <ul>
        <li><strong>भाषाएँ: C23, Rust (Async/Unsafe/No_std), Zig, x86_64 / ARM64 असेंबली</strong></li>
        <li><strong>कर्नेल रनटाइम: Linux Kernel Modules, POSIX APIs, eBPF / XDP, io_uring</strong></li>
        <li><strong>मेमोरी और समवर्ती: लॉक-फ्री परमाणु, SIMD, NUMA-जागरूक आवंटक</strong></li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h4>🌐 वितरित और बुनियादी ढाँचा</h4>
      <ul>
        <li><strong>नेटवर्किंग: कर्नेल-बाईपास (DPDK), epoll/kqueue, WebSockets, gRPC</strong></li>
        <li><strong>अवलोकन: bpftrace, perf, Valgrind, GDB, Prometheus टेलीमेट्री</strong></li>
        <li><strong>पर्यावरण: Arch Linux, Debian, Docker, LLVM/Clang, Neovim / Tmux</strong></li>
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
<summary><h2 style="display:inline-block; margin:0;">🗺️ परियोजनाएं और रोडमैप देखें</h2></summary>

<br />

<p><em>निम्न-स्तरीय बुनियादी ढांचे में सक्रिय रोडमैप और तकनीकी पहल:</em></p>

<ul>
  <li>🎯 वर्तमान फोकस: io_uring मल्टी-रिंग पोलिंग बेंचमार्क और कर्नेल फ़ज़िंग</li>
  <li>🚀 अगला मील का पत्थर: NUMA कैश-पिनिंग के साथ लॉक-मुक्त SPMC शेड्यूलर</li>
  <li>🔮 भविष्य का शोध: हार्डवेयर ऑफलोडिंग के साथ eBPF नेटवर्क राउटर</li>
</ul>

</details>

---

<details>
<summary><h2 style="display:inline-block; margin:0;">📊 आर्किटेक्चर डैशबोर्ड और मेट्रिक्स</h2></summary>

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

## 📬 संपर्क और सहयोग

निम्न-स्तरीय सिस्टम आर्किटेक्चर या लिनक्स कर्नेल पर चर्चा में रुचि रखते हैं?

[GitHub प्रोफ़ाइल](https://github.com/maya-thorne) · [सार्वजनिक रिपॉजिटरी](https://github.com/maya-thorne?tab=repositories) · [चर्चा](https://github.com/maya-thorne?tab=discussions) · [ईमेल भेजें](mailto:zse4123jo@gmail.com)

<div align="center">
  <br />
  <sub>© 2026 Maya Thorne · यांत्रिक सहानुभूति के साथ निर्मित · 🐧</sub>
</div>
